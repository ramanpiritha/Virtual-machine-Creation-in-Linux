 # Ex no-1: VIRTUAL MACHINE CREATION IN LINUX
 # Date : 20-11-24
 # Name: Piritharaman R
 # Reg no: 212223230148
 ## AIM
       To Install Virtualbox / VMware Workstation with different flavours of linux.
## PROBLEM STATEMENT
    Explain about the Experiment.

## ALGORITHM
Step 1:Open VirtualBox 
Step 2: Go to File -> New to create a new virtual machine. 
Step 3:Enter a name for your CentOS VM.Choose Linux as the type and CentOS as the version (or select the closest option available if CentOS is not listed). 
Step 4:Select the CentOS ISO image you downloaded. Set the base memory to 1024 MB (1 GB) Allocate 1 processor core Set the disk size to at least 20 GB Complete the configuration by clicking Finish to create the virtual machine 
Step 5:Select the created VM, go to Details (or Settings), and navigate to the Network tab. Configure Adapter 1 as NAT (for internet access through the host). Configure Adapter 2 as Bridged Adapter (for direct access to the local network, if needed). Click OK to save network settings. 
Step 6:Click Start to boot up the newly created virtual machine. During installation, set a password for the root user. After logging in to CentOS, open a terminal to start using the command line.
## COMMANDS

## Switch to User:
su username

# View IP Address:
ip a

# Create a Directory:
mkdir <directory_name>

# Change to the New Directory:
cd <directory_name>

# Edit the Hostname File:
vi /etc/hostname

# View the Content of the Hostname File:
cat /etc/hostname

## OUTPUT
![image](https://github.com/user-attachments/assets/a27ff5cc-a335-4950-8e32-536cf04d8e77)
## RESULT
 Virtualbox / VMware Workstation with different flavours of linux is successfully installed.

  


