# Identicon

An Identicon generator written in Elixir. This is a learning project following [Udemy Course](https://www.udemy.com/course/the-complete-elixir-and-phoenix-bootcamp-and-tutorial/)

## Installation

1. ```git clone``` repository
2. Install Elixir ```brew install elixir```
3. Run ```mix deps.get``` in ./todo-elixir

## Usage

1. Run ```iex -S mix``` in ./todo-elixir
2. Run Identicon.main/1 with a string of any length
3. You're identicon will be generated and stored in ./storage

## Example Usage

*In identicon-elixir directory*
```
> iex -S mix
iex(1)> Identicon.main("foo")
:ok
```
foo.png will be stored in ./identicon-elixir/lib/storage

