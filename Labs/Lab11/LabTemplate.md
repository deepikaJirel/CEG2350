## Lab 11

- Name:Dipika Jirel
- Email:jirel.2@wright.edu

## Part 1 Answers:

1. `tar` options:
   - `-c`: Create a new archive.
   - `-v`: Verbose output.
   - `-f`: Specifies the filename of the archive.
   - `-z`: Filter and compress the archive through gzip.
   - `-x`: Extract files from an archive.
   - `-t`:  List the contents of an archive.
2. Command(s) to create and compress your archive:`tar -cvzf labfolder.tar.gz labfolder`

## Part 2 Answers:

1. Command to connect with `sftp`:`sftp 2350`
2. `sftp` options:
   - `ls`: It lists the files and directories in the current directory on the local system.
   - `lls`: It lists the files and directories in the current directory on the local system.
   - `put`: It uploads a file from the local system to the remote server.
   - `get`: It helps download a file from the remote server to the local system.
3. Command(s) to use `sftp` to download your `.tar.gz` file to your system: `get labwork.tar.gz /home/ubuntu/`
4. Command(s) to decompress & extract your `.tar.gz` file to your system: `tar -xvzf labwork.tar.gz`


## Part 3 Answers:

1. Command to install `apache2` or `nginx`: `sudo apt install apache2`
2. Command to confirm that web serving service is running:`sudo systemctl status apache2`
3. Command to download [`simple-site.tar.gz`](simple-site.tar.gz) to your AWS instance:`wget https://github.com/pattonsgirl/CEG2350/raw/refs/heads/main/Labs/Lab11/simple-site.tar.gz`
4. Command(s) to change permissions: `sudo chown -R ubuntu:ubuntu /var/www/html`
5. Command to extract the compressed archive to `/var/www/html`:`tar -xvzf simple-site.tar.gz -C /var/www/html`
6. Required changes to `index.html` will be awarded credit based on screenshot.`http://44.217.99.208`
7. [Insert screenshot of your website (with the URL bar included)]()

## Part 4 Answers:

1. Command to generate a new key, with options entered into the fields 
```
`ssh-keygen -t rsa -b 4096 -f ~/.ssh/my_key`
Generating public/private rsa key pair.
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /root/.ssh/my_key
Your public key has been saved in /root/.ssh/my_key.pub
The key fingerprint is:
SHA256:MFaksFouu5gN6byKjX01lLKE+BirAcYISJTCVXLvClk root@DipikaJirelLT
The key's randomart image is:
+---[RSA 4096]----+
|=ooooo .o        |
|+o  oo.o         |
|=. .oE=o         |
|=o.+=.+o         |
|o=o+.+ .S        |
|+..oo +          |
|+..  o .         |
|=O ..            |
|B+*.             |
+----[SHA256]-----+

```

2. Create the user and / or prove the user exists
```
`sudo adduser deepikajirel`
Adding user `deepikajirel' ...
Adding new group `deepikajirel' (1004) ...
Adding new user `deepikajirel' (1003) with group `deepikajirel' ...
Creating home directory `/home/deepikajirel' ...
Copying files from `/etc/skel' ...
New password:
Retype new password:
passwd: password updated successfully
Changing the user information for deepikajirel
Enter the new value, or press ENTER for the default
        Full Name []: Deepika Jirel
        Room Number []: 3d
        Work Phone []: 000
        Home Phone []: 000
        Other []: 000
Is the information correct? [Y/n] y
```

3. Contents of `~/.ssh/authorized_keys` in remote user account:
```
Enter contents here
```

4. `ssh` command:

5. Updated `config` file contents:
```
Enter block with connection information in config file here
```

6. `ssh` command post `config` file entry:
