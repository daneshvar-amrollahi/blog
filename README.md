* Generating the static files of the site to be stored in the `public/` directory (gitignored):
    ```
    $ hugo -t xmin
    ```

    Once the static files are generated, go to the `public/` directory, and push the changes to the remote repository being `https://github.com/<GitHubID>/<GitHubID>.github.io.git`

* View the site locally:
    ```
    $ hugo server
    ```

* Set up repo on a new machine:
1. `git clone https://github.com/daneshvar-amrollahi/blog`
2. `git checkout cs-stanford`
3. `git clone https://github.com/daneshvar-amrollahi/daneshvar-amrollahi.github.io public`
4. `cd public`
5. `git checkout cs-stanford`