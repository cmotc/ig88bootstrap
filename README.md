ig88bootstrap
=============

local manifest for loading ig-88.xml, which configures the IG-88 ROM. From the root of your 
Android/CyanogenMod/Replicant/Ubuntu mobile development tree, run the command.

        git clone https://github.com/cmotc/ig88bootstrap .repo/local_manifests/

to add ig88bootstrap.xml to your local_manifests folder. Then run

        repo sync 

to pull down the latest IG-88 ROM manifest. Then run

        repo sync 

again to sync the ig88ROM apps.

IG-88 is a work in progress. One thing it does is include several different source repositories in
the main build, which in this case requires adding remotes to your tree(git.torproject.org, bitbucket.org).
If you get an error where it says "remote not found" simply

        rm .repo/local_manifests/ig-88.xml
        repo sync

Want the mischeif to happen faster? This is my bitcoin address. You know what to 12r5qD85GMSkBMj7KYDW3BDw89ZRCWWj5E
