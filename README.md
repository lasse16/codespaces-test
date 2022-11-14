# codespaces-test

Playground testing the new [Github Codespaces](https://docs.github.com/en/codespaces) Feature

## What to put in CodeSpaces

It's useful to think of the devcontainer.json file as providing "customization" rather than "personalization."

You should only include things that everyone working on your codebase needs as standard elements of the development environment, not things that are personal preferences.
Things like linters are good to standardize on, and to require everyone to have installed, so they're good to include in your devcontainer.json file.

Things like user interface decorators or themes are personal choices that should not be put in the devcontainer.json file.

## Configuration

- If you're adding a single devcontainer.json file that will be used by everyone who creates a codespace from your repository, create the file within a .devcontainer directory at the root of the repository.
- If you want to offer users a choice of configuration, you can create multiple custom devcontainer.json files, each located within a separate subdirectory of the .devcontainer directory.

Reference possible fields for the configuration file [here](https://containers.dev/implementors/json_reference/).
