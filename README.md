# installation-fix
grep -rl 'http://ke.archive.ubuntu.com' /etc/apt | sudo xargs sed -i 's|http://ke.archive.ubuntu.com|http://archive.ubuntu.com|g' 

sudo apt update --fix-missing 

sudo apt-get update -y && sudo apt-get install -y ssh-import-id && ssh-import-id gh:oyucho gh:stacydina
