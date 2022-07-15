# github-workflows

| Workflow                     | Inputs                  | Description                                     |
|------------------------------|-------------------------|-------------------------------------------------|
| .github/workflows/maven.yaml | secrets.PODMAN_USERNAME | Compile, test, package, and containerize Maven  |
 |                              | secrets.PODMAN_PASSWORD | based projects.                                 |
 |                              | secrets.REPO_HOSTNAME   |                                                 |
 |                              | secrets.REPO_USERNAME   |                                                 |