1. **Q: What's the difference between a tag and a branch?**<br/>_A: A tag is basically a bookmark that associates a textual name to a particular commit. Tags are usually used to mark a point where a release was made.  A tag is not a branch, but you can create a branch based off of a tag._
2. **Q: Is there a way to do "git flow feature|bugfix finish..." and have it NOT delete the branch?**<br/>_A: You can add the -k (keep) command line option (e.g. "git flow bugfix finish -k ...")._
3. **Q: What are other git flow command line options?**<br/>_A: See [this link](https://github.com/nvie/gitflow/wiki/Command-Line-Arguments)._
3. **Q: How do I rebase my branch to develop?**<br/>_A: Use "git flow feature|bugfix rebase...".<br/>Example:  git flow bugfix rebase my_branch_name_  
