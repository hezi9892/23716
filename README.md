i = 1
while i <= 9:
  j = 1
  while j <= i:
    print("%d*%d=%d" % (j,i,i*j),end=' ') # 格式化输出
    j += 1
  i += 1
  print()
