# Chapt.4 字典: 当索引行不通时

- 序列: 顺序排列, 通过索引访问的一组值的集合
- 映射 Mapping: 不顺序排列, 通过键访问的一组值的集合. 映射中的每个值与一个独特的键对应.
- 字典 Dictionary, 即`dict`类是Python中唯一的内置映射类型
    - 又称散列表
- 键: 用于访问值的值
    - 键可以是任何不可变类型的值, 包括数值, 字符串, 元组等
    - 同一个映射中的键必须是互异的, 且键与值一一对应
    - 若同一个字典定义中有多个相等的键, 后出现的定义将覆盖先出现的定义
