## laravel 框架中的语言包配置

1. #### 由于中文和英文都属于语言范畴,若使用中文需要下载中文语言包的支持

   访问  https://packagist.org/ 

   输入laravel-lang(不需要回车,自动检索)寻找下载及评论最多的php文件

   ![laravel_lang]({{ site.url }}/assets/img/laravel_lang.png)

2. #### 选择对应的版本,推荐去找下面的命令行,用composer命令安装(注意要记住当前所在的目录!!!)

   ![laravel_lang]({{ site.url }}/assets/img/laravel_lang_download.png)

3. #### 下载完成后到 vendor/caouecs/laravel-lang/src 寻找对应的语言包,

   其中zh代表中国如有其他需求也可以选择其他国家语言,

   因为学识较浅,暂时还是只看的懂中文,我就只展示中文了.

   ![laravel_lang]({{ site.url }}/assets/img/laravel_lang_path.png)

   ![laravel_lang]({{ site.url }}/assets/img/laravel_lang_zh.png)

4. #### 复制文件至 resources/lang 下

   ![laravel_lang]({{ site.url }}/assets/img/laravel_lang_set.png)

   ### 等等,还不算完,我们还要去修改配置文件

   修改config/app.php 中的  'local' => 'zh-CN'  大概80行左右

![laravel_lang]({{ site.url }}/assets/img/laravel_lang_setlang.png)