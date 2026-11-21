# 展销活动的作品曝光与成交归因

用于整理合成展览曝光与销售观察，时间精度和统计对象按记录保留。

`fixtures/records.json` 保存合成演练记录，字段说明见 `docs/数据格式.md`。

需要 Python 3.9 或更新版本，无第三方依赖。运行资料基线检查：

```sh
python3 -m unittest discover -s tests -v
```
项目目前只提供资料读取和结构检查。
