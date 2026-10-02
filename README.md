# tehrandom2.github.io

The account-level GitHub Pages site. Its job is to hold the custom domain: with
`dev.advancedstudios.net` set here (the `CNAME` file), every repository on this account
that has Pages turned on is served at `dev.advancedstudios.net/<repo>/` with no
per-project setup.

To publish something new: turn on Pages for its repository and add a link to
`index.html` here. Do not give a project repository its own custom domain unless it
should leave this one.

DNS: one `CNAME` record, `dev` to `tehrandom2.github.io`, not proxied.
