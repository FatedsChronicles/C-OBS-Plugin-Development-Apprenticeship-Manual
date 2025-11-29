# 🪜 SECTION 1 — Setting up your Developer Environments

## ✅ 1.1 Adding VS Code Extensions

On the far left of the VS Code display you will see a list of icons

Choose the on that looks like a box with 4 sections

This is your extensions panel

Search for and install & Enable the following extensions

* [ ] ✔ C/C++ by Microsoft
* [ ] ✔ C/C++ Extension Pack by Microsoft
* [ ] ✔ CMake by twxs
* [ ] ✔ CMake Tools by Microsoft
* [ ] ✔ CMake IntelliSence by Kylin-IDE Team
* [ ] ✔ GitHub Repositories by GitHub
* [ ] ✔ GitLens by GitKraken

## 🌱 1.2 Git Bash version control

Go to start menu and type:

```
Bash
```

Open the Git Bash App

At the command prompt type:

```
git --version
```

You should see the version of git.

***

#### ❌ Error

If you **dont see the version of git** you need to do the following

Otherwise you can skip this segment.

* If you missed the option during installation, search for "Environment Variables" in the Start menu and open it.
* Click "Environment Variables..." and find the "Path" variable under "System variables".
* Click "Edit", then "New", and add the path to your Git `bin` and `cmd` folders\
  (e.g., `C:\Program Files\Git\bin` and `C:\Program Files\Git\cmd`).
* Click OK to save.&#x20;

After adding Git to your PATH, Restart Git Bash. and run.

```
git --version
```

check that it works

***

## 🚀 1.3 Set VS Code as Defaault Editor

In the git Bash terminal window type:

```
git config --global core.editor "code --wait"
```

Then Enter

## ✍️ 1.4 Configure Git Bash

To set your name to your Git commits

```
git config --global user.name "Your Name"
```

To set your email to your Git commits

```
git config --global user.email "you@example.com"
```

Change the user name and email to your own.

You will use this when registering to GitHub later on.

> **Note:** If you forget to set your name or email, Git will prompt you the first time you try to commit.
>
> You can always change these settings later, and previous commits will keep the old info.

Use `--global` to set the value for **every repository** on your computer.

Use `--local` (the default) to set it only for the current repository.

#### Why Configure Git?

> Git uses your name and email to label your commits.
>
> If you do not set these, Git will prompt you the first time you try to commit.
>
> Now you have added the minimum of configuration needed to start using Git.

#### Viewing Your Configuration

In the git Bash terminal window type:

```
git config --list
```

You will now see a **complete list** of all configured items including any you have configured

{% hint style="info" %}
To view a **specific configuration** you can use:
{% endhint %}

```
git config user.name
```

```
git config user.email
```



{% hint style="info" %}
To **change or unset** config values
{% endhint %}

To change just rerun configuration from above

To unset a configuration use

```
--unset
```

example:

```
git config --global --unset user.name
```

#### Set the default branch name for new repositories

In the git Bash terminal window type:

```
git config --global init.defaultBranch main
```

### Configuration Levels

There are three levels of configuration:

* **System** (all users): `git config --system`
* **Global** (current user): `git config --global`
* **Local** (current repo): `git config --local`

The order of precedence is:

* Local (current repo)
* Global (current user)
* System (all users)

The reason to use the different levels is that you can set different values for different users or repositories.



