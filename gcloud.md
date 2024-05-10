# gcloud
## auth
**Acquire new user credentials to use for Application Default Credentials[^1]**
```
gcloud auth application-default login
```
[^1]: [gcloud auth application-default login]([https://kubernetes.io/docs/reference/kubectl/cheatsheet/](https://cloud.google.com/sdk/gcloud/reference/auth/application-default/login)https://cloud.google.com/sdk/gcloud/reference/auth/application-default/login)

## projects
**Export current project ID**
```
export PROJECT_ID=$(gcloud config get-value project)
```
**Export current project number**
```
export PROJECT_NUMBER=$(gcloud projects describe "$PROJECT_ID" --format "value(projectNumber)")
```
