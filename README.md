# CI/CD & Github-action

This rep is study records for github action and some CI/CD stuff.

## Github action
Feature in GitHub to create custom Automated Workflows
- Automate SDLC workflows
- Implement CI/CD DevOps

**1. Create a folder .github/workflows**

**2. Create YAML files under .github/workflows**

**3. YAML file content format**
```yaml
# Workflow Name
name:

# When to trigger the workflow
on:
  # Events that trigger the workflow, such as push or pull_request
  push:
    branches:
      -
  pull_request:
    branches:
      -

# Jobs can run sequentially or in parallel
jobs:
  # This workflow has jobs named "job1," "job2," and "job3"
  job1:
    # The job will run on a specified runner
    runs-on:

    # As part of the job, steps are executed sequentially
    steps:
      # The "uses" key tells the job to retrieve a specific action
      - uses:

      # Execute a command with name
      - name:
        run:

      # Execute another command with name
      - name:
        run:

  job2:
    # Configuration for job2

  job3:
    # Configuration for job3
```
