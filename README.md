# Dust.js
Dust is a Javascript templating engine. It inherits its look from the ctemplate family of languages, and is designed to run asynchronously on both the server and the browser.

# http://www.dustjs.com/
# http://akdubya.github.io/dustjs/  


# Linkedin - Where we started
<img src="https://content.linkedin.com/content/dam/engineering/en-us/blog/migrated/pre-client.png">

# Linkedin - Client-side templates
<img src="https://content.linkedin.com/content/dam/engineering/en-us/blog/migrated/post-client.png">

# Leaving JSPs in the dust

## dust.js templates offer huge benefits on many fronts: 
- Caching: unlike server-side templates, client-side templates can be served via a CDN to reduce latency for your users and bandwidth and load for your servers. Moreover, the template files can be cached in the user's browser, so after the initial page load, the web server only needs to return the dynamic data as JSON, which is maximally efficient. 
- Performance: dust.js templates can be precompiled into highly performant JavaScript functions. 
- DRY: templates can be composed of partials, allowing reuse of mark-up and rendering logic, even across different tech stacks. 
- Decoupling: dust.js templates emphasize presentation rather than the application and business logic. 
- Cross-browser, cross-library: dust.js is compatible with all modern browsers and is JS library agnostic, working equally well with YUI and jQuery. It also escapes malicious template content by default, helping to avoid XSS attacks. 
- Server side support: if you have a client that can't execute JavaScript, such as a search engine crawler, a page must be rendered server side. Once written, the same dust.js template can be rendered not only in the browser, but also on the server using node.js or Rhino. 
- Progressive rendering: dust.js templates can render asynchronously and in parallel, so expensive operations can run in the background while the rest of the template is being rendered. When rendering server-side, we can also use the async support to early flush content in chunks so the user sees some content sooner. 
- Simple, powerful, open: the dust.js template syntax is both easy to learn and to extend. We have written custom dust helpers that allow us to perform formatting, i18n, and rendering logic in a clean way. 


# Embedded JavaScript Templates
1.underscore.js 
2.Jade 
3.haml-js 
4.jQote2 
5.doT 
6.Stencil 
7.Parrot 
8.Eco 
9.EJS 
10.jQuery templates 
11.node-asyncEJS 


# Logic-less Templates ( 자바스크립트 로직이 없는  logic-less의 mustache 계열)

1.mustache 
2.dust.js 
3.handlebars 
4.Google Closure Templates 
5.Nun 
6.Mu 
7.kite 

## 템플릿 엔진을 선택할때 고려해야할 요소
### LinkedIn에서 고민했던 요소

DRY: how DRY is the templating technology? is there support for code-reuse and partials?
2.i18n: is there support for translations and multiple languages?
3.Hot reload: are changes visible immediately or is there a compile/deploy cycle?
4.Performance: how long does it take to render in the browser and server?
5.Ramp-up time: how is the learning curve?
6.Ramped-up productivity: once you’ve ramped-up, how fast can you build things?
7.Server/client support: can the same template be rendered both client-side and server-side?
8.Community: is there an active community using this project? Can you google issues?
9.Library agnostic: are there dependencies on other JS libraries, such as jQuery or Mootools?
10.Testable: how hard is it to write unit and integration tests?
11.Debuggable: is it possible to step through the code while it’s running to track down errors?
12.Editor support: is there an editor with auto-complete, syntax highlighting, error checking, etc?
13.Maturity: is this a relatively stable project or still experimenting and churning?
14.Documentation: how is the documentation?
15.Code documentation: do the templates encourage/require documentation/comments? 


 


##  출처
> https://engineering.linkedin.com/frontend/leaving-jsps-dust-moving-linkedin-dustjs-client-side-templates
> https://engineering.linkedin.com/frontend/client-side-templating-throwdown-mustache-handlebars-dustjs-and-more
