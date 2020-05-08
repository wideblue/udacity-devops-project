# udacity-devops-project
Projects for udacity  devops  nanodegree.


### Project 2


![AWS projec solution diagram](images/udacity-project-2.png "Project diagram")


#### Deploy 

There are three cloudformation script that would create three stacks in the following order :
1. network
2. servers
3. bastion

There are helper scripts for stack create and deploy in `scripts` dir, use:

```
./create.sh <stack-name> <template-body file> <parameters file>
```
or 

```
./update.sh <stack-name> <template-body file> <parameters file>
```

