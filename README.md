# Guidelines for Internal Maintainers

> To standardize workflow across multiple repositories, please follow these guidelines before opening issue, working on the issue, or making pull requests.

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

### Custom Issue Labels

- ![#0052CC](https://via.placeholder.com/15/0052CC/000000?text=+) `#0052CC` : Back End
- ![#FBCA04](https://via.placeholder.com/15/FBCA04/000000?text=+) `#FBCA04` : Front End

---

---

## Solving Issue Workflow

### Starting Steps

To start working on your assigned issue (*Must be in **TO DO** status first*): 

1. Switch the issue status to `In Progress`.

![image](https://user-images.githubusercontent.com/46631787/144339253-df59331c-fe24-461e-9ed6-2773a2ec8391.png)

2. On your local project `main` branch, `git pull origin main`
3. Create new branch, `git checkout -b [feat/fix/hotfix]/[simple-issue-name]/ELA-[issue_number]_dev_main`
    - Example: `git checkout -b feat/landing-page/ELA-001_dev_main`
    - Notice the `dev_main`
5. After creating `dev_main` branch, make new branch for the specific task `git checkout -b [feat/fix/hotfix]/[simple-issue-name]/ELA-[issue-number]_[simple-descriptive-task-name]`
    - Example: `git checkout -b feat/landing-page/ELA-001_banner_carousel_component`
    - Notice the `banner_carousel_component`
6. You can start developing at that `"banner_carousel_component"` branch 

### Making Pull Request

Assigned dev, should only make Pull Request to his/her own `dev_main` branch.

Here, we will use from previous section example branch.

1. Push both `feat/landing-page/ELA-001_dev_main` & `feat/landing-page/ELA-001_banner_carousel_component` branches to the project.
2. On the pull request menu, *New pull request* then set **base section** to your `dev_main` branch, and **compare section** to your `banner_carousel_component` branch
3. Add your project lead as **reviewer** to your pull request.

![image](https://user-images.githubusercontent.com/46631787/144339324-9d31f21a-8db0-4cea-972b-3404e9418596.png)

4. Go back this issue menu, switch the issue status to `Ready to Review`

![image](https://user-images.githubusercontent.com/46631787/144339222-e0143cf7-276f-4781-b028-dc1cfdbc2382.png)


5. Text your lead. 😂📞
6. You can keep adding commits to your `banner_carousel_component` branch until it is merged.
7. No need to worry anymore! 😁 


