# iWallet Pro

> DeFi Portfolio Rebalancing - Pro

# How to install iWallet Pro

1. Export token to system environment variable.

```sh
$ export CR_PAT="<YOUR_TOKEN>"
```
**Remarks**  
CR_PAT = Container Registry Personal Access Token

2. Close and reopen the Terminal.

3. Login to GitHub Container Registry

```sh
$ echo $CR_PAT | docker login ghcr.io -u USERNAME --password-stdin
```

4. Pull iWallet image

```sh
$ docker pull ghcr.io/jittagornp/iwallet
```

5. Install follow this link

> https://hub.docker.com/r/jittagornp/iwallet

But change `jittagornp/iwallet` to `ghcr.io/jittagornp/iwallet`
