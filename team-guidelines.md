<!-- Add a new file called team-guidelines.md to the repository that documents your team's collaboration practices. This file should include:

    A brief introduction explaining the purpose of the guidelines
    A section on branch naming conventions
    A section on commit message best practices
    A section on the Pull Request process -->

Intro:
The purpose of this is project to demonstrate mastery of the entire collaborative development cycle—from individual feature work to team integration.

Branch Naming Conventions:
Conventional branching standards establishes a shared naming pattern that instantly communicates three critical pieces of information:
1. What type of work is happening (feature development, bug fix, release preparation)
2. What specific change the branch addresses (user authentication, login redirect error)
3. How the branch fits into the team's workflow (ready for review, experimental, production-bound)
These conventions aren't enforced by Git itself—Git will accept any branch name you give it. Instead, they're team agreements that make collaboration scalable. When everyone follows the same naming pattern, you can glance at a branch list and immediately understand the state of the project. 

Commit Messages Best Practices:
Professional commit messages follow a consistent structure that maximizes clarity and usefulness. The standard format consists of three parts:
1. Summary Line (50 characters or less)
The first line is a brief, imperative summary of what the commit does. Use the imperative mood—write as if you're giving a command: "Add user authentication" not "Added user authentication" or "Adds user authentication." This convention matches Git's own automatically generated messages (like "Merge branch 'feature'") and creates consistency across your history.
Keep this line under 50 characters so it displays cleanly in git log --oneline and GitHub's commit list views. Think of it as a subject line in an email—it should be scannable and informative at a glance.
2. Blank Line
Always include a blank line between the summary and the body. This separation is crucial—many Git tools rely on it to parse commit messages correctly. Without it, the body text may be treated as part of the summary, breaking formatting in various interfaces.
3. Detailed Body (optional but recommended for complex changes)
After the blank line, provide additional context: why you made this change, what problem it solves, and any important decisions or trade-offs. Wrap lines at 72 characters for readability in terminal displays. The body should answer questions like:
    What was the motivation for this change?
    How does this differ from the previous implementation?
    Are there any side effects or limitations?
    What alternatives were considered?

Pull Request Process:
A pull request (PR) process involves
developing code on a feature branch, pushing it to a repository, and opening a request to merge changes into the main branch. Team members review, discuss, and test the code. Upon approval and passing automated checks, the code is merged.
