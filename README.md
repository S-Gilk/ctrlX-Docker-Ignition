# ctrlx-docker-ignition

Author: samuel.gilk@boschrexroth-us.com

Description: Provides Inductive Automation Ignition to ctrlX Container Engine.

Instructions to build on Linux:

1. Install Docker and configure buildx
2. Make scripts executable (chmod +x ./scripts/*.sh)
3. Run build_all.sh, passing target architecture as an argument (Ex. .scripts/build_all.sh "amd64")
4. Install Container Engine app on ctrlX CORE or ctrlX CORE Virtual
5. Install built ctrlx-docker-ignition snap on ctrlX CORE or ctrlX CORE Virtual
6. Make sure port forwarding is enabled on ctrlX CORE network adapter to access the webserver externally
