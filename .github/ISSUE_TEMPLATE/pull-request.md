---
name: Pull Request
about: Checklist for submitting PRs to this repo
title: "[Pull Request] <PR Summary Here>"
labels: ''
assignees: kmaphoenix

---

# Pull Request Template

## Description

Please include a summary of the change and which issue is fixed. Please also include relevant motivation and context. List any dependencies that are required for this change.

Fixes # (issue)

## Type of change

Please delete options that are not relevant.

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] This change requires a documentation update

## How Has This Been Tested?

Please describe the tests that you ran to verify your changes. Provide instructions and code snippets so we can reproduce. Please also list any relevant details for your test configuration (i.e. new dependencies).


### Code Snippets:
Example:
```py
def my_new_rule(resource):
  """This new rule does something cool for Resource X!"""
  for thing_im_checking in thing_list:
    is thing_im_checking not None:
      print("Do stuff!")
```

## Checklist:

- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my own code
- [ ] My code passes the linter as defined in the .pylintrc file
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation
- [ ] My changes generate no new warnings
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes
- [ ] Any dependent changes have been merged and published in downstream modules
- [ ] I have checked my code and corrected any misspellings
