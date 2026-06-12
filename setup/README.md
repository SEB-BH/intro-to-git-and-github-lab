<h1>
  <span class="headline">Git & GitHub Lab</span>
  <span class="subhead">Setup</span>
</h1>

## Requirements

Before starting, make sure you have:

- Git installed
- A GitHub account
- A `labs` folder where you save class lab work
- VS Code installed

## Open your terminal

Open your Terminal application and navigate to your **`~/code/ga/labs`** directory:

```bash
cd ~/code/ga/labs
```

Navigate to [GitHub](https://github.com/new) and create a new repository named **intro-to-git-lab**.

**Use these settings:**
* ✅ Repository name: `intro-to-git-lab`
* ✅ Visibility: Public
* ❌ Do **not** initialize the repository with a `README.md`
* ❌ Do **not** add a `.gitignore`
* ❌ Do **not** add a license

![New Repo Config](../assets/new-repo-config.png)

Using the `Quick Setup` option, clone your newly created repo into your `~/code/ga/labs` directory with the `git clone` command:

![Git HTTP](../assets/git-http.png)

```bash
git clone <your-repo-link>
```

> Note: In the link above, where it says `<your-repo-link>`, you should paste the link you cloned from github.

Your terminal might give you a warning that you appear to have cloned an empty repository.  That is OK.  Continue.

![Empty Repo](../assets/empty-repo.png)

Next, `cd` into your new cloned directory, `intro-to-git-lab`:

```bash
cd intro-to-git-lab
```

Create a file named `notes.txt`:

```bash
touch notes.txt
```

- Run the `ls` command
- Your terminal should show the `notes.txt` file.

![Checkpoint](../assets/notes.png)


Open the folder in VS Code:

```bash
code .
```

You are ready to begin!