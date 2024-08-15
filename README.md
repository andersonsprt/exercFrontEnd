# exercFrontEnd
exercicios JP


- criando chave ssh

```
MacBook-Pro-de-Anderson:~ andersongama$ ssh-keygen -t ed25519 -C "andersonprt@gmail.com"
Generating public/private ed25519 key pair.
Enter file in which to save the key (/Users/andersongama/.ssh/id_ed25519): 
Created directory '/Users/andersongama/.ssh'.
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /Users/andersongama/.ssh/id_ed25519.
Your public key has been saved in /Users/andersongama/.ssh/id_ed25519.pub.
The key fingerprint is:
SHA256:EhxwMM+c95TMpeeQnCuUHJicTQoH6fOefbpBBRNypKI andersonprt@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|    **=BO.  .    |
|    .X=O.O *     |
|   .. X = % .    |
|   .o. + + =     |
|  E  o. S o .    |
|      .o .       |
|     . o.        |
|      o ...      |
|        o+       |
+----[SHA256]-----+
```


MacBook-Pro-de-Anderson:~ andersongama$ cat < ~/.ssh/id_ed25519.pub
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIHPrqIS90SAm0yQYUE07+96btFBI/QODN7rR84c04EqK andersonprt@gmail.com
MacBook-Pro-de-Anderson:~ andersongama$ ls
Applications			Library				Public
Desktop				Movies				eval "$(ssh-agent -s)
Documents			Music				eval "$(ssh-agent -s).pub
Downloads			Pictures
MacBook-Pro-de-Anderson:~ andersongama$ cd Documents/
MacBook-Pro-de-Anderson:Documents andersongama$ ls
MacBook-Pro-de-Anderson:Documents andersongama$ git clone git@github.com:andersonsprt/exercFrontEnd.git
Cloning into 'exercFrontEnd'...
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ECDSA key fingerprint is SHA256:p2QAMXNIC1TJYWeIOttrVc98/R1BUFWu3/LiyKgUfQM.
Are you sure you want to continue connecting (yes/no)? yes
Warning: Permanently added 'github.com,20.201.28.151' (ECDSA) to the list of known hosts.
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.
