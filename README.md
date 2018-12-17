# libgooglepinyin

下面是官网关于libgooglepinyin的介绍，可以看到此lib已不再更新并且创建时的目标就不是完成一个强大先进的输入法内核。
而且libpinyin or sunpinyin的功能比libgooglepinyin更强大一些。
https://code.google.com/archive/p/libgooglepinyin/
A fork from google pinyin on android
This is not a long term project, it only began as some kind of prove concept project.
As this project starter (wengxt), I'm not interested in adding any new feature to this library. 
Since it would be only kind of re-inventing wheel against sunpinyin or libpinyin.
This project is only forked from out dated code of Google Pinyin on Android (Not the desktop version), 
and Google no longer provides up to date code for it since 2009.
If you are interested in full featured pinyin input method, please try libpinyin or sunpinyin, 
they are both supported by fcitx and ibus. They use more advanced algorithm (2-gram vs this project's unigram) and support more feature,
like Shuangpin, Zhuyin, Fuzzy Pinyin and so on. 

此项目使用了codecvt，gcc5.0之前的版本还不支持codecvt，并且最新的c++标准已放弃支持codecvt。
因此linux下调试时需要安装高版本gcc，测试使用centOS7 + gcc5.3.0可以正常编译调试。

git submodules

可以参考大牛的博客：
http://palanceli.com/2017/04/16/2017/0416libGooglePinyin01/
git submodules：
http://palanceli.com/2018/06/22/2018/0626GitSubmodule/

