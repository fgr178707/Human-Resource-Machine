#### 文字

可以直接粘贴到游戏

```
a:
    INBOX   
    COPYTO   0
    COPYFROM 9
    COPYTO   1
    COPYTO   2
    BUMPUP   2
b:
    OUTBOX  
    COPYFROM 1
    ADD      2
    COPYTO   3
    COPYFROM 0
    SUB      3
    JUMPN    a
    COPYFROM 2
    COPYTO   1
    COPYFROM 3
    COPYTO   2
    JUMP     b
```

#### 截图

![](1.png)