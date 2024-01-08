# Navbar

use useRef to toggle navlink

## Fixed Height Toggle Link

```css
.show-container {
  height: 10rem;
}
```

因为这个容器的高度是固定高度，不能动态地添加 link，要想能动态的添加 link，要用到 useRef。

## useRef Toggle Link

用 `getBoundingClientRect()` 来得到 links 容器的高度