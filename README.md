# ansible-examples
Some examples for the Ansible introduction session with OpenNTF.

## Step 9

You need to hash the user password for this step, so you can run:

    python3 -c 'import crypt,getpass;pw=getpass.getpass();print(crypt.crypt(pw) if (pw==getpass.getpass("Confirm: ")) else exit())'

and paste the output to playbook.yml.

## Step 10 

Add some variables

## Step 11

Create a new role to split the large playbook to something more readable.

    ansible-galaxy init ansible-test-role
