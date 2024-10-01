# Contributing

The following table presents information from the *Conventional commits* documentation: [www.conventionalcommits.org](https://www.conventionalcommits.org/en/v1.0.0/)


## Commits

Commits messages should always be descriptive. Meaning technical descriptions without personal believes or feelings. Commits should always include any of these prefixes:


|                Prefix                          |Use case                         |
|----------------|-------------------------------|-----------------------------|
|feat|`The commit includes new features to the project.`                     
|fix          |`The commit include fix for existing bug.`          
|docs|`The commit includes documentation.`                     
|style          |`The commit includes changes do not affect the meaning of the code.`          
|test          |`The commit includes adding missing tests or correcting existing test`          

Commits should only contain changes related to the prefix used, for example: Never commit  `feat`  files with  `docs`  files.

## The commit message should be structured as follows:



```
[prefix]: <description>

[optional body]

[optional footer(s)]
```

Commit examples:
```
feat: allow provided config object to extend other configs
```
```
docs: correct spelling of CHANGELOG
```
```
fix: prevent racing of requests

Introduce a request id and a reference to latest request. Dismiss
incoming responses other than from latest request.
```
