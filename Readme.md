
### Chnaged

.github/workflows/ci.yml — upgraded GitHub Actions dependencies to actions/checkout@v5 and actions/setup-python@v6 for Node.js 20 deprecation compatibility. Added job dependency ordering for build-scan, Docker image artifact save/upload flow, and a new conditional push-ecr deployment stage using GitHub OIDC authentication for secure Amazon ECR image pushes with commit-SHA tagging. Docker images are pushed to Amazon ECR on push/merge events to the main branch.
