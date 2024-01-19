# testr [![Go Reference](https://pkg.go.dev/badge/github.com/minizilla/testr.svg)](https://pkg.go.dev/github.com/minizilla/testr) [![main](https://github.com/minizilla/testr/actions/workflows/main.yaml/badge.svg)](https://github.com/minizilla/testr/actions/workflows/main.yaml)

Package testr provides a minimal extension to the standard library's testing.

## Features

- Minimal assertion API with  `Equal`, `ErrorIs`, `ErrorAs`, and `Panic`.
- Optional message using `WithMessage`.
- Stop the execution using `WithFailNow`.
- Ease of initialization with `Must` and `MustV`.
