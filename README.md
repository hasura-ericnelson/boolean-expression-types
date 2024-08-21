# Boolean expression types

This tool processes HML (Hasura Metadata Language) files, specifically focusing on extracting information from DataConnectorLink sections.

## Installation

1. Ensure you have Python 3.8+ and Poetry installed.
2. Clone this repository.
3. Run `poetry install` in the project directory.

## Usage

Run the tool using:

```
poetry run boolean-expression-types --project-path ../../genfare-poc --output-file ../app/metadata/mongo-boolean-expression-types.hml
```

By default, it will process HML files in the project.

## Development

To contribute to this project:

1. Fork the repository.
2. Create a new branch for your feature.
3. Make your changes.
4. Run tests using `poetry run pytest`.
5. Submit a pull request.