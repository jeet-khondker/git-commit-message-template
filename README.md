# Git Commit Message Template

## Git Commit Message Tags

- `feature` : Indication of New Feature or Functionality or a significant enhancement into the system
- `fix` : Signifies Bug or Error Fixes in the system
- `documentation` : Changes to the Documentation File(s)
- `style` : Addition / Changes to Design Styles of the Application UI / UX
- `refactor` : Code Refactoring (Variable Renaming / Code Restructuring or Formatting) that doesn't affect Functionality
- `data` : Used for database, information and data manipulation
- `test` : Adding, Fixing or Modifying Tests; No Production Code Change
- `chore` : Updating Build Scripts / Upgrading Dependencies, Maintenance and Changes in Tools; No Production Code Change
- `cicd` : Changes to CI/CD Configuration or Scripts
- `performance` : Performance Improvements / Optimization Changes
- `devEx` : Developers' Experience : Use for anything that helps to improve developers' experience
- `revert` : Undoing the changes made by a previous commit
- `miscellaneous` : Use for anything that does not clearly fall into any of the previous categories

## Examples

**General Commit Message**

```sh
git commit -m "documentation : Updated README File"
```

## Making References

**Commit Message with reference of PR (Pull Request)**

```sh
git commit -m "feature (!1234) : Created Functionality for Password Validation"
```

**Commit Message with reference of Issue / Task**

```sh
git commit -m "style (#1234) : Fixed Margin and Padding Design Issue for User Login Screen"
```

**Commit Message in the past (if you forget to commit on that particular date in the past)**

```sh
git commit --date="1 day ago" -m "feature : Added Test ID Attribute to 404 Not Found Page"
```