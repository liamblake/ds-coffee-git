2. **Why git?**

- Highly controllable backup system.
  So it backs up your work in a way that is available both online and offline

- Git encourages modularisation in code design

3. What is Github?

- Github is an online serive for hosting repositories and managing projects.
- It's (mostly) free.
- Good integration with things like VSCode and Overleaf

4. **Let's create a repo**

Show how to create a repo on Github:

- Public vs private
- Mention choosing a gitignore template. Will talk about gitignore later.
- Start with a readme so the repo has something.

5. **Cloning**

- So we've created the "online" version of our repository, which is called the "remote".
- The first thing we should do is create a local copy so we can make changes.
- This is called "cloning" the repository
-

6. Basic workflow

- Here's a very basic git workflow

- First, you should update from remote, or at least know what changes have happened. I've called this step 0 because it only matters if changes from elsewhere have happened.

6. **Adding and committing files**

7. **Pushing and pulling**

8. **Updating from remote**

9. **Gitignore**

10. **A few random tips (if time)**

- Adding to the most recent commit or changing the commit message

```shell
git commit --amend
```

- Undoing your last commit

```shell
git reset HEAD~1
```

- Overwrite the remote with whatever is on the local (dangerous)

```shell
git push --force
```

10. **IDE integration**
    Dylan
