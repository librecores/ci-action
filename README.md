# LibreCores CI Github Action

This runs a command in the [LibreCores CI docker container](https://github.com/librecores/ci-docker-image).

We recommend using FuseSoC for your project and the [LibreCores CI FuseSoC action](https://github.com/marketplace/actions/librecores-ci-with-fusesoc).

It is still in an early development phase, please feel free to open an issue with your suggestion!

## Inputs

### `command`

**Required** The command to execute in the docker container

## Example usage

```yaml
uses: librecores/ci-action@2020.6-rc1
with:
  command: verilator -exe -f verilator.vc
```
