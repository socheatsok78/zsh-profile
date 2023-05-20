# zsh-profile
Just a plain simple zsh profile management

## Install

Create a `.zsh_profiles` directory in your home directory

```sh
mkdir -p .zsh_profiles
# Run this to download the cli
git clone https://github.com/socheatsok78/zsh-profile.git ~/.zsh_profiles/lib
```

Edit `.zshrc` and add `~/.zsh_profiles/lib/bin` to `PATH` variable

```
export PATH="~/.zsh_profiles/lib/bin:$PATH"
```

## Usage

Create your profile in the `.zsh_profiles` directory
```sh
cd .zsh_profiles
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
