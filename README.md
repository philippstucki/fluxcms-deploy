# fluxcms-deploy
Simple Deployment Script for FluxCMS based projects

## Synopsis

    fluxcms-deploy [-n] [target-name]

## Description
*fluxcms-deploy* assists in deploying FluxCMS projects. Targets are configured using text files and contain user, host and directory. The user running commands on the target needs proper sudo permissions.

If *target-name* is specified the corresponding target configuration file is looked up in deployment/targets/*target-name*`.txt

### Options
* **-n** Tells rsync to perform a dry run

## Example Configuration
See deployment/targets/my-target.txt for an example target configuration.
