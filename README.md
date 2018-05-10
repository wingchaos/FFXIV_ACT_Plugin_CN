# FFXIV_ACT_Plugin_CN
汉化FFXIV_ACT_Plugin
原版权归R大所有。https://github.com/ravahn/FFXIV_ACT_Plugin

每次更新后会尽快更新到汉化版本


目前已经解决国服国际服因为客户端名字不一样导致不读取战斗数据的问题。国服国际服同时兼容，只要版本是同一个大版本（貌似这种可能性只有1星期）

将 原版本 法语 修改成了 中文， 如果 使用中文客户端，O5S-O8S副本中的BOSS名字会改成日文方便上传fflogs
 
 
未来打算：
目前有个想法是，ACT版面看到的数据全是中文，输出的log文件根据用户选择英文/或者日文，这样就避免了很多不兼容FFLOGS的问题，
但是遇到瓶颈，因为自学C#没多久，还不会跨命名空间把  FFXIV_ACT_Plugin.Parse.CombatantHistory _settings.LanguageID的值传到FFXIV_ACT_Plugin.Memory
希望有dalao指点下。

