<p align="left">
   <a href="https://discord.gg/ZpXvd2RJVz"><img src="https://img.shields.io/badge/discord-join-7289DA.svg?logo=discord&longCache=true&style=flat" /></a>
</p>

# Single-GPU-passthrough-amd-nvidia

## if you are having troubles please see the '[manual](https://github.com/wabulu/Single-GPU-passthrough-amd-nvidia/tree/3d8666e66d009493a3f5b574bdba15954ed86af5)' branch

### My single gpu passthrough guide, it is fully automatic, and it is as simple as it gets

### DISCLAIMER: This guide is pretty similar to many other single gpu guides, I am not trying to copy them nor take their credits, This guide is combining them all together for a better more fluid guide, this way you can use the scripts on all display-services and both amd/nvidia gpus (there might be some anomalies)

<br />

### Step 1:

- Get the repository on your computer, either by downloading it zipped and extracting or cloning it as below
- If you chose to clone it instead of downloading it you should do <br />
  ```cd ~/Downloads ```<br />
  ```git clone https://github.com/wabulu/Single-GPU-passthrough-amd-nvidia.git```<br />

### Step 2:

- Install pip using your default package manager, for most people it'll be either ``apt-get install python3-pip``
  or ``pacman -S python3-pip`` <br/>

### Step 3:

- Run the script which would do (almost) everything for you by changing your directory to the folder with <br/>
  ``cd Single-GPU-passthrough-amd-nvidia/ ``<br/>
  and then executing the script with ``sudo sh ./start.sh`` <br/>

### Step 4:

Now you just need to setup virt-manager as for now the scripts doesn't do it automatically, <br/>
you can do that by visiting
this <a href="https://gitlab.com/risingprismtv/single-gpu-passthrough/-/wikis/5)-Configuring-Virtual-Machine-Manager">
link</a>

### Step 5:

If you did everything right you can try running the vm (make sure it's named win10 otherwise make sure the folder win10
in /etc/libvirt/hooks/qemu.d is named accordingly) <br/>
nvidia users might also want to go to
this <a href="https://gitlab.com/risingprismtv/single-gpu-passthrough/-/wikis/6)-Preparation-and-placing-of-ROM-file">
link</a>.<br/>
If you have any problems you can join my discord server for faster response (top left) *or* you can mention me in your
reddit post at r/VFIO with u/wabulu.

### Contributing

- You can search the files for #TODOs and do them, it would help me alot !

Check out these amazing people who made this guide possible !

- https://gitlab.com/risingprismtv
- https://gitlab.com/YuriAlek
- https://passthroughpo.st/
