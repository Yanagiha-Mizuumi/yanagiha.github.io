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



