# Pull Requests


### Steps for Conducting a Pull Request

1. Create a Branch
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


