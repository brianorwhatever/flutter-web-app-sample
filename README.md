# flutter-web-app-sampl

This is a sample build of a flutter web app using openshift

## create and start build

```
oc create is flutter-web-app
oc create -f openshift/secret__flutter-web-app.yaml
oc create -f openshift/bc__flutter-web-app.yaml
oc start-build flutter-web-app
```
