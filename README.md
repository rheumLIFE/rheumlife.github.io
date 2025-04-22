# How To Use mdBook with GitHub pages

- **KEEP it simple.** *Do NOT copy somebody's complexicated cornfuckluation.* **Even this one!!!** ***Start from scratch.***

- [Install mdBook](https://rust-lang.github.io/mdBook/guide/installation.html) on your local machine, [create a book](https://rust-lang.github.io/mdBook/guide/creating.html) and get mdBook running so that you can play with your sandbox installation and book a bit ... *but do not play too much,* just KEEP your sandbox book simple.

- Create a brand new, **completely EMPTY** repository on Github

- Clone your new EMPTY repository to your local machine

- Copy ALL of the files from your minimal sandbox to you new empty repository

- In a terminal, cd into your new repository and run the `mdbook serve --open` command to assure yourself that the copied sandbox is operational in the new repository.

- Commit the working code to GitHub before making any extra additions, configurations, *keep your process as simple as possible* ... and then navigate to your new repository on Github and confirm the commit happened

- At your repository, go to `Settings`, then `Pages`, under the **Build and Deployment** heading, select the `GitHub Actions`, then configure an **mdBook** Actions to produce a `mdbook.yml` file in the `.github/workflows` directory of your new repository.  **Do NOT add/change anything in the code suggested by GitHub at this point,** *just `Commit changes`, do not change the Commit msg, just `Commit changes`.

- After a few minutes, navigate back to your new repository, go to `Settings`, then `Pages`, click on the link that follows **Your site is live at** and copy that address to the `About` settings on your repositories landing page on Github.

- OPTIONAL: Create a backup repository by copying all of your folders from your WORKING new directory to backup sandbox, to have a fallback position, a reference point or just in case you want to rollback to a simpler thing that worked.

- THEN ***complexicate*** at will.
