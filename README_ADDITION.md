## build

```sh
NODEJS_ORG_MIRROR=https://npmmirror.com/mirrors/node \
NODE_DIST_MIRROR=https://npmmirror.com/mirrors/node \
NVM_NODEJS_ORG_MIRROR=https://npmmirror.com/mirrors/node \
DSH_DESKTOP_APP_ID=com.local.dsh.desktop \
DSH_DESKTOP_UNSIGNED=1 \
    pnpm --filter @deepseek-ai/dsh-desktop package:dir
```
