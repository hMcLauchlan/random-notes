# mutt setup

This is a bundle of shenanigans so better to document it while it's fresh

- Just hard force config so it doesn't try to use sendmail, don't wana spin up a
  server for this -> var/spool shenanigans
- Gmail needs to allow IMAP and "allow less secure applications" in
  accounts.google
- So if you have some aliases added to gmail (configuring forwarding on Mailgun,
  smtp send as well), then you can route your stuff through mutt using the main
  email smtp but using "from whatever" and gmail will respect it... Thanks
  Mr.Google
