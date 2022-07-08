![Release](https://github.com/oliverl-21/meraki-ci/actions/workflows/ansible.yml/badge.svg?event=push)

# meraki github cicd test

runs ansible with github actions on push to loop over an Meraki ORG to set allow, block url patterns and Content Category Filters for Meraki MX Devices.

## Setup
Create 2 Repo Secrets

- MERAKIAPI which equals to your API KEY
- ORG which is your Meraki ORG Name

Edit ```playbooks/vars/default.yml``` to your need and commit the change.
