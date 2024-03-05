## About The Project

This project demo how to build container with docker. It has 2 versions: v1.0 and v2.0. You can use Dockerfile in each version to build container


### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* docker
* git

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Clone the repo
   ```sh
   git clone https://github.com/napat1412/demo-web-template.git
   cd demo-web-template
   ```
2. Swtich branch to v1.0
   ```sh
   git checkout v1.0

   git branch # For re-check version of source code
   ```
3. Build container with Docker
   ```sh
   docker build -t demo-web-template:v1.0 .
   ```
4. Swtich branch to v2.0
   ```sh
   git checkout v2.0

   git branch # For re-check version of source code
   ```
5. Build container with Docker
   ```sh
   docker build -t demo-web-template:v2.0 .
   ```
