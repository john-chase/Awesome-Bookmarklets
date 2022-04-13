# List of Awesome Bookmarklets :rocket: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Priyank-Vaghela/Awesome-Bookmarklets)

> How to use? 
1. Copy the code.
2. From the Bookmark bar _**Right click, add page & Paste the code.**_ Add title (Optional)
3. Done! :tada:  

- ## Instant Web Proxy (Google Translate)
```javascript
javascript:void(open('https://translate.google.co.in/translate?hl=en&sl=sq&tl=en&u='+location.href));
```

- ## 1-Click Video Downloader
```javascript
javascript:void(open('https://tbvd.herokuapp.com/redirect?url='+encodeURIComponent(location.href)));
```

- ## 1-Click Audio Downloader
```javascript
javascript:void(open('https://tbvd.herokuapp.com/video?url='+encodeURIComponent(location.href)+'&audio=on'));
```

- ## 1-Click PDF Downloader
```javascript
javascript:void(open('https://v2.convertapi.com/web/to/pdf?download=attachment&secret=5LIWRmsz4uKJCITZ&url='+encodeURIComponent(location.href)));
```

- ## 1-Click Photo Downloader
```javascript
javascript:void(open('https://v2.convertapi.com/url/to/jpg?download=attachment&secret=5LIWRmsz4uKJCITZ&url='+encodeURIComponent(location.href)));
```
- ## 1-Click Article Reader Mode
```javascript
javascript:(function(){readConvertLinksToFootnotes=false;readStyle='style-apertura';readSize='size-large';readMargin='margin-wide';_readability_script=document.createElement('script');_readability_script.type='text/javascript';_readability_script.src='https://ejucovy.github.io/readability/js/readability.js?x='+(Math.random());document.documentElement.appendChild(_readability_script);_readability_css=document.createElement('link');_readability_css.rel='stylesheet';_readability_css.href='https://ejucovy.github.io/readability/css/readability.css?1';_readability_css.type='text/css';_readability_css.media='all';document.documentElement.appendChild(_readability_css);_readability_print_css=document.createElement('link');_readability_print_css.rel='stylesheet';_readability_print_css.href='https://ejucovy.github.io/readability/css/readability-print.css';_readability_print_css.media='print';_readability_print_css.type='text/css';document.getElementsByTagName('head')[0].appendChild(_readability_print_css);})();
```

# **Website**
- ## Website Analyzer (Traffic Statistics & Market Intelligence)
```javascript
javascript:void(open('https://www.similarweb.com/website/'+encodeURIComponent(location.href)));
```

- ## Website Quick Editor
```javascript
javascript:document.body.contentEditable = 'true'; document.designMode='on'; void 0
```

- ## Website Time Machine (Wayback Machine)
```javascript
javascript:void(open('https://web.archive.org/web/*/'+decodeURIComponent(location.href)));
```

- ## Website Time Machine #2 (WebCite)
```javascript
javascript:void(open('http://www.webcitation.org/query?url='+decodeURIComponent(location.href)));
```

- ## View Cached Website
```javascript
javascript:void(open('cache:'+decodeURIComponent(location.href)));
```

- ## Similar Website Finder
```javascript
javascript:void(open('https://www.google.com/search?q=related:'+location.href));
```

- ## Website Whois Lookup
```javascript
javascript:void(open('http://whois.domaintools.com/'+encodeURIComponent(location.href)));
```

- ## Website Source Code Viewer
```javascript
javascript:void(open('view-source:'+encodeURIComponent(location.href)));
```

- ## Website Speed Test
```javascript
javascript:void(open('https://developers.google.com/speed/pagespeed/insights/?url='+encodeURIComponent(location.href)));
```

- ## Website Build with (Websites are built with what)
```javascript
javascript:void(open('https://builtwith.com/?'+encodeURIComponent(location.href)));
```

