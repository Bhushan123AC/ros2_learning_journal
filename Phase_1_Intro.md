PHASE 1 – CHEAT SHEET (Linux & Git)
Phase 1: Linux & Terminal Essentials

1. File System Commands

mkdir -p folder/subfolder: Create a directory (and parents).

cd ~: Go to Home directory.

ls: List files.

rm filename: Remove a file.

touch filename: Create an empty file.

2. Git & SSH Setup

Generate Key: ssh-keygen -t ed25519 -C "email@gmail.com"

View Key: cat ~/.ssh/id_ed25519.pub

Initialize Repo: git init

Connect Remote: git remote add origin git@github.com:USER/REPO.git

Save & Upload:

Bash

git add .
git commit -m "message"
git push
