# Automation

Repository to host various kinds of CI automation scripts or configurations for the different Podman Container Tools repositories.

Note any external usage of the created images outside of Podman Container Tools is unsupported by us.

## images/

Contains build scripts for custom qcow2 images that are then used by other projects for CI testing.

## container-images/

Contains the Containerfiles for the container image builds.

## mac_pw_pool/

Scripts to manage the custom macos github action runners as used in the podman-container-tools org.

## renovate/

Renovate config for all the repositories in the org.
