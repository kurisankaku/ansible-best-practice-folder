# ansible-best-practice-folder
Create ansible best practice directories to current directory.

## Example Usage.

Create a role.
```
  $ ansible-playbook --extra-vars 'roles=some-role' create-directories.yml
```

Create multiple roles.
```
  $ ansible-playbook --extra-vars '{"roles":["common", "webserver", "dbserver"]}' create-directories.yml
```
