# ansible-examples
Some examples for the Ansible introduction session with OpenNTF.

## Step 9

You need to hash the user password for this step, so you can run:

    python3 -c 'import crypt,getpass;pw=getpass.getpass();print(crypt.crypt(pw) if (pw==getpass.getpass("Confirm: ")) else exit())'

and paste the output to playbook.yml.
