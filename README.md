# Mix.Tasks.Niku.New

Creates a new Elixir project with some customization.

- Add a LICENSE file
- Add dependencies which help a development
  - [ex_doc](https://github.com/elixir-lang/ex_doc) for a documentation
  - [credo](https://github.com/rrrene/credo) for a static code analysis
  - [dialyxir](https://github.com/jeremyjh/dialyxir) for a static typing analysis
- Add `.travis.yml` for [(Travis)CI](https://docs.travis-ci.com/)

## Installation

```
% git clone https://github.com/niku/mix_tasks_niku_new.git
% cd mix_tasks_niku_new
% mix do archive.build, archive.install
```

## Usage

```
% mix niku.new foo
```
