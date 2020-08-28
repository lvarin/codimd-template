# CodiMD OpenShift template

CodiMD lets you collaborate in real-time with markdown. Built on HackMD source code, CodiMD lets you host and control your team's content with speed and ease. See [codimd in github](https://github.com/hackmdio/codimd).

We are using the official [codimd docker](https://hub.docker.com/r/hackmdio/hackmd) docker image in docker hub.

## Quick start

In order to install this version of the template into a namespace do:

```bash
$ oc create -f codimd.yaml
template.template.openshift.io/codimd created
```

Then use the template from the web interface, or from the command line:

```bash
oc process codimd | oc create -f -
```

