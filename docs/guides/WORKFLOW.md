## 🚦 Workflow

_Copyright (c) 2025. [Sergio Ridaura](https://github.com/sergio-ridaura)._

The proposed workflow for project development with this template is designed to provide clarity, structure, and efficiency, facilitating implementation aligned with team objectives. This template integrates best practices and recognized methodologies such as **[GitHub Flow](https://docs.github.com/get-started/using-github/github-flow)** and **[Kanban](https://asana.com/resources/what-is-kanban)**, ensuring a collaborative, organized, and adaptable process.

Use this workflow as a flexible guide that you can customize according to your project's characteristics. Adjust the stages and details as needed to fit your team and specific development goals.

### Workflow Stages

After starting the project and completing the **Initial Setup** (see [DEVELOP](DEVELOP.md)), the workflow is structured into the following main stages. These stages are repeated iteratively, usually in two-week cycles, as many times as necessary to achieve the project's objectives:

#### 1. Task Selection

In this stage, the team reviews and selects the tasks to be addressed in the cycle. The chosen tasks are moved to the **To Do** column of the Kanban board. It is essential that each task is clearly defined, prioritized, and documented in the [Action Plan](ACTION_PLAN.md), ensuring shared understanding, facilitating tracking, and enabling efficient execution by developers.

If a task is not fully defined or requires more information, it can be moved to the **Pending** column of the Kanban board. This allows the team to quickly identify tasks that need more details before being addressed.

#### 2. Development

In this phase, developers tackle the assigned tasks, moving them to the **In Progress** column of the Kanban board. Each task is developed in an independent branch of the repository, following the **GitHub Flow** model, which allows for isolated work and facilitates later integration.

**GitHub Flow** is an agile methodology based on creating branches for each new feature or fix. This approach encourages parallel work and minimizes conflicts in the main codebase.

If it is not possible to move forward with a task, it can be moved to the **Blocked** column of the Kanban board. This allows obstacles to be quickly identified and facilitates collaboration to resolve them.

Upon completing a task, a **Pull Request** (PR) is generated to request code review before merging it into the main branch. The PR should include a detailed description of the changes, references to the corresponding tasks, and any relevant information to facilitate the review.

Reviewers collaborate by providing comments and constructive suggestions. Once the PR is approved, it is merged into the main branch, updating the project status and allowing the rest of the team to access the implemented changes.

When a task is completed, it is moved to the **Completed** column of the Kanban board, providing visibility into the project's progress.

#### 3. Review

At this stage, at the end of the development cycle, the team reviews the overall status of the project and evaluates the progress made. Completed tasks are analyzed, areas for improvement are identified, and key learnings are gathered. In addition, possible obstacles encountered are discussed, and the next steps or necessary adjustments for the next cycle are defined, ensuring continuous improvement in the development process.

#### 4. Deployment

In this phase, at the end of the development cycle, the team prepares the project for deployment to the production environment. The implemented changes are carefully reviewed, final tests are run to validate stability and correct system operation, and it is verified that all requirements are met. Once these validations are passed, deployment is carried out, updating the production version and ensuring that users have access to new features and improvements. This process should be documented and preferably automated to minimize errors and ensure reliable delivery.

### Conclusion

This workflow provides a clear and efficient structure for project development, promoting collaboration and software quality. By following these stages and best practices, your team will be able to manage the project effectively, ensuring that objectives are met and a high-quality product is delivered. Remember that this workflow is flexible and can be adapted to the specific needs of your project. Good luck!
