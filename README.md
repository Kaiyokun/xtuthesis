# xtuthesis
LaTeX Thesis Template for Xiangtan University (thuthesis-based development)

此宏包旨在建立一个简单易用的湘潭大学学位论文 LaTeX 模板，该模板基于薛瑞尼教授开发的清华大学学位论文 LaTeX 模板做了一定的修改，在此对薛瑞尼教授表示真诚的感谢。

# 下载
* 开发版：[GitHub](https://github.com/yuanhaizhuan/xtuthesis)

# 更新
从 [GitHub](https://github.com/yuanhaizhuan/xtuthesis) 下载放入论文目录，执行命令（Windows 用户在文件夹空白处按`Shift+鼠标右键`，点击“在此处打开命令行窗口”）：

    xetex xtuthesis.ins

即可得到 `xtuthesis.cls` 等模板文件。

# Makefile的用法

```shell
make [{all|thesis|spine|doc|clean|cleanall|distclean}]
```

## 目标
* `make thesis`    生成论文 main.pdf；
* `make spine`     生成书脊 spine.pdf；
* `make doc`       生成模板使用说明书 xtuthesis.pdf；
* `make all`       生成论文和书籍，相当于 `make thesis && make spine`；
* `make clean`     删除示例文件的中间文件（不含 main.pdf）；
* `make cleanall`  删除示例文件的中间文件和 main.pdf；
* `make distclean` 删除示例文件和模板的所有中间文件和 PDF。


## Manual
Download the package from [GitHub](https://gixtub.com/xueruini/xtuthesis) to the root directory of your thesis, then execute the command (Windows users `Shift + right click` white area in the file window and click "Open command line window here from the popup menu"):

    xetex xtuthesis.ins

You'll get `xtuthesis.cls` along with other template files.


# Makefile Usage

```shell
make [{all|thesis|spine|doc|clean|cleanall|distclean}]
```

## Targets
* `make thesis`    generate thesis main.pdf;
* `make spine`     generate book spine for printing spine.pdf;
* `make doc`       generate template documentation xtuthesis.pdf;
* `make all`       generate thesis and spine, same as `make thesis && make spine`;
* `make clean`     delete all examples' files (excluding main.pdf);
* `make cleanall`  delete all examples' files and main.pdf;
* `make distclean` delete all examples' and templates' files and PDFs.
