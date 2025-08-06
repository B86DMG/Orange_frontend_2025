1. Display the current directory using `pwd`.
pwd
2. Create a directory named `git_project` and navigate into it.
mkdrir git_project
cd git_project

3. Inside, create two subdirectories: `src` and `docs`.
mkdir src
mkdir docs

4. Inside `src`, create two empty files: `main.py` and `utils.py`.
cd src
touch main.py
touch utils.py

5. List all files and directories including hidden ones.
ls -la
6. Go one level back and create a `README.md` file.
cd ..
touch README.md
7. Remove the `docs` folder using `rmdir` (make sure it's empty).
cd docs
ls -A
cd ..
rmdir docs
8. Create a nested folder structure `demo/test1/test2` in one command.
mkdir -p demo/test1/test2

9. Navigate to `test2` using only relative paths.
cd demo/test1/test2

10. Clear the terminal using `clear` or `Ctrl + L`.

clear
11. Commits and push the changes to your GitHub repository.

cd ../../..
git add.
git commit -m "descriere"
git push

```bash
git add .
git commit -m "choose a descriptive message"
git push