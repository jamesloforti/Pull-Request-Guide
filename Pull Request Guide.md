# Pull Request (PR) Guide
**This document is intended to be a collaborative, living guide, to help the team progress at reviewing pull requests.**

## Things to consider:
#### Understand The Change:
- Open the story for the given PR and understand what modifications should be made.

#### Branching:
- Destination Branch:
    - Main?
    - Feature?
    - Validate it's correct.

#### CI Job Status:
- Check for a link to the CI results.
    - Validate results are good.

#### Follow The Logic:
- Mentally step through the logic and check for logic errors.
    - If you cant follow the logic from the PR, pull down the branch and take a closer look.

#### Scope:
- Did the developer stay within scope.

#### Null Checks:
- Ensure null reference checks are performed where necessary:

#### Packages:
- Does the AC encapsulate any package changes?
- Are the packages new, well known?
- Are packages from the same repo have version numbers in sync?

#### Testing:
- Validate that unit tests or other testing standards are complete.

#### Logging:
- Confirm sufficient logging.

#### Error Handling:
- Confirm sufficient error handling.

#### Miscellaneous:
- Typos
- C# Styling Errors
- Namespace Errors
