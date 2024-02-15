# Minimal Clone Buildkite Plugin

Clones only the exact commit needed for the build

## Example

Add the following to your `pipeline.yml`:

```yml
steps:
  - command: ls
    plugins:
      - arilotter/minimal-clone#v1.0.0
```

## Configuration

None!

## Developing

To run the tests:

```shell
./test.sh
```
