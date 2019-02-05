# Electron Create React Example

This is an example electron/create-react-app application, and serves as an example of how to structure your project if you want to share pieces of your codebase between electron and react.

## Project structure

- `electron/`: Code for the main Electron process
- `src/react/`: Code for the React renderer process
- `src/shared/`: Code shared between React and Electron
- `package.json`: Contains scripts for running the app in development, building it, and packaging it for production using electron-builder

