====================
Execution Engine
====================

⚡ Non-blocking asynchronous execution engine.

- Uses ``QThreadPool`` to avoid UI freezing
- Topological sorting ensures correct dependency order
- Real-time status feedback:
  - Idle: Gray border
  - Running: Blue border
  - Success: Green border
  - Failed: Red border

.. image:: _images/模型运行效果.gif
   :width: 800px
   :align: center
   :alt: Execution Status