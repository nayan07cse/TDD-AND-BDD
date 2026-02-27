# TDD-AND-BDD
Development technique implementation of features and software application's behavior. Main focus is on system requirements and  unit test.


[![Python 3.9](https://img.shields.io/badge/Python-3.9-green.svg)](https://shields.io/)


## Contents

### TDD

- [01: Running Test with Nose](tdd-vs-bdd/running_tests_with_nose/README.md)
- [02: Writing Test Assertions](tdd-vs-bdd/writing_test_assertions/README.md)
- [03: Creating an Initial State Using Text Fixtures](tdd-vs-bdd/test_fixtures/README.md)
- [04: Running Test Cases with Coverage](tdd-vs-bdd/test_coverage/README.md)
- [05: Using Factories and Fakes](tdd-vs-bdd/factories_and_fakes/README.md)
- [06: Mocking Objects](tdd-vs-bdd/06_mocking_objects/README.md)
- [07: TDD](tdd-vs-bdd/practicing_tdd/README.md)

### BDD

- [08: Environment setup](tdd-vs-bdd/environment_setup)
- [09: Writing feature file](tdd-vs-bdd/writing_feature_files)
- [10: Loading test data](tdd-vs-bdd/loading_test_data)
- [11: Generating steps](tdd-vs-bdd/generating_steps)
- [12: Implementing steps](tdd-vs-bdd/implementing_steps)
- [13: Variable substitution](tdd-vs-bdd/variable_substitution)

## Development Environment

You can work on them locally using Docker and Visual Studio Code with the Remote Containers extension to provide a consistent repeatable disposable development environment for all of the tdd-vs-bdd in this project.

You will need the following software installed:

- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [Visual Studio Code](https://code.visualstudio.com)
- [Remote Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension from the Visual Studio Marketplace

All of these can be installed manually by clicking on the links above or you can use a package manager like **Homebrew** on Mac of **Chocolatey** on Windows.

### Using Remote Containers

To bring up the development environment you should clone this repo, change into the repo directory, and then open Visual Studio Code using the `code .` command. VS Code will prompt you to reopen in a container and you should say **yes**. This will take a while as it builds the Docker image and creates a container from it to develop in.

For the **BDD** you will need to run the following commands to create the proper development environment:

```bash
bash bin/setup.sh
```

Then exit that terminal and open a new one to activate the virtual environment.
