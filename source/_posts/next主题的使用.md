---
title: next主题的使用
---

安装：
git clone https://github.com/theme-next/hexo-theme-next themes/next



更新：

cd themes/next
git pull



修改备案信息：

1. 找到 \themes\next\layout\_partials\ 下面的footer.swig文件

2.修改增加代码：

```
<div class="BbeiAn-info">   	{{ __('浙ICP备') }} -    <a target="_blank" href="http://www.beian.miit.gov.cn/" style="color:#f0d784"  rel="nofollow">备案号</a>	<a target="_blank" href="http://www.beian.gov.cn/portal/registerSystemInfo?recordcode=备案号" style="color:#f0d784;text-decoration:none;padding-left:30px;background:url(https://s1.ax1x.com/2018/09/29/ilmwIH.png) no-repeat left center" rel="nofollow">{{ __('浙公网安备 你自己的备案号') }}</a>
```

