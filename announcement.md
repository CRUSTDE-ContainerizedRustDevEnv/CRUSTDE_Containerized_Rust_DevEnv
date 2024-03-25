# CRUSTDE - Containerized Rust Development Environment

![logo](https://raw.githubusercontent.com/CRUSTDE-Containerized-Rust-DevEnv/CRUSTDE-Containerized-Rust-DevEnv/main/images/crustde_250x250.png)

<https://github.com/CRUSTDE-Containerized-Rust-DevEnv>

This is an opinionated guide for beginners how to set up CRUSTDE - Containerized Rust Development Environment. The isolation of the container will not allow Rust code to mess with your primary system (FYI: this kind of isolation is good but not perfect).  

I regularly create and upload this container image to DockerHub when new version of rustc is released. Recently version 1.77.0. It already contains a lot of tools that are useful for Rust development.

This is a Linux container that can be run on Linux on bare metal or on Linux inside WSL2 on Windows.

For developers using Windows like myself, the guide starts with the Windows installation and describes how to configure WSL2 and install Debian. For good measure there are detailed description how to install and config some programs I use for development like VSCode, Total Commander and git.

Once Debian is installed inside WSL2 it works just the same as having Debian on bare metal. From here on, the same instructions can be used in Debian on bare metal or Debian in WSL2 on Windows.

In Debian, I use Podman to download, run and manage the containers and the pods (a group of containers).

Installing and using the CRUSTDE container is simple. Just follow the instructions printed by the bash scripts.

But for developers that want to tinker, there is an excruciating amount of details that describe how everything is created and can be modified.

This is an updated version  of the initial project from Mar 2022:
Rust: Hack Without Fear and Trust! (A complete development environment for Rust with VSCode inside a docker container) 
https://users.rust-lang.org/t/rust-hack-without-fear-and-trust-a-complete-development-environment-for-rust-with-vscode-inside-a-docker-container/72922/1



Subject:
Announcing CRUSTDE - Containerized Rust Development Environment


