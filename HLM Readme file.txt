VIVIDUS

This project is designed to trainning us in automation processes.

Include detailed instructions on how to install the application. This may involve listing prerequisites, dependencies, and step-by-step installation commands.

1. Install pre requisites.
2. Clone the VIVIDUS starter repository:

git clone https://github.com/vividus-framework/vividus-starter vividus
Navigate to the cloned repository directory:

cd vividus
Initialize and update the submodules:

git submodule update --init --recursive
Apply code formatting:

./gradlew spotlessApply
Build the project:

./gradlew build
Run the test stories:

./gradlew runStories
Note: After executing the runStories command, you may see the following error message:

2025-02-19 13:22:28,950 [main] ERROR org.vividus.runner.StoriesRunner - org.vividus.runner.InvalidConfigurationException: No batches with tests to execute are configured
3. Navigate to the project directory: `cd your-repo`.
4. Run the installation script: `./install.sh`.

Explain how to use the application, including examples and commands.

To start the application, run: `./start.sh`.

Provide information on how to configure the application, if necessary.

Edit the `config.yaml` file to set your preferences.

Outline the process for contributing to the project, including guidelines for submitting issues and pull requests.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Submit a pull request.

Specify the license under which the project is distributed.

This project is licensed under the NEORIS License.