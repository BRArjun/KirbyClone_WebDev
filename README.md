<img src="./preview.png"></img>

# Kirby-like game with KaboomJS

## Overview

This simple game is designed using Kaboom.js for the gaming aspects. The project is bootstrapped using Vite, a modern front-end build tool that optimizes JavaScript for the browser.

## Technologies Used

- **Kaboom.js**: A lightweight, easy-to-use library for creating 2D games in the browser.
- **Vite**: A build tool that provides fast development server and optimized builds for production.

## Project Setup

### Prerequisites

Ensure you have Node.js installed on your system. You can download it from [Node.js official website](https://nodejs.org).

### Installation

1. Clone this repository to your local machine.
``` bash
git clone https://github.com/BRArjun/Kirby_WebDev.git
```
2. Move into the directory
``` bash
cd Kirby_WebDev
```
3. Install dependencies
``` bash
npm install
```
4. Run the developmental build
```bash
npm run dev
```

## Configuration

### Vite Configuration

The `vite.config.ts` file specifies the base directory of the project, enabling hosting services to locate the root directory correctly. It uses Terser for minification instead of the default ESBuild due to compatibility issues with Kaboom.js.

### Kaboom.js Usage

Kaboom.js utilizes a sprite sheet for efficient rendering. Instead of drawing tiles individually (which is more performance-intensive), we use a tile editor to create levels and export them as images. This approach 'bakes' the tiles, optimizing performance.

See the [documentation](https://kaboomjs.com/doc/intro) for more details.
## License

This project is licensed under the MIT License.
