# mintbean-cli
Command line interface for easy creation and deployment of submissions for Mintbean hackathon challenges

## Install
`npm install -g mintbean-cli`

## Usage
This tool is run with `mint` command once installed.

Run `mint` for list of commands

### create new react app
`mint n <my-app>`

## Roadmap
Aiming for at least these features (bold indicates WIP)

| cmd  | description  |
|---   |---           |
| **`mint \|-h\|--help`**   | display help |
| **`mint -v\|--version`**  | display version|
| **`mint new\|n <project-name>`** | create new project. accepts option `-t` for project type. Currently defaults to 'react' (and react is only avail project type)  |
| `mint deploy`  | deploy project to github pages based on project type |
| `mint share`  | display remote repo link and github pages link |
| `mint login`  | save user preferences, github/mintbean credentials|