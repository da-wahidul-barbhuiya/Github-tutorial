# Generating ssh key-pair :

From terminal you can generate ssh key pair 

## step 1: Creating ssh key using your email.

```
ssh-keygen -t rsa -b 4096 -C "wahidul.b@decodeage.com"

```

## step 2: Go to the directory of .ssh . Upon of ls you will get four different files eg. id_rsa,id_rsa.pub,known_hosts,known_hosts.old

```
cat id_rsa.pub
```

## step 3: copy the content from the file and open github repo follow this
Setting > SSH and GPG keys > New SSH key> paste in the key section

## step 4: click on Add SSH key,it will save 

## step 5: Now every time when you are using git push pull you can