# helm-chart-efk
Repository for EFK Helm Chart

Install the helm:
`helm install {{ .Release.Name }} ./{{ .Chart.Name }}`

Uninstall the helm:
`helm uninstall {{ .Release.Name }}`

Check NOTES.txt for more details.

## Github Release Setup

We are using [release-it](https://github.com/release-it/release-it) to help bootstrap the release process.
