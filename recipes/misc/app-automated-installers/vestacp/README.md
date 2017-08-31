# VESTA CONTROL PANEL AUTOMATED INSTALLATION SCRIPT ON CENTOS7 AND UBUNTU1604LTS (64 BITS)

This script will do a basic distribution setup with some usefull packages, then install vestacp with all primary services. The password will be autogenerated and stored on the file "/root/vesta-credentials.txt".

Please note that this script will disable both firewalld and selinux on Centos 7 machines. If you want you can install them back after this script finish its run.

# GENERAL REQUIREMENTS:

This script will fail if the following requirements are not meet:

- Operating System: Centos 7.
- Architecture: x86_64/amd64.
- INSTALLED RAM: 1024MB (1GB).
- CPU: 1 Core/Thread.
- FREE DISK SPACE: 5GB.
