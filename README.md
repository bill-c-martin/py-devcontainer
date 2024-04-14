Devcontainer for python development in VS Code, with a sample flask app to verify it runs

## Prerequisites

- Docker
- VS Code
- "Dev Containers" V Code extension

## Instructions

1. Clone the above repo, which you forked, to your localhost
2. Open the repo in VS Code and click the "Reopen in Container" button that pops up

> **Note:**
> Or run `Dev Containers: Open Folder in Container...` in the command palette (`Ctrl+Shift+P`)

3. When the container is done provisioning, hit any key to continue
4. Start the web server:

```bash
flask run
```

5. Go to [http://localhost:5000](http://localhost:5000) and verify it runs locally.

