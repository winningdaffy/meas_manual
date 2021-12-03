4. 快速开始
===============

4.1 建立新试验项目
-------------------

(a) 点击 :numref:`tool_bar_tab` 中的 **File** 按钮，如 :numref:`tool_file` ：

.. figure:: /images/tool_file.png
    :width: 600px
    :align: center
    :name: tool_file 

    File按钮

(b) 如 :numref:`new_experiment` ，点击 **New** -> **New Experiment** 按钮，选择试验数据文件的保存目录，建议选择空目录，避免出现文件覆盖的问题。完成后在目录中会出现扩展名为 **exp** 的文件，这个文件包括了试验中所需的配置信息，再次试验时只需要重新打开试验文件就可以继续进行试验。

.. figure:: /images/new_experiment.png
    :align: center
    :name: new_experiment 

    新建试验项目

(c) 创建试验后可以在 **Experiment** 窗口看到试验包括的内容。
(d) 如 :numref:`add_device` ，点击 :numref:`tool_bar_tab` 中的 **Experiment** -> **Add Devices** 按钮，打开设备管理窗口。

.. figure:: /images/tool_add_device.png
    :width: 600px
    :align: center
    :name: add_device 

    点击添加设备按钮

(e) 在设备管理窗口中，从设备下拉列表中勾选需要添加的设备，然后点击添加按钮将设备添加到试验，如 :numref:`check_and_add_device` 所示，一次可以选择多个设备

.. figure:: /images/check_and_add_device.png
    :align: center
    :name: check_and_add_device 

    添加设备

(f) 在 :numref:`set_sn_ip` 所示位置修改设备的 **SN** 和 **IP地址** ，然后点击 **OK** 按钮确认

.. figure:: /images/set_sn_ip.png
    :align: center
    :name: set_sn_ip 

    设置SN和IP

(g) 回到主窗口后，软件会自动根据设备配置信息搜索设备，搜索到之后设备指示标志会变为绿色 :numref:`search_device` 。在状态栏中，最左侧的图标表示当前连接设备状态，状态含义参考 :numref:`device_state` 。点击此图标可以手动连接设备。

.. figure:: /images/search_device.png
    :width: 600px
    :align: center
    :name: search_device 

    设备连接状态

(h) 在状态栏中，最左侧的图标 :numref:`img_device_state` 表示当前连接设备状态，状态含义参考 :numref:`device_state` 。点击此图标可以手动连接设备。

.. figure:: /images/device_state.png
    :align: center
    :name: img_device_state 

    设备连接状态

.. table:: 设备连接状态
    :align: center
    :name: device_state 

    =============   ============
    颜色            状态
    =============   ============
    红色            所有设备未连接
    橙色            部分设备已连接
    绿色            所有设备已连接
    =============   ============

4.2 开始试验
-------------------

(a) 在设备连接后，如 :numref:`img_start_measurement` 所示，点击 :numref:`tool_bar_tab` 中的 **Measurement** -> **Run** 按钮，开始试验。

.. figure:: /images/start_measurement.png
    :align: center
    :name: img_start_measurement

    开始试验

4.3 查看数据及修改参数
--------------------------

(a) 在设备连接后，如 :numref:`img_select_data` 所示，点击 :numref:`tool_bar_tab` 中的 **Measurement** -> **Select Data** 按钮，打开数据选择窗口。

.. figure:: /images/tool_select_data.png
    :align: center
    :name: img_select_data 

    选择数据

(b) 在打开的数据选择窗口 :numref:`img_data_selector` 选择数据

    - 点击数据名称可以切换选择状态，加粗为选择状态
    - 按 **Shift** 可以进行多选
    - 使用右键菜单选择 **Add to New** 将数据添加到选中控件中
    - 使用右键菜单选择 **Add to Exist** 将数据添加到现有控件中
    - 也可以使用工具条按钮数据、过滤数据
    - 数据选择窗口可以进行多次选择

.. figure:: /images/frm_data_selector.png
    :align: center
    :name: img_data_selector 

    数据选择窗口

(c) 在数据选择完成后，可以关闭数据选择窗口，对选中数据进行监视、修改等操作。如 :numref:`img_table_control` 所示

.. figure:: /images/table_control.png
    :align: center
    :name: img_table_control

    数据选择完成

