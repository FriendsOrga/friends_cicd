# GitHub Actions Repository

This GitHub repository contains a set of GitHub Actions for automating various processes and tasks in my project.

## Available Actions

### Generic Actions

1. **ChangeLog**: This action check for changes in the `CHANGELOG.md` file and creates a new release if there are any changes.

2. **Branch name**: This action checks the name of the branch if it is a valid branch name.

3. **Pull requests labels**: This action checks the labels of the pull request and adds a label if it is missing.

### Language Specific Actions

#### Flutter

1. **Code analytics**: This action checks the Dart code for errors and warnings, formats the code, and runs the tests.

2. **Security**: This action checks the Flutter code for security vulnerabilities.

3. **Build**: This action builds the Flutter project for Android, iOS, and Web.

4. **Test**: This action runs the tests for the Flutter project.

5. **Deploy Android**: This action deploys the Flutter project to the Play Store.

6. **Deploy iOS**: This action deploys the Flutter project to the App Store.

7. **Deploy Web**: This action deploys the Flutter project to the web.

#### Kotlin

1. **Check**: This action build the Kotlin project and runs the tests.

2. **Security**: This action checks the Kotlin code for security vulnerabilities.

#### TypeScript

1. **Check**: This action checks the TypeScript code for errors and warnings.

2. **Tests**: This action runs the tests for the TypeScript project.

3. **Build**: This action builds the TypeScript project.

### Cloud Services Actions

#### Firebase

1. **Deploy Functions**: This action deploys the Firebase functions.

## How to Use These Actions

1. To use any of these actions, refer to the corresponding YAML file in the `.github/workflows` directory.

2. Each YAML file contains specific configuration for triggering and running the action.

3. Make sure you have the secrets and environment variables defined in the YAML file.

## License

This project is licensed under the [MIT License](LICENSE). Refer to the `LICENSE` file for more details.
