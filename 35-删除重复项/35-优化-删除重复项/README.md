#### 文字

可以直接粘贴到游戏

```
    COMMENT  0
    COPYFROM 14
    JUMP     b
    COMMENT  2
a:
    COPYFROM 11
    COPYTO   [14]
    OUTBOX  
    BUMPUP   14
    SUB      14
    COMMENT  3
b:
    COPYTO   [14]
c:
    COPYTO   14
    COMMENT  1
    INBOX   
    COPYTO   11
d:
    COPYFROM [14]
    JUMPZ    a
    SUB      11
    JUMPZ    c
    BUMPUP   14
    JUMP     d
```

#### 截图

![](1.png)