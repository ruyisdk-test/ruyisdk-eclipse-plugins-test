# 使用不包含 sysroot 的工具链时，指定其他工具链时仍包含该工具链

## 操作步骤

1.在Ruyi venv窗口选择New Virtual environment添加虚拟环境
2.选择不包含 sysroot 的工具链
3.选择其他工具链

## 预期结果
可以正常调用其他工具链的sysroot

## 测试结果
该过程中仍包含该工具链

![alt text](img/调用其他工具链.png)