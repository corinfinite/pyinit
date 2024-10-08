# pyinit

pyinit is a tool to help you get started with a new Python project. It will create a new directory with a basic project structure and a few other helpful things.

It was inspired by the template generated by the nix flake Python template (`nix flake example -t templates#python`).

To get started, run the following:

```
poetry run pyinit
```

# Formating & type checking
```
poetry run black pyinit
poetry run mypy pyinit
```

# Nix Support
This project comes with nix support. You can enter the nix shell by running `nix develop`.

## Building
Building can help troubleshoot packaging issues. Run `nix build` and then `results/bin/pyinit`.
