# UpdateScope

UpdateScope is a read-only update checker for Arch-based Linux systems.

The project aims to identify available package updates and present a clear summary through a command-line interface.

## Project Status

Early development. The initial Python package structure is in place.
Update discovery and reporting are not implemented yet.

## Goals

- List available package updates.
- Display installed and available package versions.
- Summarize the number of available updates.
- Provide clear error messages when update information cannot be retrieved.
- Keep the initial implementation read-only.

## Requirements

- Python 3.14 or newer.
- An Arch-based Linux distribution.
- Pacman.

## Development Setup

Clone the repository and enter its directory:

```bash
git clone git@github.com:robsilva-dev/updatescope.git
cd updatescope
```

Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

Install the project in editable mode:

```bash
python -m pip install -e .
```

## Safety

UpdateScope is intended to inspect available updates without installing, removing, or upgrading system packages.

## License

Not decided yet.
