# Coder2 for localhost

Build and start [Coder2](https://github.com/cdr/code-server) without considering security.
If you want secure version, see [original](https://github.com/cognitom/coder2-dockera).

To build and start Coder, run `bash up`. 

```bash
$ git clone https://github.com/hibi-myzk/coder2-docker.git
$ cd coder2-docker
$ bash up
```

Open http://example.com:8080 on your brwoser.


## Git user and email

Before commiting, you need to tell Git your name and email (if you haven't set them yet):

```bash
$ git config --global user.name "John Doh"
$ git config --global user.email "john.doh@example.com"
```

Then, your `.gitconfig` will be shared with the Coder container.
