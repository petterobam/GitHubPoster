# GitHubPoster

[说明文档](https://github.com/yihong0618/GitHubPoster)

## 使用

- 不同类型按下方指定的使用方式
- 可以指定年份如 --year 2021, (default) 或年份区间 2012-2021
- 生成的 svg 在 `OUT_FOLDER` 内, 用 type 命名（暂时）
- 默认自动生成不同颜色需要的 number（特殊颜色）, 也可以指定如： --special-number1 10 -- special_number2 20
- 也可以指定颜色： --special-color1 pink --special-color2 '#33C6A4'
- 其它参数可以见 [cli.py](https://github.com/yihong0618/GitHubPoster/blob/main/cli.py)
- 可以增加动画 --with-animation (加入 GOGOGO 动画), 可以控制动画时间 --animation-time 14（默认是 10s）
- 可以增加 Skyline --with-skyline (默认生成的为 to_year)

## 动态统计

### Github

![](https://github.com/yihong0618/GitHubPoster/blob/main/examples/github.svg)

### Bilibili

![](https://github.com/yihong0618/GitHubPoster/blob/main/examples/bilibili.svg)