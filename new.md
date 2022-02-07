# Show me how to git

## Checking Statuses

git status  -> Returns the status of all files, with warning for not added versions

## Adding

git add .  -> Add all new files and modification ones

## Committing

It needs to have at least one message that shows what was done.

git commit -m "message1" -m "message2"

git commit -m "Added index.html" -m "Added all the info about added_index.html, plus this new.md file"



## Pushing

In order to push (publish) the changes on the remote repository, you first need an SSH key

### SSH Key

Work as a validation key. It's needed to validate that you is you, without an logged instance

#### Generating key

ssh-keygen -t rsa -b 4096 -C "your@email.com"  <-- Same e-mail as you use on e-mail

#### Searching for key

ls <- search

It would return 2 files

1) testkey -> your own private key
2) testkey.pub -> your own public key (able to share with other to validate)