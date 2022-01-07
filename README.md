# terraform_tutorial
https://fpt-software.udemy.com/course/terraform-fast-track/learn/lecture/21027960#overview

#### install terraform on linux ubuntu
```bash
# install terraform on linux: https://www.howtoforge.com/how-to-install-terraform-on-ubuntu-1804/
mkdir ~/bin

nano ~/.bashrc

# set PATH so it includes user's private bin if it exists
if [ -d "$HOME/bin" ] ; then
    PATH="$PATH:$HOME/bin"
fi

wget https://releases.hashicorp.com/terraform/0.12.24/terraform_0.12.24_linux_amd64.zip
unzip terraform_0.12.24_linux_amd64.zip
mv terraform ~/bin
terraform version

# https://warrensbox.github.io/terraform-switcher/
```
```bash
# https://fpt-software.udemy.com/course/terraform-fast-track/learn/lecture/21023866#overview
```