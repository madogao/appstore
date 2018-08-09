# 你好 找不到你的联系方式 只能通过 PR 的方式
# 想问下你 npm 上你发的 lemon-cli 这个包有有用处吗，如果已经弃用的话，能否删除下，我这边有个相同的项目，由于你的名字导致我上传不上去。
# 感谢
# appstore

> A minimal vue admin template with Element UI & axios & iconfont & permission control & lint

**Live demo:** https://github.com/ITGodzhangyu/appstore.git

[中文文档]()

## Build Setup

``` bash

# Clone project
git clone https://github.com/ITGodzhangyu/appstore.git

# Install dependencies
npm install

# serve with hot reload at localhost:9528
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

## Demo


## Extra

## Related Project
 [appstore](https://github.com/ITGodzhangyu/appstore.git)

 [appstore](https://github.com/ITGodzhangyu/appstore.git)

### Element-Ui using cdn tutorial

Import css and js of `Element`, and then import vue. Because `Element` is vue-dependent, vue must be import before it.

Add `externals` to make webpack not package vue and element.

```
externals: {
  vue: 'Vue',
  'element-ui':'ELEMENT'
}
```

And you can use `npm run build --report` to see the effect

Pictured:

## License

Copyright (c) 2017-present PanJiaChen
