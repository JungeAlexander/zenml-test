# Taking ZenML for a spin

## Installation

```
poetry install --no-root
```

## Quick start

```
zenml go
```

## Questions

- Does ZenML still require integration-specific code? E.g. for logging training metrics the following is used `mlflow.sklearn.autolog()`.
- How could we integrate custom model serving behind a REST API?
- What would be needed to hook up evidently or similar with custom model serving behind a REST API?