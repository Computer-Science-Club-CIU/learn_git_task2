# Git CTF - Hidden Flag Challenge

Welcome to the Git CTF - Hidden Flag Challenge! This repository is designed to test your Git skills by discovering a hidden flag within the commit history.

## Challenge Description

In this challenge, a hidden flag has been added to the repository through a commit. Your task is to analyze the commit history and extract the flag.

## Instructions

1. Clone the Repository: `git clone <repository-url>`Replace `<repository-url>` with the URL of this repository. Use the `git clone` command to create a local copy of the repository on your machine.

2. Analyze the Commit History:
   Use the following command to view the commit logs:
   git log

Examine the commit history, including the commit messages and commit hashes, to identify the specific commit that added the hidden flag.

3. Extract the Hidden Flag:
   Once you have identified the commit, use the following command to view the changes made in that commit:
   git show <commit-hash>Replace `<commit-hash>` with the commit hash of the specific commit that added the flag. This command will display the diff and any added or modified files in that commit. Extract the hidden flag from the changes.

4. Challenge Completion:
   Once you have discovered the hidden flag, consider yourself successful in completing the challenge! Remember not to spoil the challenge for others by revealing the flag or commit details. if you have any Questions you can ask on the discord channel

## Additional Resources

If you are new to Git or want to enhance your Git skills, here are some resources you can explore:

- [Pro Git Book](https://git-scm.com/book/en/v2): A comprehensive guide on Git with detailed explanations and examples.
- [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials): In-depth tutorials and guides on using Git in various scenarios.
- [GitHub Git Handbook](https://guides.github.com/introduction/git-handbook/): A beginner-friendly guide to Git by GitHub.

## Disclaimer

This challenge is purely for educational and learning purposes. It aims to provide a practical exercise to enhance your Git skills. Please respect the rules and guidelines of the challenge and refrain from any unauthorized or unethical activities.

Happy flag hunting!
