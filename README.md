# GitChat - GitHub-GPT-Assistant prompts and how to make your own

Welcome to **GitChat**, a custom AI-powered assistant designed to streamline interactions with GitHub repositories, pull requests, issues, and more. This repository provides all necessary instructions, files, and schemas to create and configure your own GitHub-integrated assistant using OpenAI's custom GPTs.

---

## Purpose

The **GitHub-GPT-Assistant** is designed to enhance productivity and accessibility when working with GitHub. It allows users to interact with repositories, pull requests, commits, and more, directly from a conversational interface. This assistant is ideal for developers, project managers, or anyone who frequently navigates GitHub and wants a more conversational and integrated approach.

## Features

- **Repository Exploration**: Easily retrieve information about repositories, including stars, forks, and latest updates.
- **Pull Request Insights**: View details of pull requests, including changed files, commit history, and comments.
- **File and Code Search**: Directly search for files, folders, and code within repositories.
- **Branch Comparisons**: Compare branches or commits to view differences in code.
- **Commit History**: List and review commits with detailed information on changes.

---

## Know Issues

- It fails to fetch larger responses
- No editing APIs were added but you can try yourself

## Getting Started

Follow these steps to create your own GitHub-integrated assistant:

### 1. Create a Custom GPT
- Go to [OpenAI's GPT customization page](https://chatgpt.com/gpts/editor).
- Configure a new GPT with your desired name and icon.

### 2. Set Up a GitHub App
- Visit the [GitHub Apps creation page](https://github.com/settings/developers).
- Create a GitHub App with the necessary permissions to read repositories, pull requests, and commits.

### 3. Add Credentials to Your Custom GPT
- In your GPT setup, add the GitHub App credentials (Client ID and Secret) to enable secure API access.

### 4. Configure with Provided Files
- Use `prompt.md` for your assistant’s conversational prompt, setting expectations and guidance for responses.
- Use `schema.json` to define data interactions and parameters required for various GitHub API calls.

### 5. Test and Use
- Once configured, test your assistant to ensure it responds correctly to GitHub-related queries.
- Share and star this project if you find it useful!

### 6. Watch the video to see how to ask ChatGPT to help you add new methods
[Video url](TODO)

---

## Repository Structure

- **prompt.md**: Contains the custom prompt to define your assistant's personality and response style.
- **schema.json**: Defines the schema and parameters for GitHub API interactions, ensuring consistent and accurate data handling.
- **README.md**: This file, describing the purpose and setup of the repository.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests to suggest improvements or fixes.

---

## Additional Resources

For more details, refer to the video guide on setting up and using the GitHub-GPT-Assistant effectively. Happy coding!

Give this project a ⭐ if you find it helpful!
