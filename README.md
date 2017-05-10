myEngineering platform manifest for Quantinuum HDAP
====================================
This manifest fetchs the required to Yocto project layers to build Quantinuum project.

Download the Source
===================
Currently the manifest fetches:
 * poky layer
 * meta-oe layer
 * meta-xilinx layer (with Zybo linux_bd support)
 * ZYBO hardware design

Initializing Repository
-----------------------

Initiate core trees:

    $ repo init -u https://github.com/fh666z/meta-manifest.git -b jethro

Sync the repository:

    $ repo sync

