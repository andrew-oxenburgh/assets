## Maintains my stuff

Right now, it's just an svg in `./assets` and I have a script in `export-svg.sh`.

You need to run the script in the context of `yarn`, so it picks up the dependency `svgexport`

This should only be necessary if you change the raw svg, but to re-calc assets:

```sh
yarn
yarn svg:export
```
