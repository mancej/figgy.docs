
# Commands

The FiggyCLI follows the following convention:

`figgy {resource} {command}`

In this example the resource is the "noun", or the thing being operated against, and the "command" is the verb, or the action.

At this time there are two main resources.

- [config](/commands/config/index.html)
- [iam](/commands/iam/index.html)
- [--optional-parameters](/commands/flags/index.html)


This convention is not absolute. There are a few exceptions, including `figgy --configure` or `figgy --version`.  These
invoke purely local operations and have no downstream remote resource being operated against. 
