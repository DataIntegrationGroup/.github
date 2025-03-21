# Software Development Policies

## python
1. all python projects shall use the [psf "black" code formatter](https://github.com/psf/black) or the [ruff linter](https://docs.astral.sh/ruff/). It is recommended to use a github action for formatting and that a badge be added to the projects README file
2. all python projects shall have unittests that execute automatically on pushes/pull requests
3. all python projects shall follow this [style guide](python_style_guide.md)
4. follow the [Zen of Python](https://en.wikipedia.org/wiki/Zen_of_Python)
## api
1. all endpoints shall use `kebab-case`

## web development
1. web applications shall be built using React
2. web applications should be built using a React metaframework. Refine.dev is preferred.
3. web applications shall use MaterialUI or PrimeReact as a UI component library
4. web applications shall be bundled using Vite

## Database
1. Use postgresql
2. Databases shall be maintained such that they are never using an EOL version
