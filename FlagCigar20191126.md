Question 1-5:BAM FLAG
1.Explain BAM FLAG value:143
  143=128+8+4+2+1=10001111
第一第二read序列均未与参考序列匹配，与后续完全匹配的条件相悖，此题无法成立。
2.Explain BAM FLAG value:99
  99=64+32+2+1=1100011
第一read序列和参考序列完全匹配，没有错配和插入缺失，第二read序列比对到参考序列的负列上。
3.Explain BAM FLAG value:516
  516=512+4=1000000100
该read序列未通过质量控制且没有比对到参考序列上。
4.Explain BAM FLAG value:2064
  2064=2048+16=100000010000
补充匹配的read且其反向序列能够比对到参考序列。
5.Explain BAM FLAG value:147
  147=128+16+2+1=10010011
第二read序列比对到参考序列的负链上且和参考序列完全匹配，没有错配和插入缺失。
Question 6-10:BAM CIGAR
6.Explain BAM CIGAR:14M2D31M
该read序列起始的14bp片段与参考序列匹配，顺移2bp序列删除，顺移31bp片段与参考序列匹配。
7.Explain BAM CIGAR:3S6M1D5M
软跳过该read序列起始3bp片段，不改变read序列长度，顺移6bp片段与参考序列匹配，顺移1bp序列删除，顺移5bp片段与参考序列匹配。
8.Explain BAM CIGAR:6M14N5M
该转录组read序列起始的6bp片段与参考序列匹配，顺移跳过14bp参考序列，顺移5bp片段与参考序列匹配。
9.Explain BAM CIGAR:7M5D8M2I14M
该read序列起始的7bp片段与参考序列匹配，顺移5bp序列删除，顺移8bp片段与参考序列匹配，顺移插入2bp片段，顺移14bp片段与参考序列匹配。
10.How long is the read with alignment CIGAR of 7M5D8M2I14M?
34bp
