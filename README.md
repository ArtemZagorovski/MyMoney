# MyMoney

Architecture: VIP
Dependency manager: cocoapods
UI: UIKit

## Git rules

### Branches:

1. Branch names must have one of the following prefixes:
    1. `feature/` for new features
    2. `bugfix/` for any bugfix in develop
    3. `release/` for release branches
    4. `hotfix/` for bugfixes in release
2. Branch names must contain the ticket number after the prefix
3. Branches must be deleted after merging the PR

example: feature/MMIOS-1122-new-screen

### Commits:

1. Commit message must contain the ticket number at the beginning
2. Commit message must contain short description of the work done

example: feature/MMIOS-1122: new screen added
