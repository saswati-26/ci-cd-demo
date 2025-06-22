# ci-cd-demo

Set up a basic CI/CD pipeline using GitHub Actions to automate a simple build process

## Steps:

1. Go to GitHub and create a new repository
2. Name it (eg: `ci-cd-demo`)
3. Initialize it with a `README.md` file.
4. `git clone https://github.com/saswati-26/ci-cd-demo.git`
5. `cd ci-cd-demo`
6. `nano hello.py` => To edit the file in nano editor
7. Type `print("Hello, CI/Cd with GitHub Actions!")`
8. Press `CTRL + O` to save
9. Press `CTRL + X` to exit
10. Check for python version by running the command `python --version`. If installed python version will be display else need to install and set the `System Environment Variables` if required.
11. `mkdir -p .github/workflows/main.yml` => To create a directory with subdirectories and file
12. `nano .github/workflows/main.yml`
13. Write the code
14. `CTRL + O` then `CTRL + X`
15. `git add .`
16. `git commit -m "Added basic GitHub Actions workflow"`
17. `git push origin main`
18. Now go to GitHUub and press the `Actions` then `View workflow file` on the right-side
19. Now click on `build` on the left-side
20. Now click on `Run Script` to see the output
