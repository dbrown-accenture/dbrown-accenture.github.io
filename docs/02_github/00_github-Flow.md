

# The GitHub Flow

1. Create a Branch
2. Add Commits
3. Open a Pull Request
4. Discuss and Review your Code
5. Deploy


## 1. Create a Branch

```
✨ git checkout -b DEV-3219    
Switched to a new branch 'DEV-3219'
```

## 2. Add Commits

Add local files to staging environment, then add a commit message for the change set
```
✨ git add .

✨ git commit -m "adding changes"
[DEV-3219 d385437] adding changes
 6 files changed, 93 insertions(+), 19 deletions(-)
```


Push the committed changeset (Note: on the first push to a new branch, you must use the --set-upstream command)
```
✨ git push
fatal: The current branch DEV-3219 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin DEV-3219

✨ git push --set-upstream origin DEV-3219
```

## 3. Open a Pull Request

After pushing a new branch to GitHub, you will be able to find it in the list of branches. If a branch has recently been pushed to the repo, then you will see the notification with the option to create a new Pull Request. You can also create a pull request on the "Pull requests" tab on the GitHub repository's web page.

<table>
    <tr>
        <td>
            <i>Figure A</i>
            <br /><br />
            <img src="images/repo-recent-push.png" width="100%%" height="auto" />
        </td>
        <td>    
            <br />        
            <i>Figure B</i>
            <br /><br />
            <img src="images/create-pr.png" width="100%" height="auto" />
        </td>
    </tr>
</table>


## 4. Discuss and Review your Code


## 5. Deploy



