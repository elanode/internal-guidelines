# Guidelines for Internal Maintainers

## All About Issues Management

The entries in issues tab (menu) at each repository represents what needs to be done on that specific task. Each issue should be somewhat follows the template as shown below to homogenize issues between repositories.

### Opening Issue Steps

1. The **title** should describe short explanation about the task.

![image](https://user-images.githubusercontent.com/46631787/144267594-42d9e70a-6421-4abb-bae9-15891d0d915f.png)

2. Issue template : 

```
## Case 👀 
- Product search does not work.

## To Do / Expected 🔨 
- Product should match the search input.

## Notes 📝
- [insert some additional notes]

## Captures 📸
- [insert some screenshots]
```

3. Big issue may be broken down to sub-tasks (by project leads) :

```
## Case 👀 
- Product search does not work.

## To Do / Expected 🔨
- Product should match the search input.

- [ ] Backend API search query fix
- [ ] Frontend handle new data response

## Notes 📝
- [insert some additional notes]

## Captures 📸
- [insert some screenshots]
```

4. Add appropriate labels to the issue.

![image](https://user-images.githubusercontent.com/46631787/144267126-c6493c6e-5545-4a80-a673-acb20020a1e6.png)

5. On the projects tab on the right side of the issue. Please add the issue to **Elanode's Development Tracker** Project ‼

![image](https://user-images.githubusercontent.com/46631787/144267318-8b4c0baa-06f0-4e32-8fc6-d51b665a2bd0.png)

6. Once opened and added to **Elanode's Development Tracker**, the issue will have *On Queue* status.

### Issues Status

1. On Queue ⌚ : Waiting to be approved by project lead to proceed for assigning dev.
2. To Do ⚠ : Issue approved and assigned to dev and ready to develop.
3. In Progress 🛠 : The assigned dev moved the status to *In Progress* from that issue page at projects tab on the right side.
4. Ready to Review 👀 : The assigned dev open new pull request and ready to be reviewed by project lead.
5. Ready to Deploy ✔ : The changes are approved and ready to deploy to servers.
6. Done 🏁 : Well, it's done. 

### Labels

1. BE #0052CC : Back End
2. FE #FBCA04 : Front End
