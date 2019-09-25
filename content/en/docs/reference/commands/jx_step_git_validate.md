---
date: 2019-09-24T18:46:33Z
title: "jx step git validate"
slug: jx_step_git_validate
url: /commands/jx_step_git_validate/
---
## jx step git validate

Validates the .gitconfig is correctly configured

### Synopsis

This pipeline step validates that the .gitconfig is correctly configured

```
jx step git validate [flags]
```

### Examples

```
  # validates the user.name & user.email values are set in the .gitconfig
  jx step git validate
```

### Options

```
  -h, --help   help for validate
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output
```

### SEE ALSO

* [jx step git](/commands/jx_step_git/)	 - git [command]

###### Auto generated by spf13/cobra on 24-Sep-2019