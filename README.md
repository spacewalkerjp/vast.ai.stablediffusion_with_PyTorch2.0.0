# Setup : `vast.at` Stable Diffusion with PyTorch2.0.0

# Instance configuration (25th Apr 2023ver)
* Image : nvidia/cuda:11.8.0-cudnn8-runtime-ubuntu22.04
* Launch Type: ssh
* On-start script: Not set
* Disk Space To Allocate: over ~50GB (recommend)
* Launch mode : 
   * Run interactive shell server, SSH. This will allow you to connect and run commands using an SSH client.
   * `Checked` : Use direct SSH connection - faster than proxy, but limited to machines with open ports. Proxy ssh still available as backup.
