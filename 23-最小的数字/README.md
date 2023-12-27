#### 文字

可以直接粘贴到游戏

```

    JUMP     b
a:
    COPYFROM 0
    OUTBOX  
b:
    INBOX   
    JUMP     d
c:
    ADD      0
d:
    COPYTO   0
e:
    INBOX   
    JUMPZ    a
    SUB      0
    JUMPN    c
    JUMP     e
```

#### 截图

![](1.png)