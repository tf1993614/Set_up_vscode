# Set_up_vscode

## connect vscode with host
1. In the local, run `ssh-keygen`.
2. Put the public key to the  `.ssh` folder in the host.
3. In the host, run `cat id_rsa.pub >> authorized_keys`.
4. In the vscode, put the path of private key in the local.

#
