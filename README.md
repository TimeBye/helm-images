# helm-images
Get all docker images needed for a chart, then you can download all images in advance when installing charts.

## Usage
```
➜ helm images ./test-chart
redis:latest
nginx:1.16.0
```

## Install
```
helm plugin install https://github.com/TimeBye/helm-images
```
