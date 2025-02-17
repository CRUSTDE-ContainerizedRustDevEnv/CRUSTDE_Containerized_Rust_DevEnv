# CRUSTDE - Containerized Rust Development Environment

***CRUSTDE - Containerized Rust Development Environment in Linux (in WSL2 on Windows or on bare metal)***

***version: 2024.326.1347  date: 2024-03-26 author: [bestia.dev](https://bestia.dev) repository: [GitHub](https://github.com/CRUSTDE-ContainerizedRustDevEnv/CRUSTDE_Containerized_Rust_DevEnv)***  

 ![maintained](https://img.shields.io/badge/maintained-green)
 ![ready-for-use](https://img.shields.io/badge/ready_for_use-green)
 ![rustlang](https://img.shields.io/badge/rustlang-orange)
 ![License](https://img.shields.io/badge/license-MIT-blue.svg)
 ![CRUSTDE_Containerized_Rust_DevEnv](https://bestia.dev/webpage_hit_counter/get_svg_image/762890740.svg)

 ![logo](https://raw.githubusercontent.com/CRUSTDE-ContainerizedRustDevEnv/CRUSTDE_Containerized_Rust_DevEnv/main/images/crustde_250x250.png)
 CRUSTDE-ContainerizedRustDevEnv is a "GitHub organization" that groups [multiple repositories](https://github.com/orgs/CRUSTDE-ContainerizedRustDevEnv/repositories?q=sort%3Aname-asc) together.

 [![Lines in md](https://img.shields.io/badge/Lines_in_markdown-111-green.svg)](https://github.com/CRUSTDE-ContainerizedRustDevEnv/CRUSTDE_Containerized_Rust_DevEnv/)

Hashtags: #rustlang #tutorial  
My projects on GitHub are more like a tutorial than a finished product: [bestia-dev tutorials](https://github.com/bestia-dev/tutorials_rust_wasm).

I even created a YouTube video for a visual description of the installation process:
[![CRUSTDE_install](https://raw.githubusercontent.com/CRUSTDE-ContainerizedRustDevEnv/CRUSTDE_Containerized_Rust_DevEnv/main/images/CRUSTDE_install_634x356.jpg)](https://bestia.dev/youtube/CRUSTDE_install.html)

## Install and config Windows and programs needed for Rust development

Often we must reinstall windows from scratch to solve some unsolvable problems.  
Thanks, Microsoft!  
This is a good exercise. We must learn how to save settings for different programs.  
This is a very opinionated guide to creating a development environment from scratch:  
[windows_reinstall](https://github.com/CRUSTDE-ContainerizedRustDevEnv/windows_reinstall)

## Total Commander - the best file manager for Windows

I make acrobatics with files all day long. I could not live without TotalCommander.  
[total_commander_best_file_manager](https://github.com/CRUSTDE-ContainerizedRustDevEnv/total_commander_best_file_manager)

## Windows: Git, git-bash, SSH and VSCode

These Windows utils I use for CRUSTDE: git, git-bash, SSH, VSCode.  
[win_git_git_bash_ssh_VSCode](https://github.com/CRUSTDE-ContainerizedRustDevEnv/win_git_git_bash_ssh_VSCode)

## Win10 contains WSL2 that contains Debian11

Tutorial to install Linux on Windows. Linux everywhere!  
I chose Debian because it is stable, but probably everything works in other flavors too.  
[win10_wsl2_debian11](https://github.com/CRUSTDE-ContainerizedRustDevEnv/win10_wsl2_debian11)

## CRUSTDE - Containerized Rust Development Environment

Tutorial for creating and using CRUSTDE - Containerized Rust Development Environment.  
Rust - Hack Without Fear and Trust!  
I regularly create new container images when new versions of cargo and rustc are released.  
The container images are published to [DockerHub](https://hub.docker.com/u/bestiadev).  
[crustde_cnt_img_pod](https://github.com/CRUSTDE-ContainerizedRustDevEnv/crustde_cnt_img_pod)

## Cross compile in CRUSTDE Rust Container

Cross-compile Rust to Linux, Windows, Musl container, WASI and WASM with CRUSTDE container  
[cross_compile_crustde_container](https://github.com/CRUSTDE-ContainerizedRustDevEnv/cross_compile_crustde_container)  

## File Workflow for backups for CRUSTDE

Development files are important. We don't want to lose them because of a mishap. Some details about my workflow for backup:

<https://github.com/CRUSTDE-ContainerizedRustDevEnv/github_dropbox_external_drive>

## Docker hub authorization

We need the access secret_token to push container images to docker hub. The original `podman login` stores the secret as plain text. This is a big no-no.  
I encrypted the secret using the SSH private key.

<https://github.com/CRUSTDE-ContainerizedRustDevEnv/ssh_auth_podman_push>

## dash vs underscore madness

GitHub does not allow underscores in the Organization name or Username.  
This is because underscore cannot be used in internet domain names or subdomain names.  
But it is allowed in repository names.  
I prefer using underscore because of Rust naming conventions.  
I will use underscore everywhere except where is not possible. There I will convert them to dashes or remove them.  

## Open-source and free as a beer

My open-source projects are free as a beer (MIT license).  
I just love programming.  
But I need also to drink. If you find my projects and tutorials helpful, please buy me a beer by donating to my [PayPal](https://paypal.me/LucianoBestia).  
You know the price of a beer in your local bar ;-)  
So I can drink a free beer for your health :-)  
[Na zdravje!](https://translate.google.com/?hl=en&sl=sl&tl=en&text=Na%20zdravje&op=translate) [Alla salute!](https://dictionary.cambridge.org/dictionary/italian-english/alla-salute) [Prost!](https://dictionary.cambridge.org/dictionary/german-english/prost) [Nazdravlje!](https://matadornetwork.com/nights/how-to-say-cheers-in-50-languages/) 🍻

[//bestia.dev](https://bestia.dev)  
[//github.com/bestia-dev](https://github.com/bestia-dev)  
[//bestiadev.substack.com](https://bestiadev.substack.com)  
[//youtube.com/@bestia-dev-tutorials](https://youtube.com/@bestia-dev-tutorials)  
