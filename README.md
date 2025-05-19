# 说明
Cursor的文件关联图标很不美观，且没有设置选项，本方法通过研究注册表实现关联替换。
通过修改注册表删除Cursor的文件关联，再增加VS Code的文件关联。
# 使用方法
1. 首先通过DeleteCursorAssoc.reg，删除Cursor的文件关联。
2. 通过AddVSCodeAssoc.reg，增加VSCode的文件关联。
3. 通过cmd命令：`ie4uinit -show`，刷新文件图标缓存。
