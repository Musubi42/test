# How to push to Github

## Generate SSH Key 

Follow [Github instructions](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

```bash
ssh-keygen -f ~/.ssh/github_key -t ed25519 -C "melanie" 
```

## Add SSH Key to Github

```bash
cat ~/.ssh/id_ed25519.pub
```

Follow Github instructions to add the SSH key to Github.
[Github SSH Key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

## Test if SSH Key is working

```bash
ssh -T git@github.com
```

# How to push to github

## Add file


## Commit file

## Push to github