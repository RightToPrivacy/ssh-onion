# ssh-onion
fully automates ssh onion creation: to allow remote ssh access without having to open any ports on router/firewall.

Only those you share the onion address with will be able to ssh if you block ssh locally/do not open firewall/router port forward.

After created, onion address prints to screen.

#### USAGE

    sudo bash ssh-onion

(originally created to remotely help friends by shell - but can be used to automate ssh onion creation for anyone)

The next usernew script is for adding a trusted sudo user (audit etc/if you use it)

To use this, edit the username variable value and run with:

    sudo bash usernew

BLOG: https://www.buymeacoffee.com/politictech/posts
mirror: https://politictech.wordpress.com

email: righttoprivacy[at]tutanota.com
