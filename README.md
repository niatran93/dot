# dot

`curl https://raw.githubusercontent.com/niatran93/dot/main/dot-init | sh`

## Notes

- Installing `github-cli`
  - https://github.com/cli/cli/blob/trunk/docs/install_linux.md
  - on Debian, Ubuntu Linux, Raspberry Pi OS (apt)
  
```bash
curl -fsSL https://cli.github.com/packages/githubcli-archive-keyring.gpg | sudo dd of=/usr/share/keyrings/githubcli-archive-keyring.gpg
sudo chmod go+r /usr/share/keyrings/githubcli-archive-keyring.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/githubcli-archive-keyring.gpg] https://cli.github.com/packages stable main" | sudo tee /etc/apt/sources.list.d/github-cli.list > /dev/null
sudo apt update
sudo apt install gh
```

- Github Personal access tokens: https://github.com/settings/tokens
  - repo, workflow, admin:org
