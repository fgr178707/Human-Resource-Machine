#### 文字

可以直接粘贴到游戏

```
a:
    COPYFROM 9
    COPYTO   4
    INBOX   
    COPYTO   1
    INBOX   
    COPYTO   0
b:
    JUMPZ    c
    COPYFROM 4
    ADD      1
    COPYTO   4
    BUMPDN   0
    JUMP     b
c:
    COPYFROM 4
    OUTBOX  
    JUMP     a
```

#### 截图

![](1.png)