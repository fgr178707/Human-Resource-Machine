#### 文字

可以直接粘贴到游戏

```

    JUMP     b
a:
    COPYFROM 0
    OUTBOX
b:
c:
    INBOX
    COPYTO   0
    INBOX
    SUB      0
    JUMPZ    a
    JUMP     c
```

#### 截图

![](1.png)