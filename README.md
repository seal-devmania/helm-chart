ORKI

# helm-chart

## To Build and `pump version`, create a new branch with version. Example: 

```bash
git checkout -b 0.1.5
```

## Add repository

```sh
helm repo add orki-repo https://seal-devmania.github.io/helm-chart
```


## Install

```sh
helm install my-orki-repo orki-repo/orki
```


# Development

## Pull Request branch

Example: `0.1.22`
Command:
```sh
git checkout -b 0.1.22
```

## Local generate

```sh
helm template . | less
```
