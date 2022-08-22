# zsh-profile
Just a plain simple zsh profile management

# Usage

Create a `.zshprofile` directory in your home directory
```sh
mkdir -p .zshprofile
```

Create your profile in the `.zshprofile` directory
```sh
cd .zshprofile
mkdir jonh
```

Add your source file your newly created profile directory
```sh
cd jonh
touch .zshrc
```

Now edit your `~/.zshrc`, Add the following line:
```sh
eval "$(zsh-profile jonh .zshrc)"
```

All done!

# License
Licensed under [MIT](LICENSE)
