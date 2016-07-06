# chef

on windows, rsync,ssh,gcc such things managed by cygwin

vagrant hashiCorp

ruby installer and devkit (lower version is more stable like 2.1.0)

and git needed

# use this if it occurs error while installing vim-plugins. 
sed -i 's/\r//g' file_name
sed -i 's/^M//g' file_name

This happened to me when I cloned this repo on windows7 env and knifed to centos.

# SSL_connect returned=1 errno=0 state=SSLv3 read server certificate B: certificate verify failed

mkdir .berkshelf
cd .berkshelf
create file 'config.json' and write 
```
{
  "ssl": {
    "verify": false
  }
}
```
