# 条纹背景

`linear-gradient` 若色标重合在一起，则中间没有渐变，由此生成条纹背景。

横向条纹背景和竖向条纹背景通过 调整 `linear-gradient` 中的 `deg` 即可实现。

斜向条纹通过 `repeating-linear-gradient` 实现。（至少需要4个色标）

eg:

```css
div {
  background: repeating-linear-gradient(60deg, #fb3, #fb3 15px, #58a 0, #58a 30px);
}
```

同色系条纹通过先设置 `background-color` 然后设置 `background-image` 为透明和不透明颜色条纹。

demo: [https://cs1707.github.io/css-secrets/05-条纹背景](https://cs1707.github.io/css-secrets/05-条纹背景)

