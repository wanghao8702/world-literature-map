# 封面图片目录

把每本书的封面图放在这里，按 **书籍 id** 命名，与 `books-content.json` 里的 `cover` 字段对应：

```
covers/b001.jpg   我与地坛
covers/b002.jpg   红楼梦
covers/b003.jpg   源氏物语
covers/b004.jpg   挪威的森林
covers/b005.jpg   追风筝的人
covers/b006.jpg   耶路撒冷三千年
covers/b007.jpg   百年孤独
covers/b008.jpg   老人与海
covers/b009.jpg   了不起的盖茨比
covers/b010.jpg   约翰·克里斯朵夫
covers/b011.jpg   战争与和平
covers/b012.jpg   堂吉诃德
```

## 说明
- 文件格式 jpg/png/webp 均可；要改文件名就同步改 `books-content.json` 里对应的 `cover` 路径。
- 建议尺寸：宽高比约 3:4（书脊/书封竖版），如 600×800；过大图会拖慢加载。
- **缺图不报错**：某本书没有放图（或路径写错）时，书卡会自动回退成“文字封面”，不会出现裂图。
- **不要用豆瓣“照片页”网址**（如 `https://movie.douban.com/subject/.../photos`）：那是网页不是图片，且豆瓣图片有防盗链，从本地/别的域名加载会失败。请把图片**下载保存**到本目录。
- 版权提醒：电影海报、出版社书封等多为受版权保护的素材，仅自用预览问题不大，公开发布需注意授权。
