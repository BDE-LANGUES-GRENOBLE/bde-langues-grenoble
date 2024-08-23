# Landing Page for BDE Langues Grenoble

## Authors

[Benjamin LAZARD](https://www.linkedin.com/in/benjaminlazard/)

## BDE Members

[Emma Petit]()

## Repository structure

This uses [GitHub Pages](https://pages.github.com/)
Refer to [index.html](./index.html)

## Getting Git access

### Clone the repository

`git clone git@github.com:BDE-LANGUES-GRENOBLE/bde-langues-grenoble.git`

### Get Writing rights

- Connect to your user account on github.
- Generate a ssh key with `ssh-keygen -t ed25519 -C "<email-of-the-account>" -f ~/.ssh/bde-langues-grenoble`
- Go to <https://github.com/settings/profile> and paste the public key from your local machine (should be `~/.ssh/bde-langues-grenoble.pub`)

- Append the following to `~/.ssh/config`

```ssh
Host BDE-LANGUES-GRENOBLE
    HostName github.com
    User git
    IdentityFile C:/Users/benja/.ssh/bde-langues-grenoble
    IdentitiesOnly yes
```

- Check success of the ssh connection with `ssh -T git@BDE-LANGUES-GRENOBLE`
- Check success of the git connection with `git fetch`

## Configure github pages

The website is currently available on <https://bde-langues-grenoble.github.io/bde-langues-grenoble/>

- [Documentation on github pages](https://docs.github.com/fr/pages/quickstart)

To alter params, after logging in, [go here](https://github.com/BDE-LANGUES-GRENOBLE/bde-langues-grenoble/settings/pages). You can pick a custom URL.
