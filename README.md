# PyDevEnv

PyDevEnv provides a general guide to setting up a collaborative Python development environment.

## Terminal

You will rely heavily on the command line which can be accessed by opening a new terminal window.

<details>
<summary>Opening A Terminal Window</summary>
&nbsp;

| OS      | Command                                    |
|---------|--------------------------------------------|
| Linux   | Ctrl - Alt - T                             |
| Mac     | Spotlight > type "terminal" > Enter / OK   |
| Windows | Start > type "powershell" > Enter / OK     |

</details>

<details>
<summary>Checking Your Current Directory</summary>
&nbsp;

| OS      | Command                                    |
|---------|--------------------------------------------|
| Linux   | `pwd`                                      |
| Mac     | `pwd`                                      |
| Windows | `cd`                                       |

</details>

<details>
<summary>Navigating Into Different Directories</summary>
&nbsp;

| OS      | Command                                    |
|---------|--------------------------------------------|
| Linux   | `cd /path/to/directory/`                   |
| Mac     | `cd /path/to/directory/`                   |
| Windows | `cd \path\to\directory\`     	             |

Omit the first forward slash if you wish to navigate into a subdirectory of the **current** working directory.

</details>

<details>
<summary>Moving Up Into Parent Directories</summary>
&nbsp;

| OS      | One Directory                                    | Two Directories |
|---------|--------------------------------------------------|-----------------|
| Linux   | `cd ..`                                          | `cd ../..`      |
| Mac     | `cd ..`                                          | `cd ../..`			 |
| Windows | `cd ..`     	             								       | `cd ..\..`      |

</details>

## Language

This project uses **Python >= 3.8.10** as its primary language. You can check the version of Python currently installed on your machine with the following command:

```
python3 --version
```

If your current Python version is lower than that specified above, you can download a more recent version [here](https://www.python.org/downloads/).

## Version Control

This project uses [**Git**](https://git-scm.com/) for version control and [**GitHub**](https://github.com/) for file hosting.

Instructions for installing Git on your operating system can be found [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

If you don't already have a GitHub account, go ahead and create one [here](https://github.com/signup).

## Dependency Management

This project uses [**Poetry**](https://python-poetry.org/) for dependency management and project packaging.

Instructions for installing Poetry on your operating system can be found [here](https://python-poetry.org/docs/#installation).

## Linting and Formatting

Using the [**Flake8**](https://flake8.pycqa.org/en/latest/) linter is highly recommended. Running Flake8 will tell you if your code adheres to Python PEP8 standards, and will provide useful warnings such as having unused imports or variables.

Flake8 can be installed globally with the following command:

```
pip3 install flake8
```

Using the [**Black**](https://github.com/psf/black) formatter is also highly recommended. Running Black will automatically format your code to consistent (and highly opinionated) standards so that you do not need to spend time worrying about details such as how to break your code onto multiple lines or whether to use double or single quotes.

Black can be installed globally with the following command:

```
pip3 install black
```

Many IDEs offer the ability to run Flake8 and Black automatically while you write code instead of having to invoke them separately from your terminal. [VSCode](https://code.visualstudio.com/) is perhaps the easiest IDE to set up in this regard.

A guide on how to configure Flake8 and Black in VSCode can be found [here](https://py-vscode.readthedocs.io/en/latest/files/linting.html) and [here](https://dev.to/adamlombard/how-to-use-the-black-python-code-formatter-in-vscode-3lo0).
