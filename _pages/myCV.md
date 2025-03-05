---
layout: archive
title: "更正规的CV"
permalink: /CV/myCV/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<script>
    var sWord = prompt("这个可不能轻易给你看哦", "请输入密码嗷");
    var password = "edministrator";
    var isCancle = false;
    while(sWord != password){
        if(sWord == null){
            isCancle = true;
            break;
        }
        else{
            sWord = prompt("真的不能轻易给你看哦", "密码到底是多少呢？");
        }
    }
    if(!isCancle){
        alert("欢迎光临！");
    }
    else{
        location.replace("about:blank");
        window.close();
    }
</script>

* <a href="/files/CV1(English)_20250306.pdf" target="_blank">CV(English)</a>
  * 更新时间：2025-3-6
* <a href="/files/CV1(Chinese)_20250229.pdf" target="_blank">CV(Chinses)</a>
  * 还没有。敬请期待 QWQ

