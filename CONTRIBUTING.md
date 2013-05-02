# Contribution Guidelines
Some helpful tips for making Alcatraz more awesome

## Gitiquette

- Open an issue if there is a change you'd like to make but hasn't been discussed, so we can all participate and no efforts are duplicated or wasted
- Use feature branches, one for each major change to the codebase
- Rebase your feature branch on latest master when opening a Pull Request, to minimise conflicts

## Coding Style

- Put the opening bracket of a method implementation on the same line as the signature
- Avoid adding comments in the code detailing the changes, and instead add them to the Pull Request description and code comments

## UI Changes

- Alcatraz uses autolayout; position UI elements using constraints and avoid ambiguities that lead to many system-defined constraints
- Always rebase on latest master before making changes to the `xib`; this reduces the amount of conflicts within the file


## Logging

Output for development and crash reports can be obtained via running `tail -f /var/log/system.log`, and is a helpful addition to issue submissions.