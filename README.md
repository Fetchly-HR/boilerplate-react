# React Boilerplate

**Boilerplate with React, Next, and Tailwind CSS.**  
This boilerplate shares the same tooling used during the interview, therefore setting it up guarantees a development environment to be used during your Technical call.

## Running Locally

### Setting up the environment
##### Tools needed:
- Node.js ^14.18.0 || >=16.0.0
- Yarn

#### Installing Node.js 14
You'll need Node.js 14 to run this project, we recommend using [asdf](https://asdf-vm.com) to manage your node version on macOS and Linux (bash/zsh/fish). [Here](https://asdf-vm.com/guide/getting-started.html#_3-install-asdf) are instruction on how to install and configure it. [You'll also need the NodeJS plugin for asdf.](https://github.com/asdf-vm/asdf-nodejs). **This is just a recommendation, `NVM` also works fine, and as long as you have this project running, this is enough for the call.**

#### Installing Yarn
From this project folder, run:
```bash
npm install --global yarn
```
By running from this folder, asdf will automatically pick up the node interpreter version from .tool-versions, and make yarn available for it.

##### Install dependencies

```bash
  yarn install
```

##### Start the server

```bash
  yarn dev
```
