# @foxglove/rosmsg-msgs-foxglove

**NOTICE: This package is deprecated. It will be archived soon. Please use [@foxglove/schemas](https://github.com/foxglove/schemas) instead.**

> This library exports a map of ROS 1 datatype string keys to [@foxglove/message-definition](https://github.com/foxglove/message-definition) `MessageDefinition` values for Foxglove ROS message definitions. The message definitions include all dependent message definitions, similar to the output of the `gendeps --cat` command.

[![npm version](https://img.shields.io/npm/v/@foxglove/rosmsg-msgs-foxglove.svg?style=flat)](https://www.npmjs.com/package/@foxglove/rosmsg-msgs-foxglove)

## License

@foxglove/rosmsg-msgs-foxglove is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Releasing

1. Run `yarn version --[major|minor|patch]` to bump version
2. Run `git push && git push --tags` to push new tag
3. GitHub Actions will take care of the rest

## Stay in touch

Join our [Slack channel](https://foxglove.dev/slack) to ask questions, share feedback, and stay up to date on what our team is working on.
