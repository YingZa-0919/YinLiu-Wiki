# 🔰 身份系统

### 什么是身份系统？

身份系统为服务器内特有的一种身份表达，分为

* NPLAY - 游客玩家
* PLAYER - 正式玩家
  * RANK1 - 等级①
  * RANK2 - 等级②
  * RANK3 - 等级③
  * RANK4 - 等级④
  * ...

**`PLAYER`** 身份会继承 **`NPLAY`** 身份的所有权限 **`RANK1`** 身份会继承 **`PLAYER`** 身份的所有权限 以此类推...

***

### 升级身份有什么用？

身份等级越高，您所拥有的权限，资源越多，以下为不同身份所拥有的不同权限

*

    ![nplayer.png](https://sjwx.easydoc.xyz/95040344/files/lfnpa8st.png)

    * 资源地图解锁
    * 瘾流宝店>小金库解锁
    * 身份称号 ![nplayer.png](https://sjwx.easydoc.xyz/95040344/files/lfnpa8st.png)
    * /suicide 自杀
    * /back 返回上一地点
    * /spawn 回到主城
    * /money 查看金币
*

    ![player.png](https://sjwx.easydoc.xyz/95040344/files/lfnp9z7d.png)

    * 所有地图传送点解锁
    * 菜单所有按钮解锁
    * 基础指令全解
    * 身份称号 ![player.png](https://sjwx.easydoc.xyz/95040344/files/lfnp9z7d.png)
    * 领地大小：110x256x110
    * 领地价格：0.6元/格
    * 领地数量：1个
    * 家的数量：1个
    * 空中花园数量：1个
    * 环球市场物品上架限制：10个
    * 可设置社区传送点：1个
*

    ![rank1.png](https://sjwx.easydoc.xyz/95040344/files/lfnp9psf.png)

    * 继承 ![player.png](https://sjwx.easydoc.xyz/95040344/files/lfnp9z7d.png) 身份所有权限，并再次基础上拥有额外权限
    * 身份称号 ![rank1.png](https://sjwx.easydoc.xyz/95040344/files/lfnp9psf.png)
    * 领地大小：130x256x130
    * 领地价格：0.5元/格
    * 领地数量：2个
    * 家的数量：2个
    * 环球市场物品上架限制：20个
    * 可设置社区传送点：2个
*

    ![rank2.png](https://sjwx.easydoc.xyz/95040344/files/lfnp9fzu.png)

    * 继承 ![rank1.png](https://sjwx.easydoc.xyz/95040344/files/lfnp9psf.png) 身份所有权限，并再次基础上拥有额外权限
    * 身份称号 ![rank2.png](https://sjwx.easydoc.xyz/95040344/files/lfnp9fzu.png)
    * 领地大小：150x256x150
    * 领地价格：0.4元/格
    * 领地数量：3个
    * 家的数量：3个
    * 环球市场物品上架限制：30个
    * 可设置社区传送点：3个
*

    ![rank3.png](https://sjwx.easydoc.xyz/95040344/files/lfnp96h2.png)

    * 继承 ![rank2.png](https://sjwx.easydoc.xyz/95040344/files/lfnp9fzu.png) 身份所有权限，并再次基础上拥有额外权限
    * 身份称号 ![rank3.png](https://sjwx.easydoc.xyz/95040344/files/lfnp96h2.png)
    * 领地大小：170x256x170
    * 领地价格：0.3元/格
    * 领地数量：4个
    * 家的数量：4个
    * 环球市场物品上架限制：40个
    * 可设置社区传送点：4个
*

    ![rank4.png](https://sjwx.easydoc.xyz/95040344/files/lfnp8wjh.png)

    * 继承 ![rank3.png](https://sjwx.easydoc.xyz/95040344/files/lfnp96h2.png) 身份所有权限，并再次基础上拥有额外权限
    * 身份称号 ![rank4.png](https://sjwx.easydoc.xyz/95040344/files/lfnp8wjh.png)
    * 领地大小：190x256x190
    * 领地价格：0.25元/格
    * 领地数量：5个
    * 家的数量：5个
    * 环球市场物品上架限制：50个
    * 可设置社区传送点：5个
    * 可使用 `/hat` 指令
*

    ![rank5.png](https://sjwx.easydoc.xyz/95040344/files/lfnp7tvv.png)

    * 继承 ![rank4.png](https://sjwx.easydoc.xyz/95040344/files/lfnp8wjh.png) 身份所有权限，并再次基础上拥有额外权限
    * 身份称号 ![rank5.png](https://sjwx.easydoc.xyz/95040344/files/lfnp7tvv.png)
    * 领地大小：170x256x170
    * 领地价格：0.2元/格
    * 领地数量：6个
    * 家的数量：6个
    * 环球市场物品上架限制：60个
    * 可设置社区传送点：6个
*

    ![rank6.png](https://sjwx.easydoc.xyz/95040344/files/lfnozsil.png)

    * 继承 ![rank5.png](https://sjwx.easydoc.xyz/95040344/files/lfnp7tvv.png) 身份所有权限，并再次基础上拥有额外权限
    * 身份称号 ![rank6.png](https://sjwx.easydoc.xyz/95040344/files/lfnozsil.png)
    * 领地大小：250x256x250
    * 领地价格：0.15元/格
    * 领地数量：7个
    * 家的数量：7个
    * 开放空中花园购买权限
    * 环球市场物品上架限制：70个
    * 可设置社区传送点：7个

***

### 如何升级身份？

主城 **身份系统NPC** 处打开升级身份GUI，达到升级条件点击即可自动晋升身份，每次晋升成功后均赠送 **藏书阁之匙-十连x1**

![](https://sjwx.easydoc.xyz/95040344/files/lb6otw6n.png)
