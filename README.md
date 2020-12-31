# Wire A

Bulma + Alpine JS Chat UI

## Usage

1. Install Dev Depedencies (nodeJs 12 required)
```sh
npm install
```
2. To start development and server for live preview
```sh
npm run dev
```

# Edits
The Bulma source has been customized.

* Call to `$fullhd-enabled: false;` in `_variables.scss` to override the default Bulma.
* `/src/sass/sass/helpers/spacing.sass` has been removed from the imports. We import our own helpers instead.
