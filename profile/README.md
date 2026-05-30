# flutter-revived
 
Maintained forks of abandoned Flutter & Dart packages.
 
## Why
 
The pub.dev ecosystem has many useful packages that have been abandoned by their authors — open PRs with no response, outdated transitive dependencies blocking upgrades, and no sign of activity. This organization exists to keep those packages alive with minimal, targeted changes.
 
## What we do

We focus on keeping packages working — dependency bumps, platform support 
for newer systems, and critical bug fixes. We do not change public APIs 
or add unrelated features.
 
## Usage
 
Reference any package directly via git dependency in your `pubspec.yaml`:
 
```yaml
dependencies:
  some_package:
    git:
      url: https://github.com/flutter-revived/some_package.git
      ref: <commit-hash>  # always pin to a specific commit
```
 
Always pin to a specific commit hash rather than a branch — this ensures your dependency doesn't change unexpectedly.
 
## Packages
 
| Package | Original | Reason | Status |
|---|---|---|---|
| [system_tray](https://github.com/flutter-revived/system_tray) | https://github.com/antler119/system_tray | Abandoned since 2022, no activity | active |
 
## Policy
- If upstream merges a fix and publishes to pub.dev, we archive our fork and point back.
- Each fork's README links to the original package and explains what was changed.
- Changes are kept minimal and documented in commits.
## Contributing
 
Found another abandoned package? Open an issue or a PR. Keep changes small and focused — one problem per fork.
