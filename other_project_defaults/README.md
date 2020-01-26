# Default project files

This directory contains miscellaneous default project files, like build scripts, etc.

These must be copied to new repositories, and updated with project-specific details.

## Contents

### Scripts

- `lint.sh`, swift lint script
- `build_docs.sh`, jazzy docs script

### Templates

- `IDETemplateMacros.plist` to [customize Xcode header comments](https://oleb.net/blog/2017/07/xcode-9-text-macros/). Must be placed in  `<ProjectName>.xcodeproj/xcshareddata/IDETemplateMacros.plist` or `<WorkspaceName>.xcworkspace/xcshareddata/IDETemplateMacros.plist`.
