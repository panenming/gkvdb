Go语言开发的基于DRH(Deep-Re-Hash)深度哈希分区算法的高性能Key-Value嵌入式数据库。<br>
DRH(Deep-Re-Hash)深度哈希分区算法讲解：http://johng.cn/brief-to-deep-re-hash-algorithm/<br>
原作者john<john@johng.cn><br>

修复bug<br>
gfile.go中<br>
// sort.Slice(list, func(i, j int) bool { return list[i] < list[j] })

// 修改bug

sort.StringSlice(list).Sort()