# reader

阅读3服务器版，不需要手机。

在线体验 👉 [https://reader.htmake.com](https://reader.htmake.com)

加入TG群(限时开放) 👉 [https://t.me/+pQ8HDlANPZ84ZWNl](https://t.me/+pQ8HDlANPZ84ZWNl)

关注公众号，查看教程和书源👇

![](imgs/mpcode.png)

> 注意❗️
>
> Reader 完整源码仅开放到 v2.5.4，新版本当前仅开放部分开源源码，见 https://github.com/hectorqin/reader-legado.

<details><summary>免责声明（Disclaimer）</summary>
阅读是一款提供网络文学搜索的工具，为广大网络文学爱好者提供一种方便、快捷舒适的试读体验。

当您搜索一本书的时，阅读会将该书的书名以关键词的形式提交到各个第三方网络文学网站。各第三方网站返回的内容与阅读无关，阅读对其概不负责，亦不承担任何法律责任。任何通过使用阅读而链接到的第三方网页均系他人制作或提供，您可能从第三方网页上获得其他服务，阅读对其合法性概不负责，亦不承担任何法律责任。第三方搜索引擎结果根据您提交的书名自动搜索获得并提供试读，不代表阅读赞成或被搜索链接到的第三方网页上的内容或立场。您应该对使用搜索引擎的结果自行承担风险。

阅读不做任何形式的保证：不保证第三方搜索引擎的搜索结果满足您的要求，不保证搜索服务不中断，不保证搜索结果的安全性、正确性、及时性、合法性。因网络状况、通讯线路、第三方网站等任何原因而导致您不能正常使用阅读，阅读不承担任何法律责任。阅读尊重并保护所有使用阅读用户的个人隐私权，您注册的用户名、电子邮件地址等个人资料，非经您亲自许可或根据相关法律、法规的强制性规定，阅读不会主动地泄露给第三方。

阅读致力于最大程度地减少网络文学阅读者在自行搜寻过程中的无意义的时间浪费，通过专业搜索展示不同网站中网络文学的最新章节。阅读在为广大小说爱好者提供方便、快捷舒适的试读体验的同时，也使优秀网络文学得以迅速、更广泛的传播，从而达到了在一定程度促进网络文学充分繁荣发展之目的。阅读鼓励广大小说爱好者通过阅读发现优秀网络小说及其提供商，并建议阅读正版图书。任何单位或个人认为通过阅读搜索链接到的第三方网页内容可能涉嫌侵犯其信息网络传播权，应该及时向阅读提出书面权力通知，并提供身份证明、权属证明及详细侵权情况证明。阅读在收到上述法律文件后，将会依法尽快断开相关链接内容。
</details>

<details><summary>功能说明</summary>
  书源管理 <br/>
- 书架管理 <br/>
- 搜索 <br/>
- 书海 <br/>
- 看书 <br/>
- 移动端适配 <br/>
- 换源 <br/>
- 翻页方式 <br/>
- 手势支持 <br/>
- 自定义主题 <br/>
- 自定义样式 <br/>
- WebDAV同步 <br/>
- 文字替换过滤 <br/>
- 听书<仅部分浏览器支持，手机端会因为锁屏而失效> <br/>
- 用户配置备份恢复 <br/>
- 支持漫画 <br/>
- 支持音频 <br/>
- 书源失效检测 <br/>
- 导入本地TXT、EPUB、UMD格式的书籍 <br/>
- 书籍分组 <br/>
- RSS订阅 <br/>
- 定时更新书架 <br/>
- 并发搜书 <br/>
- 本地书仓 <br/>
</details>

## 下载与安装

详见[文档](https://github.com/hectorqin/reader/blob/master/doc.md)

## TODO

- [x] 定时更新书架书籍章节
- [x] 多源并发搜索书籍
- [x] 并发更新书架章节
- [x] 并发搜索书籍来源
- [x] WebDav同步
- [x] 导入本地书籍，支持epub
- [x] 阅读3核心兼容。已最大可能兼容，支持使用webview，支持使用javascript。
- [x] 支持RSS订阅

## 问题

- 部分使用了 `Javascript` 的书源可能会报错，如调用原生java等高级Javascript功能
- `webview` 功能需要另外部署接口，不支持 `sourceRegex` 匹配资源响应
- 不支持书源登录功能

## 感谢

- 项目初期参考了 [lightink-小说API](https://github.com/lightink-qingmo/lightink-server)
- [阅读](https://github.com/gedoor/MyBookshelf)
- [阅读3.0](https://github.com/gedoor/legado)
- 项目初期参考了 [阅读3.0Web端](https://github.com/celetor/web-yuedu3)

## 其它

- [帮助文档](https://github.com/hectorqin/reader/blob/master/doc.md)
- [界面预览](https://github.com/hectorqin/reader/blob/master/preview.md)