- ## Website Auto CSS Selector Generator
```javascript
javascript:(function(){var s=document.createElement('div');s.innerHTML='Loading...';s.style.color='black';s.style.padding='20px';s.style.position='fixed';s.style.zIndex='9999';s.style.fontSize='3.0em';s.style.border='2px solid black';s.style.right='40px';s.style.top='40px';s.setAttribute('class','selector_gadget_loading');s.style.background='white';document.body.appendChild(s);s=document.createElement('script');s.setAttribute('type','text/javascript');s.setAttribute('src','https://dv0akt2986vzh.cloudfront.net/unstable/lib/selectorgadget.js');document.body.appendChild(s);})();
```

- ## Responsive Website Tester
```javascript
javascript:void(open('http://quirktools.com/screenfly/#u='+location.href+'&w=640&h=480&a=4&s=1'));
```

# **Misc.**
- ## Add to Feedly
```javascript
javascript:void(open('https://feedly.com/i/subscription/feed/'+encodeURIComponent(location.href)));
```

- ## Add to Pocket
```javascript
javascript:(function(){var e=function(t,n,r,i,s){var o=[3139821,1691404,3942330,4280155,4867141,1525736,3824752,3937958,1747379,3644113];var i=i||0,u=0,n=n||[],r=r||0,s=s||0;var a={'a':97,'b':98,'c':99,'d':100,'e':101,'f':102,'g':103,'h':104,'i':105,'j':106,'k':107,'l':108,'m':109,'n':110,'o':111,'p':112,'q':113,'r':114,'s':115,'t':116,'u':117,'v':118,'w':119,'x':120,'y':121,'z':122,'A':65,'B':66,'C':67,'D':68,'E':69,'F':70,'G':71,'H':72,'I':73,'J':74,'K':75,'L':76,'M':77,'N':78,'O':79,'P':80,'Q':81,'R':82,'S':83,'T':84,'U':85,'V':86,'W':87,'X':88,'Y':89,'Z':90,'0':48,'1':49,'2':50,'3':51,'4':52,'5':53,'6':54,'7':55,'8':56,'9':57,'\/':47,':':58,'?':63,'=':61,'-':45,'_':95,'&':38,'$':36,'!':33,'.':46};if(!s||s==0){t=o[0]+t}for(var f=0;f<t.length;f++){var l=function(e,t){return a[e[t]]?a[e[t]]:e.charCodeAt(t)}(t,f);if(!l*1)l=3;var c=l*(o[i]+l*o[u%o.length]);n[r]=(n[r]?n[r]+c:c)+s+u;var p=c%(50*1);if(n[p]){var d=n[r];n[r]=n[p];n[p]=d}u+=c;r=r==50?0:r+1;i=i==o.length-1?0:i+1}if(s==282){var v='';for(var f=0;f<n.length;f++){v+=String.fromCharCode(n[f]%(25*1)+97)}o=function(){};return v+'b100288614'}else{return e(u+'',n,r,i,s+1)}};var t=document,n=t.location.href,r=t.title;var i=e(n);var s=t.createElement('script');s.type='text/javascript';s.src='https://getpocket.com/b/r4.js?h='+i+'&u='+encodeURIComponent(n)+'&t='+encodeURIComponent(r);e=i=function(){};var o=t.getElementsByTagName('head')[0]||t.documentElement;o.appendChild(s)})()
```

# Bonus :sparkles:
- ## Instant Notepad
```
data:text/html, <html contenteditable>
```

- ## Instant Notepad (Dark)
```
data:text/html;charset=utf-8, <title>Notepad (Nightmode)</title><body contenteditable style="font-family: DejaVu;font-weight:bold;background:%231E1E1E;color:%23FFFFFF;font-size:1rem;line-height:1.4;max-width:80rem;margin:0 auto;padding:2rem;" spellcheck="false">
```

