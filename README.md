# Docker React Template Project
React Native template for projects built and running in Docker

Example react project credits: https://github.com/KarthikeyanRanasthala/react-unit-converter

## Prerequisites
Make sure you have Yarn installed for package management.

Check with `yarn --version`

You might also want to upgrade Yarn if it's been a while.

`brew upgrade yarn`

If you don't have it, you can install Yarn with Homebrew. 

`brew install yarn`

Or with this shell script in macOS and generic Unix environments.

`curl -o- -L https://yarnpkg.com/install.sh | bash`

If you encounter any problems with installing Yarn, visit [https://classic.yarnpkg.com/en/docs/install](https://classic.yarnpkg.com/en/docs/install)

## Building and Running
Run `make start` to build and run the Docker container. 

The project will run locally in `http://localhost:3000` and will compile automatically upon changes to the src code.
