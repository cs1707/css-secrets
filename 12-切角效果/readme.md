# 切角效果

- 实现方式一：背景使用 `linear-gradient` 或 `radial-gradient` 指定角度，分别设置各个背景的位置。chrome 有浏览器bug 中间会出线白线。设置 `background-size: 51% 51%` 可以解决。
- 实现方式二：使用 `border-image` 和 `svg`
- 实现方式三：使用 `clip-path`

demo: [https://cs1707.github.io/css-secrets/12-切角效果](https://cs1707.github.io/css-secrets/12-切角效果)
