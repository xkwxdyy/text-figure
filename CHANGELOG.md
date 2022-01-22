## 更新日志

[TODO]

- 可以手动调整偏移量
- anchor=west或者east的时候先自动调整ratio，然后可以被手动调整
  - 问题在于要知道key-val设置了什么anchor才能判断
  - 但是这个key-val设置和手动设置ratio是同一接口
  - 理想是：
    - 先用户设置anchor
    - 然后自动判断是否是west或者east，并自动调整ratio
    - 然后用户手动的话以手动的为准

### [v0.0.2] - 2022-01-22

#### Added

- 可以调整图片的anchor
- 可以调整文本的宽度或者占行距的比例

## 仓库地址

Github：https://github.com/xkwxdyy/foo

Gitee：https://gitee.com/xkwxdyy/foo

