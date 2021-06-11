# Demo on how to deploy

```
% cd testdrive-rush

% rush deploy -p web3                        # this produce a deploy folder at testdrive-rush/common/deploy

% cp -a ./common/deploy/ ~/Desktop/deploy/   # must copy with "-a" to preserver hard link 

% cd ~/Desktop/deploy/

% pnpm i -r                                  # We run install here so that we have devDendencies.

% cd apps/web3

% pnpm build 

% cd build/

% http-server 
```



