# GitHubPagesTest

[![Build and Deploy](https://github.com/CodeCrafter912/GitHubPagesTest/actions/workflows/release.yml/badge.svg)](https://github.com/CodeCrafter912/GitHubPagesTest/actions/workflows/release.yml)

This is an example demonstrating how to host a custom Debian repository using GitHub pages.

# Setup
To use the repository, please follow these steps:
1. Import key:
```
wget "https://codecrafter912.github.io/GitHubPagesTest/pub.gpg" | sudo apt-add key -
```
2. Add repo:
```
echo "deb https://codecrafter912.github.io/GitHubPagesTest  bionic main" > /etc/apt/sources.list.d/ccTest.list
```
3. Apt update
```
apt update
```
