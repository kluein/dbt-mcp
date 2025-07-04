# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html),
and is generated by [Changie](https://github.com/miniscruff/changie).


## v0.2.5 - 2025-06-06
### Under the Hood
* Small improvements to improve logging and code organization.
* Move `--selector` to the code instead of the prompt
* Cursor deeplink setup
* Fix Cursor deeplinks
* Fix Cursor env var mess up
### Bug Fix
* Fix Discovery API config enablement

## v0.2.4 - 2025-06-03
### Bug Fix
* Add the missing selector argument when running commands

## v0.2.3 - 2025-06-02
### Under the Hood
* Fix release action to fetch tags

## v0.2.2 - 2025-06-02
### Under the Hood
* Update README to run the MCP server with uvx
* Logging usage events
* Improve remote tools error logging
* Move create-release-tag to release Action
* Update release process documentation
### Bug Fix
* Fix typo in GH action to create release

## v0.2.1 - 2025-05-28
### Under the Hood
* Remove hatch from tag action
* Manually triggering release

## v0.2.0 - 2025-05-28
### Enhancement or New Feature
* Using `--quiet` flag to reduce context saturation of coding assistants
* Add a tool `get_model_children`
* Added optional uniqueId parameter to model lookup methods for more precise model identification
* Enable remote tools in production
* Add selector for dbt commands
* Set pre-changie value to 0.1.13
### Under the Hood
* Require changelog entries for each PR
* Log Python version in install script
* Update license to full Apache 2.0 text
* Roll back installation script and instructions
* Re-enable tests in CI
* Refactor config for modularity
* Document remote tools
* Usage tracking scaffolding
* Update docs to clarify service token permissions required
* Increase remote tools timeout
* Update release process for new versions
* Point to the correct diagram in README
* Install hatch in release process
* Remove hatch from release process
### Bug Fix
* Fix diagram according to feature set

## v0.1.3 and before
* Initial releases before using changie