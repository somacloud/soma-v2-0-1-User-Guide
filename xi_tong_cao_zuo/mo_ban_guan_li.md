## 模板管理

模板是为SoMA平台提供一个或多个文件，其中所包含的相应的结构和工具。

按路径打开【模板】，即可看到平台中的应用模板，服务模板和虚机模板，每种最多显示10个。

点击〖查看更多〗，进入各种模板的详细列表页面。

### 应用模板 {#-0}

应用模板包含了的相应的结构和服务，构成了生成应用的拓扑和相关服务等元素。

#### 产品展示 {#-3}

1.  应用模板页面：按路径打开【模板】→【应用模板】，显示如下：

图2.1.4.1.1-1 应用模板页面

1.  应用模板信息：按路径打开【模板】→【应用模板】→『应用模板名称』，显示如下：

图2.1.4.1.1-2 应用模板信息

1.  应用模板新增：按路径打开【模板】→【应用模板】→〖新增〗，显示如下：

图2.1.4.1.1-3 新增应用模板向导

#### 应用指南 {#-4}

新增应用模板

1.  用平台管理员身份登录系统。
2.  打开路径：【模板】→【查看更多（应用模板）】，进入应用模板列表页面。
3.  点击〖新增〗，打开应用新增向导，新增名称为“UAP63标准产品”的应用，并在配置应用后〖保存〗。应用新增向导分为三个操作步骤：基本信息，应用/软件配置，服务配置。下面依次来进行操作：
    1.  配置应用基本信息：
        1.  填写应用的名称；
        2.  选择应用权限；
        3.  选择相应的应用类型，点击〖选择〗，可以看到模板选择对话框，如图2.1.4.1.2.1-2。点击某个应用类型，可以查看该类型的描述信息。选定类型后，点击〖确定〗。
        4.  〖下一步〗

图2.1.4.1.2.1-1 新增应用模板—基本信息

图2.1.4.1.2.1-2 新增应用模板—选择应用类型

*   1.  配置应用：
        1.  配置应用弹性状态，可以为应用开启自动弹性伸缩特性，并设置中间件节点个数阀值；
        2.  配置应用集群状态；
        3.  配置应用软件类型，依赖于应用模板，也可以进行软件类型删除（需确保应用中有且只有一个软件类型）
        4.  配置软件安装路径
        5.  配置需要安装的软件模块
        6.  〖下一步〗

图2.1.4.1.2.1-3 新增应用模板—配置应用信息

*   1.  配置服务：
        1.  配置服务类型，点击图2.1.4.1.2.1-4中区域1，在弹出的软件类型选择框（图2.1.4.1.2.1-5）中选择相应软件
        2.  配置服务实例
        3.  〖下一步〗

图2.1.4.1.2.1-4 新增应用模板—配置服务

图2.1.4.1.2.1-5 新增应用模板—选择服务类型

图2.1.4.1.2.1-6 新增应用模板—服务类型卡片

图2.1.4.1.2.1-7 新增应用模板—实例列表及实力配置

*   1.  预览：
        1.  预览应用的配置，可以〖上一步〗进行修改；

图2.1.4.1.2.1-8 新增应用模板—预览

*   *   1.  〖完成〗

1.  导入成功后，返回至【应用模板】，可以使用搜索查找刚刚创建的应用模板卡片。

图2.1.4.1.2.1-9 应用模板卡片

*   图例说明（如图所示，按数字顺序介绍）：
    *   1，应用模板使用权限
    *   2，应用模板名称
    *   3，应用模板类型
    *   4，应用模板使用的服务类型和服务实例个数
    *   5，依赖此应用模板，新增一个应用
    *   6，控制应用模板的共享与私有关系

1.  点击图2.1.4.1.2.1-9中的区域1，进入应用模板详细信息页面。

图2.1.4.1.2.1-10模板详细信息

按钮说明：

〖**编辑**〗：下载该应用模板。

〖**编辑标签**〗：编辑该应用模板的标签。

〖**删除**〗：删除该应用模板。

〖**分享**〗：控制该应用模板的共享与私有关系。

〖**新增应用**〗：依赖此应用模板，新增一个应用。

其中，鼠标悬停在某个服务类型卡片上，可以查看该服务类型的简要说明。

编辑应用模板

点击图2.1.4.1.2.1-9〖编辑〗，打开应用模板编辑向导。向导使用可以参照

_新增应用模板_

。

图2.1.4.1.2.2-1模板编辑页面

删除应用模板

1.  点击应用模板详细信息中的〖删除〗。

图2.1.4.1.2.3-1模板删除页面

1.  〖确定〗，即可将该模板删除。

新增应用

参照

_新建应用_

### 服务模板 {#-1}

服务模板包含了的一个服务相应的结构和软件，构成了生成软件的拓扑和相关服务等元素。

服务分为：负载均衡，中间件，数据库，队列，缓存。在下面的讲解中会分别进行介绍。

#### 产品展示 {#-5}

1.  服务模板页面：按路径打开【模板】→【查看更多（服务模板）】，显示如下：

图2.1.4.2.1-1 服务模板

1.  服务模板信息：按路径打开【模板】→【查看更多（服务模板）】→『服务模板名称』，显示如下：

图2.1.4.2.1-2 服务模板信息

1.  服务模板新增：按路径打开【模板】→【查看更多（服务模板）】→〖新增〗，显示如下：

图2.1.4.2.1-3 服务模板新增

