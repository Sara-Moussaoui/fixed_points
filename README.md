# fixed_points
# ProjectTemplate

- [Description](#description)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)


## Description

...


## Authors

**First-Name Last-Name** | @github_handle | contact@example.com


## Acknowledgments

...


## Installation

> [!TIP]
> To set up this project on a local machine, follow the steps below:

### Initialize a local copy

1. Navigate to the local directory where the root folder of the repository should reside.
  
2. Copy the URL of the project in the "Code" section of the main page.<br>
   Format: ```git@github.com:<owner-name>/<repository-name>.git```
  
3. Clone the repository:
```
git clone <repository-url>
```

### Create a virtual environment

1. Create an dedicated conda environment containing all the dependencies:
```
conda env create -f environment.yml
```

2. Register the package in "editable mode":
```
conda activate <env-name>
pip install -e /src/<package-name>
```

## Usage

...


## Contributing

> [!IMPORTANT]
> To contribute effectively, please conform to those guidelines and use the provided templates.

### Using the Issue Template

To submit a new issue:

1. In the repository page, navigate to the "Issues" tab and click on "New Issue".
2. Select the issue template.
3. Fill in the required information, following the structure provided.
4. Add relevant labels, assignees, and milestone if applicable.

### Using the Commit Message Template

1. Navigate inside the repository directory:
```
cd <repository-name>
```
   
2. Register the file to use as the commit template:
```
git config commit.template .git-message
```
   
3. Verify the configuration:
```
git config --get commit.template
```

> [!NOTE]
> To write a commit message with this template, adhere to the following format:
>
> - Capitalize the subject, do not add a period at the end
> - Limit the subject line to 50 characters
> - Use the imperative mood in the subject line
> - Separate subject from body with a blank line
> - Wrap the body at 72 characters per line
> - Use the body to explain what and why (not how)
> - Add references to issues or other commits using [GitHub keywords](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/using-keywords-in-issues-and-pull-requests)




