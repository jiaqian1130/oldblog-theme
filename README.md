# oldblog-theme  
[這是模板來源](https://github.com/codewithsadee/vcard-personal-portfolio)  
這是舊的blog theme，目前已經棄用  
如果要自訂網頁icon請把圖片轉成.ico檔案  
取名```favicon.ico```並放進```./assets/images/```

如果要新增貼文請看626行到651行
```html

            <li class="blog-post-item">
              <a href="./page/testpage.html"> <!--導向頁面-->

                <figure class="blog-banner-box">
                  <img src="./assets/images/testimage.jpg" alt="Best fonts every designer" loading="lazy">
                </figure>

                <div class="blog-content">

                  <div class="blog-meta">
                    <p class="blog-category">test</p>

                    <span class="dot"></span>

                    <time datetime="2022-02-23">2023/2/8</time>
                  </div>

                  <h3 class="h3 blog-item-title">test</h3>

                  <p class="blog-text">
                    test
                  </p>
                </div>

              </a>
            </li>

```

如果想要自訂我會啥  
像這樣  
![](https://github.com/jiaqian1130/oldblog-theme/blob/main/assets/images/%E6%88%91%E6%9C%83%E5%95%A5.png)  
請看484行到497行  

```html
            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">你的技能</h5>
                <data value="1.9">%數</data> <!--1.9要改成你要的數字-->
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width:19%;"></div> <!--這邊的19%要改成你要的-->
              </div>

            </li>
```
如果要放discord連結按一下導向到加好友頁面的話格式如下  
```https://discord.com/users_ID```
