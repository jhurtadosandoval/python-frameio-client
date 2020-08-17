# Contributing

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

## Pull Request Process

These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to our repos or how we handle your PRs.

1. Ensure any build dependencies or sensitive environment variables are removed before posting your PR.
2. In the PR summary, note the features you're adding or changes to existing interfaces.
3. Increase the version numbers ([example commit](https://github.com/Frameio/python-frameio-client/commit/3b6595aae9f8a0df984c937ca9938131afbb82c0)).  The versioning scheme we use is [SemVer](http://semver.org/).
4. If your PR includes more than a handful of commits, please squash the commits down to a single commit.
5. We'd appreciate if your PR follows the [Conventional Commit](https://www.conventionalcommits.org/en/v1.0.0/) spec.
6. Pull Requests are typically merged once they receive approval from two Frame.io developers.  If you haven't gotten approval, feel free to @mention us or send a reminder.

## Testing

We run tests using [pytest](https://docs.pytest.org/en/stable/).  Tests are admittedly weak in this repo, you can help change that!  One rule we care about: any tests run against actual Frame.io processes (like generating assets) should be accompanied by a teardown or cleanup task.

## Report a Bug

Report bugs to Issues in GitHub.  It's okay to report bugs that may not be specific to this library, i.e. if you find a bug core to the API feel free to report it. Try to include info and context that will help us reproduce the problem.  

## Code of Conduct

In the interest of fostering an open and welcoming environment, we as
contributors and maintainers pledge to making participation in our project and
our community a harassment-free experience for everyone, regardless of age, body
size, disability, ethnicity, gender identity and expression, level of experience,
nationality, personal appearance, race, religion, or sexual identity and
orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment
include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or
advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic
  address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting


### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4,
available at [http://contributor-covenant.org/version/1/4][version]

[homepage]: http://contributor-covenant.org
[version]: http://contributor-covenant.org/version/1/4/