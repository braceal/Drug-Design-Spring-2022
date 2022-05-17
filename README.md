# Drug-Design-Spring-2022
Drug design project for CMSC 35360 (Spring 2022) Autonomous Laboratories

# Install conda environments

Each generative model has an installation configuration stored in `conda_environments`.

Run `conda env create -f [yaml_file_name]` and it will create a conda environment for you.

# GitHub setup

1. Setup a [personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) for GitHub.
2. Run `git config --global credential.helper store` to store the token.
3. Clone the repository

# Jupyter setup
To access Jupyter on your local machine:
1. Run jupyter notebook on Vela: `CUDA_VISBILE_DEVICES=<GPU-ID> jupyter notebook --port 8888 --ip 0.0.0.0 --no-browser`
2. On your local terminal: `ssh -NL 8888:localhost:8888 <username>@<VELA-IP>`
3. Use the localhost URL you got on Vela on your local browser

Note: Once you enter the password for Vela on your local, the terminal will stick there (indicating port forwarding is active). To stop once you’re done, hit CTRL+C on local terminal to stop port forwarding.

# Contributing
```
git checkout -b <branchname>
git add <files you want>
git commit -m 'message'
git push
```
