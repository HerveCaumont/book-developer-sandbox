# Join your Laboratory

The purpose of this section is to guide you with the installion and use of your OpenVPN Client, in order to let you authenticate on Terradue’s VPN server and let your IP join your Laboratory on Terradue's Cloud Platform.

> What is a Laboratory ? Once you have established your Virtual Private Network, you are authorized on Terradue's Cloud, in a Cloud Services collaborative workspace called a Laboratory. A Laboratory regroups a Developers team and their Support services.

IMPORTANT NOTICE: if you have a previously installed VPN client (e.g. tunnelblick) on your system, such previously installed client must be disconnected and then be disabled (we recommend uninstalling it) BEFORE you proceed with the steps below.

* **Automated setup**: go to https://access.terradue.com and login using your Platform credentials (*username* and *password*). Once logged, most of the setup is automatic. Download your pre-configured OpenVPN client. Follow the installation wizard.

* **Running your VPN connection**: from your desktop tray, click on the “OpenVPN Connect” icon. From the dropdown menu, select the entry “Connect to access.terradue.com”. 

You are now connected ! Verify that the “OpenVPN Connect” icon is now featuring a green symbol.

Once connected to the VPN, the procedure for accessing your Sandbox will makes use of your private keys with SSH access. [Access your Sandbox](../4/Access your Sandbox.html) now !

> Need to go further with your Virtual Private Network configuration ? Check the advanced features below.

* **Manual setup on other computers**: you can download the “OpenVPN Connect” client in order to install it on another computer. Check the installation material and configuration templates from here: https://access.terradue.com/?src=login. If required, connection settings (profiles) can also be downloaded.

* **Command Line Interface**: some users need to use the OpenVPN’s command line interface. You can execute the “openvpn” command from a Unix Shell or Windows Prompt. It accepts the same parameters and has the same behavior regardless of the Operating System.

* **Autostart script**: in addition, you can use the “openvpn” command in a script to automatically start the VPN connection. The OpenVPN Command line section describes how to build and install OpenVPN for most of the operating systems, and use it via command lines.