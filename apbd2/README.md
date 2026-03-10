**1) When does Git perform a fast-forward and when is a merge commit created?**

* Fast-forward: Happens when the target branch has no new commits since the branch was created.
* Merge commit: Created when both branches have new commits. Git combines the histories and creates a new merge commit to join them.

**2) What is the practical difference between merge and rebase?**

* Merge: Combines branches and preserves the full branch history, creating a merge commit.
* Rebase: Rewrites history by moving commits on top of another branch, without merge commits.

**3) How was the conflict resolved in your repository?**
   
The conflict was resolved editing conflict files in feature-conflict and main branches, choosing the correct version using 
Rider tool for solving merge conflicts and finalizing the operation with git add + git commit + git push.