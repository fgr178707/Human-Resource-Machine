#### 文字

可以直接粘贴到游戏

```
    COMMENT  0
    COPYFROM 9
    COPYTO   8
    BUMPUP   8
    ADD      8
    COPYTO   7
    ADD      7
    COPYTO   6
    ADD      6
    COPYTO   5
a:
b:
    COMMENT  1
    INBOX   
    JUMPZ    q
    COPYTO   0
    INBOX   
    JUMPZ    p
    COPYTO   4
    SUB      5
    JUMPN    c
    JUMPZ    h
    COPYFROM 9
    JUMP     g
c:
    COPYFROM 4
    SUB      6
    JUMPZ    l
    JUMPN    e
    SUB      7
    JUMPZ    j
    JUMPN    d
    SUB      8
    JUMP     i
d:
    COPYFROM 9
    JUMP     k
e:
    COPYFROM 4
    SUB      7
    JUMPZ    n
    JUMPN    f
    SUB      8
    JUMP     m
f:
    COPYFROM 9
    JUMP     o
    COMMENT  2
g:
    ADD      0
h:
    ADD      0
i:
    ADD      0
j:
    ADD      0
k:
    ADD      0
l:
    ADD      0
m:
    ADD      0
n:
    ADD      0
o:
    ADD      0
p:
    OUTBOX  
    JUMP     a
q:
    OUTBOX  
    INBOX   
    JUMP     b
```

#### 截图

![](1.png)