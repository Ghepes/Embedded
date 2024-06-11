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


3D Enbeded Content Website

###
# 3D Enbeded Content 

### Deny Domain Info 

wen bei website domain is set 'X-Frame-Options' to 'deny', which prevents the site from being embedded in an iframe.
then you won't be able to embed that page in an iframe on your site using security policies like Content-Security-Policy or X-Frame- Options. 
In this case, you should consider other methods or alternatives to display the content of that page on your site.




