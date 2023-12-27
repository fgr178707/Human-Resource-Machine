#### 文字

可以直接粘贴到游戏

```
    JUMP     c
a:
    COMMENT  2
    COPYFROM 7
    OUTBOX  
    COMMENT  0
b:
c:
    INBOX   
    COPYTO   7
    COPYFROM 5
    COPYTO   6
    COMMENT  1
d:
    COPYFROM [6]
    JUMPZ    a
    SUB      7
    JUMPZ    b
    BUMPUP   6
    JUMP     d
```

#### 截图

![](1.png)