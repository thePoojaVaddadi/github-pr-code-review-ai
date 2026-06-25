# github pr-code-review-ai

_An AI code review GitHub bot application streamlining PRs reviews in great detail and providing each file change summary, a walkthrough of all changes, and the aspects of changes the code has been updated within the PR description itself. It also conducts code reviews and raises change requests in a thread._



## Introduction

Code Bat AI is an advanced automation tool that harnesses the power of the Llama-3-70B model by Meta to revolutionize the way code reviews are conducted. Model integrated with AI model using [Groq API](https://console.groq.com/keys), Code Bat AI delivers efficient and intelligent code analysis, helping developers enhance code quality while reducing manual review effort.

## Features

- **🏷️ Issue Labeler**:  
  Automatically adds relevant labels to issues based on their title and description, simplifying project management and reducing manual effort.

- **📜 PR Review**:  
  Generates detailed summaries for pull requests, covering all aspects such as new features, refactoring, bug fixes, and more. It updates PR descriptions and provides a comprehensive walkthrough of changes, along with a summary table for a quick overview by writing a comment.

- **❤️ AI-Based Code Review**:  
  The core feature of Code Bat AI, the AI-Based Code Review, transforms traditional code reviews by analyzing code changes, identifying potential issues, and suggesting improvements. It doesn't just stop there - it also provides code replacements and raises change requests to ensure code quality while saving time and effort. It reviews each file's changes in different code patches, analyzing and pinpointing specific areas that need attention. After thoroughly examining every file and code patch, it initiates a review thread, facilitating detailed discussions and collaboration among team members.

- **🌿 Branch Management**:  
  Automatically handles branch deletion post-merge, keeping repository clean and organized.

## Usage

### Setup and Configuration

For instructions on how to set up and configure the application locally : 
- [Configuring a GitHub App](https://probot.github.io/docs/development/#configuring-a-github-app)
- [Manually Configuring a GitHub App](https://probot.github.io/docs/development/#manually-configuring-a-github-app)

### Issue Labeler

1. Add a new issue in your project.
2. The bot will automatically add relevant labels based on the issue’s title and description.

### PR Review

1. Create a new pull request.
2. The bot will update the PR description with possible aspects of changes like featre/refactor/bug-fix/chores etc-
3. Also bot will write a detailed short walkthrough for that changes made on the basis of commeits messages and code changes.
4. Additionally, the bot will analyze the code changes, suggest improvements, and raise change requests in signle thread.

### Branch Management

1. Merge a pull request.
2. The bot will automatically delete the corresponding branch after mentioning the branch deletion in comment by tagging author, keeping your repository organized.