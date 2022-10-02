<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:version='2' class='v2' expr:dir='data:blog.languageDirection' expr:lang='data:blog.locale' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
    <meta expr:content='data:blog.isMobile         ? &quot;width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0&quot;         : &quot;width=1100&quot;' name='viewport'/>
    <b:include data='blog' name='all-head-content'/>
    <title><data:blog.pageTitle/></title>

    <b:skin><![CDATA[/*
-----------------------------------------------
Blogger Template Style
Name:     Travel
Designer: Sookhee Lee
URL:      www.plyfly.net
----------------------------------------------- */

/* Variable definitions
   ====================
   <Variable name="keycolor" description="Main Color" type="color" default="#539bcd" value="#972702"/>

   <Group description="Page Text" selector="body">
     <Variable name="body.font" description="Font" type="font"
         default="normal normal 13px 'Trebuchet MS',Trebuchet,sans-serif" value="italic bold 20px Georgia, Utopia, &#39;Palatino Linotype&#39;, Palatino, serif"/>
     <Variable name="body.text.color" description="Text Color" type="color" default="#bbbbbb" value="#474747"/>
   </Group>

   <Group description="Backgrounds" selector=".body-fauxcolumns-outer">
     <Variable name="body.background.color" description="Outer Background" type="color" default="#539bcd" value="#f36a3d"/>
     <Variable name="content.background.color" description="Main Background" type="color" default="transparent" value="rgba(0,0,0,0)"/>
   </Group>

   <Group description="Links" selector=".main-outer">
     <Variable name="link.color" description="Link Color" type="color" default="#ff9900" value="#3367d6"/>
     <Variable name="link.visited.color" description="Visited Color" type="color" default="#b87209" value="#3367d6"/>
     <Variable name="link.hover.color" description="Hover Color" type="color" default="#ff9900" value="#6f1905"/>
   </Group>

   <Group description="Blog Title" selector=".header h1">
     <Variable name="header.font" description="Font" type="font"
         default="normal normal 60px 'Trebuchet MS',Trebuchet,sans-serif" value="normal bold 70px Damion"/>
     <Variable name="header.text.color" description="Text Color" type="color" default="#ffffff"  value="#3367d6"/>
   </Group>

   <Group description="Blog Description" selector=".header .description">
     <Variable name="description.text.color" description="Description Color" type="color"
         default="$(body.text.color)"  value="#000000"/>
   </Group>

   <Group description="Tabs Text" selector=".tabs-inner .widget li a">
     <Variable name="tabs.font" description="Font" type="font"
         default="normal bold 16px 'Trebuchet MS',Trebuchet,sans-serif" value="normal bold 16px &#39;Trebuchet MS&#39;,Trebuchet,sans-serif"/>
     <Variable name="tabs.text.color" description="Text Color" type="color" default="#ffffff" value="#ffffff"/>
     <Variable name="tabs.selected.text.color" description="Selected Color" type="color" default="#ffffff" value="#ffffff"/>
   </Group>

   <Group description="Tabs Background" selector=".tabs-outer .PageList">
     <Variable name="tabs.background.color" description="Background Color" type="color" default="transparent" value="rgba(0,0,0,0)"/>
     <Variable name="tabs.selected.background.color" description="Selected Color" type="color" default="transparent" value="rgba(0,0,0,0)"/>
   </Group>

   <Group description="Date Header" selector=".main-inner h2.date-header">
     <Variable name="date.font" description="Font" type="font"
         default="normal normal 14px 'Trebuchet MS',Trebuchet,sans-serif" value="normal normal 14px &#39;Trebuchet MS&#39;,Trebuchet,sans-serif"/>
     <Variable name="date.text.color" description="Text Color" type="color" default="$(body.text.color)" value="#000000"/>
   </Group>

   <Group description="Post Title" selector="h3.post-title a">
     <Variable name="post.title.font" description="Font" type="font"
         default="normal bold 20px 'Trebuchet MS',Trebuchet,sans-serif" value="normal bold 20px &#39;Trebuchet MS&#39;,Trebuchet,sans-serif"/>
     <Variable name="post.title.text.color" description="Text Color" type="color"
         default="#ffffff" value="#000000"/>
   </Group>

   <Group description="Post Background" selector=".column-center-inner">
     <Variable name="post.background.color" description="Background Color" type="color"
         default="transparent" value="#ffffff"/>
     <Variable name="post.background.url" description="Post Background URL" type="url" default="none" value="none"/>
   </Group>

   <Group description="Gadget Title Color" selector="h2">
     <Variable name="widget.title.font" description="Font" type="font"
        default="normal bold 14px 'Trebuchet MS',Trebuchet,sans-serif" value="normal bold 14px &#39;Trebuchet MS&#39;,Trebuchet,sans-serif"/>
     <Variable name="widget.title.text.color" description="Title Color" type="color" default="#ffffff" value="#ffffff"/>
   </Group>

   <Group description="Gadget Text" selector=".footer-inner .widget, .sidebar .widget">
     <Variable name="widget.font" description="Font" type="font"
        default="$(body.font)" value="italic bold 20px Georgia, Utopia, &#39;Palatino Linotype&#39;, Palatino, serif"/>
     <Variable name="widget.text.color" description="Text Color" type="color" default="$(body.text.color)" value="#ffffff"/>
   </Group>

   <Group description="Gadget Links" selector=".sidebar .widget">
     <Variable name="widget.link.color" description="Link Color" type="color" default="$(body.text.color)" value="#3367d6"/>
     <Variable name="widget.link.visited.color" description="Visited Color" type="color" default="$(link.visited.color)" value="#6f1905"/>
     <Variable name="widget.alternate.text.color" description="Alternate Color" type="color" default="#ffffff" value="#ffffff"/>
   </Group>

   <Group description="Sidebar Background" selector=".column-left-inner .column-right-inner">
     <Variable name="widget.outer.background.color" description="Background Color" type="color" default="transparent"  value="rgba(0,0,0,0)"/>
     <Variable name="widget.border.bevel.color" description="Bevel Color" type="color" default="transparent"  value="rgba(0,0,0,0)"/>
   </Group>

   <Variable name="body.background" description="Body Background" type="background"
       color="$(body.background.color)" default="$(color) none repeat-x scroll top center" value="#972702 url(none) no-repeat fixed top center /* Credit: Raycat (http://www.istockphoto.com/portfolio/Raycat?platform=blogger) */"/>
   <Variable name="content.background" description="Content Background" type="background"
       color="$(content.background.color)" default="$(color) none repeat scroll top center" value="transparent url(https://resources.blogblog.com/blogblog/data/1kt/travel/bg_black_70.png) repeat scroll top left"/>
   <Variable name="comments.background" description="Comments Background" type="background"
       default="#cccccc none repeat scroll top center" value="#cccccc none repeat scroll top center"/>

   <Variable name="content.imageBorder.top.space" description="Content Image Border Top Space" type="length" default="0" min="0" max="100px" value="0"/>
   <Variable name="content.imageBorder.top" description="Content Image Border Top" type="url" default="none" value="none"/>

   <Variable name="content.margin" description="Content Margin Top" type="length" default="20px" min="0" max="100px" value="20px"/>
   <Variable name="content.padding" description="Content Padding" type="length" default="20px" min="0" max="100px" value="20px"/>
   <Variable name="content.posts.padding" description="Posts Content Padding" type="length" default="10px" min="0" max="100px" value="20px"/>

   <Variable name="tabs.background.gradient" description="Tabs Background Gradient" type="url"
       default="url(https://resources.blogblog.com/blogblog/data/1kt/travel/bg_black_50.png)" value="url(https://resources.blogblog.com/blogblog/data/1kt/travel/bg_black_50.png)"/>
   <Variable name="tabs.selected.background.gradient" description="Tabs Selected Background Gradient" type="url"
       default="url(https://resources.blogblog.com/blogblog/data/1kt/travel/bg_black_50.png)" value="url(https://resources.blogblog.com/blogblog/data/1kt/travel/bg_black_50.png)"/>
   <Variable name="widget.outer.background.gradient" description="Sidebar Gradient" type="url"
       default="url(https://resources.blogblog.com/blogblog/data/1kt/travel/bg_black_50.png)" value="none"/>
   <Variable name="footer.background.gradient" description="Footer Background Gradient" type="url" default="none" value="none"/>
   <Variable name="mobile.background.overlay" description="Mobile Background Overlay" type="string"
       default="transparent none repeat scroll top left" value="transparent none repeat scroll top left"/>
   <Variable name="mobile.button.color" description="Mobile Button Color" type="color" default="#ffffff"  value="#ffffff"/>
   <Variable name="startSide" description="Side where text starts in blog language" type="automatic" default="left"/>
   <Variable name="endSide" description="Side where text ends in blog language" type="automatic" default="right"/>
*/

/* Content
----------------------------------------------- */
body {
  font: $(body.font);
  color: $(body.text.color);
  background: $(body.background);
}

html body .region-inner {
  min-width: 0;
  max-width: 100%;
  width: auto;
}

a:link {
  text-decoration:none;
  color: $(link.color);
}

a:visited {
  text-decoration:none;
  color: $(link.visited.color);
}

a:hover {
  text-decoration:underline;
  color: $(link.hover.color);
}

.content-outer .content-cap-top {
  height: $(content.imageBorder.top.space);
  background: transparent $(content.imageBorder.top) repeat-x scroll top center;
}

.content-outer {
  margin: 0 auto;
  padding-top: $(content.margin);
}

.content-inner {
  background: $(content.background);
  background-position: left -$(content.imageBorder.top.space);
  background-color: $(content.background.color);
  padding: $(content.padding);
}

.main-inner .date-outer {
  margin-bottom: 2em;
}

/* Header
----------------------------------------------- */
.header-inner .Header .titlewrapper,
.header-inner .Header .descriptionwrapper {
  padding-left: 10px;
  padding-right: 10px;
}

.Header h1 {
  font: $(header.font);
  color: $(header.text.color);
}

.Header h1 a {
  color: $(header.text.color);
}

.Header .description {
  font-size: 130%;
}

/* Tabs
----------------------------------------------- */
.tabs-inner {
  margin: 1em 0 0;
  padding: 0;
}

.tabs-inner .section {
  margin: 0;
}

.tabs-inner .widget ul {
  padding: 0;
  background: $(tabs.background.color) $(tabs.background.gradient) repeat scroll top center;
}

.tabs-inner .widget li {
  border: none;
}

.tabs-inner .widget li a {
  display: inline-block;
  padding: 1em 1.5em;
  color: $(tabs.text.color);
  font: $(tabs.font);
}

.tabs-inner .widget li.selected a,
.tabs-inner .widget li a:hover {
  position: relative;
  z-index: 1;
  background: $(tabs.selected.background.color) $(tabs.selected.background.gradient) repeat scroll top center;
  color: $(tabs.selected.text.color);

}
/* Headings
----------------------------------------------- */
h2 {
  font: $(widget.title.font);
  color: $(widget.title.text.color);
}

.main-inner h2.date-header {
  font: $(date.font);
  color: $(date.text.color);
}

.footer-inner .widget h2,
.sidebar .widget h2 {
  padding-bottom: .5em;
}

/* Main
----------------------------------------------- */

.main-inner {
  padding: $(content.padding) 0;
}

.main-inner .column-center-inner {
  padding: $(content.posts.padding) 0;
}

.main-inner .column-center-inner .section {
  margin: 0 $(content.posts.padding);
}

.main-inner .column-right-inner {
  margin-left: $(content.padding);
}

.main-inner .fauxcolumn-right-outer .fauxcolumn-inner {
  margin-left: $(content.padding);
  background: $(widget.outer.background.color) $(widget.outer.background.gradient) repeat scroll top left;
}

.main-inner .column-left-inner {
  margin-right: $(content.padding);
}

.main-inner .fauxcolumn-left-outer .fauxcolumn-inner {
  margin-right: $(content.padding);
  background: $(widget.outer.background.color) $(widget.outer.background.gradient) repeat scroll top left;
}

.main-inner .column-left-inner,
.main-inner .column-right-inner {
  padding: 15px 0;
}

/* Posts
----------------------------------------------- */
h3.post-title {
  margin-top: 20px;
}

h3.post-title a {
  font: $(post.title.font);
  color: $(post.title.text.color);
}

h3.post-title a:hover {
  text-decoration: underline;
}

.main-inner .column-center-outer {
  background: $(post.background.color) $(post.background.url) repeat scroll top left;
  _background-image: none;
}

.post-body {
  line-height: 1.4;
  position: relative;
}

.post-header {
  margin: 0 0 1em;

  line-height: 1.6;
}

.post-footer {
  margin: .5em 0;
  line-height: 1.6;
}

#blog-pager {
  font-size: 140%;
}

#comments {
  background: $(comments.background);
  padding: 15px;
}

