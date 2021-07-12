<html>
	<link rel="shortcut icon" type="image/x-icon" href="https://onmessage.nd.edu/assets/188821/fullsize/athletics_monogram1.jpg">
	
	<head>
		<title>Matthew Morrison | University of Notre Dame</title>
  		<meta charset="UTF-8">
  		<meta name="description" content="Computer Science 61B: Data Structures">
  		<meta name="keywords" content="CSE 20133, CSE 20312, Computer Science, 20312, Data Structures, Intro to C/C++ Programming, Matthew Morrison, Notre Dame, CSE">
  		<meta name="viewport" content="width=device-width, initial-scale=1">
		
		<script type="text/javascript">window.NREUM||(NREUM={});NREUM.info={"beacon":"bam-cell.nr-data.net","errorBeacon":"bam-cell.nr-data.net","licenseKey":"db51011748","applicationID":"9339","transactionName":"Jw4IFxdXCQgHExslVwoFEwARVxcnDQ9AFFcIDQMRSlwMFxIAQAVQOxEHBAA=","queueTime":0,"applicationTime":320,"agent":"","atts":"H0MTQV9DRwwNEkBEAkYOCA4ASxYFBQQaCFxKBAIWR0UY"}</script>
	
		<script type="text/javascript">(window.NREUM||(NREUM={})).loader_config={licenseKey:"db51011748",applicationID:"9339"};window.NREUM||(NREUM={}),__nr_require=function(t,e,n){function r(n){if(!e[n]){var i=e[n]={exports:{}};t[n][0].call(i.exports,function(e){var i=t[n][1][e];return r(i||e)},i,i.exports)}return e[n].exports}if("function"==typeof __nr_require)return __nr_require;for(var i=0;i<n.length;i++)r(n[i]);return r}({1:[function(t,e,n){function r(){}function i(t,e,n){return function(){return o(t,[u.now()].concat(f(arguments)),e?null:this,n),e?void 0:this}}var o=t("handle"),a=t(8),f=t(9),c=t("ee").get("tracer"),u=t("loader"),s=NREUM;"undefined"==typeof window.newrelic&&(newrelic=s);var d=["setPageViewName","setCustomAttribute","setErrorHandler","finished","addToTrace","inlineHit","addRelease"],p="api-",l=p+"ixn-";a(d,function(t,e){s[e]=i(p+e,!0,"api")}),s.addPageAction=i(p+"addPageAction",!0),s.setCurrentRouteName=i(p+"routeName",!0),e.exports=newrelic,s.interaction=function(){return(new r).get()};var m=r.prototype={createTracer:function(t,e){var n={},r=this,i="function"==typeof e;return o(l+"tracer",[u.now(),t,n],r),function(){if(c.emit((i?"":"no-")+"fn-start",[u.now(),r,i],n),i)try{return e.apply(this,arguments)}catch(t){throw c.emit("fn-err",[arguments,this,t],n),t}finally{c.emit("fn-end",[u.now()],n)}}}};a("actionText,setName,setAttribute,save,ignore,onEnd,getContext,end,get".split(","),function(t,e){m[e]=i(l+e)}),newrelic.noticeError=function(t,e){"string"==typeof t&&(t=new Error(t)),o("err",[t,u.now(),!1,e])}},{}],2:[function(t,e,n){function r(t){if(NREUM.init){for(var e=NREUM.init,n=t.split("."),r=0;r<n.length-1;r++)if(e=e[n[r]],"object"!=typeof e)return;return e=e[n[n.length-1]]}}e.exports={getConfiguration:r}},{}],3:[function(t,e,n){function r(){return f.exists&&performance.now?Math.round(performance.now()):(o=Math.max((new Date).getTime(),o))-a}function i(){return o}var o=(new Date).getTime(),a=o,f=t(10);e.exports=r,e.exports.offset=a,e.exports.getLastTimestamp=i},{}],4:[function(t,e,n){function r(t){return!(!t||!t.protocol||"file:"===t.protocol)}e.exports=r},{}],5:[function(t,e,n){function r(t,e){var n=t.getEntries();n.forEach(function(t){"first-paint"===t.name?d("timing",["fp",Math.floor(t.startTime)]):"first-contentful-paint"===t.name&&d("timing",["fcp",Math.floor(t.startTime)])})}function i(t,e){var n=t.getEntries();n.length>0&&d("lcp",[n[n.length-1]])}function o(t){t.getEntries().forEach(function(t){t.hadRecentInput||d("cls",[t])})}function a(t){if(t instanceof m&&!g){var e=Math.round(t.timeStamp),n={type:t.type};e<=p.now()?n.fid=p.now()-e:e>p.offset&&e<=Date.now()?(e-=p.offset,n.fid=p.now()-e):e=p.now(),g=!0,d("timing",["fi",e,n])}}function f(t){d("pageHide",[p.now(),t])}if(!("init"in NREUM&&"page_view_timing"in NREUM.init&&"enabled"in NREUM.init.page_view_timing&&NREUM.init.page_view_timing.enabled===!1)){var c,u,s,d=t("handle"),p=t("loader"),l=t(7),m=NREUM.o.EV;if("PerformanceObserver"in window&&"function"==typeof window.PerformanceObserver){c=new PerformanceObserver(r);try{c.observe({entryTypes:["paint"]})}catch(v){}u=new PerformanceObserver(i);try{u.observe({entryTypes:["largest-contentful-paint"]})}catch(v){}s=new PerformanceObserver(o);try{s.observe({type:"layout-shift",buffered:!0})}catch(v){}}if("addEventListener"in document){var g=!1,h=["click","keydown","mousedown","pointerdown","touchstart"];h.forEach(function(t){document.addEventListener(t,a,!1)})}l(f)}},{}],6:[function(t,e,n){function r(t,e){if(!i)return!1;if(t!==i)return!1;if(!e)return!0;if(!o)return!1;for(var n=o.split("."),r=e.split("."),a=0;a<r.length;a++)if(r[a]!==n[a])return!1;return!0}var i=null,o=null,a=/Version\/(\S+)\s+Safari/;if(navigator.userAgent){var f=navigator.userAgent,c=f.match(a);c&&f.indexOf("Chrome")===-1&&f.indexOf("Chromium")===-1&&(i="Safari",o=c[1])}e.exports={agent:i,version:o,match:r}},{}],7:[function(t,e,n){function r(t){function e(){t(a&&document[a]?document[a]:document[i]?"hidden":"visible")}"addEventListener"in document&&o&&document.addEventListener(o,e,!1)}e.exports=r;var i,o,a;"undefined"!=typeof document.hidden?(i="hidden",o="visibilitychange",a="visibilityState"):"undefined"!=typeof document.msHidden?(i="msHidden",o="msvisibilitychange"):"undefined"!=typeof document.webkitHidden&&(i="webkitHidden",o="webkitvisibilitychange",a="webkitVisibilityState")},{}],8:[function(t,e,n){function r(t,e){var n=[],r="",o=0;for(r in t)i.call(t,r)&&(n[o]=e(r,t[r]),o+=1);return n}var i=Object.prototype.hasOwnProperty;e.exports=r},{}],9:[function(t,e,n){function r(t,e,n){e||(e=0),"undefined"==typeof n&&(n=t?t.length:0);for(var r=-1,i=n-e||0,o=Array(i<0?0:i);++r<i;)o[r]=t[e+r];return o}e.exports=r},{}],10:[function(t,e,n){e.exports={exists:"undefined"!=typeof window.performance&&window.performance.timing&&"undefined"!=typeof window.performance.timing.navigationStart}},{}],ee:[function(t,e,n){function r(){}function i(t){function e(t){return t&&t instanceof r?t:t?u(t,c,a):a()}function n(n,r,i,o,a){if(a!==!1&&(a=!0),!l.aborted||o){t&&a&&t(n,r,i);for(var f=e(i),c=v(n),u=c.length,s=0;s<u;s++)c[s].apply(f,r);var p=d[w[n]];return p&&p.push([b,n,r,f]),f}}function o(t,e){y[t]=v(t).concat(e)}function m(t,e){var n=y[t];if(n)for(var r=0;r<n.length;r++)n[r]===e&&n.splice(r,1)}function v(t){return y[t]||[]}function g(t){return p[t]=p[t]||i(n)}function h(t,e){l.aborted||s(t,function(t,n){e=e||"feature",w[n]=e,e in d||(d[e]=[])})}var y={},w={},b={on:o,addEventListener:o,removeEventListener:m,emit:n,get:g,listeners:v,context:e,buffer:h,abort:f,aborted:!1};return b}function o(t){return u(t,c,a)}function a(){return new r}function f(){(d.api||d.feature)&&(l.aborted=!0,d=l.backlog={})}var c="nr@context",u=t("gos"),s=t(8),d={},p={},l=e.exports=i();e.exports.getOrSetContext=o,l.backlog=d},{}],gos:[function(t,e,n){function r(t,e,n){if(i.call(t,e))return t[e];var r=n();if(Object.defineProperty&&Object.keys)try{return Object.defineProperty(t,e,{value:r,writable:!0,enumerable:!1}),r}catch(o){}return t[e]=r,r}var i=Object.prototype.hasOwnProperty;e.exports=r},{}],handle:[function(t,e,n){function r(t,e,n,r){i.buffer([t],r),i.emit(t,e,n)}var i=t("ee").get("handle");e.exports=r,r.ee=i},{}],id:[function(t,e,n){function r(t){var e=typeof t;return!t||"object"!==e&&"function"!==e?-1:t===window?0:a(t,o,function(){return i++})}var i=1,o="nr@id",a=t("gos");e.exports=r},{}],loader:[function(t,e,n){function r(){if(!R++){var t=M.info=NREUM.info,e=v.getElementsByTagName("script")[0];if(setTimeout(u.abort,3e4),!(t&&t.licenseKey&&t.applicationID&&e))return u.abort();c(E,function(e,n){t[e]||(t[e]=n)});var n=a();f("mark",["onload",n+M.offset],null,"api"),f("timing",["load",n]);var r=v.createElement("script");0===t.agent.indexOf("http://")||0===t.agent.indexOf("https://")?r.src=t.agent:r.src=l+"://"+t.agent,e.parentNode.insertBefore(r,e)}}function i(){"complete"===v.readyState&&o()}function o(){f("mark",["domContent",a()+M.offset],null,"api")}var a=t(3),f=t("handle"),c=t(8),u=t("ee"),s=t(6),d=t(4),p=t(2),l=p.getConfiguration("ssl")===!1?"http":"https",m=window,v=m.document,g="addEventListener",h="attachEvent",y=m.XMLHttpRequest,w=y&&y.prototype,b=!d(m.location);NREUM.o={ST:setTimeout,SI:m.setImmediate,CT:clearTimeout,XHR:y,REQ:m.Request,EV:m.Event,PR:m.Promise,MO:m.MutationObserver};var x=""+location,E={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net",agent:"js-agent.newrelic.com/nr-1209.min.js"},O=y&&w&&w[g]&&!/CriOS/.test(navigator.userAgent),M=e.exports={offset:a.getLastTimestamp(),now:a,origin:x,features:{},xhrWrappable:O,userAgent:s,disabled:b};if(!b){t(1),t(5),v[g]?(v[g]("DOMContentLoaded",o,!1),m[g]("load",r,!1)):(v[h]("onreadystatechange",i),m[h]("onload",r)),f("mark",["firstbyte",a.getLastTimestamp()],null,"api");var R=0}},{}],"wrap-function":[function(t,e,n){function r(t,e){function n(e,n,r,c,u){function nrWrapper(){var o,a,s,p;try{a=this,o=d(arguments),s="function"==typeof r?r(o,a):r||{}}catch(l){i([l,"",[o,a,c],s],t)}f(n+"start",[o,a,c],s,u);try{return p=e.apply(a,o)}catch(m){throw f(n+"err",[o,a,m],s,u),m}finally{f(n+"end",[o,a,p],s,u)}}return a(e)?e:(n||(n=""),nrWrapper[p]=e,o(e,nrWrapper,t),nrWrapper)}function r(t,e,r,i,o){r||(r="");var f,c,u,s="-"===r.charAt(0);for(u=0;u<e.length;u++)c=e[u],f=t[c],a(f)||(t[c]=n(f,s?c+r:r,i,c,o))}function f(n,r,o,a){if(!m||e){var f=m;m=!0;try{t.emit(n,r,o,e,a)}catch(c){i([c,n,r,o],t)}m=f}}return t||(t=s),n.inPlace=r,n.flag=p,n}function i(t,e){e||(e=s);try{e.emit("internal-error",t)}catch(n){}}function o(t,e,n){if(Object.defineProperty&&Object.keys)try{var r=Object.keys(t);return r.forEach(function(n){Object.defineProperty(e,n,{get:function(){return t[n]},set:function(e){return t[n]=e,e}})}),e}catch(o){i([o],n)}for(var a in t)l.call(t,a)&&(e[a]=t[a]);return e}function a(t){return!(t&&t instanceof Function&&t.apply&&!t[p])}function f(t,e){var n=e(t);return n[p]=t,o(t,n,s),n}function c(t,e,n){var r=t[e];t[e]=f(r,n)}function u(){for(var t=arguments.length,e=new Array(t),n=0;n<t;++n)e[n]=arguments[n];return e}var s=t("ee"),d=t(9),p="nr@original",l=Object.prototype.hasOwnProperty,m=!1;e.exports=r,e.exports.wrapFunction=f,e.exports.wrapInPlace=c,e.exports.argsToArray=u},{}]},{},["loader"]);</script>
		
		<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
		<link rel="preconnect" href="https://static.nd.edu/" crossorigin>
		<link rel="preconnect" href="https://emergency.nd.edu/">
		<link rel="preconnect" href="https://ajax.googleapis.com/">
		<link rel="preconnect" href="https://fonts.googleapis.com/">
		<link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin>


  		<link rel="shortcut icon" type="image/x-icon" href="https://onmessage.nd.edu/assets/188821/fullsize/athletics_monogram1.jpg">

 		<link href="https://fonts.googleapis.com/css?family=Inconsolata" rel="stylesheet">
  		<link rel="stylesheet" type="text/css" href="https://mmorri22.github.io/index/assets/css/common.css">
  		<link rel="stylesheet" type="text/css" href="https://sp21.datastructur.es/assets/css/font-awesome.min.css">
  		<link rel="stylesheet" type="text/css" href="https://sp21.datastructur.es/assets/css/sunburst.css">

  		<script src="https://sp21.datastructur.es/assets/js/jquery.min.js" type="text/javascript"></script>
  		<script src="https://sp21.datastructur.es/assets/js/script.js" type="text/javascript"></script>
  		<script src="https://sp21.datastructur.es/assets/js/cheet.min.js" type="text/javascript"></script>
  
        <link rel="stylesheet" type="text/css" href="https://sp21.datastructur.es/assets/css/index.css">
        <link rel="stylesheet" type="text/css" href="https://sp21.datastructur.es/assets/css/fullcalendar.min.css">
        <link rel="stylesheet" type="text/css" href="https://sp21.datastructur.es/assets/css/calendar.css">
        <link rel="stylesheet" href="https://unpkg.com/tippy.js@3/dist/themes/light.css">
        <script src="/assets/js/moment.min.js"></script>
        <script src="/assets/js/fullcalendar.min.js"></script>
        <script src="https://unpkg.com/tippy.js@3/dist/tippy.all.min.js"></script>

	</head>
    
<body id="athletics-branding" class="athletics-branding athletics-branding page-default nav-top-false " vocab="https://schema.org/">

<!-- Skip links -->
<nav class="skip-links" aria-label="Skip links">
  <ul>
    <li><a href="#content" accesskey="C" title="Skip to content = C">Skip To Content</a></li>
    <li><a href="#nav" accesskey="S" title="Skip to navigation = S">Skip To Navigation</a></li>
    <li><a href="#search-input-nav-top">Skip To Search</a></li>
  </ul>
</nav>

<!-- Mobile Drawer -->
<div class="nav-mobile" id="nav-mobile"></div>

<div class="wrapper" id="wrapper">

  <!-- Site Header -->
  <header id="header" class="site-header">
    <p class="mark-header"><a href="https://www.nd.edu/">University of Notre Dame</a></p>
    <div class="site-title-group has-tagline">
      
      <p id="site-title" class="site-title"><a href="/" accesskey="1" title="Homepage shortcut key = 1">On Message</a></p>
      
      <p class="site-tagline">Elements of the Notre Dame Brand</p>
    </div>

    <!-- Header Search/Nav  -->
    <div class="nav-header">
      <div class="nav-search-wrapper">
        <form method="get" action="/search/" id="search-nav-top" class="search-form" role="search" aria-label="Site search">
          <input type="hidden" name="as_sitesearch" value="onmessage.nd.edu">
          <input type="hidden" name="entqr" value="3">
          <input type="search" name="q" class="search-input" id="search-input-nav-top" placeholder="Search this site" title="type your search term" aria-label="Site Search input">
          <button class="search-button" type="submit" aria-label="Search"><svg class="icon" data-icon="search" width="16" height="16"><use xlink:href="#icon-search"></use></svg></button>
        </form>
      </div>
    </div>

    <!-- Mobile Navbar -->
    <div class="nav-mobile-util">
      <ul class="no-bullets">
        <li><a href="/"><svg class="icon" data-icon="home" width="16" height="16"><use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#icon-home"></use></svg> Home</a></li>
        <li><button class="btn-search search-toggle"><svg class="icon" data-icon="search" width="16" height="16"><use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="#icon-search"></use></svg> Search</button>
        <li>
          <a href="#nav" class="nav-menu nav-skip">
          <svg version="1.1" class="icon" xmlns="http://www.w3.org/2000/svg"  width="16" height="16" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 20 20" xml:space="preserve">
            <line class="ni ni1" stroke-width="2" stroke-linecap="square" stroke-miterlimit="10" x1="0.98" y1="2" x2="18.94" y2="2"/>
            <line class="ni ni2" stroke-width="2" stroke-linecap="square" stroke-miterlimit="10" x1="0.98" y1="8.69" x2="18.94" y2="8.69"/>
          </svg>
          <span class="ni ni3">Menu</span>
        </a>
        </li>
      </ul>
      <div class="nav-search-wrapper">
        <form method="get" action="/search/" id="search-navbar-mobile" class="search-form" role="search" aria-label="Site search">
          <input type="hidden" name="as_sitesearch" value="onmessage.nd.edu">
          <input type="hidden" name="entqr" value="3">
          <input type="search" name="q" class="search-input" id="search-input-navbar-mobile" placeholder="Search this site" title="type your search term" aria-label="Site Search input">
          <button class="search-button" type="submit" aria-label="Search"><svg class="icon" data-icon="search" width="16" height="16"><use xlink:href="#icon-search"></use></svg></button>
          <button class="search-close search-toggle" aria-label="Close Search"><svg class="icon" data-icon="close" width="16" height="16"><use xlink:href="#icon-close"></use></svg></button>
        </form>
      </div>
    </div>
  </header>

  <!-- Site Content -->
  <div id="content" class="site-content">

  <div class="page-header"></div>
  <main class="page-main">
    <ol class="breadcrumbs"><li><a href="/">Home</a> &rsaquo; </li><li>Athletics Branding</li></ol>
    <h1 class="page-title">Athletics Branding</h1>
    <div class="grid grid-md-3">
      <div class="page-primary span-md-2">
        <p>Athletics at the University of Notre Dame qualifies as one of the most recognizable, popular and powerful brands found anywhere in sports. To protect and improve the University’s athletics brand equity, it is important that all those who communicate on behalf of Notre Dame do so in consistently strong manners across all platforms.</p>
<p>This document provides detailed information required to ensure the Notre Dame athletics brand—including official <a href="/athletics-branding/colors/">colors</a>, <a href="/athletics-branding/logos/">marks</a> and <a href="/athletics-branding/typography/">typography</a>—is presented appropriately while utilizing any and all communication channels.</p>
<p><a class="btn btn-cta" href="/assets/192682/brand_guidelines_v3_1.pdf"><span class="icon" data-icon="file-pdf-o"></span> University of Notre Dame Athletics Brand Standards</a></p>
<hr>
<p class="image-right"><img alt="Athletics Monogram 1" src="/assets/188821/fullsize/athletics_monogram1.jpg" title="Athletics Monogram 1"></p>

<h2>Primary Brand Assets Overview</h2>

<p>The <a href="/athletics-branding/logos/monogram/">Notre Dame monogram</a> and the primary color palette of blue and gold are the primary identifiers for Notre Dame. They should always be used to represent the university in the most visible and high profile brand touchpoints. The Notre Dame monogram and the primary color palette of blue and gold represent the tradition, legacy, and excellence of our athletic program. Use the monogram and our colors to communicate the passion of our community – one bridled in faith and in pursuit of the highest standards.</p>

<ul>
<li>Official team uniforms</li>
<li>Athletic playing fields, like the basketball court or hockey rink</li>
<li>Formal department communication</li>
<li>Header of a website</li>
<li>Graphic elements in broadcasts</li>
</ul>

<h2>Spirit Branding Assets Overview</h2>

<p class="image-default"><img alt="Spirit Marks Examples 1" src="/assets/189368/580x/spirit_marks_examples_1.jpg" title="Spirit Marks Examples 1"></p>

<p>The <a href="/athletics-branding/logos/leprechaun/">leprechaun</a>, <a href="/athletics-branding/wordmarks/">wordmark</a>, and the <a href="/athletics-branding/colors/">spirit palette</a> of blue, gold and green represent the fighting spirit of Notre Dame. Use the mark and colors to communicate our determination, grit and underdog mentality. These brand assets serve as inspiring visual elements for Notre Dame in competitive scenarios and should be used to instill passion and a competitive spirit among our audiences. The green shamrock is a secondary spirit mark representing the Irish heritage of Notre Dame. While the shamrock is not our primary identifier, it allows us to reference a part of our history (both the shamrock and its green color are clear references to Irish heritage). Therefore, it should never be used as a standalone identifier for Notre Dame and should be used sparingly.</p>
      </div>
      <div class="page-aside"><h3>NOTE:</h3>
<p>The assets featured in this section are to be used solely by the University of Notre Dame Athletics Department. They are not intended to be used in academic or administrative communications.</p>
<p>In the rare instance that an Athletics asset could be considered for use by an academic or administrative entity, that entity must first request use of the branding element(s) by <a href="mailto:FIM@nd.edu">contacting Fighting Irish Media</a>.</p></div>
    </div>
  </main>
  <div class="page-sidebar">
    <nav id="nav" class="nav-site nav-full" role="navigation" aria-label="Primary navigation"><ul class="nav-level-1 depth_1"><li class="first nav-72888"><a href="/">Home</a></li><li class="li-has-children nav-72890"><a href="/university-branding/">University Branding</a></li><li class="li-has-children nav-72908"><a href="/academic-branding/">Academic Branding</a></li><li class="li-has-children nav-72919"><a href="/administrative-branding/">Administrative Branding</a></li><li class="active li-has-children nav-72923"><a href="/athletics-branding/" aria-current="page" class="current current-last">Athletics Branding</a><ul class="nav-level-2 depth_2"><li class="first nav-72924"><a href="/athletics-branding/colors/">Colors</a></li><li class="li-has-children nav-72925"><a href="/athletics-branding/logos/">Logos &amp; Spirit Marks</a></li><li class="nav-72930"><a href="/athletics-branding/typography/">Typography</a></li><li class="li-has-children nav-72931"><a href="/athletics-branding/wordmarks/">Wordmarks</a></li><li class="last protected nav-73344"><a href="/athletics-branding/athletics-downloads/">Athletics Downloads</a></li></ul></li><li class="protected nav-72932"><a href="/downloads/">Downloads</a></li><li class="li-has-children nav-72933"><a href="/policies-and-guidelines/">Policies and Guidelines</a></li><li class="last nav-72938"><a href="/campus-communicators-directory/">Campus Communicators Directory</a></li></ul></nav>
  <nav class="nav-section nav-site" role="navigation" aria-label="Section navigation">
    <div id="nav_sub"><ul class="nav-level-1 depth_2"><li class="first nav_sub-72924"><a href="/athletics-branding/colors/">Colors</a></li><li class="li-has-children nav_sub-72925"><a href="/athletics-branding/logos/">Logos &amp; Spirit Marks</a></li><li class="nav_sub-72930"><a href="/athletics-branding/typography/">Typography</a></li><li class="li-has-children nav_sub-72931"><a href="/athletics-branding/wordmarks/">Wordmarks</a></li><li class="last protected nav_sub-73344"><a href="/athletics-branding/athletics-downloads/">Athletics Downloads</a></li></ul></div>
  </nav>

  </div>
  </div>

  <!-- Site Footer -->
  <footer id="footer" class="site-footer">
    <div class="footer-org" typeof="Organization" resource="#siteorg">
      <meta property="parentOrganization" resource="#parentorg" content="University of Notre Dame">
      <ul class="footer-breadcrumbs">
        <li><a href="https://opac.nd.edu/">Office of Public Affairs and Communications</a></li>
      </ul>
      <p><a href="/" class="site-link" property="url"><span property="name">On Message</span></a></p>
      <div class="footer-contacts">
        <p class="contact-info">
          <span class="address" property="address" typeof="PostalAddress">
            <span property="streetAddress">500 Grace Hall</span><br> 
            <span property="addressLocality">Notre Dame</span>, <span property="addressRegion">IN</span> <span property="postalCode">46556</span> <span property="addressCountry">USA</span>
          </span>
          
          
          
        </p>
        <nav class="social" aria-label="Social media navigation" vocab="">
          <ul>
            
            
            
            
            
          </ul>
        </nav>
      </div>
      <div property="logo" typeof="ImageObject"><meta property="url" content="https://static.nd.edu/images/webclips/default/webclip-60.png"></div>
      <p class="copyright"><a href="https://www.nd.edu/copyright/">&copy; 2021</a> <a href="https://www.nd.edu">University of Notre Dame</a></p>
    </div>
    <div class="footer-parent" property="parentOrganization" typeof="CollegeOrUniversity" resource="#parentorg">
      <meta property="name" content="University of Notre Dame">
      <a href="https://www.nd.edu/" class="mark-footer" property="url logo" typeof="ImageObject" aria-label="University of Notre Dame">
        <img src="https://static.nd.edu/images/marks/gray/ndmark.svg" width="250" height="60" loading="lazy" alt="University of Notre Dame" property="url">
      </a>
      <div class="footer-parent-links">
        <nav aria-label="Footer links navigation">
          <ul class="footer-links">
            <li><a href="https://search.nd.edu/">Search</a></li>
            <li><a href="https://mobile.nd.edu/">Mobile App</a></li>
            <li><a href="https://news.nd.edu/">News</a></li>
            <li><a href="https://events.nd.edu/">Events</a></li>
            <li><a href="https://www.nd.edu/visit/">Visit</a></li>
            <li><a href="https://www.nd.edu/about/accessibility/">Accessibility</a></li>
          </ul>
        </nav>
        <nav class="social" aria-label="Social media navigation" vocab="">
          <ul>
            <li><a class="soc-facebook" href="https://www.facebook.com/notredame/" rel="noopener"><svg class="icon" data-icon="facebook" width="16" height="16"><use xlink:href="#icon-facebook"></use></svg> Facebook</a></li>
            <li><a class="soc-twitter" href="https://twitter.com/NotreDame/" rel="noopener"><svg class="icon" data-icon="twitter" width="16" height="16"><use xlink:href="#icon-twitter"></use></svg> Twitter</a></li>
            <li><a class="soc-instagram" href="https://www.instagram.com/notredame/" rel="noopener"><svg class="icon" data-icon="instagram" width="16" height="16"><use xlink:href="#icon-instagram"></use></svg> Instagram</a></li>
            <li><a class="soc-youtube" href="https://www.youtube.com/user/NDdotEDU" rel="noopener"><svg class="icon" data-icon="youtube" width="16" height="16"><use xlink:href="#icon-youtube"></use></svg> YouTube</a></li>
            <li><a class="soc-linkedin" href="https://www.linkedin.com/school/university-of-notre-dame/" rel="noopener"><svg class="icon" data-icon="linkedin" width="16" height="16"><use xlink:href="#icon-linkedin"></use></svg> LinkedIn</a></li>
          </ul>
        </nav>
      </div>
    </div>
  </footer>
</div><!-- .wrapper -->
<nav id="navbar" class="navbar nav-top" role="navigation"></nav>
<script src="/javascripts/themes/ndt/v3/ndt.js"></script>
<script src="/javascripts/jquery.1600091309.js"></script>
<script src="/javascripts/site.1600091309.js"></script>

</body>
</html>
    
</html>