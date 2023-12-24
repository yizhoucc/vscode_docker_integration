# the vscode docker template for dev container


## prerequisite
### vscode extension
- Dev Containers, by Miscrosoft   
[link to extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- (optional) Docker, by Miscrosoft
### docker
- docker desktop
- docker image (eg, python image)
- dockerfile (install other dependencies that are not shipped with the image)

## usage
- clone this repo and cd into the repo folder.
- cmd+shift+P  in vscode to bring up the console.
- type in commond: 'Dev Container: Reopen in Container'
- then the vscode's terminal is in docker env.
- to use your own env, replace the dockerfile with your own, and change the .devcontainer.json file to update the docker image name.

