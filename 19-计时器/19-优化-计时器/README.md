#### 文字

可以直接粘贴到游戏

```
a:
    INBOX   
    COPYTO   0
b:
c:
    OUTBOX  
    COPYFROM 0
    JUMPZ    a
    JUMPN    d
    BUMPDN   0
    JUMP     b
d:
    BUMPUP   0
    JUMP     c
```

#### 截图

![](1.png)