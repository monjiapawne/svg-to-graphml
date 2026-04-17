<div align="center">
  <h4>svg-to-graphml</h4>
  <img src="yedtographml.svg" alt="logo" width="200">
  <p>Convert SVG icons to yEd/GraphML for use in yEd diagrams.</p>
</div>

## Usage

```bash
go run ./cmd -path <svg file or folder> -out <output dir>
```

- Input can be a single SVG or a directory of SVGs.
- Output is one or more .graphml files in the output directory.

## Examples

```bash
go run ./cmd -path /test/1_go.svg -out ./out
go run ./cmd -path /test -out ./out
```

## WASM Demo

`/web` contains the WASM demo hosted on Github Pages, for single or multiple file converions. It lacks the ability to retain the source folder structure that exists in the cli version.
