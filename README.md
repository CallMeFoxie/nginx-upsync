Sample configure call:

First step:
```
git clone https://github.com/xiaokai-wang/nginx-stream-upsync-module.git

git clone https://github.com/weibocom/nginx-upsync-module.git

git clone https://github.com/CallMeFoxie/nginx-upsync.git
```
Second step:
```
cp nginx-stream-upsync-module/* nginx-upsync/nginx-stream-upsync-module/
cp nginx-upsync-module/* nginx-upsync/nginx-upsync-module/
```
Then:
```
./configure --add-module=addons/nginx-upsync --with-stream
```

Notice:
```
nginx be required nginx-1.9.0++
```
