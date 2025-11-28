# 🪜 SECTION 1 — Installing Your Tools (Step-by-Step, No Guessing)

## 🔧 1.1 Install Visual Studio Code

**We're going to install three things:**

1. Visual Studio Code — your text editor
2. MSVC Build Tools — your compiler
3. Git — your version control tool

Don't worry — I’ll walk you through every click.

#### Step 1 — Open your browser

Click in the address bar and type:

```http
https://code.visualstudio.com
```

Press **Enter**.

#### Step 2 — Download

Click the big **“Download for Windows”** button.

#### Step 3 — Run the installer

Go to your Downloads Folder.

Double-click the file called:

```
VSCodeUserSetup-x64.exe
```

#### Step 4 — Click through the installer

Select "I accept the agreement"

Then click "Next"

Tick the following boxes:

* Create a desktop icon
* Add "**Open with Code**" action to Windows Explorer file context menu
* **Add “Open with Code” action to Windows Explorer directory context menu**
* **Register Code as an editor for support file types**
* **Add to PATH (requires shell restart)**

Click **Next** → **Install**.

#### Step 5 — Open VS Code

Once installed, VS Code will launch automatically.

If not, click the Start Menu → type **“Visual Studio Code”** → press **Enter**.

***

***

## 🧩 1.2 Install C++ Build Tools (MSVC)

This is the part most beginners get stuck on — but don’t worry, we’re doing it together.

#### Step 1 — Visit Visual Studio downloads

In your browser, type:

```
https://visualstudio.microsoft.com/downloads
```

Press **Enter**.

#### Step 2 — Scroll down the page to “Tools for Visual Studio”

Find:

**Build Tools for Visual Studio**\
Click **Download**.

#### Step 3 — Open the installer or go to Downloads Folder

Double-click:

```
vs_BuildTools.exe
```

#### Step 4 — Select the correct workload

A window open for Visual Studio Installer

Click "Continue"

A Download and install will begin, wait for it to finish.

A big window appears.

Select "Select workloads and components manually"

Thee click **Next**

#### Step 5 — Install the required components

Across the top choose **"Workloads"**

**Select "Desktop development with C++**

Across the top choose **"Individual components"**

In the summary (right side), make sure these are ticked:

* [ ] ✔ MSVC v143 (or latest)
* [ ] ✔ MSVC Build Tools for x64/x86 (Latest)
* [ ] ✔ MSVC Build Tools v 14.50 for x64/x86
* [ ] ✔ Windows 11 SDK (10.0.22621.0)
* [ ] ✔ Windows 11 SDK (10.0.26100.6901)
* [ ] ✔ C++ CMake tools for Windows

If any of the above are missing use the search on the top left to add them

#### Step 6 — Install

Click **Install**\
This might take 5–15 minutes.

***

***

## 🌱 1.3 Install Git + GitHub Desktop



Git saves your progress and helps you undo mistakes — think of it like a time machine for developers.

#### Install Git

1. Go to:

```http
https://git-scm.com
```

2. Click **Download for Windows** Then **Git for Windows x64 Setup**
3. Go to Downloads Folder
4. Double click Git-2.52.0-64-bit.exe
5. On Term & Conditions click **Next**
6. On Select Components click **Next**
7. On Choose the default editor, Select "Use Visual Studio as Git's default editor" then click **Next**
8. On Adjusting the name of the initial branch in new repositories, Choose "Override the default name" Write "main" without the quotes in the box. Then click **Next**
9. On Adjusting you PATH environment. Select Git from the command line. Then click **Next**
10. On Choosing the SSH executable, select **Use bundled OpenSSH**
11. On Choosing HTTPS transport backend, select Use the native Windows Secure Channel library. Then click **Next**
12. On Configuring the line ending conversions, select Checkout as-is, commit Unix-style line endings. The click **Next**
13. On Configuring the terminal emulator to use with Git Bash, Select Use MinTTY (the default terminal of MSYS2). The click **Next**
14. On Choose the default behavior of 'git pull', Select Fast-forward or merge. The click **Next**
15. On Choose a credential helper, Select Git Credential Manager. The click **Next**
16. On Configuring extra options, Select Enable file system caching. The click **Install**

#### Install GitHub Desktop

* Go to:

```http
https://desktop.github.com
```

* Click **Download Now** Then **Download for Windows (64 bit)**
* Go to Downloads Folder
* Double click GitHubDesktopSetup-x64.exe
* Sign in with your GitHub account
* And that’s it — Git is ready.
* To login to a different account
  *   Click File Then Account



## 🎉 **Big Pause: You Did Something Huge**

This is the part where most beginners give up.\
And you didn’t.

You installed a real development environment — the same tools professionals use.\
That's a big step. Be proud of yourself.
