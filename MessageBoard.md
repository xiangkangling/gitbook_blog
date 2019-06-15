<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.css">
<script src="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js"></script>
<div id="gitalk-container"></div>
<script>
  var gitalk = new Gitalk({
    "clientID": "fe0763ec070321e5fd11",
    "clientSecret": "30c8cea1d7eec881720dfd139ed1ddd83a21e206",
    "repo": "gitbook_blog",
    "owner": "xiangkangling",
    "admin": ["xiangkangling"],
    "id": location.href,      
    "distractionFreeMode": false  
  });
  gitalk.render("gitalk-container");
</script>