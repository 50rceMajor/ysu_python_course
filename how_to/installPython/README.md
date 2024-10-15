## Installing Python

### For Windows:

1. **Download Python:**
   - Go to the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/).
   - Click on the big yellow button to download the latest version of Python (e.g., Python 3.11).

2. **Run the Installer:**
   - Open the downloaded `.exe` file.
   - **Important**: Check the box that says **"Add Python to PATH"** before clicking **Install Now**.
   - Click **Install Now** and allow the installation to proceed.

3. **Verify Installation:**
   - Open the **Command Prompt** by searching for "cmd" in the Start Menu.
   - Type `python --version` and press **Enter**. You should see the Python version displayed, indicating Python is successfully installed.
   - You can also type `pip --version` to verify that `pip`, Python's package manager, is installed.

### For macOS:

1. **Install Homebrew (Recommended Method):**
   - Homebrew is a popular package manager for macOS. If you haven’t installed Homebrew, open the **Terminal** and paste the following command:
     ```bash
     /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
     ```
   - Press **Enter** and follow the on-screen instructions.

2. **Install Python Using Homebrew:**
   - Once Homebrew is installed, run:
     ```bash
     brew install python
     ```

3. **Verify Installation:**
   - In the Terminal, type `python3 --version` and press **Enter**.
   - You should see the Python version displayed.

### For Linux (Ubuntu/Debian-based):

1. **Open Terminal** and update the package list:
   ```bash
   sudo apt update
   ```

2. **Install Python:**
   - Install Python by running:
     ```bash
     sudo apt install python3
     ```
   - Install `pip` as well:
     ```bash
     sudo apt install python3-pip
     ```

3. **Verify Installation:**
   - In Terminal, type `python3 --version` and `pip3 --version` to verify the installation.