#comments .comment-author {
  padding-top: 1.5em;
}

#comments h4,
#comments .comment-author a,
#comments .comment-timestamp a {
  color: $(post.title.text.color);
}

#comments .comment-author:first-child {
  padding-top: 0;
  border-top: none;
}

.avatar-image-container {
  margin: .2em 0 0;
}

/* Comments
----------------------------------------------- */
#comments a {
  color: $(post.title.text.color);
}

.comments .comments-content .icon.blog-author {
  background-repeat: no-repeat;
  background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEgAACxIB0t1+/AAAAAd0SU1FB9sLFwMeCjjhcOMAAAD+SURBVDjLtZSvTgNBEIe/WRRnm3U8RC1neQdsm1zSBIU9VVF1FkUguQQsD9ITmD7ECZIJSE4OZo9stoVjC/zc7ky+zH9hXwVwDpTAWWLrgS3QAe8AZgaAJI5zYAmc8r0G4AHYHQKVwII8PZrZFsBFkeRCABYiMh9BRUhnSkPTNCtVXYXURi1FpBDgArj8QU1eVXUzfnjv7yP7kwu1mYrkWlU33vs1QNu2qU8pwN0UpKoqokjWwCztrMuBhEhmh8bD5UDqur75asbcX0BGUB9/HAMB+r32hznJgXy2v0sGLBcyAJ1EK3LFcbo1s91JeLwAbwGYu7TP/3ZGfnXYPgAVNngtqatUNgAAAABJRU5ErkJggg==);
}

.comments .comments-content .loadmore a {
  border-top: 1px solid $(post.title.text.color);
  border-bottom: 1px solid $(post.title.text.color);
}

.comments .comment-thread.inline-thread {
  background: $(post.background.color);
}

.comments .continue {
  border-top: 2px solid $(post.title.text.color);
}


/* Widgets
----------------------------------------------- */
.sidebar .widget {
  border-bottom: 2px solid $(widget.border.bevel.color);
  padding-bottom: 10px;
  margin: 10px 0;
}

.sidebar .widget:first-child {
  margin-top: 0;
}

.sidebar .widget:last-child {
  border-bottom: none;
  margin-bottom: 0;
  padding-bottom: 0;
}

.footer-inner .widget,
.sidebar .widget {
  font: $(widget.font);
  color: $(widget.text.color);
}


.sidebar .widget a:link {
  color: $(widget.link.color);
  text-decoration: none;
}

.sidebar .widget a:visited {
  color: $(widget.link.visited.color);
}

.sidebar .widget a:hover {
  color: $(widget.link.color);
  text-decoration: underline;
}

.footer-inner .widget a:link {
  color: $(link.color);
  text-decoration: none;
}

