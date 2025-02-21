---
hide:
  - toc
---

# 移除注册中心

1. 在`接入注册中心列表`页选择需要移除的注册中心，在右侧点击 **`⋯`** 并选择`移除`。

    ![进入移除页面](https://docs.daocloud.io/daocloud-docs-images/docs/skoala/registry/integrated/imgs/delete-1.png)

2. 输入注册中心的名称，点击`移除`。

    ![进入移除页面](https://docs.daocloud.io/daocloud-docs-images/docs/skoala/registry/integrated/imgs/delete-2.png)

!!! note

    接入型的注册中心仅支持`移除`操作，而托管型的注册中心仅支持`删除`操作。二者的区别在于：

    - 移除：只是将注册中心从 DCE 5.0 的微服务引擎中移除，不会删除原有的注册中心和数据，后续还可以再次接入该注册中心。
    - 删除：删除注册中心及其中的所有数据，后续无法再次使用该注册中心，需要重新创建新的注册中心。
