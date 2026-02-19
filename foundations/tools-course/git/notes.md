# SSH setup

## Genrating SSH Key
```
ssh-keygen -t ed25519 -C "your_email@example.com"
```
## Adding SSH key to the ssh-agent
- Start the ssh-agent in the background.
```
eval "$(ssh-agent -s)"
```
- Add your SSH private key to the ssh-agent.
```
ssh-add ~/.ssh/id_ed25519
```
- Add SSH public key to GitHub account

# Git branches

## Create branch
```
git branch branch-name
```
## Switching between branches
```
git checkout branch-name
```
