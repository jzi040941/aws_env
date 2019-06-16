# aws_env
aws_env shell

# what to do

`
sudo apt-get update
sudo apt-get isntall cmake
sudo apt-get install build-essential
sudo apt-get install xinit
`

# x11 env

## Edit (or create) the file /etc/X11/Xwrapper.config with the following content:

`
allowed_users=anybody
needs_root_rights=yes
`