.footer-inner .widget a:visited {
  color: $(link.visited.color);
}

.footer-inner .widget a:hover {
  color: $(link.color);
  text-decoration: underline;
}

.widget .zippy {
  color: $(widget.alternate.text.color);
}

.footer-inner {
  background: transparent $(footer.background.gradient) repeat scroll top center;
}

/* Mobile
----------------------------------------------- */
body.mobile  {
  background-size: 100% auto;
}

body.mobile .AdSense {
  margin: 0 -10px;
}

.mobile .body-fauxcolumn-outer {
  background: $(mobile.background.overlay);
}

.mobile .footer-inner .widget a:link {
  color: $(widget.link.color);
  text-decoration: none;
}

.mobile .footer-inner .widget a:visited {
  color: $(widget.link.visited.color);
}

.mobile-post-outer a {
  color: $(post.title.text.color);
}

.mobile-link-button {
  background-color: $(link.color);
}

.mobile-link-button a:link, .mobile-link-button a:visited {
  color: $(mobile.button.color);
}

.mobile-index-contents {
  color: $(body.text.color);
}

.mobile .tabs-inner .PageList .widget-content {
  background: $(tabs.selected.background.color) $(tabs.selected.background.gradient) repeat scroll top center;
  color: $(tabs.selected.text.color);
}

