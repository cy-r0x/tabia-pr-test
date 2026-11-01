# tabia-pr-test

A small Java program with a `divide` function and a `main` method that prints the happy path (`10 / 2`).

## Contributing

Changes are reviewed through a pull request. A pull request is a proposal to merge your branch into `main` on [cy-r0x/tabia-pr-test](https://github.com/cy-r0x/tabia-pr-test). You work on your own copy of the repository, push that work to GitHub, then open the request in the browser so it can be reviewed before it lands on `main`.

You need a [GitHub account](https://github.com/signup) and [Git](https://git-scm.com/downloads) installed. The commands below use the terminal.

### 1. Fork the repository

A fork is your personal copy of this repository on GitHub. Open [cy-r0x/tabia-pr-test](https://github.com/cy-r0x/tabia-pr-test) and click **Fork** in the top right. Leave the owner as your account and click **Create fork**.

GitHub then opens `https://github.com/<your-username>/tabia-pr-test`. That copy is yours. Commits you push go there, not straight into this repository.

### 2. Clone your fork and create a branch

Cloning downloads your fork onto your computer. A branch is a separate line of work, so your change stays off `main` until the pull request is merged.

Replace `<your-username>` with your GitHub username:

```bash
git clone https://github.com/<your-username>/tabia-pr-test.git
cd tabia-pr-test
git checkout -b your-change
```

`your-change` is the branch name. Pick a short name that describes the work, such as `fix-divide-message`. Use that same name in the later steps.

### 3. Make the change, commit it, and push

Edit the files, then save them in Git with a commit. A commit is a snapshot plus a message that says what you changed. Pushing uploads that branch to your fork on GitHub.

```bash
git add .
git commit -m "Describe the change."
git push -u origin your-change
```

`git add .` stages every change in the folder. The commit message should say what the change does, for example `Print the division result with a label.` The first push of a new branch needs `-u` so Git remembers that `your-change` tracks `origin/your-change`. Later pushes of the same branch can be `git push`.

### 4. Open the pull request in the browser

After the push, GitHub can compare your branch with `main` on this repository. Open this page, again replacing `<your-username>` and using your real branch name:

https://github.com/cy-r0x/tabia-pr-test/compare/main...<your-username>:your-change

Check the two sides at the top of the page before you continue:

- **base repository:** `cy-r0x/tabia-pr-test`, **base:** `main`. This is the branch your change will merge into.
- **head repository:** `<your-username>/tabia-pr-test`, **compare:** `your-change`. This is the branch you just pushed.

If the compare list is empty, the branch name in the URL does not match the branch you pushed.

Click **Create pull request**. Write a title and a short description of what changed and why, then click **Create pull request** again. That opens the request. The repository owner can review it, ask for changes, and merge it into `main`.
