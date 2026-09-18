1. What did the rejected push error message tell you, and why did it happen?

My push was rejected because the error said that the remote had changes that I did not have locally. This happened because Clone A and Clone B had different commits on the same branch.

2. What's the actual difference between how you resolved Task 3 (merge) vs Task 4 (rebase)?

For Task 3, I used merge to combine both branches and then resolved the conflict. For Task 4, I used rebase to put my local commit on top of the updated remote branch and then resolved the conflict.

3. What one habit would have avoided both rejected pushes in this lab?

I should have fetched the latest changes from the remote before making new changes. This would have helped me know that another clone had already pushed changes.

4. Which approach - merge or rebase - would you default to on a shared team branch, and why?



I would default to merge on a shared team branch because it preserves the existing commit history. It also avoids rewriting commits that other team members may already have.



