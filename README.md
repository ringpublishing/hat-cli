
## Description
This is a CLI for Head App Template. It is not required, but it facilitates work and project management.

## Installation

```bash
npm i git+https://github.com/ringpublishing/hat-cli.git --global
```

## Usage


### setup

From project folder:

```bash 
hatcli setup
```
then follow the configurator to create/edit profiles for project.

## Notes

### Variant change by request header

There is possibility to change variant by request header `x-websites-config-variant`

## Development of HAT packages

When developing any HAT package eg.`hat-server` by using `hat-boilderplate`, you should use `npm link`

On `hat-server` repository:
```bash
npm link
```

On `hat-boilderplate` repository:
```bash
npm link "hat-server"
```
