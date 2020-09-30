# Learning Git

[Git LFS](https://github.com/git-lfs/git-lfs/wiki/Tutorial)

For Windows:- 

Git LFS requires Git version 1.8.2 or later to be installed.

Download and install the git-lfs client by visiting the [GIT LFS](https://git-lfs.github.com/) homepage. If you downloaded the binary release, install git-lfs by running the provided install.sh.

Most package managers also provide the git-lfs client. Since, LFS is a rapidly evolving technology, package managers will help you keep up with new git-lfs releases. For example, Mac users with Homebrew can simply run brew install git-lfs and brew upgrade git-lfs.

Once git-lfs is installed, run:

git config --global lfs.batch false
git lfs install
to configure Git to use Git LFS in your ~/.gitconfig file.

Next, decide whether you will need to push Git LFS data, or only clone and pull from Git LFS managed repositories. 
