#### 文字

可以直接粘贴到游戏

```
a:
b:
c:
d:
e:
f:
    INBOX   
    COPYTO   0
    INBOX   
    COPYTO   1
    SUB      0
    JUMPN    g
    INBOX   
    COPYTO   2
    SUB      0
    JUMPN    j
    COPYFROM 2
    SUB      1
    JUMPN    k
    COPYFROM 0
    OUTBOX  
    COPYFROM 1
    OUTBOX  
    COPYFROM 2
    OUTBOX  
    JUMP     a
g:
    INBOX   
    COPYTO   2
    SUB      0
    JUMPN    h
    COPYFROM 1
    OUTBOX  
    COPYFROM 0
    OUTBOX  
    COPYFROM 2
    OUTBOX  
    JUMP     f
h:
    COPYFROM 2
    SUB      1
    JUMPN    i
    COPYFROM 1
    OUTBOX  
    COPYFROM 2
    OUTBOX  
    COPYFROM 0
    OUTBOX  
    JUMP     e
i:
    COPYFROM 2
    OUTBOX  
    COPYFROM 1
    OUTBOX  
    COPYFROM 0
    OUTBOX  
    JUMP     d
j:
    COPYFROM 2
    OUTBOX  
    COPYFROM 0
    OUTBOX  
    COPYFROM 1
    OUTBOX  
    JUMP     c
k:
    COPYFROM 0
    OUTBOX  
    COPYFROM 2
    OUTBOX  
    COPYFROM 1
    OUTBOX  
    JUMP     b
```

#### 截图

![](1.png)