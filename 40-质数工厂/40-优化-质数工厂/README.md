#### 文字

可以直接粘贴到游戏

```
    COPYFROM 24
a:
    COPYTO   5
    COPYTO   2
    BUMPUP   5
    INBOX   
    COPYTO   0
    COMMENT  0
b:
    BUMPUP   5
c:
    COPYFROM 24
    COPYTO   1
    COPYTO   2
    BUMPDN   0
    COMMENT  3
    JUMPZ    a
    BUMPUP   0
d:
    SUB      5
    COMMENT  1
    JUMPN    b
    COPYTO   2
    BUMPUP   1
    COPYFROM 2
    JUMPZ    e
    JUMP     d
e:
    COMMENT  2
    COPYFROM 5
    OUTBOX  
    COPYFROM 1
    COPYTO   0
    JUMP     c
```

#### 截图

![](1.png)