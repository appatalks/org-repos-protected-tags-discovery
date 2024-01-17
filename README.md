# Orginization and Repos Discovery of Visibility and Protected Tags

This action lists all repositories in a given organization along with their visibility settings and protected tags status. The output is saved in a CSV file named `org_repo_report.csv`.

## Requirements

- Create a [repository secret](https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions) ```PATLANG``` with ```Personal Access Token```.
- Scopes Required: ```repo```, ```read:org```

## Inputs

### `orgName`

**Required** The name of the organization to check. This input is required to run the action.

## Outputs

The action outputs a CSV file named `org_repo_report.csv` with columns `Repository Name`, `Visibility`, `Protected Tags`, and `Tag Name`.

Download the `org_repo_report.csv` which can be accessed in the Actions tab of your GitHub repository.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
