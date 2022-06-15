# Open API Proto Messages

You can download the latest version of Open API proto message files from this repository releases.

You can find each relese changelog and also for references you can check Open API [documentation](https://spotware.github.io/open-api-docs/).


## Update Docs References Action

This action will run on each release, it clones the help portal repository, then it updates the proto message files of Open API and then it commits and pushes.

For creating SSH key use:

```
$ ssh-keygen -t rsa -b 4096 -f ./KEY_FILE_NAME -C "your-email@spotware.com" -N ""
```

Then use public key as deploy key for Help Portal repository and private key for cloning or pushing changes to it.