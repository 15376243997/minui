# wxc-toast

> MinUI 小程序组件 - 提示框

## Install

``` bash
$ min install @minui/wxc-toast
```

<br/>

> Please make sure you have installed [Min-Cli](https://github.com/meili/min-cli)☟

```
$ npm install -g @mindev/min-cli
```

For more information about MinUI, please visit [MinUI in Github](https://github.com/meili/minui).

## API

### Toast【props】

| 名称                  | 描述                         |
|----------------------|------------------------------|
|`is-show`             | [说明]： `toast` 显示控制字段。<br>类型：`Boolean`<br>默认值：`false`|
|`text`                | [说明]：提示的文案，必填。<br>类型：`String`<br>默认值：`""` <br>     |
|`icon`                | [说明]：图标。<br>类型：`String`<br>默认值：`""` <br> 可选值详见 `wxc-icon` 组件中的 `type` 属性    |
|`icon-image`          | [说明]：自定义图标的路径，image 的优先级高于 icon。<br>类型：`String`<br>默认值：`""` <br>       |
|`icon-color`          | [说明]：图标颜色。<br>类型：`String`<br>默认值：`"#fff"` <br> |
|`duration`            | [说明]：提示的延迟时间，单位毫秒。<br>类型：`Number`<br>默认值：`2000` <br>  |
|`bind:success`        | [说明]：调用成功的回调函数。|

##  ChangeLog

#### v1.0.2（2017.11.02）

- update .npmignore

#### v1.0.1（2017.10.24）

- 初始版本
