<details>
 <summary>Code Review Checklist</summary>

Reviewers follows [these guidelines](https://dr-dropin.atlassian.net/wiki/spaces/DD/pages/42369027/Dr.Dropin+Code+Review+Guidelines) when reviewing pull requests.

The following checklist is strictly targeted towards the committed code. 

Should you find non-PR related code that could be improved, request a new PR for this.

## Documentation
- [ ] The Jira ticket name is prepended to the name of the pull request
- [ ] Related documentation, configuration and readme files has been updated
 
## Error Handling and Logging
- [ ] Has proper logging and debugging

## Security and Data Privacy
- [ ] User input is validated, sanitized and escaped to prevent security attacks such as cross-site scripting, SQL injection
- [ ] The data retrieved from external APIs and libraries is validated accordingly

## Testing and Testability
- [ ] The code contains sufficient testing
 
</details>

