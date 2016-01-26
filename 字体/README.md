# 字体

### 一个常规的css字体设置示例：

```css
// 单独设置：
font-family: "Microsoft YaHei",Tahoma, Helvetica, Arial, "SimSun",sans-serif;
// 综合设置
font: 14px/24px arial,"\5b8b\4f53",sans-serif,"Microsoft YaHei",tahoma;
```

**按字体顺序检索排列，以英文逗号隔开，如果字体名称包含空格或中文，则应使用引号包裹起来。**

#### 最常见字体ASCII对照(DIY)：

```css
font-family: Helvetica, Tahoma, Arial, STXihei, "华文细黑", "Microsoft YaHei", "微软雅黑", SimSun, "宋体", Heiti, "黑体", sans-serif;
```

```css
font-family: Helvetica, Tahoma, Arial, STXihei, \534E\6587\7EC6\9ED1, "Microsoft YaHei", \5FAE\8F6F\96C5\9ED1, SimSun, \5B8B\4F53, Heiti, \9ED1\4F53, sans-serif;
```

随着时代的发展和技术的升级，字体的使用也开始出新的方式了。比如：**Icon font, svg,以及最近出现的font-spider等。**其中icon font相对的已经很成熟了，应用也很广泛了。

扩展阅读：

- [http://www.w3school.com.cn/css/css_font.asp](http://www.w3school.com.cn/css/css_font.asp)
- [http://www.w3school.com.cn/css3/css3_font.asp](http://www.w3school.com.cn/css3/css3_font.asp)
- [Firefox&Chrome默认字体的渲染差异](http://div.io/topic/1012)
- [Web 中文字体应用指南](https://ruby-china.org/topics/14005)
- [你未必知道的CSS故事：揭开leading的面纱（line-height）](http://www.ituring.com.cn/article/18076)