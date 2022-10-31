# Selective services example

Open repo with selective services:

- [![frontend](https://shields.io/badge/style-frontend-green?logo=gitpod&style=for-the-badge&label=Gitpod)](https://gitpod.io/#SERVICES=frontend/github.com/gitpod-io/template-selective-services)
- [![backend](https://shields.io/badge/style-backend-green?logo=gitpod&style=for-the-badge&label=Gitpod)](https://gitpod.io/#SERVICES=backend/github.com/gitpod-io/template-selective-services)
- [![webpage](https://shields.io/badge/style-webpage-green?logo=gitpod&style=for-the-badge&label=Gitpod)](https://gitpod.io/#SERVICES=webpage/github.com/gitpod-io/template-selective-services)
- [![all](https://shields.io/badge/style-all-green?logo=gitpod&style=for-the-badge&label=Gitpod)](https://gitpod.io/#SERVICES=frontend|backend|webpage/github.com/gitpod-io/template-selective-services)

# Customizing

The service startup is handled on [.gitpod.yml](./.gitpod.yml)

You can specify the `SERVICES` value via a button 👆 or from your address bar like so:

https://gitpod.io/#SERVICES=frontend|backend|webpage/github.com/gitpod-io/template-selective-services

So it's like `https://gitpod.io/#SERVICES=<values>/<repo>`, values are separated by `|`.

It's mainly powered by this Gitpod feature:

- https://www.gitpod.io/docs/configure/projects/environment-variables#providing-one-time-environment-variables-via-url
