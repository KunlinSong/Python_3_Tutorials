# Python 3 学习教程

截至目前，Python仍然是在人工智能和数据科学领域中被广泛使用的语言。虽然有一个新语言叫做Mojo，但是其最终是否能够替代Python的地位仍然需要时间验证。

其实目前已经存在有许多的学习资料可以学习Python，包括各种书籍、博客、视频等等。本教程也并不保证优于已有的各种学习资料，但是如果它可以为你提供一些参考，就是本教程最大的荣幸。

以下列出了一些其他的Python教程，一些方法和特性本教程也许没有覆盖，这些教程可以为你提供一些参考：

- [Python 官方文档](https://docs.python.org/3/)（[以及中文文档](https://docs.python.org/zh-cn/3/)）
- [廖雪峰的Python教程](https://liaoxuefeng.com/books/python/introduction/index.html)
- [菜鸟教程](https://www.runoob.com/python/python-tutorial.html)

本教程主要以学会使用Python为主，不会详细介绍Python的如GIL等概念以及编程规范。有关Python的编程规范，可以参考以下指南：

- [PEP 8](https://peps.python.org/pep-0008/)
- [Black](https://black.readthedocs.io/en/stable/the_black_code_style/current_style.html)
- [Google Python 风格指南](https://zh-google-styleguide.readthedocs.io/en/latest/google-python-styleguide/contents.html)

有关于环境配置，本教程不会涉及。如果你没有配置好Python环境，本教程有一些建议：

- 对于MacOS和Linux用户，可以使用[Miniforge](https://github.com/conda-forge/miniforge)或者[MiniConda](https://docs.anaconda.com/miniconda/)管理环境。
- 对于Windows用户，可以使用[WSL](https://learn.microsoft.com/en-us/windows/wsl/setup/environment)在Windows系统中进入Linux环境，再使用[Miniforge](https://github.com/conda-forge/miniforge)或者[MiniConda](https://docs.anaconda.com/miniconda/)管理环境。（对于已经熟悉Linux系统、愿意学习Linux系统、以及未来学习工作中会用到Linux系统的用户（尤其是需要接触生物信息学的用户），推荐这一个方案）
- 对于其他Windows用户，可以使用[Anaconda](https://docs.anaconda.com/anaconda/install/windows/)管理环境。它对依赖GUI的大多数Windows用户来说十分友好，并且自带一个IDE（Spyder）。

本教程假设你已经配置好了Python环境，并且可以使用jupyter notebook（或者支持.ipynb格式的IDE或编辑器，如VSCode、PyCharm等）来运行代码。

本教程完全使用jupyter notebook实现。它是一个很方便的工具，允许你以十分简单的方式运行代码。在学习过程中，请随意尝试你的任何想法，不要害怕代码语法错误和程序运行报错，这些都是正常的，也是所有编写程序的人们经常经历的情况。

学习任何东西都不会是一蹴而就的。知识并不会因为收藏视频和博客，或者购买教程和书籍就会主动进到脑子里。学习Python也是如此。当然它也没有太难，只要付出一定的努力和时间，我想大多数人都可以从零编程基础开始学会Python这门语言。

由于编写者思维跳脱，本教程每个标题下包含的内容不局限于该标题，有时候（大部分时候）会由一些内容跳跃到其他比较相关的内容上。所以这个教程并不适合系统化学习Python，上面给出的几个教程应该能满足你系统化学习的需求。对于喜欢通过探索逐步掌握知识的用户，本教程应该适合你。但不论是哪一种用户，都请你积极地尝试运行代码，以及修改教程中的示例代码尝试你的想法，这会对你的学习有很大帮助。

另外本教程也推荐以下社区，你在学习过程中遇到的问题，很多时候其他人也遇到过。如果一些问题难住了你，不妨在社区中寻找答案。

中文社区：

- [稀土掘金](https://juejin.cn/)
- [CSDN](https://www.csdn.net/)

国际社区：

- [stack overflow](https://stackoverflow.com/)

希望你能通过本教程，增加一点对Python的了解，为你的学习工作带来一些帮助。如果你有任何对本教程的建议，都欢迎你在issue中提出。
