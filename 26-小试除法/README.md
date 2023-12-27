#### 文字

可以直接粘贴到游戏

```
a:
    COPYFROM 9
    COPYTO   7
    INBOX   
    COPYTO   0
    INBOX   
    COPYTO   1
b:
    COPYFROM 0
    SUB      1
    JUMPN    c
    COPYTO   0
    BUMPUP   7
    JUMP     b
c:
    COPYFROM 7
    OUTBOX  
    JUMP     a
```

#### 截图

![](1.png)