## Installing WSL on Windows

### 1. Enable WSL

1. **Open PowerShell as Administrator:**
   - Right-click the **Start Menu** and select **Windows PowerShell (Admin)** or **Command Prompt (Admin)**.

2. **Run the WSL Command:**
   - In the PowerShell window, type the following command and press **Enter**:
     ```powershell
     wsl --install
     ```
   - This command will enable the necessary components and install **Ubuntu** by default, which is a popular Linux distribution. If your system needs a restart, follow the on-screen instructions to do so.

### 2. Set Up WSL

1. **Launch WSL:**
   - Once installed, search for **Ubuntu** in the Start Menu and launch it.
   - On first launch, it will take a few moments to install and set up.

2. **Create a User:**
   - You'll be prompted to create a new Linux user. Enter a **username** and **password** that will be used in the WSL environment.

### 3. Install Python in WSL

1. **Update Package Lists:**
   - Run the following command in your Ubuntu terminal:
     ```bash
     sudo apt update
     ```

2. **Install Python:**
   - Run:
     ```bash
     sudo apt install python3
     ```
   - Install `pip` as well:
     ```bash
     sudo apt install python3-pip
     ```

3. **Verify Installation:**
   - Type `python3 --version` and `pip3 --version` to make sure Python and `pip` are installed.

### 4. Installing VSCode for WSL

1. **Install VSCode if Not Already Done:**
   - Visit the [VSCode website](https://code.visualstudio.com/) and download the Windows version if you haven’t installed it yet.

2. **Install WSL Extension for VSCode:**
   - Open VSCode and click on the **Extensions** icon (or press `Ctrl+Shift+X`).
   - Search for **"Remote - WSL"** and click **Install**.
   - This extension allows you to use VSCode to develop inside your WSL Linux environment.

3. **Open a WSL Project in VSCode:**
   - Open VSCode.
   - Press `Ctrl+Shift+P` to open the Command Palette.
   - Type **"Remote-WSL: New Window"** and press **Enter**.
   - You will be connected to the WSL environment, and you can now open and create files as if you were working on Linux.

