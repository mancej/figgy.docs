---
title: --profile
has_children: false
nav_order: 3
parent: Flags
---

## --profile flag

Example: 

```console
    $   figgy config validate --profile ${PROFILE}
```

Ignores all existing CLI configurations and authenticates the Figgy session with the AWS CLI profile provided. This profile
must exactly match a profile configuring in the users `~/.aws/config` and `~/.aws/credentials` files.

This command is especially for use with the [validate](/docs/commands/config/validate.html) command during CICD pipeline builds.