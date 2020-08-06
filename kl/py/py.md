>思维导图下载：[点我下载](./kl/py/Python源程序.png)
# 1.Python源程序

1. Python源程序只是一个特殊的``文本文件``，可以用`` 任何文本编辑器做``Python开发

2. Python文件扩展名有很多:

* .py：Python文件扩展名通常就是.py

* .py3：Python3脚本

  > （Python3脚本通常以.py而不是.py3结尾，很少使用）

* .pyc：这是编译好的字节码。如果导入一个模块，python将生成一个*.pyc包含字节码的文件，以便再次导入它更容易(也更快)。

  > .pyc二进制文件可以反编译成.py文件，反编译软件叫Easy Python Decompiler。

* .pyd：这基本上是一个Windows DLL文件。

* .pyi：MyPy存根，存根文件（PEP 484）。

* .pyw：用pythonw.exe执行的Windows的Python脚本。

* .pyx：将Cython src转换为C/C++。

* pyz：Python脚本归档（PEP 441）

  > 这是一个包含标准Python脚本头之后的二进制形式的压缩Python脚本（ZIP）的脚本.

* .pywz：用于MS-Windows的Python脚本归档（PEP 441）。

  > 这是一个包含标准Python脚本头之后的二进制形式的压缩Python脚本（ZIP）的脚本.

* .rpy：包含应用程序或框架特定功能的RPython脚本或Python脚本。

* .pyde：处理使用的Python脚本。

* .pyp：Py4D Python插件。

* .pyt：Python声明文件。

* .pyo：这是在优化(-O)时创建的*.pyc文件

> 从Python3.5开始，Python将只使用.pyc而不是.pyo和.pyc。

* .py [cod]：.gitignore中的通配符表示该文件可能是.pyc，.pyo或.pyd。

