# vpn flint

An open source script for launching your own easy to manage VPN service powered by [Tinc](https://www.tinc-vpn.org/) by spinning up a micro instance of AWS, securing and maintaining it for you.

## Setting up your AWS account

Once you've registered for the free-tier AWS services you'll need to create a user with API access with `AdministratorAccess` in order to spin up a VPN automatically.

Once you have these credentials:

```
export AWS_ACCESS_KEY_ID=foo
export AWS_SECRET_ACCESS_KEY=bar
```

You can stick this in your `.bashrc` or `.zshrc` so that you don't have to do this everytime you use this script.
