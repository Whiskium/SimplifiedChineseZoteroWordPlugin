### Zotero Office Word 插件汉化

功能如标题所示，其实英文也不难看懂，只是为了美观统一

### 中英文对照

|中文|英文|
|---|---|
|添加/编辑引用|Add/Edit Citation|
|添加/编辑参考文献|Add/Edit Bibliography|
|插入笔记|Insert Note|
|文档偏好|Document Preferences|
|刷新|Refresh|
|取消关联引用|Unlink Citations|
|插入一个新的引用或编辑当前位置的引用|Insert a new citation, or edit the citation at the current cursor position|
|插入一个新的参考文献或编辑当前位置的现有参考文献|Insert a new bibliography, or edit the existing bibliography, at the current cursor position|
|在当前位置插入一条新笔记|Insert a new note at the current cursor position|
|更改引用样式|Change the citation style or locale|
|刷新所有引用|Update all citations to reflect changes|
|移除所有 Zotero 代码并取消与 Zotero 文库的关联|Remove all Zotero field codes and unlink from Zotero library|

### 使用方法

#### 已安装插件
1. 打开 `%APPDATA%\Microsoft\Word\STARTUP`
2. 将 `Zotero.dotm` 扩展名改为 `zip` 并解压
3. 下载 `customUI.xml` 替换解压内容中的 `customUI\customUI.xml`
4. 重新压缩为 `zip` 文件
5. 将 `zip` 改为 `dotm` 替换原 `dotm` 文件

> 如果可以直接替换压缩包中的内容可以直接替换，不必进行解压再压缩的步骤，但因为权限问题不一定可以，解压再压缩方式更稳妥。

#### 未安装插件
1. 找到 Zotero 的安装文件夹
2. 打开其中的 `integration\word-for-windows` 文件夹
3. 重复 <a href="#已安装插件">已安装插件</a> 中的步骤 2 到步骤 5
4. 打开 Zotero，选择 `Edit` - `Settings` - `引用` - `文档编辑软件` - `安装加载项 Microsoft Word`