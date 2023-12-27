#### 文字

可以直接粘贴到游戏

```
a:
    INBOX   
    JUMPZ    d
    COPYTO   1
b:
    COPYTO   0
    BUMPDN   1
    JUMPZ    c
    ADD      0
    JUMP     b
c:
    COPYFROM 0
d:
    OUTBOX  
    JUMP     a
```

#### 截图

![](1.png)