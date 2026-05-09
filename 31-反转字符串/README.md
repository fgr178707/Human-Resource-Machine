#### 文字

可以直接粘贴到游戏

```
    JUMP     d
a:
b:
    BUMPDN   14
    JUMPZ    c
    COPYFROM [14]
    OUTBOX  
    JUMP     b
c:
d:
e:
    BUMPUP   14
    INBOX   
    JUMPZ    a
    COPYTO   [14]
    JUMP     e

```

#### 截图

![](1.png)
