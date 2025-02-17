# CPU Viewer 💖

A real-time system resource monitoring application built with Electron that provides instant insights into your computer's CPU and memory usage.

![CPU Viewer Screenshot](./screenshot.png)

## Features

- 🔄 Real-time CPU usage monitoring
- 💾 Live memory usage tracking
- 💻 Total system memory display
- 🚀 Updates every second
- 🖥️ Cross-platform support (Windows, macOS, Linux)

## Prerequisites

Before running this application, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (version 14 or higher)
- npm (usually comes with Node.js)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/AshirbadGudu/cpu-viewer-electron-app.git
```

2. Navigate to the project directory:

```bash
cd cpu-viewer-electron-app
```

3. Install dependencies:

```bash
npm install
```

## Usage

To run the application in development mode:

```bash
npm start
```

## Building the Application

To create a distributable package:

```bash
# For all platforms
npm run make

# For Windows installer
npm run build-installer
```

The built applications will be available in the `out` directory.

## Development

The application is built using:

- Electron
- Node.js
- os-utils

Key files:

- `src/index.js` - Main process file
- `src/index.html` - Application UI
- `src/index.css` - Styling

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Ashirbad Panigrahi**

- Email: ashirbadapanigrahi@gmail.com
- GitHub: [@AshirbadGudu](https://github.com/AshirbadGudu)

## Acknowledgments

- Thanks to the Electron team for the amazing framework
- os-utils package for system metrics
