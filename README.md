# product-dev-net

Installs helpful tools for network, system, and devops engineers.


It is currently working with Debian systems.

RPM testing will be next, and MacOS will come later.

## Getting Started

To install the packages on a local machine, install [ansible](https://www.ansible.com/), and
run the follwing command.

```bash
sudo ansible-pull -U https://github.com/pwilliams-ck/product-dev-net
```

That's it, very noteworthy mentions are:

- `fzf` - Fuzzy file finding
- `rg` - Ripgrep, faster `grep`, repects hidden files
- `dust` - Fancy `du` for disk usage. Just run `dust`

## Conclusion

This is inspired by my other repo for automating the set up of my developer environmet, you 
can check it out [here](https://github.com/pwilliams-ck/product-dev). There is some other neat
stuff related to `neovim`, `tmux`, and `fzf`, among others.
