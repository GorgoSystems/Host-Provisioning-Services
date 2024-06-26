# Host Provisioning Services
Virtual Disks deployment platform in local hardware with VHDx.

Create and deploy vDisks with VHDx and Windows Native Boot, clients will download and locally mount the vDisk working with the local hardware as if the operating system was locally installed. You can centrally update your vDisks and clients will be updated too. No more deploying Windows updates with WSUS or installing new software.

Check out the [documentation page](https://doc.gorgosystems.com) for details of the available features.

- Super-Fast Deployment: image compression up to 50% of the image size.
- Bandwidth Optimization: Robust Background Intelligent Transfers and Branchcache on WinPE.
- User Data Management: User State Migration and persistent drive.
- Driver Management: use the Windows Catalog or distribute drivers from the console.
- Domain Integration: multi-domain support.
- High Availability: disks and configuration synchronization between servers.
- Permanent License: Host Provisioning will not stop working with an expired license.

Here you can [download](https://github.com/GorgoSystems/Host-Provisioning-Services/releases/latest) the binaries of Host Provisioning Services.

- Host Provisioning Server: use the Administration Console in a browser to configure clients and servers.
- Host Provisioning Client: install the client in your base images to centrally manage configurations and updates.
- Host Provisioning WinPE Preparation Tool: create a ready-to-go WinPE image to deploy operating systems.
- Configuration files: sample configuration files for User State Migration Tool (USMT), 802.1x enabled deployments, unattended sysprepped images.

Find out how to [get started](https://doc.gorgosystems.com/getting-started/install-server).

Contact us and license information at https://www.gorgosystems.com
