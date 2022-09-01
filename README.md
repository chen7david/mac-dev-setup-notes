# mac-dev-setup-notes

### Applications

- VsCode: <a href="https://code.visualstudio.com/download">download</a>
- Docker: <a href="https://docs.docker.com/desktop/install/mac-install/">download</a>
- Tableplus: <a href="https://tableplus.com/">download</a>
- Handbreak: <a href="https://handbrake.fr/">download</a>
- Keka: <a href="https://www.keka.io/en/">download</a>
- iTube: <a href="https://itube.aimersoft.com/">download</a>
- Node: <a href="https://nodejs.org/en/">download</a>
- Git: <a href="https://git-scm.com/download/mac">download</a>
- Python: <a href="https://www.python.org/downloads/macos/">download</a>

#### Install HomeBrew Package manager

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
##### Change Path
```bash
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/davidchen/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

#### Install python-tk

```bash
brew install python-tk
```

#### Install nodejs

```bash
brew install node
```

#### Install git

```bash
brew install git
```

#### VSCode setup

- facebook material theme
- emmet
- liveserver
- eslint
- prettier
- markdown preview github styling


#### Setting up GitHub

```bash
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```
