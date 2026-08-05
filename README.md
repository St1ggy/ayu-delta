# Ayu for delta

An unofficial [Ayu](https://github.com/ayu-theme/ayu-colors) theme port for [delta](https://github.com/dandavison/delta).

## Variants

- `ayu-dark.gitconfig`
- `ayu-mirage.gitconfig`
- `ayu-light.gitconfig`

## Install

Include one variant in your Git configuration, then enable its shared `ayu` delta feature:

```sh
git config --global include.path /path/to/ayu-delta/themes/ayu-dark.gitconfig
git config --global delta.features ayu
```

Each variant defines the same feature name, so replace the included file to switch variants.

## Upstream

- Application: [delta](https://github.com/dandavison/delta)
- Theme: [Ayu](https://github.com/ayu-theme/ayu-colors)

## License

Apache-2.0. Ayu palette copyright 2016-present Ike Kurghinyan.
