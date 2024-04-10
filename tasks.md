Documenting manual tasks first and worry about automation later:
- [ ] Create .ssh key and add to github
- [ ] Get GPG key from bitwarden
- [ ] Install Xcode Command Line Tools
- [x] Install Homebrew
  - [ ] gpg2
  - [ ] asdf
  - [ ] bash
  - [ ] jq
  - [ ] starship
  - [ ] yq
  - [ ] direnv

- FIX GPG FOR MACOS
```
brew upgrade gnupg  # This has a make step which takes a while
brew link --overwrite gnupg
brew install pinentry-mac
echo "pinentry-program $(brew --prefix)/bin/pinentry-mac" >> ~/.gnupg/gpg-agent.conf
killall gpg-agent
```
- Install ASDF packages (latest) && set global to latest version
  - kubectl
  - kubectx
  - terraform
  - terragrunt
  - terrascan
  - tflint
- Install oh-my-zsh
  - Install custom oh-my-zsh config
- Install Brave browser
  - Configure Brave as default browser
- Install Visual Studio Code and sing-in to sync settings
- Install Office Suite
- Install
List of tools that I need and where they come form:
- Brave browser
- Visual Studio Code
  - Sync settings (singin to github, probably manual only)
- Office Suite
- Warp.dev
