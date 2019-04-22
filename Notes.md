# PGP/GPG

## Scope
These notes are a source of reference for PGP/GPG.

## Key Server
I'm currently using [hkps://hkps.pool.sks-keyservers.net] as the
key server to store my keys.

## Set up on a new device
I use the [https://wiki.archlinux.org/index.php/GnuPG#SSH_agent] article
from the Arch documentation.  I end up implementing the .bashrc section
to get things to work.  I've uploaded my test key to the public key
server, but it doesn't seem to be pulling correctly yet.  Instead, I
have manually exported and imported my public keys.

## Generate SSH key
To generate the ssh key, use `gpg --export-ssh-key <userid>` to print
the SSH key to the console.
