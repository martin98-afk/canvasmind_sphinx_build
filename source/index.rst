CanvasMind |version_str|
#########################

CanvasMind a Visual Programming Workflow Development Tool written in python that can be implemented.

.. image:: _images/子连通图执行顺序定义示意图.png

Install
*******

Requirements
------------

- Python 3.8+
- PyQt5 or PySide2

Install Dependencies
--------------------

.. cmd::

    pip install -r requirements.txt

Run the Application
-------------------

.. cmd::

    python main.py

Package with PyInstaller
------------------------

.. cmd::

    pyinstaller --onedir --add-data "app;app" --add-data "icons;icons" --add-data "envs/Miniconda3-py311_23.11.0-2-Windows-x86_64.exe;envs" --add-data
 ".venv/Lib/site-packages/spyder;spyder" --add-data "resource;resource" --add-data "examples;examples" --copy-metadata jupyter_client --hidden-import jupyter_client.provisioning.local --hidden-import ipykernel -i icons/logo3.png main.py

or alternatively you can download the source `here <https://github.com/martin98-afk/CanvasMind/releases/download/v.0.1.7/CanvasMind.zip>`_.


----

| Source: https://github.com/martin98-afk/CanvasMind
| Issues: https://github.com/martin98-afk/CanvasMind/issues

.. toctree::
    :hidden:
    :caption: Hightlights
    :name: apitoc
    :maxdepth: 2
    :titlesonly:

    menu
    introduction
    execution_engine
    ui_design
    control_flow

.. toctree::
    :hidden:
    :caption: Canvas Development
    :name: apitoc
    :maxdepth: 2
    :titlesonly:

    canvas/development_notes

.. toctree::
    :hidden:
    :caption: Widgets
    :name: wdgtstoc
    :maxdepth: 2

    node_widgets
    builtin_widgets/PropertiesBinWidget
    builtin_widgets/NodesPaletteWidget
    builtin_widgets/NodesTreeWidget

.. toctree::
    :hidden:
    :caption: Examples
    :name: exmplstoc
    :maxdepth: 1

    examples/ex_overview
    examples/ex_node
    examples/ex_port
    examples/ex_pipe
    examples/ex_menu
    host_apps/_index_apps