- ## WordLookup Instant Dictionary
```javascript
javascript:(()=>{function e(){this.style.backgroundColor="yellow"}function t(){this.style.backgroundColor="transparent",this.classList.remove("def-tooltip")}function n(e){e.target;const t=document.getElementById("def-help"),n=document.getElementsByClassName("def-div")[0];t.innerText="",console.log(t),(async e=>{e=(e=e.replace(/[\u2000-\u206F\u2E00-\u2E7F!"#$%&()*+,\.\/:;<=>?@\[\]^_`{|}~]/g,"")).replace(/'(.*?)'/g,"$1"),console.log(e);let t=await fetch(`https://api.dictionaryapi.dev/api/v2/entries/en/${e}`);const n=`Sorry, we could not find "${e}" in the dictionary, or the service is down. You can try the search again at later time or head to the <a href="https://www.dictionary.com/" target="_blank">web</a> instead.`;if(t.status>=200&&t.status<=299){let e=await t.json(),i="";if(e[0]){console.log(e[0]);const t=e[0].word,n=e[0].meanings[0].partOfSpeech?e[0].meanings[0].partOfSpeech:"",o=e[0].phonetics.length&&e[0].phonetics[0].text?e[0].phonetics[0].text:"";let a="";o.length&&(i=` (${o})`),e[0].phonetics.length&&(e[0].phonetics.forEach((e=>{if(void 0!==e.audio&&e.audio.length)return a=`<a href="${e.audio}" target="_blank"><svg width="25px" height="20px" viewBox="-1 -14 40 40" xmlns="http://www.w3.org/2000/svg"><title>file_type_audio</title><path d="M17.229,4a.9.9,0,0,0-.569.232l-7.6,6.32a1.158,1.158,0,0,1-.955.328H3.208A1.2,1.2,0,0,0,2,12.088v7.826A1.2,1.2,0,0,0,3.208,21.12H8.1a1.158,1.158,0,0,1,.955.328l7.6,6.32c.521.433,1.081.224,1.081-.289V4.522A.494.494,0,0,0,17.229,4ZM27,6.3,25.209,8.093a14.708,14.708,0,0,1,0,15.844l1.785,1.776A17.19,17.19,0,0,0,27,6.3Zm-4.333,4.323L20.905,12.4a6.035,6.035,0,0,1,0,7.237l1.756,1.756a8.554,8.554,0,0,0,.01-10.769Z" style="fill:#00007f"/></svg></a>`})),console.log(a));const d=e[0].meanings[0].definitions[0].definition?e[0].meanings[0].definitions[0].definition:"";return`${t.toUpperCase()} ${a}- ${n}${i}: ${d}`}return n}return n})(e.target.innerText).then((e=>{t.innerHTML=e,e.includes("Sorry, we could not find ")?n.classList.add("def-tooltip-not-found"):n.classList.remove("def-tooltip-not-found")}))}(()=>{document.head.appendChild(document.createElement("style")).innerText="\n/*GENERAL*/ .p { border: 1px solid dodgerblue; border-radius: .5rem; padding: .5rem; margin: 1rem 5rem; font-size: 15px; line-height: 21px; } .hidden { display: none; } /*DEFINITION GROUP*/ .def-div { background-color: dodgerblue; position: fixed; z-index: 99999999; min-width: 100%; height: 32px; top: 0; text-align: left; line-height: 1rem; } .def-span { padding: 0 0 12px 4px; text-align: center; color: blue; font-weight: bold; font-style: italic; margin: 0.5rem; } .def-help { font-style: italic; margin: 0.5rem; } .def-help a:link { color: blue; } .def-help a:visited { color: purple; } .def-help a:hover { color: orange; } .def-help a:active { color: white; } .def-audio { width: 32px; height: 32px; margin-bottom: -.3rem; padding-left: 4px; display: inline-block; background-image: url(\"data:image/svg+xml,%3Csvg width='25px' height='20px' viewBox='-1 -16 40 44' xmlns='http://www.w3.org/2000/svg'%3E%3Ctitle%3Efile_type_audio%3C/title%3E%3Cpath d='M17.229,4a.9.9,0,0,0-.569.232l-7.6,6.32a1.158,1.158,0,0,1-.955.328H3.208A1.2,1.2,0,0,0,2,12.088v7.826A1.2,1.2,0,0,0,3.208,21.12H8.1a1.158,1.158,0,0,1,.955.328l7.6,6.32c.521.433,1.081.224,1.081-.289V4.522A.494.494,0,0,0,17.229,4ZM27,6.3,25.209,8.093a14.708,14.708,0,0,1,0,15.844l1.785,1.776A17.19,17.19,0,0,0,27,6.3Zm-4.333,4.323L20.905,12.4a6.035,6.035,0,0,1,0,7.237l1.756,1.756a8.554,8.554,0,0,0,.01-10.769Z' style='fill:%23000000'/%3E%3C/svg%3E\"); } /*TOOLTIPS*/ .def-tooltip { content: (data-tooltip); position: relative; -webkit-transition: all 0.3s ease; -o-transition: all 0.3s ease; transition: all 0.3s ease; text-decoration: none; cursor: -webkit-grabbing; cursor: grabbing; z-index: 999999; -webkit-box-sizing: border-box; box-sizing: border-box; } .def-tooltip-not-found { color: white; font-weight: bold; background: red; } /*TOGGLE SWITCH*/ input[type=checkbox], .def-input { margin: 0; -webkit-appearance: none; -moz-appearance: none; appearance: none; padding: 0 0 0 30px; border-radius: 16px; background: -o-radial-gradient(circle 12px, white 100%, transparent calc(100% + 1px)) #ccc -16px; background: radial-gradient(circle 12px, white 100%, transparent calc(100% + 1px)) #ccc -16px; -webkit-transition: 0.3s ease-in-out; -o-transition: 0.3s ease-in-out; transition: 0.3s ease-in-out; position: inherit; height: 32px; width: 64px; top: 0; bottom: 0; -webkit-box-shadow: none; box-shadow: none; } .def-input::before { content: \"OFF\"; font: bold 12px/32px Verdana; color: white; text-shadow: 0 1px black; } .def-input:checked { padding: 0 0 0 8px; background-color: rgb(37, 151, 62); background-position: 16px; height: 32px; width: 64px; } .def-input:checked::before { content: \"ON\"; }\n    ";const i=document.getElementsByTagName("body")[0],o=document.createElement("div");o.classList.add("def-div"),i.insertBefore(o,i.firstChild);const a=document.createElement("label");o.appendChild(a);const d=document.createElement("span");d.classList.add("def-span"),d.innerText="Definitions",a.appendChild(d);const l=document.createElement("input");l.setAttribute("type","checkbox"),l.classList.add("def-input"),a.appendChild(l);const r=document.createElement("span");let s;r.setAttribute("id","def-help"),r.classList.add("hidden","def-help"),r.innerText="Hover over a word to highlight, then click/tap to show definition tooltip.",a.appendChild(r);let c=document.getElementsByTagName("p"),p=[];const h=e=>{let t=(e=e.replace("&nbsp;"," ")).split(" "),n="";return t.forEach((e=>{n+=`<span>${e}</span> `})),n};l.onchange=()=>{if(l.checked){r.classList.remove("hidden");for(let i=0;i<c.length;i++)if(null!=c[i]&&""!==c[i].innerText){c[i].classList.add("p"),p.push(c[i].innerHTML),c[i].innerHTML=h(c[i].innerText),s=c[i].getElementsByTagName("span");for(let i=0;i<s.length;i++)s[i].onmouseover=e,s[i].onmouseout=t,s[i].onclick=n}}else{r.classList.add("hidden"),r.innerText="Hover over a word to highlight, then click/tap to show definition tooltip.";for(let e=0;e<c.length;e++)null!=c[e]&&""!==c[e].innerText&&(c[e].classList.remove("p"),c[e].innerHTML=p[e])}}})()})();
```

## License
[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](//creativecommons.org/publicdomain/zero/1.0/)
