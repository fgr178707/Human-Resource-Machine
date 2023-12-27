#### 文字

可以直接粘贴到游戏

```
    COMMENT  3
    COPYFROM 24
    COPYTO   0
    BUMPUP   0
    BUMPUP   0
    COPYTO   1
    BUMPUP   1
    ADD      0
    COPYTO   2
    ADD      0
    COPYTO   3
    ADD      0
    ADD      0
    COPYTO   4
    ADD      0
    COPYTO   5
    ADD      0
    ADD      0
    COPYTO   6
    ADD      0
    COPYTO   7
a:
    COPYFROM 24
    COPYTO   23
    COPYTO   21
    INBOX   
    COPYTO   22
b:
c:
d:
    SUB      [23]
    JUMPZ    h
    JUMPN    f
    SUB      [23]
    JUMPZ    g
    JUMPN    e
    COPYTO   20
    BUMPUP   21
    BUMPUP   21
    COPYFROM 20
    JUMP     d
e:
f:
    COMMENT  1
    BUMPUP   23
    COPYFROM 24
    COPYTO   21
    COPYFROM 22
    JUMP     c
g:
    COMMENT  2
    BUMPUP   21
h:
    COMMENT  0
    COPYFROM [23]
    OUTBOX  
    COPYFROM 21
    JUMPZ    a
    BUMPUP   21
    COPYTO   22
    COPYFROM 24
    COPYTO   21
    COPYFROM 22
    JUMP     b
```
#### 截图

**太长了没有截图**