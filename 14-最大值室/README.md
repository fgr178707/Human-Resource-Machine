#### 文字

可以直接粘贴到游戏

```
a:
    INBOX
    COPYTO   0
    INBOX
    SUB      0
    JUMPN    b
    ADD      0
    JUMP     c
b:
    COPYFROM 0
c:
    OUTBOX
    JUMP     a
```

#### 截图

![](1.png)