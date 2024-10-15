## Installing VSCode

### For Windows:

1. **Download VSCode:**
   - Visit the [Visual Studio Code website](https://code.visualstudio.com/).
   - Click **Download for Windows**.

2. **Run the Installer:**
   - Open the downloaded `.exe` file.
   - Accept the agreement and click **Next**.
   - Choose the **destination location** and click **Next**.
   - On the **Select Additional Tasks** page, check the box that says **"Add to PATH"** and **"Create a desktop icon"** if you prefer.
   - Click **Install**.

3. **Launch VSCode:**
   - Once installed, you can launch VSCode from the Start Menu or the desktop icon.

### For macOS:

1. **Download VSCode:**
   - Go to the [VSCode website](https://code.visualstudio.com/).
   - Click **Download for macOS**.

2. **Install VSCode:**
   - Open the downloaded `.zip` file.
   - Drag the **Visual Studio Code.app** to your **Applications** folder.

3. **Launch VSCode:**
   - You can launch VSCode from the **Applications** folder.

### For Linux (Ubuntu/Debian-based):

1. **Download VSCode:**
   - Open Terminal and run the following commands:
     ```bash
     sudo apt update
     sudo apt install wget gpg
     wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg
     sudo install -o root -g root -m 644 packages.microsoft.gpg /etc/apt/trusted.gpg.d/
     sudo sh -c 'echo "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main" > /etc/apt/sources.list.d/vscode.list'
     sudo apt install apt-transport-https
     sudo apt update
     sudo apt install code
     ```

2. **Launch VSCode:**
   - You can launch VSCode from the Terminal by typing `code` or by searching for **Visual Studio Code** in your applications.

## Configuring Python with VSCode

1. **Open VSCode:**
   - Launch VSCode as described in the steps above.

2. **Install Python Extension:**
   - Click on the **Extensions** icon on the left sidebar (or press `Ctrl+Shift+X`).
   - Search for **Python** and click **Install**.
   - This extension provides features like syntax highlighting, debugging, code formatting, and autocompletion.

3. **Select the Python Interpreter:**
   - Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS) to open the Command Palette.
   - Type **"Python: Select Interpreter"** and select it.
   - Choose the version of Python you installed.

