# Automated GitHub Repository Creation with Selenium

This project demonstrates how to automate the creation of a GitHub repository using Selenium. The automation script collects necessary repository details and GitHub login credentials from the user, then automatically creates a new repository on the user's GitHub account.

## Features

- Automated login to GitHub with provided credentials.
- Automated creation of a new repository with specified details.
- Customization options for repository name, description, visibility (public/private), and more.

## Prerequisites

- Python 3.x
- [Selenium](https://pypi.org/project/selenium/)
- [WebDriver](https://selenium.dev/documentation/webdriver/getting_started/install_drivers/) (e.g., ChromeDriver for Google Chrome)
- GitHub account

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo.git
    cd your-repo
    ```

2. **Install dependencies:**
    ```bash
    pip install selenium
    ```

3. **Download the appropriate WebDriver** for your browser and ensure it is in your PATH.

## Usage

1. **Update the script with your GitHub login details and desired repository details.**

2. **Run the script:**
    ```bash
    python automate_github_repo.py
    ```

3. **The script will:**
    - Open a browser window.
    - Log into GitHub using your credentials.
    - Create a new repository with the supplied details.



> **Note:**  
> - For security, avoid hardcoding your credentials. Consider using environment variables or secure credential storage.
> - Using Selenium to automate login may violate GitHub's terms of service and can be blocked by CAPTCHAs or security measures. Prefer using the [GitHub API](https://docs.github.com/en/rest) for automation.

## License

This project is licensed under the MIT License.

## Disclaimer

This script is for educational purposes only. Automating login to websites may violate their terms of service. Use responsibly.
