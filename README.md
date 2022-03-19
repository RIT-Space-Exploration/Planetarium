# Planetarium
VR Planetarium for SPEX

## Setting Up Source Control (Windows)

1. [Download git client](https://gitforwindows.org/) and install
2. [Download git LFS](https://git-lfs.github.com/) and install
3. Open command prompt, and run `git lfs install`
4. [Download GitHub Desktop](https://desktop.github.com/) and login
5. Copy the path to this repository (from the "Code" drop down in the top right of this repository)
6. Go to GitHub desktop and press "add" and "clone repository". Paste the repo path into the URL field.
7. Find the file path of the repo in your files and open the project `exe`
8. Press "Source Control" and make the provider "Git". If the git path does not autofill, then find the file path to `git.exe` from step 1. Press 'Accept Settings'
9. Once you have changes to push, press source control and press "check out modified files." Then press submit files and write a description of your commit. Press submit.
10. Open GitHub Desktop and press Push Origin.
11. Check GitHub to ensure the assets you added or modified were pushed properly

## Source Control Etiquette

### Branches
It is good etiquette to make a branch for yourself in order to keep your changes seperate from the `main` branch. Traditionally, the `main` branch contains the full release (meaning everything within `main` is working) and branches are for experiments and/or development. To create a branch, open GitHub Desktop and under the current branch select "new branch". Create a name for the branch and whenever you push or pull from GitHub Desktop, make sure you are on the correct branch.

### Merging & Pull Requests
*TBA*

### Pulling
To pull progress made by other contributors to your project then open GitHub Desktop and press "fetch". Then make sure you are on the desired branch and press pull origin. Open your unreal project to see if the new assets are in your content browser.