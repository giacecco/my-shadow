my-shadow
=========

##Requirements
- GPG 1.x
- https://github.com/sferik/t
- https://github.com/defunkt/gist

##Installation
1. Install the *gpg*, *t* and *gist* binaries, so that they are in the $PATH.
2. Configure *t* and move the Twitter credentials from ```~/.trc``` to ```secret/twitter.credentials```. Test to see if it works, e.g. by reading someone else's timeline: ```t timeline giacecco --profile=secret/twitter.credentials```.
3. Create key pairs for any reader you would like to - some day in the future - disclose your secrets to, by doing ```./create-recipient [recipient nickname]```.
4. Write your secret in a simple text file, e.g. ```message.txt```.
5. Send the secret to everybody, by doing ```./send-to-all message.txt```.
