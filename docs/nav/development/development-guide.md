# Development guide

September 7, 2024

---

## How to test the local package?

### Prerequisites

Install uv (if not already installed):

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

### Environment Setup

Create and sync virtual environment with dependencies:

```bash
uv sync --dev
```

This command automatically creates a virtual environment and installs all dependencies defined in `pyproject.toml`.

### Development

Make your changes as desired in the `./src/mkdocs_mini_blog/` folder. You can enjoy and change whatever you want,
please have fun.

```bash
ls src/mkdocs_mini_blog
```

### Test

Run the following command to start the development server:

```bash
mkdocs serve
```

Now you can access the [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## License

![GitHub](https://img.shields.io/github/license/dpoulopoulos/mkdocs-mini-blog?style=flat-square)

This project is licensed under the terms of the MIT license.
