# iWallet Pro

> DeFi Portfolio Rebalancing - Pro

# Features

| Feature | Fre | Pro | 
|---------|-----|-----|
| Support multiple wallets. | :white_check_mark: | :white_check_mark: |
| Support multiple networks (BSC, Polygon, Bitkub). | :white_check_mark: | :white_check_mark: |
| Automated rebalancing (50:50) | :white_check_mark: | :white_check_mark: |
| Automated fill gas. | :white_check_mark: | :white_check_mark: |
| PWA (Progressive Web App), can install to Desktop and Mobile. | :white_check_mark: | :white_check_mark: |
| Support Two-Factor Authentication (2FA), Google Authenticator | :white_check_mark: | :white_check_mark: |
| Rebalancing History | :white_check_mark: | :white_check_mark: |
| Transfer History |  | :white_check_mark: |
| Know your Profit & Loss |  | :white_check_mark: |
| Transfer UI |  | :white_check_mark: |
| Line Notification |  | :white_check_mark: |

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
