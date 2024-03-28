# CRUSTDE - Containerized Rust Development Environment


//github.com/CRUSTDE-ContainerizedRustDevEnv/CRUSTDE_Containerized_Rust_DevEnv

This is an opinionated guide for beginners how to set up CRUSTDE - Containerized Rust Development Environment. The isolation of the container will not allow Rust code to mess with your primary system (FYI: this kind of isolation is good but not perfect).  

I even created a YouTube video for a visual description of the installation process.

I regularly create and upload this container image to DockerHub when new version of rustc is released. Recently version 1.77.0. The image contains a lot of tools that are useful for Rust development. So you don't have to install them.

This is a Linux container that can be run on Linux on bare metal or on Linux inside WSL2 on Windows.

For developers using Windows like myself, the guide starts with the Windows installation and describes how to configure WSL2 and install Debian. For good measure there are detailed description how to install and config some programs I use for development like VSCode, Total Commander and Git.

Once Debian is installed inside WSL2 it works just the same as having Debian on bare metal. From here on, the same instructions can be used in Debian on bare metal or Debian in WSL2 on Windows.

In Debian, I use Podman (alternative to Docker) to download, run and manage containers and pods.

Installing and using the CRUSTDE container is simple. Just follow the instructions printed by the bash scripts.

But for developers that want to tinker, there is an excruciating amount of details that describe how everything is created and can be modified.



Subject:
Announcing CRUSTDE - Containerized Rust Development Environment

The moderator keep removeing my post. First because it is a video. 
And the excuse is that the game posts videos.

