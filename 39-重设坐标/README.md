#### 文字

可以直接粘贴到游戏

```
    JUMP     b
    COMMENT  2
a:
    ADD      15
    OUTBOX  
    COPYFROM 1
    OUTBOX  
    COMMENT  1
b:
    COPYFROM 14
    COPYTO   1
    INBOX   
    COMMENT  0
c:
    SUB      15
    JUMPN    a
    COPYTO   0
    BUMPUP   1
    COPYFROM 0
    JUMP     c
```

#### 截图

![](1.png)