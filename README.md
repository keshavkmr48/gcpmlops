
0. git clone remote repo.
1. Create .devcontainer folder
2. Within the .devcontainer folder, create devcaontainer.json file.
3. Create the Dockerfile in the same folder for creation of dev container.
4. create pyproject.toml for depency management outside .devcontainer folder
5. create .gitignore, license file and readme.md file.
6. create gcpmlopregression package.

CI/CD  Steps

1. Enable Cloud Run and Cloud Build API.
2. For further setup refer https://medium.com/@_davidanderson/set-up-ci-cd-using-github-actions-and-google-cloud-build-c0c4252e0cbe
3. Write github-cloudbuild ci-cd yaml file
4. 