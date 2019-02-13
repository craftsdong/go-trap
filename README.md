# go-trap
golang trap

## map 
1. map range 是乱序的
2. map 并发读写会触发不可recover的panic。并发读写不一定panic，是不同协程分别进入读-写临界区才会触发
