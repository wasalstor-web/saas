# saas

## Getting Started

### Cloning the Repository

This repository includes git submodules. To clone the repository with all submodules, use:

```bash
git clone --recurse-submodules https://github.com/wasalstor-web/saas.git
```

If you have already cloned the repository without the `--recurse-submodules` flag, you can initialize and update the submodules with:

```bash
git submodule update --init --recursive
```

## Third-Party Dependencies

### Dyad

This repository includes [dyad](https://github.com/dyad-sh/dyad.git) as a git submodule located at `third_party/dyad`. Dyad is licensed under the Apache License, Version 2.0. See `third_party/dyad/LICENSE` for details.