# Sphinx Todo

A proof-of-concept modern, strongly-typed implementation of the Sphinx 'todo extension' example

## Typed Configuration

custom configuration object is fully typed, providing a self-documenting configuration API

*conf.py*
```python
from sphinx_todo import Config as TodoConfig

todo_config = TodoConfig(include_todos=True)
```