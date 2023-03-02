# [tacotron2](http://github.com/nvidia/tacotron2) support for [VeTube](https://github.com/metalalchemist/VeTube)

## Introduction

Let's remember that VeTube is a program that allows us to read chats from your favorite live streamings in real time. This includes user messages, moderation, donations, etc.

This plug-in is a support for reading chats using voices made with artificial intelligence, thanks to Tacotron2, one of these technologies that offer us these possibilities.

## instructions

Note: For now, the server can only be run via source code. Work is being done on a distributed version for all users.

### Cloning

#### From VeTuve repo

1. Clone the repo:

`git clone https://github.com/metalalchemist/VeTube`

2. Make a CD to the repo:

`cd VeTube`

3. Initialize the submodules:

`git submodule init`

`git submodule update`

#### Clone the repository directly (useful for submitting contributions)

1. clone the repo:

`git clone https://github.com/rmcpantoja/tacotron2-for-VeTube`

2. CD to the repo:

`cd tacotron2-for-VeTube`

### installing

1. To run the client, you need [AutoIt](http://autoitscript.com/) version 3.3.16+.

2. for server, you can go to his folder in the main repo

`cd server`

and install requirements:

`pip install -r requirements.txt`

## use

To use this plugin, you just need to run `client/tt4VeTube.au3`. The client and server will load and when this is done you will be shown a message that everything is ready and some instructions.

## key commands:

At the moment, the plugin has two key commands that can be executed in the background and they are the following:

* CTRL+SHIFT+E: Exits the client.
* CTRL+SHIFT+S: Opens a configuration window of the plugin, where you can select parameters related to the voices, including the download of them. We have many models in Spanish for now.

# credits

Mainly to [metalalchemist](http://github.com/metalalchemist) and all his collaborators behind this project.