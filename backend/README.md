## Project Chat GPT

## Youtube link 
 - https://youtu.be/13tMEW8r6C0 - How To Build a FastAPI & React Full Stack App | Clerk, Databases, LLMs & More

## Install UV like pip for fast api
```
Download the uv executable: Go to the official uv releases page on GitHub: https://github.com/astral-sh/uv/releases

Find the latest release.Under the "Assets" section, download the file named something like uv-x86_64-pc-windows-msvc.zip (for 64-bit Windows).

Extract the executable:
Unzip the downloaded file. You'll find an executable file named uv.exe inside.

Choose a location for uv.exe:
Create a new folder where you want to store uv.exe. A good place might be C:\Program Files\uv or C:\Users\YourUsername\bin. For this example, let's assume you put it in C:\uv.
Move the uv.exe file into this new folder.

Add uv to your System PATH:
Search for "Environment Variables": Click the Windows Start button and type "environment variables".
Select "Edit the system environment variables".
In the "System Properties" window, click the "Environment Variables..." button.

Under "User variables for [Your Username]" (or "System variables" if you want it available for all users), find the "Path" variable and select it.
Click "Edit...".
Click "New" and add the full path to the directory where you placed uv.exe (e.g., C:\uv).
Click "OK" on all open windows to save the changes.

Verify the installation:
  Close and reopen any Command Prompt or PowerShell windows you have open. This is crucial for the PATH changes to take effect.
  Type the following command and press Enter:
  uv --version ->    :You should now see the uv version number.

After Installation
Once uv is installed, you can start using it in your Python projects. Here are a few common commands to get you started:
Create a virtual environment (and install into it):
  uv venv   - >This will create a .venv directory in your current project.

Activate the virtual environment:
  PowerShell: .\.venv\Scripts\Activate.ps1
  Command Prompt: .\.venv\Scripts\activate.bat

Install packages:
  uv pip install requests ->Install from a requirements.txt file:

  uv pip install -r requirements.txt

Upgrade packages:
  uv pip install --upgrade your-package-name
uv aims to be a faster and more integrated alternative to pip and venv, so exploring its commands will significantly improve your Python development workflow.
```

$ uv init .
$ uv add fastapi uvicorn sqlalchemy python-dotenv clerk-sdk-python openai
$ npm create vite@latest frontend -- --template react
$ npm i react-router-dom@6 @clerk/clerk-react