.mobile .tabs-inner .PageList .widget-content .pagelist-arrow {
  border-$startSide: 1px solid $(tabs.selected.text.color);
}
]]></b:skin>

    <b:template-skin>
      <b:variable default='960px' name='content.width' type='length' value='1071px'/>
      <b:variable default='0' name='main.column.left.width' type='length' value='0px'/>
      <b:variable default='310px' name='main.column.right.width' type='length' value='0px'/>

      <![CDATA[
      body {
        min-width: $(content.width);
      }

      .content-outer, .content-fauxcolumn-outer, .region-inner {
        min-width: $(content.width);
        max-width: $(content.width);
        _width: $(content.width);
      }

      .main-inner .columns {
        padding-left: $(main.column.left.width);
        padding-right: $(main.column.right.width);
      }

      .main-inner .fauxcolumn-center-outer {
        left: $(main.column.left.width);
        right: $(main.column.right.width);
        /* IE6 does not respect left and right together */
        _width: expression(this.parentNode.offsetWidth -
            parseInt("$(main.column.left.width)") -
            parseInt("$(main.column.right.width)") + 'px');
      }

      .main-inner .fauxcolumn-left-outer {
        width: $(main.column.left.width);
      }

      .main-inner .fauxcolumn-right-outer {
        width: $(main.column.right.width);
      }

      .main-inner .column-left-outer {
        width: $(main.column.left.width);
        right: 100%;
        margin-left: -$(main.column.left.width);
      }

      .main-inner .column-right-outer {
        width: $(main.column.right.width);
        margin-right: -$(main.column.right.width);
      }

      #layout {
        min-width: 0;
      }

      #layout .content-outer {
        min-width: 0;
        width: 800px;
      }

      #layout .region-inner {
        min-width: 0;
        width: auto;
      }

      body#layout div.add_widget {
        padding: 8px;
      }

      body#layout div.add_widget a {
        margin-left: 32px;
      }
      ]]>
    </b:template-skin>

    <b:if cond='data:skin.vars.body_background.image.isResizable'>
      <b:include cond='not data:view.isPreview' data='{                          image: data:skin.vars.body_background.image,                          selector: &quot;body&quot;                        }' name='responsiveImageStyle'/>
    </b:if>

    <b:include data='blog' name='google-analytics'/>
  </head>

  <body expr:class='&quot;loading&quot; + data:blog.mobileClass'>
  <b:section class='navbar' id='navbar' maxwidgets='1' name='Navbar' showaddelement='no'>
    <b:widget id='Navbar1' locked='true' title='Navbar' type='Navbar'>
      <b:includable id='main'>&lt;script type=&quot;text/javascript&quot;&gt;
    function setAttributeOnload(object, attribute, val) {
      if(window.addEventListener) {
        window.addEventListener(&#39;load&#39;,
          function(){ object[attribute] = val; }, false);
      } else {
        window.attachEvent(&#39;onload&#39;, function(){ object[attribute] = val; });
      }
    }
  &lt;/script&gt;
&lt;div id=&quot;navbar-iframe-container&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;https://apis.google.com/js/platform.js&quot;&gt;&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
      gapi.load(&quot;gapi.iframes:gapi.iframes.style.bubble&quot;, function() {
        if (gapi.iframes &amp;&amp; gapi.iframes.getContext) {
          gapi.iframes.getContext().openChild({
              url: &#39;https://www.blogger.com/navbar.g?targetBlogID\x3d7412913976681486149\x26blogName\x3dM.R.+Richmind\x26publishMode\x3dPUBLISH_MODE_BLOGSPOT\x26navbarType\x3dDISABLED\x26layoutType\x3dLAYOUTS\x26searchRoot\x3dhttps://mrrichmind.blogspot.com/search\x26blogLocale\x3den_GB\x26v\x3d2\x26homepageUrl\x3dhttp://mrrichmind.blogspot.com/\x26vt\x3d-8565027052111095232&#39;,
              where: document.getElementById(&quot;navbar-iframe-container&quot;),
              id: &quot;navbar-iframe&quot;
          });
        }
      });
    &lt;/script&gt;&lt;script type=&quot;text/javascript&quot;&gt;
(function() {
var script = document.createElement(&#39;script&#39;);
script.type = &#39;text/javascript&#39;;
script.src = &#39;//pagead2.googlesyndication.com/pagead/js/google_top_exp.js&#39;;
var head = document.getElementsByTagName(&#39;head&#39;)[0];
if (head) {
head.appendChild(script);
}})();
&lt;/script&gt;
</b:includable>
    </b:widget>
  </b:section>

  <b:if cond='data:blog.pageType == &quot;index&quot;'>
    <div itemscope='itemscope' itemtype='http://schema.org/Blog' style='display: none;'>
      <meta expr:content='data:blog.title' itemprop='name'/>
      <b:if cond='data:blog.metaDescription'>
        <meta expr:content='data:blog.metaDescription' itemprop='description'/>
      </b:if>
    </div>
  </b:if>

  <div class='body-fauxcolumns'>
    <div class='fauxcolumn-outer body-fauxcolumn-outer'>
    <div class='cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left'>
    <div class='fauxborder-right'/>
    <div class='fauxcolumn-inner'>
    </div>
    </div>
    <div class='cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>
  </div>

  <div class='content'>
  <div class='content-fauxcolumns'>
    <div class='fauxcolumn-outer content-fauxcolumn-outer'>
    <div class='cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left'>
    <div class='fauxborder-right'/>
    <div class='fauxcolumn-inner'>
    </div>
    </div>
    <div class='cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>
  </div>

  <div class='content-outer'>
  <div class='content-cap-top cap-top'>
    <div class='cap-left'/>
    <div class='cap-right'/>
  </div>
  <div class='fauxborder-left content-fauxborder-left'>
  <div class='fauxborder-right content-fauxborder-right'/>
  <div class='content-inner'>

    <header>
    <div class='header-outer'>
    <div class='header-cap-top cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left header-fauxborder-left'>
    <div class='fauxborder-right header-fauxborder-right'/>
    <div class='region-inner header-inner'>
      <b:section class='header' id='header' maxwidgets='1' name='Header' showaddelement='no'>
        <b:widget id='Header1' locked='true' title='M.R. Richmind (Header)' type='Header'>
          <b:widget-settings>
            <b:widget-setting name='displayUrl'>https://1.bp.blogspot.com/-RAM8bewEqZw/Ydqms6vkM9I/AAAAAAAAAV0/5m2i-D668wYZPeCvvS2hU7b5IJi3by7GACNcBGAsYHQ/s1031/IMG-20161104-WA0005.jpg</b:widget-setting>
            <b:widget-setting name='displayHeight'>549</b:widget-setting>
            <b:widget-setting name='sectionWidth'>1031</b:widget-setting>
            <b:widget-setting name='useImage'>true</b:widget-setting>
            <b:widget-setting name='shrinkToFit'>true</b:widget-setting>
            <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
            <b:widget-setting name='displayWidth'>1031</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <b:if cond='data:mobile'>
        <div id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width: 0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      <b:else/>
        <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height                      + &quot;_height: &quot; + data:height                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width: 0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
          <b:include name='description'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <h1 class='title'>
          <b:include name='title'/>
        </h1>
      </div>
      <b:include name='description'/>
    </div>
  </b:if>
</b:includable>
          <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
          <b:includable id='title'>
  <b:tag cond='data:blog.url != data:blog.homepageUrl' expr:href='data:blog.homepageUrl' name='a'>
    <data:title/>
  </b:tag>
</b:includable>
        </b:widget>
      </b:section>
    </div>
    </div>
    <div class='header-cap-bottom cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>
    </header>

    <div class='tabs-outer'>
    <div class='tabs-cap-top cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left tabs-fauxborder-left'>
    <div class='fauxborder-right tabs-fauxborder-right'/>
    <div class='region-inner tabs-inner'>
      <b:section class='tabs' id='crosscol' maxwidgets='1' name='Cross-Column' showaddelement='yes'>
        <b:widget id='HTML4' locked='false' title='Search on google' type='HTML'>
          <b:widget-settings>
            <b:widget-setting name='content'>Google? Rashid Richmind</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
        </b:widget>
      </b:section>
      <b:section class='tabs' id='crosscol-overflow' name='Cross-Column 2' showaddelement='no'>
        <b:widget id='PageList1' locked='false' title='Pages' type='PageList'>
          <b:widget-settings>
            <b:widget-setting name='pageListJson'><![CDATA[{"554144114829326907":{"href":"https://mrrichmind.blogspot.com/p/blog-page_15.html","position":4,"title":"Testimonials"},"1343555130887422717":{"href":"https://mrrichmind.blogspot.com/p/blog-page_16.html","position":5,"title":"Photo Gallery"},"4760925779948665903":{"href":"https://mrrichmind.blogspot.com/p/links.html","position":20,"title":"Contact"},"216995433607471000":{"href":"https://mrrichmind.blogspot.com/p/blog-page_27.html","position":7,"title":"Nasihatein"},"7573615714870021382":{"href":"https://mrrichmind.blogspot.com/p/ek-waqya.html","position":16,"title":"Ek Khwab"},"5858593174852669225":{"href":"https://mrrichmind.blogspot.com/p/translated-work.html","position":11,"title":"Translation"},"2330913218606443928":{"href":"https://mrrichmind.blogspot.com/p/hobbies_15.html","position":17,"title":"Hobbies"},"1144295446146577770":{"href":"https://mrrichmind.blogspot.com/p/curriculum-vitae_19.html","position":21,"title":"Curriculum Vitae"},"6575815403600539618":{"href":"https://mrrichmind.blogspot.com/p/tmu-contents.html","position":13,"title":"TMU"},"0":{"href":"https://mrrichmind.blogspot.com/","position":0,"title":"Vision & Mission"},"link1":{"href":"https://urdu-mrrichmind.blogspot.com","position":8,"title":"Urdu Blog"},"2544210546825366735":{"href":"https://mrrichmind.blogspot.com/p/an-insident.html","position":15,"title":"Ek Waqeya"},"link0":{"href":"http://mrrichmind.blogspot.com/p/contact-me.html","position":1,"title":"Bio"},"link5":{"href":"https://docs.google.com/document/u/0/d/172OeAO3S8LskGXtl2endkDbgJEiQ6MR8pQ_2XNU4kQA/","position":22,"title":"Reviews"},"3866027479179090874":{"href":"https://mrrichmind.blogspot.com/p/name-mohammad-rashid-date-of-birth-july.html","position":2,"title":"Profile"},"5675461879271713612":{"href":"https://mrrichmind.blogspot.com/p/vision-board.html","position":3,"title":"Vision Board"},"link4":{"href":"https://richmindinc.blogspot.com/","position":18,"title":"Richmind Inc "},"link3":{"href":"http://mrrichmind.blogspot.com/p/story.html","position":10,"title":"Story"},"link2":{"href":"https://english-mrrichmind.blogspot.com/","position":9,"title":"English Blog"},"6692869579373548559":{"href":"https://mrrichmind.blogspot.com/p/ma-elt.html","position":14,"title":"AMU"},"7295472622264379451":{"href":"https://mrrichmind.blogspot.com/p/english-page.html","position":6,"title":"Thoughts"},"8133348786117937024":{"href":"https://mrrichmind.blogspot.com/p/publication.html","position":12,"title":"Publication"},"4631012464906355223":{"href":"https://mrrichmind.blogspot.com/p/download.html","position":19,"title":"Download"}}]]></b:widget-setting>
            <b:widget-setting name='homeTitle'>Home</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content'>
    <b:if cond='data:mobile'>
      <select expr:id='data:widget.instanceId + &quot;_select&quot;'>
        <b:loop values='data:links' var='link'>
          <option expr:value='data:link.href'>
            <b:attr cond='data:link.isCurrentPage' name='selected' value='selected'/>
            <data:link.title/>
          </option>
        </b:loop>
      </select>
      <span class='pagelist-arrow'>&amp;#9660;</span>
    <b:else/>
      <ul>
        <b:loop values='data:links' var='link'>
          <li>
            <b:class cond='data:link.isCurrentPage' name='selected'/>
            <a expr:href='data:link.href'><data:link.title/></a>
          </li>
        </b:loop>
      </ul>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
        </b:widget>
      </b:section>
    </div>
    </div>
    <div class='tabs-cap-bottom cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>

    <div class='main-outer'>
    <div class='main-cap-top cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>

    <div class='fauxborder-left main-fauxborder-left'>
    <div class='fauxborder-right main-fauxborder-right'/>
    <div class='region-inner main-inner'>

      <div class='columns fauxcolumns'>

        <div class='fauxcolumn-outer fauxcolumn-center-outer'>
        <div class='cap-top'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        <div class='fauxborder-left'>
        <div class='fauxborder-right'/>
        <div class='fauxcolumn-inner'>
        </div>
        </div>
        <div class='cap-bottom'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        </div>

        <div class='fauxcolumn-outer fauxcolumn-left-outer'>
        <div class='cap-top'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        <div class='fauxborder-left'>
        <div class='fauxborder-right'/>
        <div class='fauxcolumn-inner'>
        </div>
        </div>
        <div class='cap-bottom'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        </div>

        <div class='fauxcolumn-outer fauxcolumn-right-outer'>
        <div class='cap-top'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        <div class='fauxborder-left'>
        <div class='fauxborder-right'/>
        <div class='fauxcolumn-inner'>
        </div>
        </div>
        <div class='cap-bottom'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        </div>

        <!-- corrects IE6 width calculation -->
        <div class='columns-inner'>

        <div class='column-center-outer'>
        <div class='column-center-inner'>
          <b:section class='main' id='main' name='Main' showaddelement='no'>
            <b:widget id='Blog1' locked='true' title='Blog Posts' type='Blog'>
              <b:widget-settings>
                <b:widget-setting name='showDateHeader'>false</b:widget-setting>
                <b:widget-setting name='style.textcolor'>#5c5c5c</b:widget-setting>
                <b:widget-setting name='showShareButtons'>false</b:widget-setting>
                <b:widget-setting name='authorLabel'>Google?</b:widget-setting>
                <b:widget-setting name='showCommentLink'>false</b:widget-setting>
                <b:widget-setting name='style.urlcolor'>#a1a1a1</b:widget-setting>
                <b:widget-setting name='showAuthor'>true</b:widget-setting>
                <b:widget-setting name='style.linkcolor'>#3b65b3</b:widget-setting>
                <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
                <b:widget-setting name='style.bgcolor'>#ffffff</b:widget-setting>
                <b:widget-setting name='reactionsLabel'/>
                <b:widget-setting name='showAuthorProfile'>true</b:widget-setting>
                <b:widget-setting name='style.layout'>1x1</b:widget-setting>
                <b:widget-setting name='showLabels'>false</b:widget-setting>
                <b:widget-setting name='showLocation'>false</b:widget-setting>
                <b:widget-setting name='showTimestamp'>false</b:widget-setting>
                <b:widget-setting name='postsPerAd'>1</b:widget-setting>
                <b:widget-setting name='showBacklinks'>false</b:widget-setting>
                <b:widget-setting name='style.bordercolor'>#ffffff</b:widget-setting>
                <b:widget-setting name='showInlineAds'>false</b:widget-setting>
                <b:widget-setting name='showReactions'>false</b:widget-setting>
              </b:widget-settings>
              <b:includable id='main' var='top'>
  <b:if cond='!data:mobile'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.isDateStart and not data:post.isFirstPost'>
          &lt;/div&gt;&lt;/div&gt;
        </b:if>
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-outer&quot;&gt;
        </b:if>
        <b:if cond='data:post.dateHeader'>
          <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
        </b:if>
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-posts&quot;&gt;
        </b:if>
        <div class='post-outer'>
          <b:include data='post' name='post'/>
          <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
        </div>

        <!-- Ad -->
        <b:if cond='data:post.includeAd'>
          <div class='inline-ad'>
            <data:adCode/>
          </div>
        </b:if>
      </b:loop>
      <b:if cond='data:numPosts != 0'>
        &lt;/div&gt;&lt;/div&gt;
      </b:if>
    </div>

    <!-- navigation -->
    <b:include name='nextprev'/>

    <!-- feed links -->
    <b:include name='feedLinks'/>

  <b:else/>
    <b:include name='mobile-main'/>
  </b:if>
</b:includable>
              <b:includable id='backlinkDeleteIcon' var='backlink'/>
              <b:includable id='backlinks' var='post'/>
              <b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <h4 id='comment-post-message'><data:postCommentMsg/></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
              <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
        <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
              <b:includable id='comment_count_picker' var='post'>
  <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
    <data:post.commentLabelFull/>:
  </a>
</b:includable>
              <b:includable id='comment_picker' var='post'>
  <b:if cond='data:post.showThreadedComments'>
    <b:include data='post' name='threaded_comments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
</b:includable>
              <b:includable id='comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>
      <h4><data:post.commentLabelFull/>:</h4>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <b:if cond='data:post.hasOlderLinks'>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
              &#160;
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
              &#160;
          </b:if>

          <data:post.commentRangeText/>

          <b:if cond='data:post.hasNewerLinks'>
            &#160;
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
            &#160;
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
          </b:if>
        </span>
      </b:if>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
          <b:loop values='data:post.comments' var='comment'>
            <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
              <b:if cond='data:comment.favicon'>
                <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
              </b:if>
              <a expr:name='data:comment.anchorName'/>
              <b:if cond='data:blog.enabledCommentProfileImages'>
                <data:comment.authorAvatarImage/>
              </b:if>
              <b:if cond='data:comment.authorUrl'>
                <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
              <b:else/>
                <data:comment.author/>
              </b:if>
              <data:commentPostedByMsg/>
            </dt>
            <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
              <b:if cond='data:comment.isDeleted'>
                <span class='deleted-comment'><data:comment.body/></span>
              <b:else/>
                <p>
                  <data:comment.body/>
                </p>
              </b:if>
            </dd>
            <dd class='comment-footer'>
              <span class='comment-timestamp'>
                <a expr:href='data:comment.url' title='comment permalink'>
                  <data:comment.timestamp/>
                </a>
                <b:include data='comment' name='commentDeleteIcon'/>
              </span>
            </dd>
          </b:loop>
        </dl>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
            <data:post.oldestLinkText/>
          </a>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
            <data:post.olderLinkText/>
          </a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
            <data:post.newerLinkText/>
          </a>
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
            <data:post.newestLinkText/>
          </a>
        </span>
      </b:if>

      <p class='comment-footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='comment-form'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:elseif cond='data:post.allowComments'/>
          <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
        </b:if>
      </p>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

  </div>
</b:includable>
              <b:includable id='feedLinks'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
        <b:include data='feedLinks' name='feedLinksBody'/>
      </div>
    </b:if>

  <b:else/> <!--Post feed links -->
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:include cond='data:post.allowComments and data:post.feedLinks' data='post.feedLinks' name='feedLinksBody'/>
      </b:loop>
    </div>
  </b:if>
</b:includable>
              <b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:feedLinksMsg/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
              <b:includable id='iframe_comments' var='post'>
  <!-- G+ comments, no longer available. The includable is retained for backwards-compatibility. -->
</b:includable>
              <b:includable id='mobile-index-post' var='post'>
  <div class='mobile-date-outer date-outer'>
    <b:if cond='data:post.dateHeader'>
      <div class='date-header'>
        <span><data:post.dateHeader/></span>
      </div>
    </b:if>

    <div class='mobile-post-outer'>
      <a expr:href='data:post.url'>
        <h3 class='mobile-index-title entry-title' itemprop='name'>
          <data:post.title/>
        </h3>

        <div class='mobile-index-arrow'>&amp;rsaquo;</div>

        <div class='mobile-index-contents'>
          <b:if cond='data:post.thumbnailUrl'>
            <div class='mobile-index-thumbnail'>
              <div class='Image'>
                <img expr:src='data:post.thumbnailUrl'/>
              </div>
            </div>
          </b:if>

          <div class='post-body'>
            <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
          </div>
        </div>

        <div style='clear: both;'/>
      </a>

      <div class='mobile-index-comment'>
        <b:include cond='data:blog.pageType != &quot;static_page&quot;                          and data:post.allowComments                          and data:post.numComments != 0' data='post' name='comment_count_picker'/>
      </div>
    </div>
  </div>
</b:includable>
              <b:includable id='mobile-main' var='top'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-index-post'/>
        </b:loop>
      <b:else/>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-post'/>
        </b:loop>
      </b:if>
    </div>

   <b:include name='mobile-nextprev'/>
</b:includable>
              <b:includable id='mobile-nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <div class='mobile-link-button' id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;lsaquo;</a>
      </div>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <div class='mobile-link-button' id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
      </div>
    </b:if>

    <div class='mobile-link-button' id='blog-pager-home-link'>
    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
    </div>

    <div class='mobile-desktop-link'>
      <a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
    </div>

  </div>
  <div class='clear'/>
</b:includable>
              <b:includable id='mobile-post' var='post'>
  <div class='date-outer'>
    <b:if cond='data:post.dateHeader'>
      <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
    </b:if>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
          <b:if cond='data:post.thumbnailUrl'>
            <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
          </b:if>
          <meta expr:content='data:blog.blogId' itemprop='blogId'/>
          <meta expr:content='data:post.id' itemprop='postId'/>

          <a expr:name='data:post.id'/>
          <b:if cond='data:post.title'>
            <h3 class='post-title entry-title' itemprop='name'>
              <b:if cond='data:post.link'>
                <a expr:href='data:post.link'><data:post.title/></a>
              <b:elseif cond='data:post.url and data:blog.url != data:post.url'/>
                <a expr:href='data:post.url'><data:post.title/></a>
              <b:else/>
                <data:post.title/>
              </b:if>
            </h3>
          </b:if>

          <div class='post-header'>
            <div class='post-header-line-1'/>
          </div>

          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
            <data:post.body/>
            <div style='clear: both;'/> <!-- clear for photos floats -->
          </div>

          <div class='post-footer'>
            <div class='post-footer-line post-footer-line-1'>
              <span class='post-author vcard'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                        <span itemprop='name'><data:post.author/></span>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <span itemprop='name'><data:post.author/></span>
                    </span>
                  </b:if>
                </b:if>
              </span>

              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <data:top.timestampLabel/>
                  <b:if cond='data:post.url'>
                    <meta expr:content='data:post.url.canonical' itemprop='url'/>
                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
              </span>

              <span class='post-comment-link'>
                <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                                  and data:post.allowComments' data='post' name='comment_count_picker'/>
              </span>
            </div>

            <div class='post-footer-line post-footer-line-2'>
              <b:if cond='data:top.showMobileShare'>
                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                  <a href='javascript:void(0);'><data:shareMsg/></a>
                </div>
              </b:if>
            </div>

          </div>
        </div>

        <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
      </div>
    </div>
  </div>
</b:includable>
              <b:includable id='nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>

    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
              <b:includable id='post' var='post'>
  <div class='post hentry uncustomized-post-template' itemprop='blogPost' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
    <b:if cond='data:post.firstImageUrl'>
      <meta expr:content='data:post.firstImageUrl' itemprop='image_url'/>
    </b:if>
    <meta expr:content='data:blog.blogId' itemprop='blogId'/>
    <meta expr:content='data:post.id' itemprop='postId'/>

    <a expr:name='data:post.id'/>
    <b:if cond='data:post.title'>
      <h3 class='post-title entry-title' itemprop='name'>
      <b:if cond='data:post.link or (data:post.url and data:blog.url != data:post.url)'>
        <a expr:href='data:post.link ? data:post.link : data:post.url'><data:post.title/></a>
      <b:else/>
        <data:post.title/>
      </b:if>
      </h3>
    </b:if>

    <div class='post-header'>
    <div class='post-header-line-1'/>
    </div>

    <!-- Then use the post body as the schema.org description, for good G+/FB snippeting. -->
    <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' expr:itemprop='(data:blog.metaDescription ? &quot;&quot; : &quot;description &quot;) + &quot;articleBody&quot;'>
      <data:post.body/>
      <div style='clear: both;'/> <!-- clear for photos floats -->
    </div>

    <b:if cond='data:post.hasJumpLink'>
      <div class='jump-link'>
        <a expr:href='data:post.url + &quot;#more&quot;' expr:title='data:post.title'><data:post.jumpText/></a>
      </div>
    </b:if>

    <div class='post-footer'>
    <div class='post-footer-line post-footer-line-1'>
      <span class='post-author vcard'>
        <b:if cond='data:top.showAuthor'>
          <data:top.authorLabel/>
            <b:if cond='data:post.authorProfileUrl'>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                <a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                  <span itemprop='name'><data:post.author/></span>
                </a>
              </span>
            <b:else/>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <span itemprop='name'><data:post.author/></span>
              </span>
            </b:if>
        </b:if>
      </span>

      <span class='post-timestamp'>
        <b:if cond='data:top.showTimestamp'>
          <data:top.timestampLabel/>
          <b:if cond='data:post.url'>
            <meta expr:content='data:post.url.canonical' itemprop='url'/>
            <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
          </b:if>
        </b:if>
      </span>

      <span class='post-comment-link'>
        <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                          and data:post.allowComments' data='post' name='comment_count_picker'/>
      </span>

      <span class='post-icons'>
        <!-- email post links -->
        <b:if cond='data:post.emailPostUrl'>
          <span class='item-action'>
          <a expr:href='data:post.emailPostUrl' expr:title='data:top.emailPostMsg'>
            <img alt='' class='icon-action' height='13' src='https://resources.blogblog.com/img/icon18_email.gif' width='18'/>
          </a>
          </span>
        </b:if>

        <!-- quickedit pencil -->
        <b:include data='post' name='postQuickEdit'/>
      </span>

      <!-- share buttons -->
      <div class='post-share-buttons goog-inline-block'>
        <b:include cond='data:post.sharePostUrl' data='post' name='shareButtons'/>
      </div>

      </div>

      <div class='post-footer-line post-footer-line-2'>
      <span class='post-labels'>
        <b:if cond='data:top.showPostLabels and data:post.labels'>
          <data:postLabelsLabel/>
          <b:loop values='data:post.labels' var='label'>
            <a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='not data:label.isLast'>,</b:if>
          </b:loop>
        </b:if>
      </span>
      </div>

      <div class='post-footer-line post-footer-line-3'>
      <span class='post-location'>
        <b:if cond='data:top.showLocation and data:post.location'>
          <data:postLocationLabel/>
          <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
        </b:if>
      </span>
      </div>
      <b:if cond='data:post.authorAboutMe'>
        <div class='author-profile' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
          <b:if cond='data:post.authorPhoto.url'>
            <img expr:src='data:post.authorPhoto.url' itemprop='image' width='50px'/>
          </b:if>
          <div>
            <a class='g-profile' expr:href='data:post.authorProfileUrl' itemprop='url' rel='author' title='author profile'>
              <span itemprop='name'><data:post.author/></span>
            </a>
          </div>
          <span itemprop='description'><data:post.authorAboutMe/></span>
        </div>
      </b:if>
    </div>
  </div>
</b:includable>
              <b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <img alt='' class='icon-action' height='18' src='https://resources.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
      </a>
    </span>
  </b:if>
</b:includable>
              <b:includable id='shareButtons' var='post'>
  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showPinterestButton'><a class='goog-inline-block share-button sb-pinterest' expr:href='data:post.sharePostUrl + &quot;&amp;target=pinterest&quot;' expr:title='data:top.shareToPinterestMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToPinterestMsg/></span></a></b:if>
</b:includable>
              <b:includable id='status-message'>
  <b:if cond='data:navMessage'>
  <div class='status-msg-wrap'>
    <div class='status-msg-body'>
      <data:navMessage/>
    </div>
    <div class='status-msg-border'>
      <div class='status-msg-bg'>
        <div class='status-msg-hidden'><data:navMessage/></div>
      </div>
    </div>
  </div>
  <div style='clear: both;'/>
  </b:if>
</b:includable>
              <b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
              <b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;

// <![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }

      var bodyFromEntry = function(entry) {
        var text = (entry &&
                    ((entry.content && entry.content.$t) ||
                     (entry.summary && entry.summary.$t))) ||
            '';
        if (entry && entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + text + '</span>';
            }
          }
        }
        return text;
      }

      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                  comment.displayTime = entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };

      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };

      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '250px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          replybox.src = '';
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };

      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }

      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };

      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };

      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();
