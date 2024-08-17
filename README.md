# DDAS

## Description
DDAS (Download Directory Auto Sorter) is a Node.js application that monitors your Downloads directory and automatically sorts files based on their extensions. It uses the `chokidar` library to watch for new files and `fs-extra` for file operations.

## Features
- Monitors the Downloads directory for new files.
- Ignores temporary and partial download files.
- Automatically sorts files into appropriate directories based on their extensions.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/<yourusername>/DDAS.git
    cd DDAS
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

## Usage

1. Start the application:
    ```sh
    npm start
    ```

2. The application will start monitoring your Downloads directory for new files and sort them accordingly.

## Dependencies

- [chokidar](https://www.npmjs.com/package/chokidar) - A neat wrapper around node.js fs.watch / fs.watchFile / fsevents.
- [crypto](https://www.npmjs.com/package/crypto) - Node.js built-in library for cryptographic functionality.
- [fs-extra](https://www.npmjs.com/package/fs-extra) - A module that extends the native Node.js `fs` module with additional functionality.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the ISC License.

## Acknowledgements

- [Node.js](https://nodejs.org/)
- [chokidar](https://github.com/paulmillr/chokidar)
- [fs-extra](https://github.com/jprichardson/node-fs-extra)
