# Playbooks and Examples for Artifactory on OpenShift

This repository contains unsupported code that can be used in conjunction with other Red Hat documentation.

This repository contains a set of playbooks that are used in conjunction with Red Hat's Implementation Guide for JFrog Artifactory on OpenShift Container Platform.

In Addition to that we provide a NodeJS example how to use Artifactory in OpenShift build.

### Environment Variables

Two environment variables are used to configure access to OpenShift, each playbook may have a section for defaults at the top of each file. `OCP_URL` is used to point to the OpenShift API, `OCP_TOKEN` must contain a valid token for authentication. This token could be obtained via the OpenShift web console.

### Usage
```
export OCP_URL="ocp.example.com"
export OCP_TOKEN="XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
ansible-playbook playbooks/nodejs-artifactory-example.yaml 
```
