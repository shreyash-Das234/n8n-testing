# n8n GitHub Automation Test

This repository is for testing an **n8n workflow** that automatically creates a Dockerfile and CI/CD pipeline.

When a push event occurs, the n8n workflow should:
1. Detect that only this README file exists.
2. Generate a simple `Dockerfile`.
3. Generate a `.github/workflows/ci.yml` file.
4. Commit those files back to this repository.

---
**Purpose:** Validate that the GitHub Trigger node in n8n works correctly and can perform automated file creation and commits.
