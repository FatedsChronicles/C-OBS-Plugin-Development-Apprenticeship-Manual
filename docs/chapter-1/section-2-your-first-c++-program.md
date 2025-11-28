# 💻 SECTION 2 — Your First C++ Program

We’re going to create a tiny program that prints a message on the screen.

I’ll guide you through **every click and keystroke**.

## 🚀 **2.1 Create a Project Folder**

#### Step 1 — Open File Explorer

Press:\
**Windows Key + E**

#### Step 2 — Create a new folder

Create a a new development folder where you want your dev builds to live

Right-click → **New** → **Folder**

Name it:

```
dev-builds
```

Press **Enter**.

Inside that folder

Right-click → **New** → **Folder**

```bash
cpp-beginner
```

Press **Enter**.

## 📂 **2.2 Open the Folder in VS Code**

#### Step 1 — Open VS Code

Click the Start Menu

Type **Developer Command for VS 2022**

**Click on app**

**Now we need to change drive to the folder we made earlier**

**If you installed on C: drive**

change directory to its location

```
cd dev-builds\cpp-beginner
```

Press **Enter**

**If you installed on a different drive**

**First change to that drive**

```
D:
```

Then use the change directory command above

#### Step 2 — Open VS Code

Once in the correct folder in **Developer Command for VS 2022**

Type the following

```
code .
```

Opening VS Code this way allows us to use MSVC compiler

In VS Code:

You should now see an empty folder inside VS Code.

## 📄 **2.3 Create Your First Code File**

Inside VS Code:

1. Look at the left sidebar
2. Click the icon “New File” (a little page with a +)
3. Type the name:

```cpp
hello.cpp
```

Press **Enter**.

You now have an empty C++ file ready for code.

## ✍️ **2.4 Type Your First Program (Line by Line)**

Type this **exactly** as written: (type it rather than copy/paste you will learn more that way)

```cpp
#include <iostream>

int main() {
    std::cout << "Hello, world!" << std::endl;
    return 0;
}
```

Don't worry if you don’t understand it yet — you will soon.

## ✅ 2.5 Adding VS Code Extensions

On the far left of the VS Code display you will see a list of icons

Choose the on that looks like a bos with 4 sections

This is your extensions panel

Search for and install the following extensions





