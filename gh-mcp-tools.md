This guide provides hands-on activities for all 91 GitHub MCP tools. Each activity includes real-world scenarios and step-by-step demonstrations.

## Prerequisites Setup

Before starting, ensure you have:
- GitHub account with appropriate permissions
- VS Code with GitHub Copilot Chat extension
- MCP configuration in `.vscode/mcp.json`:

```json
{
  "servers": {
    "github": {
      "type": "http",
      "url": "https://api.githubcopilot.com/mcp/"
    }
  }
}
```

## Activity Categories

### 1. Repository Management (15 tools)

#### Activity 1.1: Repository Creation and Setup
**Tools Used:** `create_repository`, `get_repository`, `update_repository`

**Scenario:** Create a new project repository for a professional portfolio website.

**Steps:**
1. **Create Repository**
   - Ask Copilot: "Create a new repository called 'student-portfolio' with description 'My personal portfolio website' and make it public"
   - Tool: `create_repository`
   - Expected outcome: New repository created with README

2. **Get Repository Details**
   - Ask Copilot: "Get details about the student-portfolio repository"
   - Tool: `get_repository`
   - Expected outcome: Repository metadata, clone URLs, default branch

3. **Update Repository Settings**
   - Ask Copilot: "Update the repository description to include 'Built with HTML, CSS, and JavaScript'"
   - Tool: `update_repository`
   - Expected outcome: Updated repository description

#### Activity 1.2: Repository Visibility and Settings
**Tools Used:** `get_repository_topics`, `replace_repository_topics`, `delete_repository`

**Steps:**
1. **Add Topics**
   - Ask Copilot: "Add topics 'portfolio', 'javascript', 'html', 'css' to the repository"
   - Tool: `replace_repository_topics`

2. **View Topics**
   - Ask Copilot: "Show me all topics for this repository"
   - Tool: `get_repository_topics`

#### Activity 1.3: Repository Collaboration
**Tools Used:** `list_repository_collaborators`, `add_repository_collaborator`, `remove_repository_collaborator`

**Steps:**
1. **List Current Collaborators**
   - Ask Copilot: "Who are the current collaborators on this repository?"
   - Tool: `list_repository_collaborators`

2. **Add Collaborator**
   - Ask Copilot: "Add 'colleague-username' as a collaborator with push access"
   - Tool: `add_repository_collaborator`

### 2. Branch Management (12 tools)

#### Activity 2.1: Branch Operations
**Tools Used:** `list_branches`, `create_branch`, `get_branch`, `update_branch_protection`

**Scenario:** Set up a development workflow with feature branches and protection rules.

**Steps:**
1. **List All Branches**
   - Ask Copilot: "Show me all branches in this repository"
   - Tool: `list_branches`

2. **Create Feature Branch**
   - Ask Copilot: "Create a new branch called 'feature/navbar' from the main branch"
   - Tool: `create_branch`

3. **Get Branch Details**
   - Ask Copilot: "Get details about the main branch"
   - Tool: `get_branch`

4. **Protect Main Branch**
   - Ask Copilot: "Protect the main branch by requiring pull request reviews"
   - Tool: `update_branch_protection`

#### Activity 2.2: Branch Comparison and Merging
**Tools Used:** `compare_commits`, `merge_branch`, `delete_branch`

**Steps:**
1. **Compare Branches**
   - Ask Copilot: "Compare the main branch with feature/navbar branch"
   - Tool: `compare_commits`

2. **Merge Branch**
   - Ask Copilot: "Merge feature/navbar into main branch"
   - Tool: `merge_branch`

### 3. Issues Management (18 tools)

#### Activity 3.1: Issue Creation and Management
**Tools Used:** `create_issue`, `list_issues`, `get_issue`, `update_issue`

**Scenario:** Track bugs and feature requests for the portfolio project.

**Steps:**
1. **Create Bug Report**
   - Ask Copilot: "Create an issue titled 'Navigation menu not responsive on mobile' with label 'bug' and assign it to me"
   - Tool: `create_issue`

