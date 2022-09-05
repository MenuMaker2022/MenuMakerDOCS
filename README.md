# MenuMakerDOCS

## GitHub Workflow
  * **If you have the repo locally:**
    * checkout the base branch if it's not already available : 
       `git checkout <base_branch_name>` - *you should be inside the repo main folder*
  * **if you don't have the repo locally**
    * change directory to a folder where you want to have the source code
    * clone the repository : `git clone -b <base_branch> <ssh_link/html_link>`
  * ensure that you don't have other uncommitted changes : 
     `git fetch origin && git reset --hard origin/HEAD && git clean -d -f`
  * create a feature branch from the base branch: `git checkout -b <feature_branch_name>` 
  * create your changes
  * add your changes ( preparing them for committing): 
       * `git add .` or `git add *` for adding all the files changed 
       * `git add <filename>` in order to add only a specific file
  * commit your changes addend: `git commit -m "<message_for_commit>"`
  * push your changes to the remote : `git push origin <feature_branch_name>` 
