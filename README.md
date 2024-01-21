# Pre-commit use gitleaks

This repository contains the pre-commit hook script for automate installation of [gitleaks](https://github.com/gitleaks/gitleaks) and checks for sensitive information 🔒


## Requirements 📋

Before using this script, make sure you have the following dependencies installed:

✔️ Git

✔️ Curl

## Installation ⚙️

To install the script, simply run the following command in your terminal:

``` sh
curl -sSfL https://raw.githubusercontent.com/obezsmertnyi/pre-commit-gitleaks/main/install.sh | bash
```

## Enable or Disable plugin

✅ Enable:

```sh
git config hooks.gitleaks-enable true
```

❌ Disable:

```sh
git config hooks.gitleaks-enable disable
```

## Usage 🚀

After running the installation command, it will automatically install and configure `pre-commit` hooks for your Git repository. It also integrates `gitleaks` to scan for sensitive information in your codebase and prevent leaks. 🛡️

Pre-commit searches sensitive information in commits, the staging area, modified files.

## DEMO 🎥
![Image](img/demo_gitleaks.gif)


