# github.com/phaseburn/dotfiles

PhaseBurn's dotfiles, managed with [`chezmoi`](https://github.com/twpayne/chezmoi).

Install them with:
    `sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply --guess-repo-url=false https://github.com/phaseburn/dotfiles.git`

Once they're installed, to set up for pushing changes:
```
chezmoi cd
git remote set-url origin git@github.com:phaseburn/dotfiles.git
```
