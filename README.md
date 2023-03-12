# Isaac-Sim-Install-Guide
An installation guide/log of Isaac Sim on Ubuntu 20.04

## Following the 'Workstation Setup'
Follow the steps on [the official Omniverse IssacSim Workstation Setup](https://docs.omniverse.nvidia.com/app_isaacsim/app_isaacsim/install_workstation.html#isaac-sim-app-install-workstation).

1. Download the Omniverse Launcher (need registration). It is an AppImage file. [Change it to an executable file](https://docs.appimage.org/introduction/quickstart.html) and run it.

2. Install Cache. Use the default paths for instllation, and check the box for installing Cache. (If not checked, don't worry, go to EXCHANGE tab after installation, and search for 'cache', then install it there.)

3. Install Nucleus. Go to the NUCLEUS tab, and click 'Add local nucleus service'. Follow [this official guide](https://docs.omniverse.nvidia.com/prod_nucleus/prod_nucleus/workstation/installation.html) for the rest of the steps. If successful, click the 'three bars' next to 'Local Nucleus Service' and select 'Settings', it should bring up the status of the Nucleus service.

4. Install Isaac Sim. Go to the EXCHANGE tab, and search for 'isaac', install it. (This may take a while, and there are different ways this can fail. Refer to the next section for some typical issues and resolutions.)