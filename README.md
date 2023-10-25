# My GitHub Actions Repository

This GitHub repository contains a set of GitHub Actions for automating various processes and tasks in my project.

## Available Actions

1. **ChangeLog**: This action check for changes in the `CHANGELOG.md` file and creates a new release if there are any changes.

2. **Branch name**: This action checks the name of the branch if it is a valid branch name.

3. **Pull requests labels**: This action checks the labels of the pull request and adds a label if it is missing.

4. **Flutter / Dart action**: This action checks the Dart code for errors and warnings, formats the code, and runs the tests.

5. **Kotlin / Spring boot action**: This action checks the Kotlin code for errors and warnings, formats the code, and runs the tests.

6. **Flutter Security**: This action checks the Flutter code for security vulnerabilities.

7. **Kotlin Security**: This action checks the Kotlin code for security vulnerabilities.

## How to Use These Actions

1. To use any of these actions, refer to the corresponding YAML file in the `.github/workflows` directory.

2. Each YAML file contains specific configuration for triggering and running the action.

3. Make sure you have the secrets and environment variables defined in the YAML file.

## License

This project is licensed under the [MIT License](LICENSE). Refer to the `LICENSE` file for more details.
