---
title: 说说
date: 2022-03-31 09:14:23
---

<!-- 引用 HexoPlusPlus_Talk组件 -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/HexoPlusPlus/HexoPlusPlus@1.2.0/talk.css" /> 
<script src="https://cdn.jsdelivr.net/gh/HexoPlusPlus/HexoPlusPlus@1.2.0/talk_user.js"></script>
<!-- 创建HexoPlusPlus_Talk容器 -->
<div id="hpp_talk"></div>
<!-- 激活HexoPlusPlus_Talk -->
<script>
new hpp_talk({
id:"hpp_talk",//容器id
domain: "lpblog.rdpstudio.top",//您的HexoPlusPlus域名，如admin.cyfan.top
limit: 10,//单次获取的最多条数
start: 0,//从第几条开始
themecss: "https://cdn.jsdelivr.net/gh/HexoPlusPlus/CDN@master/plugin/style/heimu.css" //自定义说说主题，可选【仅1.1.0版本及以上使用】
});
</script>