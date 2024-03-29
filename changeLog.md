https://github.com/ceastld/IToolsRelease/releases

# v0.1.18
* 自动保存自定义窗口的位置（使用窗口标识）
* 自定义窗口，自动保存关闭窗口的位置，从而可以在下一次启动时恢复
* 启动位置判断策略，选项：NA，此时可以自定义位置，若没有，则使用上次关闭窗口的位置

# v0.1.17
* 重写时间窗口
* 完善自定义窗口模块（自己重新实现了一个）

# v0.1.15
* 修复版本判断的问题，以及导致生成的子程序无法使用的问题
* 优化版本控制

# v0.1.11
* 修复动作被删除过后，超级菜单报错的问题

# v0.1.10
* 使用图标控件的 DefaultIconBrush 属性
* 获取剪贴板内容时添加一个 try catch
* 修复动作被删除过后，调用右键菜单报错的问题

# v0.1.8
* 更新生成动作对应的子程序版本（之前生成没法用了，需要重新生成，或者点击编辑动作，右键更新子程序版本）
* “CeaCore_执行命令” 子程序增加参数：是否自动处理动作参数（默认值：false）
* 优化剪贴板界面中暂停按钮的提示
* 修复拆分为多行乱序的问题
	* 添加了一个二次排序参数（SubIndex），用于对拆分过后的条目进行排序（这样可以全部设置为一样的时间）

# v0.1.7
* 禁止收藏夹首页被删除
* 修复文件菜单无法打开的问题
* 开发批量分享动作功能，方便一次性发布

