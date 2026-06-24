# ACT Samba Server

First, install samba.

```sh
brew install samba
```

Now, setup the server config.

```sh
./setup-config
```

Finally, run it!

```sh
./start-server
```

You should be able to connect from UTM using.

```sh
\\10.0.2.2\actbackup
```

and the password you set when setting up the server config.
