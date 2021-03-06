# cookiecutter-openstack-puppet-modules

Cookiecutter template for a compliant Openstack puppet-modules

## Installation

Install [cookiecutter](https://cookiecutter.readthedocs.org/) either from source, pip or package if it exists

## Usage

There are two ways to create the boilerplate for the puppet module.

### Locally

  1. Clone locally the [cookiecutter-openstack-puppet-modules](https://github.com/enovance/cookiecutter-openstack-puppet-modules.git) repository.
  2. Run `cookiecutter /path/to/cloned/repo`

### Remotely (ie. using a git repo)

  1. Run `cookiecutter https://github.com/enovance/cookiecutter-openstack-puppet-modules.git`

## What's next

Once the boilerplate created, in order to be compliant with the other modules, the files managed by [msync](https://github.com/puppet-community/modulesync), (or [configs](https://github.com/stackforge/puppet-modulesync-configs)) needs to be in the project folder. Once synced module is ready, announce its existence to the ML, make the proper patch to openstack-infra and finally wait for the reviews to do the rest.
