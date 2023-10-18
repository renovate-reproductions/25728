# renovate-category-labels
This repo is for minimal reproduction of the issue mentioned in https://github.com/renovatebot/renovate/discussions/25074.

It only has one dependency (python urllib3) and I expect, that the category template field has the value "python", but it doesn't work. I added the package rule to show, that renovate successfully detects the category `python`.
