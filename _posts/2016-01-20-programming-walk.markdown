---
layout: post
comments: true
title: "Программирование и Весенняя Прогулка"
date:   2016-04-27 12:00:00
categories: programming video
---

Просто эксперименты в MATLAB:

<iframe width="740" height="417" src="http://www.youtube.com/embed/ZL_tbMdrdM4" frameborder="0" allowfullscreen></iframe>

А вот тут - попытка реализовать игру Munchkin, но кажется в этом видео не очень хорошо получилось:

<iframe width="740" height="417" src="http://www.youtube.com/embed/-hXzRkrRQkw" frameborder="0" allowfullscreen></iframe>

Ну и напоследок немного креатива -- записали небольшое видео в процессе прогулки по району:

<iframe width="740" height="417" src="http://www.youtube.com/embed/2YOYxIgEp7I" frameborder="0" allowfullscreen></iframe>

{% if page.comments %}
<div id="disqus_thread"></div>
<script>
    /**
     *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
     *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables
     */
    /*
    var disqus_config = function () {
        this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
        this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() {  // DON'T EDIT BELOW THIS LINE
        var d = document, s = d.createElement('script');
        
        s.src = '//matkrug.disqus.com/embed.js';
        
        s.setAttribute('data-timestamp', +new Date());
        (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>
{% endif %}