// ]]>
  </script>
</b:includable>
              <b:includable id='threaded_comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <h4><data:post.commentLabelFull/>:</h4>

    <div class='comments-content'>
      <b:include cond='data:post.embedCommentForm' data='post' name='threaded_comment_js'/>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
    </div>
    </div>
  </div>
</b:includable>
            </b:widget>
            <b:widget id='HTML2' locked='false' title='Bitter Truth' type='HTML'>
              <b:widget-settings>
                <b:widget-setting name='content'><![CDATA[<blockquote style="font-style: normal; font-weight: normal;"></blockquote><span style="font-weight: bold;"></span><span style="font-style: italic;"></span><span style="font-style: italic;"></span><span style="font-weight: bold;"></span><span style="font-style: normal; font-weight: bold;"><blockquote></blockquote></span><span style="font-style: normal; font-weight: bold;"></span><blockquote style="font-style: normal; font-weight: normal;"><span style="font-style: normal; font-weight: bold;color:white;"></span></blockquote><blockquote style="font-style: normal; font-weight: normal;"><span style="font-style: normal; font-weight: bold;"></span></blockquote><p face="&quot;" size="medium" style="margin: 0px;"></p><p style="margin-bottom: .0001pt; margin: 0in; text-align: justify;"><b><i><span =""    style="font-family:&quot;;font-size:16.0pt;color:#000099;">Man works throughout his life for being accepted in the society but in the last hours of his life he wants God to accept him.<br /></span></i></b></p><p style="margin-bottom: .0001pt; margin: 0in; text-align: justify;"><b><i><span =""    style="font-family:&quot;;font-size:16.0pt;color:#000099;">...by Rashid Richmind</span></i></b></p><br /><p></p>]]></b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
            </b:widget>
            <b:widget id='HTML1' locked='false' title='Quick Links' type='HTML'>
              <b:widget-settings>
                <b:widget-setting name='content'><![CDATA[<p class="MsoNormal"><b><span data-darkreader-inline-=""   style="line-height: 115%;font-family:&quot;;font-size:14.0pt;">| </span></b><b  style="font-size: 100%;font-size:100%;"><span data-darkreader-inline-=""   style="line-height: 21.4667px;font-family:&quot;;font-size:14pt;"><a href="https://linktr.ee/rashidrichmind">Linktree</a> </span></b><b =""  style="font-size:100%;"><span data-darkreader-inline-=""   style="line-height: 55.2px;font-family:&quot;;font-size:14.0pt;">| </span></b><b =""  style="font-size:100%;"><span data-darkreader-inline-=""   style="line-height: 115%;font-family:&quot;;font-size:14.0pt;"><a href="https://www.facebook.com/rashidrichmind">Facebook</a> | <a href="https://twitter.com/rashidrichmind">Twitter</a> | <a href="https://www.linkedin.com/in/rashidrichmind">LinkedIn</a> | <a href="https://www.youtube.com/channel/UCyTRJpjX_J8Brdu0eZ_XnKw/videos">YouTube</a> | <a href="https://www.pinterest.com/rashidrichmind">Pintrest</a> | <a href="https://www.instagram.com/rashidrichmind">Instagram</a> | <a href="https://www.slideshare.net/rashidflawless">SlideShare</a> | <a href="https://www.scribd.com/user/589621003/Mohammad-Rashid-Richmind">Scribd</a> | <a href="https://www.yourquote.in/rashidrichmind">YourQuote</a> | <a href="https://mrrichmind.blogspot.com/p/blog-page_12.html">Services</a> | <a href="https://english-mrrichmind.blogspot.com/">English Blog</a> | <a href="https://urdu-mrrichmind.blogspot.com/">Urdu Blog</a> | <a href="https://www.goodreads.com/rashidrichmind">Goodreads</a> | <a href="https://wa.me/919044489869?text=Hello%20Sir%2C%0A%0AI%27m%20really%20impressed%20by%20your%20works.%20I%20appreciate%20your%20hardwork">WhatsApp</a> | <a href="https://www.facebook.com/consultrashid">Facebook Page</a> | <a href="https://www.instagram.com/consultrashid">Instagram Page</a> | <a href="https://richmindinc.blogspot.com/">Richmind Inc</a> |</span></b></p>]]></b:widget-setting>
              </b:widget-settings>
              <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
            </b:widget>
          </b:section>
        </div>
        </div>

        <div class='column-left-outer'>
        <div class='column-left-inner'>
          <aside>
          <macro:include id='main-column-left-sections' name='sections'>
            <macro:param default='0' name='num' value='0'/>
            <macro:param default='sidebar-left' name='idPrefix'/>
            <macro:param default='sidebar' name='class'/>
            <macro:param default='true' name='includeBottom'/>
          </macro:include>
          </aside>
        </div>
        </div>

        <div class='column-right-outer'>
        <div class='column-right-inner'>
          <aside>
          <macro:include id='main-column-right-sections' name='sections'>
            <macro:param default='2' name='num' value='0'/>
            <macro:param default='sidebar-right' name='idPrefix'/>
            <macro:param default='sidebar' name='class'/>
            <macro:param default='true' name='includeBottom'/>
          </macro:include>
          </aside>
        </div>
        </div>

        </div>

        <div style='clear: both'/>
      <!-- columns -->
      </div>

    <!-- main -->
    </div>
    </div>
    <div class='main-cap-bottom cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>

    <footer>
    <div class='footer-outer'>
    <div class='footer-cap-top cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left footer-fauxborder-left'>
    <div class='fauxborder-right footer-fauxborder-right'/>
    <div class='region-inner footer-inner'>
      <macro:include id='footer-sections' name='sections'>
        <macro:param default='2' name='num' value='3'/>
        <macro:param default='footer' name='idPrefix'/>
        <macro:param default='foot' name='class'/>
        <macro:param default='false' name='includeBottom'/>
      </macro:include>
      <!-- outside of the include in order to lock Attribution widget -->
      <b:section class='foot' id='footer-3' name='Footer' showaddelement='no'>
        <b:widget id='Attribution1' locked='true' title='' type='Attribution'>
          <b:widget-settings>
            <b:widget-setting name='copyright'>Copyright &#169; Since May 2014 by Rashid Richmind. All Rights are reserved by Richmind Inc</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
    <div class='widget-content' style='text-align: center;'>
      <b:if cond='data:attribution != &quot;&quot;'>
       <data:attribution/>
      </b:if>
    </div>

    <b:include name='quickedit'/>
  </b:includable>
        </b:widget>
      </b:section>
    </div>
    </div>
    <div class='footer-cap-bottom cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>
    </footer>

  <!-- content -->
  </div>
  </div>
  <div class='content-cap-bottom cap-bottom'>
    <div class='cap-left'/>
    <div class='cap-right'/>
  </div>
  </div>
  </div>

  <script type='text/javascript'>
    window.setTimeout(function() {
        document.body.className = document.body.className.replace(&#39;loading&#39;, &#39;&#39;);
      }, 10);
  </script>
</body>

<macro:includable id='sections' var='col'>
  <macro:if cond='data:col.num == 0'>
  <macro:else/>
    <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-1&quot;' preferred='yes' showaddelement='yes'/>

    <macro:if cond='data:col.num &gt;= 2'>
      <table border='0' cellpadding='0' cellspacing='0' mexpr:class='&quot;section-columns columns-&quot; + data:col.num'>
      <tbody>
      <tr>
        <td class='first columns-cell'>
          <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-2-1&quot;'/>
        </td>

        <td class='columns-cell'>
          <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-2-2&quot;'/>
        </td>

        <macro:if cond='data:col.num &gt;= 3'>
          <td class='columns-cell'>
            <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-2-3&quot;'/>
          </td>
        </macro:if>

        <macro:if cond='data:col.num &gt;= 4'>
          <td class='columns-cell'>
            <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-2-4&quot;'/>
          </td>
        </macro:if>
      </tr>
      </tbody>
      </table>

      <macro:if cond='data:col.includeBottom'>
        <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-3&quot;' showaddelement='no'/>
      </macro:if>
    </macro:if>
  </macro:if>
</macro:includable>

<b:section-contents id='footer-1'>
  <b:widget id='HTML3' locked='false' title='Philosophy of Life' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'>Either you get yourself better than the previous day, or you waste one day of your precious life....Rashid Richmind</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
  <b:widget id='Stats1' locked='false' title='You are Visitor No.' type='Stats'>
    <b:widget-settings>
      <b:widget-setting name='showGraphicalCounter'>true</b:widget-setting>
      <b:widget-setting name='showAnimatedCounter'>true</b:widget-setting>
      <b:widget-setting name='showSparkline'>false</b:widget-setting>
      <b:widget-setting name='sparklineStyle'>BLACK_TRANSPARENT</b:widget-setting>
      <b:widget-setting name='timeRange'>ALL_TIME</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content'>
    <!-- Content is going to be visible when data will be fetched from server. -->
    <div expr:id='data:widget.instanceId + &quot;_content&quot;' style='display: none;'>
      <!-- Counter and image will be injected later via AJAX call. -->
      <b:if cond='data:showSparkline'>
        <script src='https://www.gstatic.com/charts/loader.js' type='text/javascript'/>
        <span expr:id='data:widget.instanceId + &quot;_sparklinespan&quot;' style='display:inline-block; width:75px; height:30px'/>
      </b:if>
      <span expr:class='&quot;counter-wrapper &quot; + (data:showGraphicalCounter ? &quot;graph-counter-wrapper&quot; : &quot;text-counter-wrapper&quot;)' expr:id='data:widget.instanceId + &quot;_totalCount&quot;'>
      </span>
      <b:include name='quickedit'/>
    </div>
  </div>
</b:includable>
  </b:widget>
</b:section-contents><b:section-contents id='footer-2-1'>
  <b:widget id='PageList3' locked='false' title='TMU Contents' type='PageList'>
    <b:widget-settings>
      <b:widget-setting name='pageListJson'><![CDATA[{"7923199316001349579":{"href":"https://mrrichmind.blogspot.com/p/bsc-chem-1st-year.html","position":4,"title":"B.Sc. (Chem.) 1st 2018-19"},"8559616590161725918":{"href":"https://mrrichmind.blogspot.com/p/session-2018-19-odd-semester.html","position":2,"title":"B.Tech (ME) II 2017-18"},"7153978128565502842":{"href":"https://mrrichmind.blogspot.com/p/btech-elect-1st-year.html","position":0,"title":"B.Tech. (EE) 1st 2018-19"},"9106704033629961335":{"href":"https://mrrichmind.blogspot.com/p/bsc-maths-1st-year.html","position":3,"title":"B.Sc. (Maths.) 1st 2018-19"},"6411054261591296576":{"href":"https://mrrichmind.blogspot.com/p/ba-j-1st-year.html","position":7,"title":"B.A. (J&amp;MC) 1st 2018-19"},"8012761055252491817":{"href":"https://mrrichmind.blogspot.com/p/btech-civil-1st-year.html","position":1,"title":"B.Tech. (CE) 1st 2018-19"},"8105875866527902645":{"href":"https://mrrichmind.blogspot.com/p/mpt-1.html","position":6,"title":"Department of Physiotherapy"},"4619320415157257037":{"href":"https://mrrichmind.blogspot.com/p/bds-1st-year.html","position":5,"title":"Dental College &amp; Research Centre"}}]]></b:widget-setting>
      <b:widget-setting name='homeTitle'>Home</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content'>
    <b:if cond='data:mobile'>
      <select expr:id='data:widget.instanceId + &quot;_select&quot;'>
        <b:loop values='data:links' var='link'>
          <option expr:value='data:link.href'>
            <b:attr cond='data:link.isCurrentPage' name='selected' value='selected'/>
            <data:link.title/>
          </option>
        </b:loop>
      </select>
      <span class='pagelist-arrow'>&amp;#9660;</span>
    <b:else/>
      <ul>
        <b:loop values='data:links' var='link'>
          <li>
            <b:class cond='data:link.isCurrentPage' name='selected'/>
            <a expr:href='data:link.href'><data:link.title/></a>
          </li>
        </b:loop>
      </ul>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
  </b:widget>
</b:section-contents><b:section-contents id='footer-2-2'>
  <b:widget id='PageList4' locked='false' title='Quick Links' type='PageList'>
    <b:widget-settings>
      <b:widget-setting name='pageListJson'><![CDATA[{"3361486941520376566":{"href":"https://mrrichmind.blogspot.com/p/contact-me.html","position":0,"title":"Bio"},"554144114829326907":{"href":"https://mrrichmind.blogspot.com/p/blog-page_15.html","position":1,"title":"Testimonials"},"link1":{"href":"https://docs.google.com/document/d/1HzeD5Nf4mZM6-h99u0RE28ILcxqf08Ni8pC8ATfWjeE","position":8,"title":"CV Docs"},"link0":{"href":"https://sarahah.top/u/rashidrichmind","position":2,"title":"Saraha.com"},"216995433607471000":{"href":"https://mrrichmind.blogspot.com/p/blog-page_27.html","position":4,"title":"Nasihatein"},"5858593174852669225":{"href":"https://mrrichmind.blogspot.com/p/translated-work.html","position":6,"title":"Translation"},"7295472622264379451":{"href":"https://mrrichmind.blogspot.com/p/english-page.html","position":3,"title":"Thoughts"},"8133348786117937024":{"href":"https://mrrichmind.blogspot.com/p/publication.html","position":5,"title":"Publication"},"4631012464906355223":{"href":"https://mrrichmind.blogspot.com/p/download.html","position":7,"title":"Download"}}]]></b:widget-setting>
      <b:widget-setting name='homeTitle'>Home</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content'>
    <b:if cond='data:mobile'>
      <select expr:id='data:widget.instanceId + &quot;_select&quot;'>
        <b:loop values='data:links' var='link'>
          <option expr:value='data:link.href'>
            <b:attr cond='data:link.isCurrentPage' name='selected' value='selected'/>
            <data:link.title/>
          </option>
        </b:loop>
      </select>
      <span class='pagelist-arrow'>&amp;#9660;</span>
    <b:else/>
      <ul>
        <b:loop values='data:links' var='link'>
          <li>
            <b:class cond='data:link.isCurrentPage' name='selected'/>
            <a expr:href='data:link.href'><data:link.title/></a>
          </li>
        </b:loop>
      </ul>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
  </b:widget>
</b:section-contents><b:section-contents id='footer-2-3'>
  <b:widget id='PageList5' locked='false' title='Know More' type='PageList'>
    <b:widget-settings>
      <b:widget-setting name='pageListJson'><![CDATA[{"0":{"href":"https://mrrichmind.blogspot.com/","position":0,"title":"Vision & Mission"},"2946564624529140441":{"href":"https://mrrichmind.blogspot.com/p/synonyms.html","position":3,"title":"Synonyms"},"3131862024114264167":{"href":"https://mrrichmind.blogspot.com/p/letters.html","position":8,"title":"Letters"},"2503804967959081415":{"href":"https://mrrichmind.blogspot.com/p/one-word-substi.html","position":1,"title":"Types of Words"},"6190750624372097429":{"href":"https://mrrichmind.blogspot.com/p/blog-page_7.html","position":5,"title":"Homophones"},"4012511949124002721":{"href":"https://mrrichmind.blogspot.com/p/article.html","position":7,"title":"Article"},"6223065889218865888":{"href":"https://mrrichmind.blogspot.com/p/blog-page.html","position":2,"title":"50 Words"},"9127000558842688724":{"href":"https://mrrichmind.blogspot.com/p/poems.html","position":6,"title":"Poems"},"8669831724294910486":{"href":"https://mrrichmind.blogspot.com/p/homonyms.html","position":4,"title":"Homonyms"}}]]></b:widget-setting>
      <b:widget-setting name='homeTitle'>Home</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content'>
    <b:if cond='data:mobile'>
      <select expr:id='data:widget.instanceId + &quot;_select&quot;'>
        <b:loop values='data:links' var='link'>
          <option expr:value='data:link.href'>
            <b:attr cond='data:link.isCurrentPage' name='selected' value='selected'/>
            <data:link.title/>
          </option>
        </b:loop>
      </select>
      <span class='pagelist-arrow'>&amp;#9660;</span>
    <b:else/>
      <ul>
        <b:loop values='data:links' var='link'>
          <li>
            <b:class cond='data:link.isCurrentPage' name='selected'/>
            <a expr:href='data:link.href'><data:link.title/></a>
          </li>
        </b:loop>
      </ul>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
  </b:widget>
</b:section-contents></html>
