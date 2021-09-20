# Pull Requests


### Steps for Conducting a Pull Request

1. [Create a Branch](https://dbrown-accenture.github.io/#/docs/02_github/02_repositories?id=creating-a-new-branch)
1. Checkin the Changes
1. Create Pull Request
1. Merge Branch



### Branching Workflow

*Description*

When working on a task, you should usually create a branch, specifically for the task item. The branch and the task should be linked through the ticket number and the branch name. When creating a new branch to manage a task's work, you should name the branch after the task's ticket number. For example if the Jira task number is `DEV-3219`, then you would name your branch the same value of  `DEV-3219`.


#### Feature Branch Diagram

```mermaid

gitGraph:
options
{
    "nodeSpacing": 150,
    "nodeRadius": 10
}
end
commit
branch DEV-3219
checkout DEV-3219
commit
checkout master
commit
merge DEV-3219


```

### Creating a Pull Request

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
