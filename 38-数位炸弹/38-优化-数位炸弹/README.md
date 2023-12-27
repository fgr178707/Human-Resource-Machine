#### 文字

可以直接粘贴到游戏

```
    COMMENT  0
a:
    COPYFROM 9
    COPYTO   0
    COPYTO   1
    INBOX   
    COPYTO   2
    COMMENT  1
b:
    COPYFROM 2
    SUB      11
    JUMPN    c
    COPYTO   2
    BUMPUP   0
    JUMP     b
c:
d:
    COPYFROM 2
    SUB      10
    JUMPN    e
    COPYTO   2
    BUMPUP   1
    JUMP     d
    COMMENT  2
e:
    COPYFROM 0
    JUMPZ    f
    OUTBOX  
    JUMP     g
f:
    COPYFROM 1
    JUMPZ    h
g:
    COPYFROM 1
    OUTBOX  
h:
    COPYFROM 2
    OUTBOX  
    JUMP     a
```

#### 截图

![](1.png)