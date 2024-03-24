# LinkedIn Google Cloud Professional Machine Learning Engineering Certificate Preparation
This repository is part of my effort to pass the Google Cloud Professional Machine Learning Engineering Certificate

It follow the course given by Noah Gift on LinkedIn Learning: https://www.linkedin.com/learning/paths/prepare-for-the-google-cloud-professional-machine-learning-engineer-certification

Here you can find my notes on the exam: https://gortium.github.io/Slit-box/LinkedIn-Google-Cloud-Professional-Machine-Learning-Engineer-Certification

## 1. Framing ML Problems
Here you can find my notes on this chapter: https://gortium.github.io/Slit-box/Framing-ML-Problems

In addition to the terms and definitions, in this chapter, Noah Gift showed us multiple practical tricks to allow better CI\CD workflow in MLOps:

### Github codespaces
Codespace allow online, and always clean environment. It also allow the use of cloud computing to build code or train ML models. It use docker and vscode.

#### devcontainer.json
This file allow us to define a custom codespace (online vscode) deployed within our custom docker and our personalized vscode extention. That way we always have a clean development environment to work in.

#### Dockerfile
This file allow us to define our custom environment where our codespace will be installed in.

### Github actions
Github action allow automated workflow to be executed by github manualy, or at every push. Similar to Jenkins.

#### Makefile
This file make it easier to call the different CI/CD steps of our develpment workflow.

#### cicd.yml
This file allow us to call ours Makefile from github automaticaly, or manualy.

