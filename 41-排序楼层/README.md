#### 文字

可以直接粘贴到游戏

```
a:
b:
    BUMPUP   24
    INBOX   
    JUMPZ    d
    COPYTO   [24]
    JUMP     a
c:
    COPYFROM [19]
    OUTBOX  
    COPYFROM [24]
    COPYTO   [19]
d:
    BUMPDN   24
    JUMPZ    b
    COPYTO   23
e:
    COPYFROM 23
    COPYTO   19
f:
    BUMPDN   23
    JUMPZ    c
    COPYFROM [23]
    SUB      [19]
    JUMPN    e
    JUMP     f
```

#### 截图

![](1.png)