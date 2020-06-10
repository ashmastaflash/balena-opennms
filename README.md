# balena-opennms
opennms managed by Balena

## Setup

*  Create an account with balena.io
*  Create a project in Balena for this, running on Intel NUC.
*  Download the installer from the Balena project and install onto the NUC or into a VM.
*  Clone this repo locally and set up the Balena taret as a remote: `git remote add balena ${BALENA_PROJECT_URL}`
*  `git push balena master`

You can use environment variables in the Balena project config to override the environment variables you see in the `docker-compose.yml` file.
