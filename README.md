# ssh-onion
fully automates ssh onion creation: to allow remote ssh access without having to open any ports on router/firewall.

Only those you share the onion address with will be able to ssh if you block ssh locally/do not open firewall or port forward.

After created, onion address prints to screen.

#### USAGE

##### OPTION #1: INSTALLS SSH + Tor AND ADDS SUDO USER + CONFIGURES/CREATES SSH ONION ADDRESS

run setup in your shell to completely setup everything (adds sudo user as well as installs ssh + tor + configures ssh onion):

    bash setup
    
Running 'bash setup' will execute both ssh-onion and usernew. Read the script to better understand.    
    
### OPTION #2: RUNNING THIS SCRIPT (ssh-onion) ALONE ONLY CREATES AN SSH TOR HIDDEN SERVICE AND PRINTS IT TO SCREEN:

    sudo bash ssh-onion

(originally created to remotely help others by onion based ssh shell - but ssh-onion alone can be used to automate ssh onion creation for anyone)

The next usernew script is for adding a trusted sudo user

To add sudo user, edit the username variable (inside usernew) and run:

    sudo bash usernew



BLOG: https://www.buymeacoffee.com/politictech/posts
mirror: https://politictech.wordpress.com

email: righttoprivacy[at]tutanota.com
