# VMWare Problems and Solutions FAQ


## My VM will not start at all!
I get an error message in a dialog box that contains … Error cannot access ... Virtual Disk.vmdk' or one of the snapshot disks it depends on. Module 'Disk' power on failed. Failed to start the virtual machine.

### Steps to Resolve:
1. Go to your virtual machine file in the Finder.
2. Right click on the file and choose Show Package Contents
3. Now you will need to scan through the files looking for xxxxx.vmx.lck  You will probably find two folders with a name like that.  You should Trash both of those folders  Restart your VM, and it should work.



# Contribute to this FAQ
If you run into a problem, and figure out how to fix it on your own, please contribute your problem and solution here.

1.  Fork this repository
2.  Make your changes to this file
3.  Make a pull request
