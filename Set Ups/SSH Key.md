Check if you’ve got one:
`ssh -T git@github.com`

Permission Denied:
`ls ~/.ssh`

Create one
`ssh-keygen -t ed25519 -C "star.phillips03@gmail.com"`

Display key to be pasted
`cat ~/.ssh/id_ed25519.pub`

In GitHub:
Paste full line - including email

Test again
`ssh -T git@github.com`