2. **List All Issues**
   - Ask Copilot: "Show me all open issues in this repository"
   - Tool: `list_issues`

3. **Get Issue Details**
   - Ask Copilot: "Get details about issue #1"
   - Tool: `get_issue`

4. **Update Issue**
   - Ask Copilot: "Update issue #1 to add label 'high-priority' and assign to 'team-member-username'"
   - Tool: `update_issue`

#### Activity 3.2: Issue Comments and Reactions
**Tools Used:** `create_issue_comment`, `list_issue_comments`, `update_issue_comment`, `delete_issue_comment`

**Steps:**
1. **Add Comment**
   - Ask Copilot: "Add a comment to issue #1 saying 'I'll work on this using CSS media queries'"
   - Tool: `create_issue_comment`

2. **List Comments**
   - Ask Copilot: "Show me all comments on issue #1"
   - Tool: `list_issue_comments`

#### Activity 3.3: Issue Labels and Milestones
**Tools Used:** `list_labels`, `create_label`, `get_label`, `update_label`, `delete_label`

**Steps:**
1. **Create Custom Labels**
   - Ask Copilot: "Create a label called 'enhancement' with green color #00ff00"
   - Tool: `create_label`

2. **List All Labels**
   - Ask Copilot: "Show me all labels in this repository"
   - Tool: `list_labels`

### 4. Pull Requests (16 tools)

#### Activity 4.1: Pull Request Workflow
**Tools Used:** `create_pull_request`, `list_pull_requests`, `get_pull_request`, `update_pull_request`

**Scenario:** Submit and review code changes for the portfolio project.

**Steps:**
1. **Create Pull Request**
   - Ask Copilot: "Create a pull request from 'feature/navbar' to 'main' with title 'Add responsive navigation menu'"
   - Tool: `create_pull_request`

2. **List Pull Requests**
   - Ask Copilot: "Show me all open pull requests"
   - Tool: `list_pull_requests`

3. **Get PR Details**
   - Ask Copilot: "Get details about pull request #1"
   - Tool: `get_pull_request`

#### Activity 4.2: Pull Request Reviews
**Tools Used:** `list_pull_request_reviews`, `create_pull_request_review`, `update_pull_request_review`

**Steps:**
1. **Create Review**
   - Ask Copilot: "Create a review for PR #1 with approval and comment 'Great work on the responsive design!'"
   - Tool: `create_pull_request_review`

2. **List Reviews**
   - Ask Copilot: "Show me all reviews for pull request #1"
   - Tool: `list_pull_request_reviews`

#### Activity 4.3: Pull Request Comments
**Tools Used:** `list_pull_request_comments`, `create_pull_request_comment`, `update_pull_request_comment`

**Steps:**
1. **Add Line Comment**
   - Ask Copilot: "Add a comment to line 25 in navbar.css suggesting to use flexbox instead of float"
   - Tool: `create_pull_request_comment`

### 5. Files and Content Management (10 tools)

#### Activity 5.1: File Operations
**Tools Used:** `get_file_contents`, `create_or_update_file`, `delete_file`

**Scenario:** Manage portfolio website files through MCP tools.

**Steps:**
1. **Read File Contents**
   - Ask Copilot: "Show me the contents of index.html file"
   - Tool: `get_file_contents`

2. **Create New File**
   - Ask Copilot: "Create a new file called 'styles.css' with basic CSS reset styles"
   - Tool: `create_or_update_file`

3. **Update Existing File**
   - Ask Copilot: "Update the README.md file to include installation instructions"
   - Tool: `create_or_update_file`

#### Activity 5.2: Directory Structure
**Tools Used:** `get_directory_contents`, `search_code`

**Steps:**
1. **List Directory Contents**
   - Ask Copilot: "Show me all files in the css directory"
   - Tool: `get_directory_contents`

2. **Search Code**
   - Ask Copilot: "Search for all files containing 'navbar' in the code"
   - Tool: `search_code`

