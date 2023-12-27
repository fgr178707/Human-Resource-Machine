#### 文字

可以直接粘贴到游戏

```
a:
    INBOX   
    COPYTO   0
    INBOX   
    COPYTO   1
    COPYFROM 0
b:
    SUB      1
    JUMPN    c
    JUMP     b
c:
    ADD      1
    OUTBOX  
    JUMP     a
```

#### 截图

![](1.png)