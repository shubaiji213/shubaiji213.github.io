安装 Shopify Subscriptions 应用并设置订阅套餐后，您的客户可以定期进行计划购买。您可以在 Shopify Subscriptions 应用中管理所有订阅选项和合同，并在您的在线商店中展示这些订阅套餐。Shopify Subscriptions 应用还将为您的商店增添新的订阅政策和电子邮件通知。

## 客户订阅管理

如果您有有效的客户账户，客户可以通过您的在线商店菜单登录并管理他们的订阅。如果您有旧版客户账户，可以分享订阅管理 URL，以便客户有权限管理自己的订阅。

对于拥有客户账户的客户，他们可以点击您自动发送的订阅电子邮件通知中的 **管理您的订阅** 进行管理。

在 Shopify 后台设置中启用订阅管理，以方便客户操作他们的订阅。

### 步骤：

1. 在 Shopify 后台中，转至 **设置** > **客户账户**。
2. 在 **客户账户** 部分，打开 **订阅管理** 切换按钮。

详细了解客户的订阅管理。

## 在您的在线商店展示订阅

设置订阅套餐后，您可以将订阅小组件添加到产品页面，购物车页面及感谢页面上展示订阅信息。

### “Online Store 2.0” 模板

> **备注**：如需将订阅小组件添加到 Online Store 2.0 模板，请确保在模板编辑器的 **应用嵌入** 部分关闭 **订阅小组件** 开关，以确保小组件正确显示。

### 步骤：

**桌面**

1. 在 Shopify 后台中，转至 **在线商店** > **模板**。
2. 在要添加订阅小组件的模板旁边，点击 **自定义**。
3. 选择现有产品模板，或创建新模板以添加订阅小组件。
4. 在 **产品信息** 下，点击 **添加块**，然后选择 **订阅小组件**。
5. 可选：自定义订阅小组件以适应商店模板。
6. 点击 **保存**。

**iPhone**

1. 在 Shopify 应用中，点击 **…** 按钮。
2. 在 **销售渠道** 部分，点击 **在线商店**。
3. 在要添加订阅小组件的模板旁边，点击 **自定义**。
4. 选择现有产品模板，或创建新模板以添加订阅小组件。
5. 在 **产品信息** 下，点击 **添加块**，然后点击 **订阅小组件**。
6. 可选：自定义订阅小组件以适应商店模板。
7. 点击 **保存**。

**Android**

1. 在 Shopify 应用中，点击 **☰** 按钮。
2. 在 **销售渠道** 部分，点击 **在线商店**。
3. 在要添加订阅小组件的模板旁边，点击 **自定义**。
4. 选择现有产品模板，或创建新模板以添加订阅小组件。
5. 在 **产品信息** 下，点击 **添加块**，然后点击 **订阅小组件**。
6. 可选：自定义订阅小组件以适应商店模板。
7. 点击 **✓**。

### 经典模板

> **注意**：Theme Store 中不提供经典模板。经典模板没有 Shopify Online Store 2.0 模板中的功能，并且 Shopify 免费经典模板不会收到除安全性修复以外的更新。

仅以下经典模板支持订阅小组件：
- Debut 15.0 或更高版本
- Brooklyn 17.0 或更高版本

### 步骤：

1. 在 Shopify 后台中，转至 **在线商店** > **模板**。
2. 在要添加订阅小组件的模板旁边，点击 **…** > **编辑代码**。
3. 在 **product-template.liquid** 文件中，将以下代码片段添加到您希望订阅小组件显示的位置：

    liquid
    <div class="subscriptions_app_embed_block"></div>
    

4. 点击 **保存**，然后点击 **退出**。
5. 点击该模板旁边的 **自定义**。
6. 在侧边栏中，点击 **应用嵌入** 图标，然后点击 **订阅小组件** 旁边的切换按钮以开启小组件。
7. 可选：自定义订阅小组件以适应商店模板。
8. 点击 **保存**。

详细了解如何自定义模板和编辑模板代码。

## Shopify Subscriptions 应用设置

您可以在 Shopify Subscription 应用的 **设置** 页面中管理结算尝试设置、客户的订阅管理，并重新安装订阅小组件。

### 结算尝试

如订阅合同中的产品库存不足以创建订单，您可以调整结算尝试次数及款项获取失败时的重试时间间隔，同时选择订阅产品是否跟踪库存。

您还可以选择在所有重试均失败时跳过、暂停或取消订阅，并向客户发送通知。

### 步骤：

**桌面**

1. 在 Shopify 后台中，转至 **订阅** > **设置**。
2. 在 **结算尝试** 分区中，对 **付款方式失败** 和/或 **库存不足** 执行下列更改组合：
   - 调整 **重试尝试次数**。
   - 调整 **付款重试尝试之间的天数**。
   - 选择 **所有重试尝试失败时的操作**。
3. 点击 **保存**。

**iPhone**

1. 在 Shopify 应用中，点击 **…** 按钮。
2. 在 **应用** 部分，点击 **订阅** > **设置**。
3. 在 **结算尝试** 分区中，对 **付款方式失败** 和/或 **库存不足** 执行下列更改组合：
   - 调整 **重试尝试次数**。
   - 调整 **付款重试尝试之间的天数**。
   - 选择 **所有重试尝试失败时的操作**。
4. 点击 **保存**。

**Android**

1. 在 Shopify 应用中，点击 **☰** 按钮。
2. 在 **应用** 部分，点击 **订阅** > **设置**。
3. 在 **结算尝试** 分区中，对 **付款方式失败** 和/或 **库存不足** 执行下列更改组合：
   - 调整 **重试尝试次数**。
   - 调整 **付款重试尝试之间的天数**。
   - 选择 **所有重试尝试失败时的操作**。
4. 点击 **保存**。

### 订阅管理 URL

订阅管理 URL 是供客户访问订阅管理页面的链接。您可以在任何需要添加订阅管理页面入口点的位置加入此链接，包括电子邮件通知和在线商店的菜单。

## Shopify Subscriptions 通知

使用 Shopify Subscriptions，您可以接收、发送及修改订阅电子邮件通知。您可以激活或停用所有您收到与发送给客户的电子邮件通知，默认状态为激活。

### 步骤：

1. 在 Shopify 后台中，转至 **设置** > **通知**。
2. 在 **订阅** 部分的 **客户通知** 下，选择电子邮件通知进行激活，取消选择以停用。系统将自动保存您的选择。
3. 在 **订阅** 部分的 **员工订单通知** 下，选择电子邮件通知进行激活，取消选择以停用。系统将自动保存您的选择。

详细了解通知和编辑通知模板。

## 添加订阅政策

如果您设置了订阅，新的 **购买选项取消政策** 将自动添加至您的商店。该政策链接将出现在购物车页面、结账页面的 **快速结账** 部分（显示为 **取消政策**）以及结账页面页脚（显示为 **订阅政策**）。

如果在 Shopify 后台的设置中留空该政策，则系统将向客户显示默认模板。

客户在结账时必须先同意取消政策条款，才能完成购买。

👉 [野卡 | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)