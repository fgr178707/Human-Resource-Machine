#### 文字

可以直接粘贴到游戏

```
a:
    INBOX   
    COPYTO   0
    INBOX   
    COPYTO   1
    INBOX   
    COPYTO   2
    SUB      1
    JUMPN    c
    COMMENT  0
b:
    COPYFROM 2
    COPYTO   3
    COPYFROM 1
    COPYTO   2
    COPYFROM 3
    COPYTO   1
    COMMENT  3
c:
    COPYFROM 1
    SUB      0
    JUMPN    d
    COMMENT  1
    COPYFROM 1
    COPYTO   3
    COPYFROM 0
    COPYTO   1
    COPYFROM 3
    COPYTO   0
    COMMENT  2
d:
    COPYFROM 1
    SUB      2
    JUMPN    b
    COMMENT  4
    COPYFROM 2
    OUTBOX  
    COPYFROM 1
    OUTBOX  
    COPYFROM 0
    OUTBOX  
    JUMP     a
```

#### 截图

![](1.png)