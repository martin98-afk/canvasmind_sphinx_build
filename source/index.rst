CanvasMind |version_str|
#########################

CanvasMind 是一款基于 Python 开发的可视化编程工作流开发工具。在传统数据流画布的基础上，CanvasMind 创新性地融合了 **全局变量系统** 、 **控制流执行机制** 、 **节点智能推荐引擎** ，以及 **大模型驱动的画布智能分析能力** ，实现从数据处理、逻辑编排到 AI 辅助推理的一体化低代码开发体验。

通过高度可定制的节点体系、流畅的交互界面与强大的后端执行支持（如 IPython 内核、远程 SSH 执行），CanvasMind 旨在为算法工程师、数据科学家和 AI 应用开发者提供一个 **高效、直观且可扩展** 的可视化编程环境。

.. image:: _images/项目标志卡片.png
   :alt: CanvasMind 项目标志卡片
   :align: center

----

.. image:: _images/可视化训练效果.png
   :alt: 可视化训练画布
   :align: center

----

**资源链接**
^^^^^^^^^^^

- 源码仓库：https://github.com/martin98-afk/CanvasMind  
- 问题反馈：https://github.com/martin98-afk/CanvasMind/issues  
- 官方文档：https://canvasmind-sphinx-build.readthedocs.io/zh-cn/latest/

🚀 快速开始
^^^^^^^^^^^

环境要求
------------

- Python 3.8+
- PyQt5 或 PySide2

安装依赖
--------------------

.. code-block:: bash

    pip install -r requirements.txt

运行应用
-------------------

.. code-block:: bash

    python main.py

PyInstaller 打包
------------------------

.. code-block:: bash

    python build.py

💡 您也可以直接下载预打包的发行版：`点击此处获取 CanvasMind v0.4.3 完整压缩包 <https://github.com/martin98-afk/CanvasMind/releases/download/v0.4.3/CanvasMind_installer.exe>`_



.. toctree::
    :hidden:
    :caption: 总览
    :name: orverview
    :maxdepth: 2
    :titlesonly:

    index
    整体介绍

.. toctree::
    :hidden:
    :caption: 核心引擎
    :name: engine
    :maxdepth: 2
    :titlesonly:

    execution_engine
    control_flow
    ui_design

.. toctree::
    :hidden:
    :caption: 画布开发
    :name: canvas
    :maxdepth: 2
    :titlesonly:

    canvas/开发基础设定
    canvas/画布基础操作
    canvas/节点拖拽树
    canvas/属性面板
    canvas/画布UI功能
    canvas/画布执行模式
    canvas/画布节点智能推荐
    canvas/组件调试模式
    canvas/画布项目导出

.. toctree::
    :hidden:
    :caption: 特殊节点介绍
    :name: nodes
    :maxdepth: 2

    nodes/分支节点
    nodes/迭代节点
    nodes/循环节点
    nodes/自定义代码节点
    nodes/工具调用节点

.. toctree::
    :hidden:
    :caption: 组件开发
    :name: component
    :maxdepth: 2
    :titlesonly:

    component/组件基础配置
    component/组件树使用
    component/组件调试
    component/组件版本管理
    component/组件开发大模型助手

.. toctree::
    :hidden:
    :caption: 项目管理
    :name: export
    :maxdepth: 2
    :titlesonly:

    export/导出项目测试
    export/导出项目服务上线

.. toctree::
    :hidden:
    :caption: 环境管理
    :name: environment
    :maxdepth: 2
    :titlesonly:

    environment/环境管理介绍

.. toctree::
    :hidden:
    :caption: Examples
    :name: examples
    :maxdepth: 1

    examples/react智能体
    examples/常用机器学习模型
    examples/自动生成组件

.. toctree::
    :hidden:
    :caption: 软件配置
    :name: settings
    :maxdepth: 2
    :titlesonly:

    settings/软件系统配置说明
