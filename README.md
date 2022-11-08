# OpenVSCode Server releases

This repo is only to produce releases for [OpenVSCode Server](https://github.com/gitpod-io/openvscode-server).

# 1. docker build --tag vscode .
# 2. docker run -it --init -p 3000:3000 -v "$(pwd):/home/workspace:cached" vscode