#### 应用指南 {#-6}

新增服务模板

1.  用平台管理员身份登录系统。
2.  打开路径【模板】→【查看更多（服务模板）】，进入服务模板列表页面。
3.  〖新增〗名称为“uap63_master”的服务模板，并设置该模板权限：

图2.1.4.2.2.1-1服务模板新增页面

1.  点击〖选择〗，在弹出的服务类型对话框中选择需要的服务类型

图2.1.4.2.2.1-2服务模板新增—选择服务类型

1.  〖保存〗，完成服务模板新建；
2.  导入成功后，返回至【服务模板】，可以使用搜索查找刚刚创建的服务模板卡片。

图2.1.4.2.2.1-3服务模板卡片

*   图例说明（如图所示，按数字顺序介绍）：
    *   1，服务模板权限
    *   2，服务模板名称
    *   3，服务模板的角色和类型
    *   4，依赖此服务模板，根据模板类型，可以新增不同的服务
    *   5，管理服务模板的权限

1.  点击图2.1.4.2.2.1-3中的区域1，进入服务模板详细信息页面。

图2.1.4.2.2.1-4服务模板信息

按钮说明：

〖**编辑**〗：编辑该服务模板。

〖**编辑标签**〗：编辑该服务模板标签。

〖**删除**〗：删除该服务模板。

〖**分享**〗：管理服务模板的权限。

〖**新增中间件/负载均衡/数据库/队列/缓存**〗：依赖此服务模板，根据模板类型，可以新增不同的服务

编辑服务模板

1.  点击图2.1.4.2.2.1-4的〖编辑〗，修改相关参数。

图2.1.4.2.2.2-1服务模板编辑页面

1.  〖保存〗，即可更新服务模板信息。

删除服务模板

1.  点击服务模板详细信息的〖删除〗。

图2.1.4.2.2.3-1服务模板删除页面

1.  〖确定〗，即可将该模板删除。

新增

依赖于不同类型的服务模版，可以进行不同的新增操作，具体参照

_新建服务_

可以进行的新增操作如下：

*   对于负载均衡类型的服务，可以进行新增负载均衡操作
*   对于中间件类型的服务，可以进行新增中间件操作
*   对于数据库类型的服务，可以进行新增数据库操作
*   对于队列类型的服务，可以进行新增队列操作
*   对于缓存类型的服务，可以进行新增缓存操作

### 虚机模板 {#-2}

虚机模板为在云平台上创建虚机的样例，需要完成两个方面的准备工作：

*   在云平台上传相应的镜像及配置。
*   在SoMa平台上完成虚拟数据中心创建，详见[_创建虚拟数据中心_](#-2)。

#### 产品展示 {#-7}

1.  应用模板页面：按路径打开【模板】→【查看更多（虚机模板）】，显示如下：

图2.1.4.3.1-1 虚机模板页面

1.  应用模板信息：按路径打开【模板】→【查看更多（虚机模板）】→『虚机模板名称』，显示如下：

图2.1.4.3.1-2 虚机模板信息

#### 应用指南 {#-8}

新增虚机模板

1.  用平台管理员身份登录系统。
2.  打开路径【模板】→【虚机模板】。
3.  〖新增〗名称为“xsytmpl”的虚机模板，支持创建UAP云平台，Vcenter和阿里云的虚机模板。
    1.  创建UAP云平台虚机模板：

图2.1.4.3.2.1-1虚机模板新增页面—新增UAP云平台虚机模板

*   1.  创建VCenter虚机模板：

图2.1.4.3.2.1-2虚机模板新增页面—新增VCenter平台虚机模板

*   1.  创建阿里云虚机模板：

图2.1.4.3.2.1-3虚机模板新增页面—新增阿里云平台虚机模板

1.  〖保存〗，成功后，返回至【虚机模板】，可以使用搜索查找刚刚创建的虚机模板卡片。

图2.1.4.3.2.1-4 虚机模板卡片

*   图例说明（如图所示，按数字顺序介绍）：
    *   1，虚机模板创建者和权限。
    *   2，虚机模板名称
    *   3，虚机模板配置
    *   4，依赖此应用目录，新增一个虚机
    *   5，管理虚机模板权限

1.  点击虚机模板卡片信息中的模板名称，进入虚机模板详细信息页面。

图2.1.4.3.2.1-5虚机模板信息

按钮说明：

〖**编辑**〗：编辑该虚机模板。

〖**编辑标签**〗：编辑该虚机模板的标签。

〖**删除**〗：删除该虚机模板。

〖**分享**〗：管理该虚机模板分享权限。

〖**新增虚机**〗：依赖此虚机模板，新增一个虚机。

编辑虚机模板

1.  点击图2.1.4.3.2.1-4的〖编辑〗，修改相关参数。

图2.1.4.3.2.2-1 虚机模板编辑页面

1.  〖保存〗，即可更新虚机模板信息。

删除虚机模板

1.  点击虚机详细信息的〖删除〗。

图2.1.4.3.2.3-1 虚机模板删除页面

1.  〖确定〗，即可将该模板删除。

分享模板

1.  点击图2.1.4.3.2.1-4的〖分享〗。

图2.1.4.3.2.4-1 虚机模板共享页面

新增虚机

1.  点击图2.1.4.3.2.1-4的〖新增虚机〗。填写虚机名称：

图2.1.4.3.2.5-1 新增虚机页面

1.  〖确定〗，即可使用该模板创建一台虚机。