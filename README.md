# brainfix-projects

Small projects in brainfix

## Compiling

I've not yet set up a build script, but what I do the following for compiling.

On my desktop, there's a dir called brainfix.

```sh
brainfix
├── brainfix
└── projects
```

The brainfix folder nested in there is a clone of the jorenheit/brainfix github repo. The other folder is this repo.

I can now run the following command for compiling something. In this example, I'm compiling the rps file in this example.

```bash
$ mkdir dist/ # skip if you've already got a dist folder
$ clear && bfx --random -o dist/rps.bf -I ~/Desktop/brainfix/brainfix/std/ rps.bfx && bfint --random dist/rps.bf`
```

## Projects

So far, I've done the following projects.

- rock, paper, scissors (rps.bfx)
