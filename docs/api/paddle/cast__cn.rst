.. _cn_api_paddle.cast_:

cast\_
-------------------------------

.. py:function:: paddle.cast_(x, dtype='int32')
Inplace 版本的 :ref:`cn_api_paddle.cast` API，输出的 Tensor 将与输入张量 x 共享内存并直接替换原有值。

更多关于 inplace 操作的介绍请参考 `3.1.3 原位（Inplace）操作和非原位操作的区别`_ 了解详情。

.. _3.1.3 原位（Inplace）操作和非原位操作的区别: https://www.paddlepaddle.org.cn/documentation/docs/zh/develop/guides/beginner/tensor_cn.html#id3
