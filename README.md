# 霞鹜文楷

支持 **霞鹜文楷** 各种格式的字体，使字体兼容更旧的浏览器。

## 引入字体

### 普通引入
速度较慢，但是可以得到更多兼容

#### 引入完全版字体

```html
<link rel="stylesheet" href="https://gxlydlyf.github.io/LXGW-font/original/font.css">
```

#### 引入精简版字体

```html
<link rel="stylesheet" href="https://gxlydlyf.github.io/LXGW-font/lite/font.css">
```

#### 引入精简版字体 ( font-family无需加Lite )

```html
<link rel="stylesheet" href="https://gxlydlyf.github.io/LXGW-font/lite/font2.css">
```
### 分包引入
速度较快，兼容现代浏览器

#### 引入完全版字体

```html
<link rel="stylesheet" href="https://gxlydlyf.github.io/LXGW-font/original/split/font.css">
```

#### 引入精简版字体

```html
<link rel="stylesheet" href="https://gxlydlyf.github.io/LXGW-font/lite/split/font.css">
```

#### 引入精简版字体 ( font-family无需加Lite )

```html
<link rel="stylesheet" href="https://gxlydlyf.github.io/LXGW-font/lite/split/font2.css">
```
### 兼容引入
如果支持分包，则引入分包，不支持则使用普通引入

#### 引入完全版字体

```html
<link rel="stylesheet" href="https://gxlydlyf.github.io/LXGW-font/original/font.css">
<link rel="stylesheet" href="https://gxlydlyf.github.io/LXGW-font/original/split/font.css">
```

#### 引入精简版字体

```html
<link rel="stylesheet" href="https://gxlydlyf.github.io/LXGW-font/lite/font.css">
<link rel="stylesheet" href="https://gxlydlyf.github.io/LXGW-font/lite/split/font.css">
```

#### 引入精简版字体 ( font-family无需加Lite )

```html
<link rel="stylesheet" href="https://gxlydlyf.github.io/LXGW-font/lite/font2.css">
<link rel="stylesheet" href="https://gxlydlyf.github.io/LXGW-font/lite/split/font2.css">
```
### 注意
将会自动重定向，请不要把url改为重定向后的url(除非浏览器不支持自动重定向)



## 使用字体

#### 使用完全版字体( 和使用精简版font-family无需加Lite字体 )
```html
<style>
    html, textarea, pre, code {
        font-family: LXGW WenKai, LXGW WenKai Mono, SF Pro SC, SF Pro Text, SF Pro Icons, PingFang SC, Helvetica Neue, Helvetica, Arial, sans-serif;
    }
</style>
```

#### 使用精简版字体
```html
<style>
    html, textarea, pre, code {
        font-family: LXGW WenKai Lite, LXGW WenKai Mono Lite, SF Pro SC, SF Pro Text, SF Pro Icons, PingFang SC, Helvetica Neue, Helvetica, Arial, sans-serif;
    }
</style>
```