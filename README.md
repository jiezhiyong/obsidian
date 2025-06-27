# 我的第一篇笔记

这是我的第一篇笔记，使用 Obsidian 进行创建。

## 链接其他笔记

你可以使用双向链接来链接其他笔记，比如 [[第二篇笔记]]。

## 使用标签

添加标签便于分类和搜索，比如 #知识管理。

## 列表

- 项目1
- 项目2
  - 子项目2.1
  - 子项目2.2

## 代码块

```python
print("Hello, Obsidian!")
```

```mermaid
sequenceDiagram
    Alice->>Bob: Hello Bob, how are you ?
    Bob->>Alice: Fine, thank you. And you?
    create participant Carl
    Alice->>Carl: Hi Carl!
    create actor D as Donald
    Carl->>D: Hi!
    destroy Carl
    Alice-xCarl: We are too many
    destroy Bob
    Bob->>Alice: I agree
```

```mermaid
--- 
config:
  look: handDrawn
  theme: forest
  layout: elk
---

sequenceDiagram
    autonumber
    participant Alice
    participant John
    participant Bob

    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```