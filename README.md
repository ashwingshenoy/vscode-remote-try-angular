# Try Out Development Containers: Angular

[![Open in Remote - Containers](https://img.shields.io/static/v1?label=Remote%20-%20Containers&message=Angular&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/ashwingshenoy/vscode-remote-try-angular)

A **development container** is a running [Docker](https://www.docker.com) container with a well-defined tool/runtime stack and its prerequisites. You can try out development containers with **[GitHub Codespaces](https://github.com/features/codespaces)** or **[Visual Studio Code Remote - Containers](https://aka.ms/vscode-remote/containers)**.

This is a sample Angular project that lets you try out either option in a few easy steps.

> **Note:** If you already have a Codespace or dev container, you can jump to the [Things to try](#things-to-try) section.

## Setting up the development container

### GitHub Codespaces
Follow these steps to open this sample in a Codespace:
1. Click the Code drop-down menu and select the **Open with Codespaces** option.
1. Select **+ New codespace** at the bottom on the pane.

For more info, check out the [GitHub documentation](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces/creating-a-codespace#creating-a-codespace).
  
### VS Code Remote - Containers

If you already have VS Code and Docker installed, you can click the badge above or [here](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/ashwingshenoy/vscode-remote-try-angular) to get started. Clicking these links will cause VS Code to automatically install the Remote - Containers extension if needed, clone the source code into a container volume, and spin up a dev container for use.

Follow these steps to open this sample in a container using the VS Code Remote - Containers extension:

1. If this is your first time using a development container, please ensure your system meets the pre-reqs (i.e. have Docker installed) in the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started).

2. To use this repository, you can either open the repository in an isolated Docker volume:

    - Press <kbd>F1</kbd> and select the **Remote-Containers: Clone Repository in Container Volume...** command to clone the source code in a Docker volume instead of the local filesystem, wait for the container to start, and try things out!. [Volumes](https://docs.docker.com/storage/volumes/) are the preferred mechanism for persisting container data.

    Or open a locally cloned copy of the code:

   - Clone this repository to your local filesystem.
   - Press <kbd>F1</kbd> and select the **Remote-Containers: Open Folder in Container...** command.
   - Select the cloned copy of this folder, wait for the container to start, and try things out!

## Things to try

Once you have this sample opened, you'll be able to work with it like you would locally.

> **Note:** This container runs as a non-root user with sudo access by default. Comment out `"remoteUser": "node"` in `.devcontainer/devcontainer.json` if you'd prefer to run as root.

Some things to try:

1. **Edit:**
   - Open `src/app/app.component.html`
   - Try adding some code and check out the language features. 
   - Notice that below mentioned extensions are already installed in the container since the `.devcontainer/devcontainer.json` lists to install these automatically when the container is created.
        - Angular Language Service,
        - ESLint,
        - GitLens,
        - IntelliCode,
        - Prettier
2. **Terminal:** Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>\`</kbd> and type `uname` and other Linux commands from the terminal window.

    This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.18.

    ### Development server

    Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

    ### Code scaffolding

    Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

    ### Build

    Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

    ### Running unit tests

    Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

    ### Running end-to-end tests

    Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

    ### Further help

    To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## License

Licensed under the MIT License. See LICENSE in the project root for license information.
