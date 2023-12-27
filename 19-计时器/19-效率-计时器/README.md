#### 文字

可以直接粘贴到游戏

```

    JUMP     d
a:
b:
c:
    OUTBOX  
d:
    INBOX   
    COPYTO   0
    JUMPN    f
    JUMPZ    a
e:
    OUTBOX  
    BUMPDN   0
    JUMPZ    b
    JUMP     e
f:
g:
    OUTBOX  
    BUMPUP   0
    JUMPZ    c
    JUMP     g
```

#### 截图

![](1.png)