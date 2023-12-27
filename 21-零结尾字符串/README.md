#### 文字

可以直接粘贴到游戏

```
a:
    INBOX   
    JUMPZ    d
b:
    COPYTO   0
    INBOX   
    JUMPZ    c
    ADD      0
    JUMP     b
c:
    COPYFROM 0
d:
    OUTBOX  
    JUMP     a
```

#### 截图

![](1.png)