# Contribution Guidelines

Please note that this project is released with a
[Contributor Code of Conduct](code-of-conduct.md). By participating in this
project you agree to abide by its terms.

---

Ensure your pull request adheres to the following guidelines:

- Items should be added like this:
  ```json
  {
    "name": "play-button",
    "category": "extension",
    "repo": "https://github.com/daviddarnes/play-button",
    "url": "https://darn.es/play-button-web-component/",
    "script": "npm install @daviddarnes/play-button",
    "snippet": "<play-button><button>Play me</button><audio src='...'></audio></play-button>"
  }
  ```
- Items should always have a `name`, `category` and `repo`
- `category` can be `extension`, `time`, `custom` or `novelty`
- `url`, `script` and `snippet` are optional
- If it's a significant change, please file an issue to discuss first
- And don't forget to check other PRs for duplicates

Thank you for your suggestions!

## Updating your PR

A lot of times, making a PR adhere to the standards above can be difficult.
If the maintainers notice anything that we'd like changed, we'll ask you to
edit your PR before we merge it. There's no need to open a new PR, just edit
the existing one. If you're not sure how to do that,
[here is a guide](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md)
on the different ways you can update your PR so that we can merge it.
