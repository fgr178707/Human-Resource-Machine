#### 文字

可以直接粘贴到游戏

```
a:
b:
    COPYFROM 23
    COPYTO   22
c:
    INBOX   
    COPYTO   [22]
    JUMPZ    d
    BUMPUP   22
    JUMP     c
d:
    COMMENT  0
    COPYFROM 23
    COPYTO   22
e:
    COPYFROM [22]
    JUMPZ    j
    INBOX   
    COPYTO   21
    JUMPZ    a
    SUB      [22]
    JUMPZ    f
    JUMPN    l
    JUMP     g
f:
    COPYFROM 21
    OUTBOX  
    BUMPUP   22
    JUMP     e
g:
    COMMENT  1
h:
    COPYFROM [22]
    JUMPZ    i
    OUTBOX  
    BUMPUP   22
    JUMP     h
i:
j:
k:
    INBOX   
    JUMP     k
    COMMENT  3
l:
    COMMENT  2
    COPYFROM 21
    OUTBOX  
m:
    INBOX   
    JUMPZ    b
    OUTBOX  
    JUMP     m
```

#### 截图

![](1.png)