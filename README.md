## go-zset
golang的sorted set实现，其中skiplist的实现基本和redis一致(参考https://github.com/xjdrew/lua-zset)
关于持久化可参考https://github.com/Skycrab/cham/blob/master/lib/zset/zset.go
与redis类似，fork后写文件，不同的是redis是rdb格式，我使用的是json格式，由于选择多，在go-zset没有提供。

## test
go test
