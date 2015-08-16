这是示例文档
#############################

:modified: 2015-08-16 18:40
:slug: my-super-post
:authors: Yuanbo She, BBC
:tags: 标签1, 标签2
:summary: 这里写摘要。

	环境：Windows8.1, AAAAA, BBBBB

.. contents:: 目录

一级标题
===============
写你想写的

二级标题
-----------
继续写

三级标题
++++++++++
下面的符号要比标题长

示例
=======

插入代码
---------

.. code-block:: ubuntu

    sudo sh -c 'echo "deb http://packages.ros.org/ahendrix-mirror/ubuntu precise main" > /etc/apt/sources.list.d/ros-latest.list'
	wget http://packages.ros.org/ros.key -O - | sudo apt-key add -

那个 **ubuntu** 也可以不写，表示一种风格，我暂时没加针对性的解析器。

插入图片
---------

.. image:: {var_imagepath}/logo.png
    :alt: default

或者是

.. figure:: {var_imagepath}/logo.png
    :alt: default

插入表格
---------

====================  ================================================================
ros-groovy-ros-base   Meta package for ros-base variant of ROS.
ros-groovy-ros-comm   ROS communications-related packages, including
                      core client libraries (roscpp, rospy) and graph
                      introspection tools (rostopic, rosnode, rosservice, rosparam).
ros-groovy-ros-full   Meta package for ros-full variant of ROS.
====================  ================================================================

引用
----------

    PARAMETERS
     * /rosdistro
     * /rosversion

    NODES

    auto-starting new master
    process[master]: started with pid [3734]
    ROS_MASTER_URI=http://ubuntu:11311/

    setting /run_id to 5956b562-f670-11de-8ea2-26eb04d6389b
    process[rosout-1]: started with pid [3747]
    started core service [/rosout]

其他
======
自己摸索吧。