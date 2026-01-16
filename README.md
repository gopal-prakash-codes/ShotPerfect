# ShotPerfect

## Introduction
ShotPerfect is a powerful desktop application designed to enhance your screenshot experience. Built with modern web technologies and leveraging the Tauri framework, ShotPerfect provides a seamless and efficient way to capture, annotate, and manage screenshots. The application is designed with a focus on performance and user experience, making it an ideal tool for both casual users and professionals.

## Key Features
- **Screenshot Capture**: Easily capture screenshots with customizable options.
- **Annotation Tools**: Annotate your screenshots with text, shapes, and highlights.
- **Global Shortcuts**: Use keyboard shortcuts for quick access to screenshot functionalities.
- **Cross-Platform Support**: Runs on Windows, macOS, and Linux.
- **Tauri Integration**: Utilizes Tauri for a lightweight and secure desktop application.
- **Real-time Preview**: Preview your screenshots instantly after capture.
- **Image Processing**: Leverage Tesseract.js for OCR capabilities.

## Folder Structure
The project is organized as follows:

- `.git/`: Git version control files.
- `.github/`: GitHub-specific files and workflows.
- `.vscode/`: Visual Studio Code configuration files.
- `AGENTS.md`: Documentation for agents used in the project.
- `CHANGELOG.md`: A log of changes and updates made to the project.
- `CODE_OF_CONDUCT.md`: Guidelines for community behavior.
- `CONTRIBUTING.md`: Instructions for contributing to the project.
- `LICENSE`: License information for the project.
- `bettershot-landing/`: Landing page assets and components.
- `index.html`: Main HTML file for the application.
- `package.json`: Project metadata and dependencies.
- `pnpm-lock.yaml`: Lockfile for package dependencies.
- `postcss.config.js`: Configuration for PostCSS.
- `public/`: Public assets for the application.
- `scripts/`: Custom scripts for build and development processes.
- `src/`: Source code for the application.
- `src-tauri/`: Tauri-specific source code and configuration.
- `tsconfig.json`: TypeScript configuration file.
- `tsconfig.node.json`: Node-specific TypeScript configuration.
- `vite.config.ts`: Vite configuration file for the project.
- `vitest.config.ts`: Configuration for testing with Vitest.

## Installation & Setup
To get started with ShotPerfect, clone the repository and install the dependencies:

```bash
git clone https://github.com/gopal-prakash-codes/ShotPerfect.git
cd ShotPerfect
pnpm install
```

Make sure you have [Node.js](https://nodejs.org/) and [pnpm](https://pnpm.io/) installed on your machine.

## Usage
To run the application in development mode, use the following command:

```bash
pnpm dev
```

For building the application for production, execute:

```bash
pnpm build
```

To preview the built application, run:

```bash
pnpm preview
```

You can also run tests using:

```bash
pnpm test
```

For a comprehensive list of available scripts, refer to the `scripts` section in the `package.json` file. 

--- 

For further information on contributing, please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file.