# ssh-onion
fully automates ssh onion creation: to allow remote ssh access without having to open any ports on router/firewall.

Only those you share the onion address with will be able to ssh if you block ssh locally/do not open firewall/router port forward.

After created, onion address prints to screen.

#### USAGE

##### OPTION #1:

run setup in your shell to completely setup everything:

    bash setup
    
### OR DO THE FOLLOWING TO RUN SCRIPTS BY HAND:

    sudo bash ssh-onion

(originally created to remotely help friends by shell - but can be used to automate ssh onion creation for anyone)

The next usernew script is for adding a trusted sudo user

To use this, edit the username variable value and run with:

    sudo bash usernew
    
(Created to help secure friend Linux system) If usernew script is run, escalation to root can be done with:

    sudo bash 

from the $username inside usernew.



BLOG: https://www.buymeacoffee.com/politictech/posts
mirror: https://politictech.wordpress.com

email: righttoprivacy[at]tutanota.com