### 6. Commits and History (8 tools)

#### Activity 6.1: Commit History Analysis
**Tools Used:** `list_commits`, `get_commit`, `compare_commits`

**Steps:**
1. **List Recent Commits**
   - Ask Copilot: "Show me the last 10 commits on the main branch"
   - Tool: `list_commits`

2. **Get Commit Details**
   - Ask Copilot: "Get details about commit abc123def including changes made"
   - Tool: `get_commit`

3. **Compare Commits**
   - Ask Copilot: "Compare commit abc123 with commit def456 to see what changed"
   - Tool: `compare_commits`

### 7. Releases and Tags (6 tools)

#### Activity 7.1: Release Management
**Tools Used:** `list_releases`, `create_release`, `get_release`, `update_release`

**Steps:**
1. **Create Release**
   - Ask Copilot: "Create a release v1.0.0 for the main branch with title 'Initial Portfolio Release'"
   - Tool: `create_release`

2. **List All Releases**
   - Ask Copilot: "Show me all releases for this repository"
   - Tool: `list_releases`

### 8. Actions and Workflows (6 tools)

#### Activity 8.1: GitHub Actions Management
**Tools Used:** `list_workflow_runs`, `get_workflow_run`, `rerun_workflow`

**Steps:**
1. **List Workflow Runs**
   - Ask Copilot: "Show me the last 5 workflow runs"
   - Tool: `list_workflow_runs`

2. **Get Run Details**
   - Ask Copilot: "Get details about workflow run #123456"
   - Tool: `get_workflow_run`

## Comprehensive Practical Exercises

### Exercise 1: Complete Project Setup (30 minutes)
**Objective:** Set up a complete project from scratch using MCP tools only.

**Tasks:**
1. Create repository with proper description and topics
2. Set up branch protection rules
3. Create initial issues for project planning
4. Add collaborators with appropriate permissions
5. Create and merge first pull request
6. Create initial release

### Exercise 2: Bug Tracking and Resolution (45 minutes)
**Objective:** Practice full bug lifecycle management.

**Tasks:**
1. Create bug report with appropriate labels
2. Assign bug to team member
3. Create fix branch and implement solution
4. Submit pull request with proper description
5. Conduct code review with comments
6. Merge fix and close issue
7. Create patch release

### Exercise 3: Feature Development Workflow (60 minutes)
**Objective:** Complete feature development cycle.

**Tasks:**
1. Create feature request issue
2. Break down into smaller tasks
3. Create feature branch
4. Implement feature with multiple commits
5. Create pull request with detailed description
6. Handle review feedback and iterate
7. Merge feature and update documentation
8. Create minor release

## Advanced Scenarios

### Scenario A: Team Collaboration
**Tools:** All collaboration-related tools
**Objective:** Simulate real team development environment

### Scenario B: Open Source Project Management
**Tools:** Issues, PRs, releases, labels
**Objective:** Manage community contributions

### Scenario C: CI/CD Pipeline Integration
**Tools:** Actions, workflows, releases
**Objective:** Automate deployment pipeline

## Assessment Rubric

### Beginner Level (Tools 1-30)
- Basic repository operations
- Simple issue creation
- Basic file management

### Intermediate Level (Tools 31-60)
- Pull request workflows
- Branch management
- Review processes

### Advanced Level (Tools 61-91)
- Complex workflows
- Automation setup
- Team collaboration

## Troubleshooting Common Issues

### MCP Connection Issues
1. Verify `.vscode/mcp.json` configuration
2. Check GitHub authentication
3. Ensure proper permissions

### Tool Execution Errors
1. Check repository permissions
2. Verify branch existence
3. Confirm proper syntax

## Additional Resources

- [GitHub API Documentation](https://docs.github.com/en/rest)
- [MCP Specification](https://modelcontextprotocol.io/)
- [GitHub Best Practices](https://guides.github.com/)

---

*Note: This guide assumes professionals have basic Git/GitHub knowledge. Adjust complexity based on experience level.*