# 说明
Cursor的文件关联图标很不美观，且没有设置选项，本方法通过研究注册表实现关联替换。
通过修改注册表删除Cursor的文件关联，再增加VS Code的文件关联。
# Summary
The file association icon for Cursor is not aesthetically pleasing, and there are no settings options. This method achieves the association replacement by studying the registry. By modifying the registry to delete the file association for Cursor and then adding the file association for VS Code.
# 使用方法
1. 首先通过`DeleteCursorAssoc.reg`，删除Cursor的文件关联。
2. 通过`AddVSCodeAssoc.reg`，增加VSCode的文件关联。
3. 通过cmd命令：`ie4uinit -show`，刷新文件图标缓存。
# Instruction
1. Delete the file association for Cursor by running `DeleteCursorAssoc.reg`. 
2. Add the file association for VSCode by running `AddVSCodeAssoc.reg`. 
3. Refresh the file icon cache using the cmd command: `ie4uinit -show`.
