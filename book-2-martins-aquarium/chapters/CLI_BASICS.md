# Setting Up Your Project

## Learning Objectives

* You should be able to create new directories in the terminal with the `mkdir` command.
* You should be able to create new files in the terminal with the `touch` command.
* You should be able to navigate directories in the terminal with the `cd` command.


## Getting Started

1. Make a new project directory in workspace
    ```sh
    cd ~/workspace
    mkdir martins-aquarium
    ```
2. Navigate to your project directory
    ```sh
    cd martins-aquarium
    ```
3. Type in the `git init` command
4. You now have a git repository for tracking your progress

## Project Files

Once the directory is created, you need to create the HTML file and the CSS file. The standard name for the initial HTML for any web site is `index.html`.

Create the file with the following command.

```sh
touch index.html
```

Next, create a `styles` sub-directory and create a file named `main.css` in it.

```sh
mkdir styles
touch styles/main.css
```

Create another sub-directory named `scripts` and create a file named `main.js` in it.

```sh
mkdir scripts
touch scripts/main.js
```

## Create Github Repo

1. Log into your Github account.
1. Click the `+` sign in the top right corner.
1. Choose "New repository".
1. In the "Repository name" field, enter in `martins-aquarium`.
1. Scroll down and click the green "Create Repository" button.
1. Copy the repository's connection string.
    ![](./images/copy-github-connection-string.gif)
1. Follow the second set of instructions.
    ![](./images/add-origin.png)

Now that the code has successfully been backed up, go back to your browser, and refresh the page. You will see that your remote repository backup now has your aquarium HTML, JavaScript and CSS files in it.
