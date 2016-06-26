# steganographic-polyglots

This repo is an experiment with hiding code from one programming language
inside of another. It started as a joke about steganography and
the [whitespace](http://compsoc.dur.ac.uk/whitespace/tutorial.html) language.

You'll probably want a whitespace [interpreter](https://github.com/hostilefork/whitespacers)
to play around.

## Golang + whitespace

`hello.go` is your standard hello world program written in golang, but the
whitespace describes a different program.

- `go run hello.go`
- `whitespace hello.go`

## HTML + whitespace

`html/index.html` contains a Polymer TO-DO list app, which works in a modern web
browser, but the whitespace describes a fibonacci number calculator.

- From `html` directory, run `bower update` to install web components
- `docker-compose up` and navigate to `http://localhost` (or wherever)
- `curl localhost > todo.html; whitespace todo.html`

