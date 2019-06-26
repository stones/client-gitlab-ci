# Client GitlabCI container

>A docker container node and awscli


## Build
`docker build -t stones/client-gitlab-ci .`

## Publishing
This project is set up to auto build on commit, but if you need to trigger manually for any reason:

`docker push stones/client-gitlab-ci:<tagname>`