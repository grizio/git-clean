# git-cleanup 🧹

A simple script to clean your remote local branches without a remote one.

## Getting started

Download the script:

```
curl https://raw.githubusercontent.com/grizio/git-cleanup/master/git-cleanup > git-cleanup
```

Use it:

```
./git-cleanup
```

## Other tricks

### Add this script globally

```
curl https://raw.githubusercontent.com/grizio/git-cleanup/master/git-cleanup > /usr/local/bin/git-cleanup
```

### Use it as a git command

Once the script is in `/usr/local/bin` or anywhere in your `${PATH}`, you can use it as a git command:

```
git cleanup
``` 

## Comes with some security

Instead of forcing the deletion of all your branches, you can review the branches to delete before executing the cleaning.

## Troubleshooting

Please open an issue on https://github.com/grizio/git-cleanup/issues

## Contributing

Pull requests are gladly accepted

## Documentation

Please open an issue or a pull request to improve documentation.
If you have some trick to share, do not hesitate to open a pull request updating this README.
