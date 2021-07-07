# sklearn toolbox

`scikit-learn`是一个适用于python语言环境的机器学习算法的开源库，从它的[官方网站](https://scikit-learn.org/stable)可以获得其安装途径、简单教程、和用户手册。\
`scikit-learn` is an open source library of machine learning algorithms for the python environment. The [official website of scikit-learn](https://scikit-learn.org/stable) provides its installation method, simple tutorial, and user guide.

写这份工具箱的初衷是为像我一样的非纯计算机领域的学习者和研究者提供一个可以便捷查询和使用所需机器学习算法的工具。工具箱没有试图面面俱到地囊括scikit-learn的所有内容，但覆盖了根据我的学习和理解认为相较常用的部分。另外，未曾详细记录的工具标注了参考链接。我真切地希望这个工具箱可以帮助有需要的研究者和学习者节省时间和精力，从而利用好机器学习这一如今最有效的工具之一、点燃更多智慧的火花。\
The purpose of this toolbox is to provide a convenient  method for researchers and learners like me, who do not focuses on pure computers science, to look up and utilize the machine learning algorithms they need. The toolbox does not attempt to embrace everything of scikit-learn, but only covers what I personally think is commonly needed. In addition, tools that are not recorded in detail are noted with reference links for deeper knowing. I truly hope the toolbox will help researchers and learners who need it to save time and effort, so that they can take advantage of machine learning, one of the most effective tools available today, and ignite their sparks of wisdom.

本工具箱是一个jupyter notebook，以下是几点使用说明。\
This tookbox is a jupyter notebook, and the following is a few notes on how to use it.

0. 这个notebook的最开始添加了目录，但仍然推荐安装[jupyter_contrib_nbextensions](https://github.com/ipython-contrib/jupyter_contrib_nbextensions)并开启Table of Contents以便于互动式导航。\
A table of contents is added at the beginning of this notebook, but it is still recommended to install [jupyter_contrib_nbextensions](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) and enable Table of Contents for interactive navigation.

1. 这个notebook仅用于查询和简单的使用。如果你想了解更多关于机器学习模型和算法的知识，请购买书籍或参加课程。我个人推荐周志华老师的《机器学习》。\
This notebook is for __query and simple use__ only. If you want to know more about machine learning models and algorithms, do buy a book or take a course. Personally I would recommend "Machine Learning" by Professor Zhihua Zhou.

2. 这个notebook所用的`scikit-learn`的版本是0.23.2，其中通过注释提到了0.24版本的一些变化，但没有写在运行代码中。\
The version of `scikit-learn` used in this notebook was 0.23.2. Some changes in version 0.24 are mentioned by comments, but not used in the running code.

3. 强烈建议在不确定或需要更深入使用时查看[user guide](https://scikit-learn.org/stable/user_guide.html#user-guide)，以确保正确使用和良好性能。\
Checking the official [user guide](https://scikit-learn.org/stable/user_guide.html#user-guide) is always highly recommended to ensure proper usage and good performance. 

4. 第1-3节需要先运行第0节以获得测试数据；第4节需要先运行第4节最开头的box以获得测试数据。\
Sections 1-3 requires running section 0 first to get the test data; section 4 requires running the box at the beginning of section 4 first to get the test data.

5. 对于有标签的数据，可以通过ctrl+find "clf"搜索分类器；同样，ctrl+find "reg "可以搜索回归器。\
With labelled data, search for classifiers by ctrl+find "clf"; similarly, search for regressor by ctrl+find "reg".

6. 对于未标注的数据，可以通过ctrl+find "density estimation"、"clustering "或 "dimensionality reduction"来搜索相应的算法。\
With unlabelled data, ctrl+find "density estimation", "clustering", or "dimensionality reduction" to search for corresponding algorithms.

7. 形如“parameters=xxx”的注释通常意味着xxx为算法的默认值，偶尔是便于理解的其他值；使用时请根据实际情况调整。\
Comments like "parameters=xxx" usually mean that xxx is the default value of the parameter. Occasionally it is some other value that is easier to use. __Please adjust them in the practice__ .

8. 形如“其他参数就像somefunction的参数一样”意味着我没有重复记录这些参数，请查看对应算法的注释。\
Comments like "other parameters are like somefunction's" mean that I would not repeat those parameters. So please check the corresponding algorithms.

9. 其他事项有待补充\
More to add
