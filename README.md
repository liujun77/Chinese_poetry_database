# Chinese Poetry Database (CPD)
[![License](https://img.shields.io/badge/license-CC--BY--4.0-blue.svg?)](https://github.com/liujun77/Chinese_poetry_database/blob/master/LICENSE)
## 最全的中国古典诗词数据库
* 先秦：500余首
* 两汉：300余首
* 魏晋：2800余首
* 南北朝：4000余首
* 唐：48000余首
* 宋：27万余首
* 元：6万余首
* 明：24万余首
* 清：13万余首
* 近现代：5万余首
* 当代：3万余首

|作者统计|类别统计|
| :---: | :---: |
| ![作者统计](https://github.com/liujun77/Chinese_poetry_database/blob/master/img/authors.png "作者统计")| ![类别统计](https://github.com/liujun77/Chinese_poetry_database/blob/master/img/types.png "类别统计")|

### 诗歌json格式

```text
[
    {
        "author": "严嵩", 
        "era": "明", 
        "subtype": "七言律诗", 
        "text": [
            "江上新传李郭舟，鹤汀凫渚羡清游。", 
            "谁知今雨来千里，似忆佳期渺十洲。", 
            "梧竹越山栖綵凤，风云天路引骅骝。", 
            "相留拟下南州榻，醉里狂歌海月秋。"
        ], 
        "title": "徐养斋方棠陵偕至喜而有作用王浚川韵", 
        "type": "律诗", 
        "yun": "尤"
    }, 
  ... 每个json文件5000条诗歌记录
]
```
