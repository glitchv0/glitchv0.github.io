In this post I’m going to over getting a local AWX instance going on CentOS 8.  AWX is the open source version of Ansible Tower and it is a web interface/API interface.  AWX allows you to use things like HashiCorp Vault for credentials (which I’ve covered).

Don't worry, this will be super easy, barely an inconvenience.

I’m going to be installing CentOS 8 on Vmware ESXi 6.7.  Your hypervisor shouldn’t matter however, you should be able to do this in any environment.

I’m creating a VM with 4 CPU and 8GB of RAM, 20GB of disk space.  I’m using the CentOS 8 install DVD for the source install.

In the Setup for CentOS, In the Software Selection part, I set it to Minimal Install
