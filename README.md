# opwrt_ext

**Only For** [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)

```shell
cat ./feeds.conf.default > ./feeds.conf
echo "src-git opwrt_ext https://github.com/ubbkn/opwrt_ext;master" >> ./feeds.conf

./scripts/feeds update -a
./scripts/feeds install -a
```
