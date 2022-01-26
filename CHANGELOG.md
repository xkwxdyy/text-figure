# 更新日志

## [v1.0.1] - 2022-01-25
### Added
- 增加`top-center`, `bottom-center`键值

### Changed
- `fig-pos`初始值改为`right-top`

### Fixed
- 修复`Improper \prevdepth`报错（[#I4S8MX](https://gitee.com/xkwxdyy/text-figure/issues/I4S8MX)）
- 修复`fig-pos = left-*` 或 `right-*` 和 `text-ratio` 同时设置时的顺序问题（[#I4S8OE](https://gitee.com/xkwxdyy/text-figure/issues/I4S8OE)）


## [v1.0.1] - 2022-01-25
### Changed
- 将`expl3`宏包的检测改为2020/03/03

### Fixed
- 修复msg的bug


## [v0.1.0] - 2022-01-23
### Added
- 增加`figure-vsep`, `figure-hsep`控制图片偏移

### Changed
- 将原来的`vsep`, `hsep`改为了控制整体的偏移


### Fixed

- 解决coffin内有list环境，外套一个list环境后出现的label对齐问题 [#I4RVQX](https://gitee.com/xkwxdyy/text-figure/issues/I4RVQX)

## [v0.0.4] - 2022-01-22

### Added

- 可以调整图片的`anchor`
- 可以调整文本的宽度或者占行距的比例
- `anchor = west`或者`east`的时候先自动调整`ratio`，然后可以被手动调整
- 增加了图片的水平和垂直方向的偏移量键值
- 增加了和`left`和`right`等价的`left-center`,`right-center`

### Changed

- 调整`anchor`为`fig-pos`
- 调整`anchor`的东南西北系列（`east, south, west, north` 及其组合）为fig-pos上下左右系列（`top, bottom, left, right` 及其组合）
- 增加了`left`和`right`的`top`和`bottom`形式（`top-right`是右上，`right-top`是右边的顶部）

## 仓库地址

Github：https://github.com/xkwxdyy/text-figure

Gitee：https://gitee.com/xkwxdyy/text-figure

