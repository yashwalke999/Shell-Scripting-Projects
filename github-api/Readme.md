# 🚀 GitHub Active Users Extractor

Author: YASH S. WALKE  
Date: 11th Feb 24  
Version: v1.0  
Purpose: To extract the active users of a GitHub repository by Github API 

---

## 📝 Description

The **GitHub Active Users Extractor** is a Bash script that automates the extraction of active users from a GitHub repository. By leveraging the GitHub API, this script simplifies access management for repository administrators and DevOps engineers by providing a quick and efficient way to identify users with pull access to the repository.

---

## 🔍 Why This Script

Managing access permissions for GitHub repositories is crucial, especially in collaborative environments. This script addresses the need for administrators to easily identify active users. By automating this task, it saves time and effort, allowing administrators to focus on other essential aspects of repository management.

---

## 🛠️ Requirements

- **GitHub Account:** Access to the repository you want to extract active users from.
- **Personal Access Token:** Generate a personal access token on GitHub with appropriate permissions (e.g., `repo` scope) for API authentication.
- **Bash Environment:** The script is written in Bash and requires a Bash-compatible environment.
- **jq**: Ensure `jq` is installed on your system for parsing JSON responses from the GitHub API.

---

## 🚀 Usage

To use the GitHub Active Users Extractor, follow these steps:

1. Clone this repository or download the script file `github_active_users_extractor.sh`.
2. Set up a personal access token on GitHub with appropriate permissions.
3. Open the script file and replace `$username` and `$token` with your GitHub username and personal access token, respectively.
4. Run the script, providing the repository owner's username and the repository name as arguments.

```bash
./github_active_users_extractor.sh owner_username repository_name
