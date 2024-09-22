# Simple Arras Template

<img alt="Logo" src="public/favicon.ico" width="120" />

![GitHub Release](https://img.shields.io/github/v/release/phosphorus9273/simple-arras-template-server)
![Discord](https://img.shields.io/discord/1004907608018264094)
![GitHub repo size](https://img.shields.io/github/repo-size/phosphorus9273/simple-arras-template-server)

An optimized and customizable template for building Arras private servers. Perfect for developers looking to use a clean, organized, and easy-to-use code structure, this template provides a solid foundation for your community or personal use.


## Note

The Bun JS Runtime as of 22/9/24 cannot run simple-arras-template as it requires google-closure-library for the quadtree which is currently not available.

## Features

- **Optimized Performance**: Streamlined code for efficient server performance.
- **Customizable Structure**: Easily modify and adapt to your needs.
- **Clean Codebase**: Well-organized files and documentation for easy navigation.
- **Community Focused**: Designed with features suitable for both personal and community servers.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- [Node.js](https://nodejs.org/) (for development tools)
- A text editor (e.g., [Visual Studio Code](https://code.visualstudio.com/))

### Installation

1. **Client Installation**:
- Go to [SAT Client](https://github.com/phosphorus9273/simple-arras-template-client) and install the required files.
- If you are using glitch, go to the [SAT Client](https://glitch.com/~simple-arras-template-client) on glitch and remix it.
- Search `serverlist` or go to line 200 in app.js and input your server or if you are using localhost input localhost:port.
2. **Server Installation**:
- Go to [SAT Server](https://github.com/phosphorus9273/simple-arras-template-server) and install the required files.
- Go to the terminal and run `npm i` to install the dependencies.
- In config.js, replace your host with the domain of the server or localhost.
- After installing the dependencies, run `node index/server`
- If you are using glitch, go to the [SAT Server](https://glitch.com/~simple-arras-template-server) on glitch and remix it.
- Input your-project-name.glitch.me in "host".
