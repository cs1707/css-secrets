# 满幅的背景，定宽的内容

传统方式实现“背景满福，内容宽度固定”这种布局，需要为每个区块准备两层元素。外层宽度设置背景，内层定宽居中。

``` html
<footer>
  <div class="wraper">
    <!-- 页脚内容 -->
  </div>
</footer>
```

``` css
footer {
  background: #333;
}
.wraper {
  max-width: 900px;
  margin: 1em auto;
}
```

书中方式使用 `calc()` 函数，只需要一层元素搞定。

``` css
footer {
  padding: 1em calc(50% - 450px);
}
```

demo: [https://cs1707.github.io/css-secrets/39](https://cs1707.github.io/css-secrets/39)
