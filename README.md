\# product-dev-net

Installs helpful tools for network, system, and devops engineers.

It is currently working with Debian systems.

RPM testing next, MacOS will come later.

## Getting Started

To install everything on a local machine, you need to install [ansible](https://www.ansible.com/) first.

### Debian/Ubuntu

```bash
sudo apt install ansible
```
### RPM

```bash
sudo yum install ansible
```
### Darwin

```bash
brew install ansible
```
---

Now that Ansible is installed, run the follwing command.

```bash
sudo ansible-pull -U https://github.com/pwilliams-ck/product-dev-net
```

That's it, noteworthy mentions to try out are:

- `fzf` - Fuzzy file finding
- `rg` - Ripgrep, faster `grep`, respects hidden files
- `dust` - Fancy `du` for disk usage

## Conclusion

This is inspired by my other repo for automating the set up of my developer environment, you 
can check it out [here](https://github.com/pwilliams-ck/product-dev). There is some other neat
stuff related to `neovim`, `tmux`, and `fzf`, among others.
