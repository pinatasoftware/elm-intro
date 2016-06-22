# Intro to Elm

## Why?

* No Runtime Exceptions
* Friendly Error Messages
* Performance
* Dependencies with Guarantees
* Clean Syntax
* Javascript Interop (with guarantees)


## Installation
With NPM:

`npm install -g elm`

## Editors
* Atom
* Emacs
* Vim
* VS Code
* Sublime
* Brackets


## REPL

Terminal

`elm-repl`

## Elm Architecture

* Model
* View
* Update


## Working with Elm files

Install HTML package
`elm package install elm-lang/html`

With a file:
`elm make Counter.elm`


Using the reactor
`elm-reactor`


## Elm Documentation
* [Core](http://package.elm-lang.org/packages/elm-lang/core/4.0.1/)
* [Packages](http://package.elm-lang.org/)


## Time Travel
Install debugger:
```
  elm package install jinjor/elm-time-travel
  elm-reactor
```

Go to TimeTravelCounter in reactor



## HTTP
Install package
`elm package install evancz/elm-http`
