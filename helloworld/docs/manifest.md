# mainifast.json 字段释义

| 字段名 | 说明 |
|-|-|  
| manifest_version | 清单文件的版本,这个必须写,我们这里写 3 |
| name | 插件的名称 |
| version | 插件的版本 |
| description | 插件描述 |  
| icons | 图标 |
| background | 配置插件在后台运行的js代码 |
| content_scripts | 定义一系列匹配规则,当URL被匹配时,自动执行js |
| permissions | 插件运行需要的权限 |
| action | 浏览器右上角图标设置 |
| options_page | 右键插件图标的 -> 选项页面,允许用户进行个性化设置 |
| omnibox | 向地址栏注册一个关键字以提供搜索建议,只能设置一个关键字 |
| web_accessible_resources | 用来指定可从扩展程序中访问的资源,包括 HTML、图片、CSS、JavaScript 等文件 |
| theme | 主题配置 |