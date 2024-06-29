# Embedded iframe
## https://ghepes.github.io/Enbeded/

<a href="https://ghepes.github.io/Enbeded/">@Ghepes/Enbeded</a>
<!--
<iframe src="https://jeromeetienne.github.io/threex.planets/examples/earth.html" width="25%" height="440px" frameborder="0" scrolling="0"></iframe><iframe src="https://jeromeetienne.github.io/threex.planets/examples/earth.html" width="25%" height="440px" frameborder="0" scrolling="0"></iframe><iframe src="https://jeromeetienne.github.io/threex.planets/examples/earth.html" width="25%" height="440px" frameborder="0" scrolling="0"></iframe><iframe src="https://jeromeetienne.github.io/threex.planets/examples/earth.html" width="25%" height="440px" frameborder="0" scrolling="0"></iframe><iframe src="https://jeromeetienne.github.io/threex.planets/examples/earth.html" width="25%" height="440px" frameborder="0" scrolling="0"></iframe><iframe src="https://jeromeetienne.github.io/threex.planets/examples/earth.html" width="25%" height="440px" frameborder="0" scrolling="0"></iframe><iframe src="https://jeromeetienne.github.io/threex.planets/examples/earth.html" width="25%" height="440px" frameborder="0" scrolling="0"></iframe><iframe src="https://jeromeetienne.github.io/threex.planets/examples/earth.html" width="25%" height="440px" frameborder="0" scrolling="0"></iframe>
-->


### Head Accept domain security for main domain: 
````
<head>
    <title></title>
    <meta charset="utf-8" />
    <!-- Permite încorporarea în iframes -->
    <meta http-equiv="Content-Security-Policy" content="frame-ancestors 'self' https://www.wromo.com">
</head>
````

### Body ifram No security
````
<!DOCTYPE html>
<html>
    <head>
        <title></title>
        <meta charset="utf-8" />
    </head>
    <body>
        <iframe src="https://www.wromo.com/index-business.html" width="100%" height="640px" frameborder="0" scrolling="0"></iframe>
    </body>  
</html>
````

### iframe full-screen-preview__frame
````
<iframe class="full-screen-preview__frame" src="https://www.wromo.com/tf/xeco/" name="preview-frame" frameborder="0" noresize="noresize" data-view="fullScreenPreview" allow="geolocation 'self'; autoplay 'self'" style="height: 1217px;">
</iframe>
````   
### Exemple iframe cookiebot
````
<iframe tabindex="-1" role="presentation" aria-hidden="true" title="Blank" src="https://consentcdn.cookiebot.com/sdk/bc-v4.min.html" style="position: absolute; width: 1px; height: 1px; top: -9999px;"></iframe>
````


### Exemple 4000 milisecunde = 4 secunde
````

<iframe id="myFrame" src="https://ai.wromo.com/img/index/" width="600" height="400"></iframe>

<script>
function refreshFrame() {
  var frame = document.getElementById('myFrame');
  frame.src = frame.src;
}

setInterval(refreshFrame, 4000); // 4000 milisecunde = 4 secunde
</script> 
````

### Exemple Non blok embedded .js from Gist github like cdn
````

<script type="text/javascript" charset="UTF-8" async="" src="https://gist.githubusercontent.com/Ghepes/68d961b429b062c123857ab3c90a794a/raw/1b447167da3f31dab4b2eb0dde2d1b121b83820e/login-attempts?renew=false&amp;referer=iframe-wromo.test&amp;dnt=false&amp;init=false"></script><script type="text/javascript" async="" src="https://gist.githubusercontent.com/Ghepes/204501b59fccddc5fa322a2d2963fb0b/raw/f7b07122080e2cb54e0f293a12f8fb34c921f07d/app.min.js" nonce=""></script><script type="text/javascript" async="" src="https://gist.githubusercontent.com/Ghepes/204501b59fccddc5fa322a2d2963fb0b/raw/f7b07122080e2cb54e0f293a12f8fb34c921f07d/bootstrap-slider.min.js" nonce=""></script><script type="text/javascript" async="" src="https://gist.github.com/Ghepes/204501b59fccddc5fa322a2d2963fb0b.js" nonce=""></script><script type="text/javascript" async="" src=""></script><script async="" src=""></script><script>
    var xhr = new XMLHttpRequest();
    xhr.open("OPTIONS", "", true);
    xhr.setRequestHeader("Content-Type", "application/json");
    xhr.send();
</script>
````

# Exemple iframe with css icon end js ... function to fix height of iframe!
````
//]]>
</script><link rel="stylesheet" media="all" href="https://public-assets.envato-static.com/assets/market/core/index-1870c48b7aeda502aff780c5a21bd7b15ab21ebc2ebb4b5fa87c65b862ceb3a8.css">
    <link rel="stylesheet" media="all" href="https://public-assets.envato-static.com/assets/market/pages/preview/index-c20c294967c4ed0be90d33e130e591a57859fccaebd0a19bf00bf499d001afc3.css">

      <link rel="apple-touch-icon-precomposed" type="image/x-icon" href="https://public-assets.envato-static.com/icons/themeforest.net/apple-touch-icon-72x72-precomposed.png" sizes="72x72">
  <link rel="apple-touch-icon-precomposed" type="image/x-icon" href="https://public-assets.envato-static.com/icons/themeforest.net/apple-touch-icon-114x114-precomposed.png" sizes="114x114">
  <link rel="apple-touch-icon-precomposed" type="image/x-icon" href="https://public-assets.envato-static.com/icons/themeforest.net/apple-touch-icon-144x144-precomposed.png" sizes="144x144">
<link rel="apple-touch-icon-precomposed" type="image/x-icon" href="https://public-assets.envato-static.com/icons/themeforest.net/apple-touch-icon-precomposed.png">

    <script src="index-12553ba97c0c709bc106912064580bef531a9617671f599502aca9598a9086fa.js" nonce=""></script>

    <script nonce="">
//<![CDATA[
      //function to fix height of iframe!
      var calcHeight = function() {
        var headerDimensions = $('.preview__header').height();
        $('.full-screen-preview__frame').height($(window).height() - headerDimensions);
      }

      $(document).ready(function() {
        calcHeight();
      });

      $(window).resize(function() {
        calcHeight();
      }).load(function() {
        calcHeight();
      });

//]]>
</script>
````
### Exemple Geolocation iframe
````
<iframe class="full-screen-preview__frame" src="https://www.wromo.com/" name="preview-frame" frameborder="0" noresize="noresize" data-view="fullScreenPreview" allow="geolocation 'self'; autoplay 'self'" style="height: 1217px;">
</iframe>


    <script nonce="">
//<![CDATA[
      $(function(){viewloader.execute(Views);});

//]]>
</script>
    <script nonce="">
````

### Exemple oembed

````
<link rel="alternate" type="application/json+oembed" href="http://www.domain.com/wp-json/oembed/1.0/embed?url=http%3A%2F%2Fwww.domain.com%3A433%2F">
````

3D Enbeded Content Website

###
# 3D Enbeded Content 

### Deny Domain Info 

wen bei website domain is set 'X-Frame-Options' to 'deny', which prevents the site from being embedded in an iframe.
then you won't be able to embed that page in an iframe on your site using security policies like Content-Security-Policy or X-Frame- Options. 
In this case, you should consider other methods or alternatives to display the content of that page on your site.





