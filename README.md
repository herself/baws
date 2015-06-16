# baws
Simple shell script for listing AWS resources - bash AWS

### What it can do
Not much! For now, three things:
* List VPCs with their names
* List all EC2 instances in a VPC
* Monitor (with `watch`) instances in a VPC

It does it much faster than clicking though the AWS EC2 console or wrestling with the cli client each though!

### What it needs
* The `aws` cli client (duh!)
* A very recent version of [jq](https://github.com/stedolan/jq) (which you need to download manually from their github, since it's a release candidate)
* [fzf](https://github.com/junegunn/fzf) for handling interactive dialogs

### Installation
As easy as dropping the script into your `$PATH`

### Demo
![gif](http://zippy.gfycat.com/FocusedThickBluewhale.gif)
