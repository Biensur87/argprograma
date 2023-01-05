# Marcelo Medina
<html lang="es">
  Soy de Rosario, tengo 35 años y este es mi trabajo final para Argentina Programa
  </title><meta charset='utf-8'><meta name="description" content="Soy de Rosario, tengo 35 años y este es mi trabajo final para Argentina Programa"><meta name="apple-mobile-web-app-capable" content="yes"><meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no"><link rel="stylesheet" type="text/css" href="dist/style.css"><script src="dist/all.js" type="4d86592fe0d78198f6a0bfb1-text/javascript"></script></head><body class=""><div id="navbar" class=""><div class="nav_toggle"><div class="icon"><div></div><div></div><div></div></div></div><ul><li><a href="index">Home</a></li><li><a href="photos">User Photos</a></li><li><a href="documentation">Documentation</a></li><li><a href="changelog">Change Log</a></li><li><a href="stats">Stats &amp; Graphs</a></li><li><a href="donate">Donate</a></li><li><a href="copyright">Copyright Notice</a></li><li class="blank"></li><li><a href="photoshop">Photoshop Extension</a></li></ul></div><header><h1>Redes</h1><p> <a id="- Linkedin" href="https://www.linkedin.com/in/marcelo-medina-962a9b69/?originalSubdomain=ar%22">open-source</a> </p><a href="https://twitter.com/randomapi" class="twitter"><img src="img/twitter.png">Linkedin</a></header><div class="frame card_offset"><div class="card"><div class="details"><div class="user_photo horizontal_center" id="user_photo"><a href="javascript:getNewUser();" class="refresh">New</a><img src=""></div><p id="user_title">Hi, My name is</p><p id="user_value">...</p></div><ul class="values_list horizontal_center" id="values_list"><li data-title="Hi, My name is" data-value="..." data-label="name" class="active"></li><li data-title="My email address is" data-value="..." data-label="email" data-caps="false"></li><li data-title="My birthday is" data-value="..." data-label="birthday"></li><li data-title="My address is" data-value="..." data-label="location"></li><li data-title="My phone number is" data-value="..." data-label="phone"></li><li data-title="My password is" data-value="..." data-label="pass" data-caps="false"></li></ul></div><section class="sponsor"><h2>Sponsored</h2><h3>RandomAPI</h3><p>Want to create your own <b>customized</b> data generator for your application?<br>Check out our other service RandomAPI!</p><button id="learnmore" class="button" onClick="if (!window.__cfRLUnblockHandlers) return false; window.open('https://randomapi.com');" data-cf-modified-4d86592fe0d78198f6a0bfb1-="">Learn More</button></section><section class="advertisement"><script async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js" type="4d86592fe0d78198f6a0bfb1-text/javascript"></script><ins class="adsbygoogle" style="display:inline-block;width:230px;height:200px" data-ad-client="ca-pub-2036801804961954" data-ad-slot="7646598623"></ins><script type="4d86592fe0d78198f6a0bfb1-text/javascript">(adsbygoogle = window.adsbygoogle || []).push({});</script><ins class="adsbygoogle" style="display:inline-block;width:230px;height:200px;margin:0 16px;" data-ad-client="ca-pub-2036801804961954" data-ad-slot="7646598623"></ins><script type="4d86592fe0d78198f6a0bfb1-text/javascript">(adsbygoogle = window.adsbygoogle || []).push({});</script><ins class="adsbygoogle" style="display:inline-block;width:230px;height:200px" data-ad-client="ca-pub-2036801804961954" data-ad-slot="7646598623"></ins><script type="4d86592fe0d78198f6a0bfb1-text/javascript">(adsbygoogle = window.adsbygoogle || []).push({});</script></section><section><h2>How to use</h2><p>You can use AJAX to call the Random User Generator API and will receive a randomly generated user in return. If you are using jQuery, you can use the $.ajax() function in the code snippet below to get started.</p><pre>$.ajax({
  url: '<span>https://randomuser.me/api/</span>',
  dataType: '<span>json</span>',
  success: function(<span>data</span>) {
    console.log(<span>data</span>);
  }
});
      </pre></section><section><h2>Results</h2><p>The application will provide you with a JSON, XML, CSV, or YAML object that you can parse and apply to your application.</p><p>You can specify the format you want the results in using the <a href="documentation#format">format</a> parameter.</p><pre>{
  "results": [
    {
      "gender": "<span>female</span>",
      "name": {
        "title": "<span>Miss</span>",
        "first": "<span>Jennie</span>",
        "last": "<span>Nichols</span>"
      },
      "location": {
        "street": {
          "number": <span>8929</span>,
          "name": "<span>Valwood Pkwy</span>",
        },
        "city": "<span>Billings</span>",
        "state": "<span>Michigan</span>",
        "country": "<span>United States</span>",
        "postcode": "<span>63104</span>",
        "coordinates": {
          "latitude": "<span>-69.8246</span>",
          "longitude": "<span>134.8719</span>"
        },
        "timezone": {
          "offset": "<span>+9:30</span>",
          "description": "<span>Adelaide, Darwin</span>"
        }
      },
      "email": "<span><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="2a404f4444434f04444349424546596a4f524b475a464f04494547">[email&#160;protected]</a></span>",
      "login": {
        "uuid": "<span>7a0eed16-9430-4d68-901f-c0d4c1c3bf00</span>",
        "username": "<span>yellowpeacock117</span>",
        "password": "<span>addison</span>",
        "salt": "<span>sld1yGtd</span>",
        "md5": "<span>ab54ac4c0be9480ae8fa5e9e2a5196a3</span>",
        "sha1": "<span>edcf2ce613cbdea349133c52dc2f3b83168dc51b</span>",
        "sha256": "<span>48df5229235ada28389b91e60a935e4f9b73eb4bdb855ef9258a1751f10bdc5d</span>"
      },
      "dob": {
        "date": "<span>1992-03-08T15:13:16.688Z</span>",
        "age": <span>30</span>
      },
      "registered": {
        "date": "<span>2007-07-09T05:51:59.390Z</span>",
        "age": <span>14</span>
      },
      "phone": "<span>(272) 790-0888</span>",
      "cell": "<span>(489) 330-2385</span>",
      "id": {
        "name": "<span>SSN</span>",
        "value": "<span>405-88-3636</span>"
      },
      "picture": {
        "large": "<span>https://randomuser.me/api/portraits/men/75.jpg</span>",
        "medium": "<span>https://randomuser.me/api/portraits/med/men/75.jpg</span>",
        "thumbnail": "<span>https://randomuser.me/api/portraits/thumb/men/75.jpg</span>"
      },
      "nat": "<span>US</span>"
    }
  ],
  "info": {
    "seed": "<span>56d27f4a53bd5441</span>",
    "results": <span>1</span>,
    "page": <span>1</span>,
    "version": "<span>1.4</span>"
  }
}
</pre></section><section><h2>Thank you for helping us help you help us all</h2><p>Found a bug or have an idea?<br>Contribute to randomuser.me's database on our <a href="https://github.com/RandomAPI/Randomuser.me-Node">Github Repo</a>.</p><h2>Contact Us</h2><p>If you have any questions/feedback or would like to get in touch with us, tweet us <a href="https://twitter.com/randomapi">@randomapi</a></p></section><section class="cheat"><p>&uarr; &uarr; &darr; &darr; &larr; &rarr; &larr; &rarr; B A</p></section></div><footer><div class="frame"><h1>Random User Generator</h1><div class="block"><div class="builder"><h3>Designed</h3><a href="https://twitter.com/arronhunt"><img src="img/creator_arron.png" width="80px" alt="Designed by Arron Hunt" title="Designed by Arron Hunt" /></a></div><div class="builder"><h3>Developed</h3><a href="https://twitter.com/solewolf1993"><img src="img/creator_keith.png" width="80px" alt="Developed by Keith Armstrong" title="Developed by Keith Armstrong" /></a></div></div><div class="block"><h3>Copyright Notice</h3><p>All randomly generated photos were hand picked from the authorized section of <a href="http://uifaces.com">UI Faces</a>. Please visit <a href="https://web.archive.org/web/20160811185628/http://uifaces.com/faq">UI Faces FAQ</a> for more information regarding how you can use these faces.<br><br></div></div></footer><script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script type="4d86592fe0d78198f6a0bfb1-text/javascript">(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)})(window,document,'script','//www.google-analytics.com/analytics.js','ga');ga('create', 'UA-42942064-1', 'randomuser.me');ga('send', 'pageview');</script><script src="/cdn-cgi/scripts/7d0fa10a/cloudflare-static/rocket-loader.min.js" data-cf-settings="4d86592fe0d78198f6a0bfb1-|49" defer=""></script></body></html>
