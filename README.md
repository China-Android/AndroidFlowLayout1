# Android-SearchFlowLayout
## 热门标签，搜索记录标签，流式布局，支持最大行数，元素内最大字数的限制，每个条目之间的间距设置，字体颜色，元素背景，元素文字左边图片标头显示等，体积小，易上手！！！直接上效果

![image](https://user-images.githubusercontent.com/65054178/188781377-f76727d4-8322-4332-b5ae-6dc3216cdde7.png)

![image](https://user-images.githubusercontent.com/65054178/188769198-ba297d3b-1d79-4bc1-bfca-474ca9b51bd8.png)

### 引入方式：
<pre><code>
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
	    }
   
dependencies {
	        implementation 'com.github.China-Android:Android-SearchFlowLayout:1.0'
	     }
</code></pre>
  
  1.设置每个条目之间的间距
  <pre><code>
   fl_layout.setHorizontalMargin(10);
   </code></pre>
  2.设置每一行之间的间距
  <pre><code>
  fl_layout.setVerticalMargin(30);
  </code></pre>
  3.设置字体颜色
  <pre><code>
  fl_layout.setTextColor(R.color.purple_500);
  </code></pre>
  4.设置每一条最大字显示体个数，超过部分截取不显示
  <pre><code>
  fl_layout.setTextMaxLength(10);
  </code></pre>
  5.设置文字左面图片
  <pre><code>
  fl_layout.setTextDrawableLeft(R.drawable.xxx);
  </code></pre>
  6.设置列表数据
  <pre><code>
  fl_layout.setTextList(list);
  </code></pre>
  7.设置点击事件
  <pre><code>
  fl_layout.setOnClickItemListener((v, text) -> {

  });
  </code></pre>
 对应也可在xml中进行相关属性设置
 <pre><code>
  itemHorizontalMargin = "10"
  itemVerticalMargin = "10"
  textMaxLength = "3"
  textColor = "@color/xxx"
  textDrawableLeft="@drawable/c"
 </code></pre>
  
