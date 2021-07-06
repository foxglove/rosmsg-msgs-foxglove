# rosmsg-msgs-foxglove

This library exports a map of ROS1 datatype string keys to [@foxglove/rosmsg](https://github.com/foxglove/rosmsg) `RosMsgDefinition` values for Foxglove ROS message definitions. The message definitions include all dependent message definitions, similar to the output of the `gendeps --cat` command.

## License

@foxglove/rosmsg-msgs-foxglove is licensed under [MIT License](https://opensource.org/licenses/MIT).

## Releasing

1. Run `yarn version --[major|minor|patch]` to bump version
2. Run `git push && git push --tags` to push new tag
3. GitHub Actions will take care of the rest
