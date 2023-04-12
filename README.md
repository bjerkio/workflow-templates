# Bjerk Workflow Templates

This repository contains a collection of workflow templates for GitHub Actions.

## Features

- Add issues to a project board when they are opened
- Assign author of pull request to the pull request
- Create issues from TODO comments in code
- Enable automatic management of dependencies of issues and pull requests

## Updating workflow templates

I suggest using `microplane` to update the workflow templates in your
repositories.

```bash
mp plan -b update-workflows -- cp -r .github/workflows/ ./
```

## License

[Apache 2.0](LICENSE)
