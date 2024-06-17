# GitHub Docker Workflow

## How to use

1. Clone the project:

```bash
git clone https://github.com/<your-github-username>/github-docker-workflow
```
2. Move [deploy.yml](deploy.yml) to **.github/workflows** in your repository.

3. Create repository secrets for `DOCKER_USERNAME` and `DOCKER_PASSWORD` as your Docker Username and Password respectively.

4. Change **myusername/myapp** to your desired Docker image name.

_Once you commit to GitHub, the workflow will automatically run and attempt to build and push your image to Docker Hub. Look for the workflow status under the 'Actions' tab in your repository._

#### Star this project ✨
