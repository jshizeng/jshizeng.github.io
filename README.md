py5 字典示例

文件:
- `py5_dictionary_example.py`：一个使用字典管理形状（objects）的 py5 示例。

运行说明（Windows PowerShell）:

确保安装了 `py5`：
```powershell
python -m pip install py5
```

运行示例：
```powershell
python "py5_dictionary_example.py"
```

键位说明：
- 鼠标点击：在鼠标位置添加一个新形状（示例使用字典插入）。
- `c`：清空所有形状（同时清空字典）。
- `d`：删除最后一个形状（并从字典中删除该 id）。
- `r`：随机化所有形状颜色（演示通过字典迭代并更新字段）。

说明：
- 本示例同时演示了字典的创建、插入、查找、更新、删除以及字典与列表配合使用的常见模式。