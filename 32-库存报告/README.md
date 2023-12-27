#### 文字

可以直接粘贴到游戏

```

    JUMP     b
a:
    COPYFROM 15
    OUTBOX  
b:
    INBOX   
    COPYTO   16
    COPYFROM 14
    COPYTO   15
    COPYTO   17
    JUMP     e
c:
    BUMPUP   15
d:
    BUMPUP   17
e:
    COPYFROM [17]
    JUMPZ    a
    SUB      16
    JUMPZ    c
    JUMP     d
```

#### 截图

![](1.png)