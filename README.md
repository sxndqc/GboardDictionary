# GboardDictionary
更好地体验Gboard，让Gboard生机勃勃
## 介绍
### 个人词典(`.zip`)
**优点**：便于制作，按模板来就行。
**缺点**：只支持编码对词条，在中文输入中不支持简拼，更不支持双拼和五笔。  
后续会补充小鹤双拼的词库，毕竟我也在用小鹤双拼。
### 用户词典(`user_dict_3_3`)
**优点**：能够支持简拼和双拼，更像真正的“词库”。
**缺点**：需要Root才能使用，不方便制作，词库删改麻烦，需要借助`谷歌拼音输入法`。

## 制作：
### 个人词典的制作
#### 1.制作`dictionary.txt`

    # Gboard Dictionary version:1  
    <编码>  <词条>  <语言>
**注：**用Tab符分开  
中文（简体）：`zh-CN`  
如果要适用于所有语言，直接空就好，但要保留Tab符。
#### 2.打包`zip`
很简单，不多说
#### 3.大功告成


## 安装：
### 个人词典(`.zip`)
1.  在Release页面中，下载最新版本，不需要解压。
2.  在Gboard中，选择“词典”、“个人词典”，选择要安装的语言
3.  点击右上角…号，导入词库。
### 用户词典(`user_dict_3_3`)
*过两天补充。*

## 制作工具
+ Microsoft Excel
+ 深蓝词库转换工具
+ Notepad++
