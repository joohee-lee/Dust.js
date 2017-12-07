# Dust.js
Dust is a Javascript templating engine. It inherits its look from the ctemplate family of languages, and is designed to run asynchronously on both the server and the browser.

# http://www.dustjs.com/


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
