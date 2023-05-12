<html dir="ltr" prefix="og: https://ogp.me/ns#" translate="no" class="js" style="" lang="zh-hans"><script type="text/javascript" async="" src="//crmemails.ogilvy.com/js/frs-next.js"></script><script src="moz-extension://81109b08-84f5-4d0d-a850-0b429a3bfb10/static/shadow.js"></script><head>
<script type="text/javascript">
    function getGeoCode(){
      var req = new XMLHttpRequest();
      req.open("GET", '/check-geo-country', false);
      req.send(null);
      var gcode = req.getResponseHeader("x-geo-country");
      return (gcode) ? gcode.toLowerCase() : "us";
    }
    var geo_country_code = getGeoCode();
    var geo_website_codes = {"af":"","ax":"","al":true,"dz":"","as":"","ad":"","ao":"","ai":"","ag":"","ar":"","am":"","aw":"","au":true,"at":true,"az":"","bs":"","bh":true,"bd":"","bb":"","by":"","be":true,"bz":"","bj":"","bm":"","bt":"","bo":true,"bq":"","ba":"","bw":"","bv":"","br":true,"io":"","bn":"","bg":"","bf":"","bi":"","cv":"","kh":"","cm":"","ca":true,"ky":"","cf":"","td":"","cl":"","cn":true,"cx":"","cc":"","co":"","km":"","cd":"","cg":"","ck":"","cr":"","hr":"","cu":"","cw":"","cy":"","cz":true,"dk":true,"dj":"","dm":"","do":true,"ec":"","eg":true,"sv":"","gq":"","er":"","ee":"","sz":"","et":"","fk":"","fo":"","fj":"","fi":"","fr":true,"gf":"","pf":"","tf":"","ga":"","gm":"","ge":"","de":true,"gh":"","gi":"","gr":true,"gl":"","gd":"","gp":"","gu":"","gt":true,"gg":"","gn":"","gw":"","gy":"","ht":"","hm":"","va":"","hn":"","hk":"","hu":true,"is":"","in":true,"id":"","ir":"","iq":"","ie":true,"im":"","il":"","it":true,"jm":"","jp":true,"je":"","jo":true,"kz":"","ke":true,"ki":"","kw":true,"kg":"","la":"","lv":true,"lb":true,"ls":"","lr":"","ly":"","li":"","lt":true,"lu":"","mo":"","mg":"","mw":"","my":"","mv":"","ml":"","mt":"","mh":"","mq":"","mr":"","mu":"","yt":"","mx":true,"fm":"","md":"","mc":"","mn":"","me":"","ms":"","ma":"","mz":"","mm":"","na":true,"nr":"","np":"","nl":true,"nc":"","nz":"","ni":true,"ne":"","ng":"","nu":"","nf":"","mk":"","mp":"","no":"","om":"","pk":"","pw":"","ps":"","pa":true,"pg":"","py":"","pe":"","ph":"","pn":"","pl":true,"pt":true,"pr":"","qa":true,"ro":"","ru":true,"rw":true,"re":"","bl":"","sh":"","kn":"","lc":"","mf":"","vc":"","ws":"","sm":"","st":"","sa":true,"sn":"","rs":true,"sc":"","sl":"","sg":true,"sx":"","sk":"","si":"","sb":"","so":"","za":true,"gs":"","kr":true,"ss":"","es":true,"lk":true,"sd":"","sr":"","sj":"","se":"","ch":true,"sy":"","tw":true,"tj":"","tz":"","th":"","tl":"","tg":"","tk":"","to":"","tt":true,"tn":true,"tr":true,"tm":"","tc":"","tv":"","ug":"","ua":"","ae":true,"gb":true,"us":true,"um":"","uy":true,"uz":"","vu":"","ve":"","vn":"","vg":"","vi":"","wf":"","eh":"","ye":"","zm":"","zw":""};
    var current_path = window.location.pathname;
    var path_array = current_path.split('/');
    var path_country = path_array[1];
    var visit_site = 'glb';
    if(path_country != "" && path_country == 'uk') {
      path_country = "gb";
    }
    if (path_country != "" && geo_website_codes.hasOwnProperty(path_country) && geo_website_codes[path_country]) {
      visit_site = path_country;
    }
</script>
<meta charset="utf-8"><script type="text/javascript">(window.NREUM||(NREUM={})).init={ajax:{deny_list:["bam.nr-data.net"]}};(window.NREUM||(NREUM={})).loader_config={licenseKey:"290a3572ee",applicationID:"213500175"};;(()=>{"use strict";var e,t,n={8768:(e,t,n)=>{n.d(t,{T:()=>r,p:()=>i});const r=/(iPad|iPhone|iPod)/g.test(navigator.userAgent),i=r&&Boolean("undefined"==typeof SharedWorker)},2919:(e,t,n)=>{n.d(t,{P_:()=>h,Mt:()=>p,C5:()=>c,DL:()=>w,OP:()=>N,lF:()=>C,Yu:()=>A,Dg:()=>v,CX:()=>u,GE:()=>y,sU:()=>I});var r={};n.r(r),n.d(r,{agent:()=>x,match:()=>k,version:()=>_});var i=n(6797),o=n(4286);const a={beacon:i.ce.beacon,errorBeacon:i.ce.errorBeacon,licenseKey:void 0,applicationID:void 0,sa:void 0,queueTime:void 0,applicationTime:void 0,ttGuid:void 0,user:void 0,account:void 0,product:void 0,extra:void 0,jsAttributes:{},userAttributes:void 0,atts:void 0,transactionName:void 0,tNamePlain:void 0},s={};function c(e){if(!e)throw new Error("All info objects require an agent identifier!");if(!s[e])throw new Error("Info for ".concat(e," was never set"));return s[e]}function u(e,t){if(!e)throw new Error("All info objects require an agent identifier!");s[e]=new o.I(t,a),(0,i.Qy)(e,s[e],"info")}var d=n(2797),f=n(2374);const l={allow_bfcache:!0,privacy:{cookies_enabled:!0},ajax:{deny_list:void 0,enabled:!0,harvestTimeSeconds:10},distributed_tracing:{enabled:void 0,exclude_newrelic_header:void 0,cors_use_newrelic_header:void 0,cors_use_tracecontext_headers:void 0,allowed_origins:void 0},session:{domain:void 0,expiresMs:d.oD,inactiveMs:d.Hb},ssl:void 0,obfuscate:void 0,jserrors:{enabled:!0,harvestTimeSeconds:10},metrics:{enabled:!0},page_action:{enabled:!0,harvestTimeSeconds:30},page_view_event:{enabled:!0},page_view_timing:{enabled:!0,harvestTimeSeconds:30,long_task:!1},session_trace:{enabled:!0,harvestTimeSeconds:10},spa:{enabled:!0,harvestTimeSeconds:10}},g={};function h(e){if(!e)throw new Error("All configuration objects require an agent identifier!");if(!g[e])throw new Error("Configuration for ".concat(e," was never set"));return g[e]}function v(e,t){if(!e)throw new Error("All configuration objects require an agent identifier!");g[e]=new o.I(t,l),(0,i.Qy)(e,g[e],"config")}function p(e,t){if(!e)throw new Error("All configuration objects require an agent identifier!");var n=h(e);if(n){for(var r=t.split("."),i=0;i<r.length-1;i++)if("object"!=typeof(n=n[r[i]]))return;n=n[r[r.length-1]]}return n}const m={accountID:void 0,trustKey:void 0,agentID:void 0,licenseKey:void 0,applicationID:void 0,xpid:void 0},b={};function w(e){if(!e)throw new Error("All loader-config objects require an agent identifier!");if(!b[e])throw new Error("LoaderConfig for ".concat(e," was never set"));return b[e]}function y(e,t){if(!e)throw new Error("All loader-config objects require an agent identifier!");b[e]=new o.I(t,m),(0,i.Qy)(e,b[e],"loader_config")}const A=(0,i.mF)().o;var x=null,_=null;const j=/Version\/(\S+)\s+Safari/;if(navigator.userAgent){var D=navigator.userAgent,E=D.match(j);E&&-1===D.indexOf("Chrome")&&-1===D.indexOf("Chromium")&&(x="Safari",_=E[1])}function k(e,t){if(!x)return!1;if(e!==x)return!1;if(!t)return!0;if(!_)return!1;for(var n=_.split("."),r=t.split("."),i=0;i<r.length;i++)if(r[i]!==n[i])return!1;return!0}var S=n(1651);const T={buildEnv:S.Re,bytesSent:{},queryBytesSent:{},customTransaction:void 0,disabled:!1,distMethod:S.gF,isolatedBacklog:!1,loaderType:void 0,maxBytes:3e4,offset:Math.floor(f._A?.performance?.timeOrigin||f._A?.performance?.timing?.navigationStart||Date.now()),onerror:void 0,origin:""+f._A.location,ptid:void 0,releaseIds:{},session:void 0,xhrWrappable:"function"==typeof f._A.XMLHttpRequest?.prototype?.addEventListener,userAgent:r,version:S.q4},P={};function N(e){if(!e)throw new Error("All runtime objects require an agent identifier!");if(!P[e])throw new Error("Runtime for ".concat(e," was never set"));return P[e]}function I(e,t){if(!e)throw new Error("All runtime objects require an agent identifier!");P[e]=new o.I(t,T),(0,i.Qy)(e,P[e],"runtime")}function C(e){return function(e){try{const t=c(e);return!!t.licenseKey&&!!t.errorBeacon&&!!t.applicationID}catch(e){return!1}}(e)}},4286:(e,t,n)=>{n.d(t,{I:()=>o});var r=n(909),i=n(8610);class o{constructor(e,t){Object.assign(this,function(e,t){const n={};try{return e&&"object"==typeof e?t&&"object"==typeof t?(Object.assign(n,t),Object.entries(e).forEach((e=>{let[o,a]=e;if(!Object.keys(t).includes(o))return;const s=(0,r.q)(o);s.length&&a&&"object"==typeof a&&s.forEach((e=>{e in a&&((0,i.Z)('"'.concat(e,'" is a protected attribute and can not be changed in feature ').concat(o,".  It will have no effect.")),delete a[e])})),n[o]=a})),n):(0,i.Z)("Setting a Configurable requires a model to set its initial properties"):(0,i.Z)("New setting a Configurable requires an object as input")}catch(e){(0,i.Z)("An error occured while setting a Configurable",e)}}(e,t))}}},1651:(e,t,n)=>{n.d(t,{Re:()=>i,gF:()=>o,q4:()=>r});const r="1.232.0",i="PROD",o="CDN"},9557:(e,t,n)=>{n.d(t,{w:()=>o});var r=n(8610);const i={agentIdentifier:"",ee:void 0};class o{constructor(e){try{if("object"!=typeof e)return(0,r.Z)("shared context requires an object as input");this.sharedContext={},Object.assign(this.sharedContext,i),Object.entries(e).forEach((e=>{let[t,n]=e;Object.keys(i).includes(t)&&(this.sharedContext[t]=n)}))}catch(e){(0,r.Z)("An error occured while setting SharedContext",e)}}}},4329:(e,t,n)=>{n.d(t,{L:()=>d,R:()=>c});var r=n(3752),i=n(7022),o=n(4045),a=n(2325);const s={};function c(e,t){const n={staged:!1,priority:a.p[t]||0};u(e),s[e].get(t)||s[e].set(t,n)}function u(e){e&&(s[e]||(s[e]=new Map))}function d(){let e=arguments.length>0&&void 0!==arguments[0]?arguments[0]:"",t=arguments.length>1&&void 0!==arguments[1]?arguments[1]:"feature";if(u(e),!e||!s[e].get(t))return a(t);s[e].get(t).staged=!0;const n=Array.from(s[e]);function a(t){const n=e?r.ee.get(e):r.ee,a=o.X.handlers;if(n.backlog&&a){var s=n.backlog[t],c=a[t];if(c){for(var u=0;s&&u<s.length;++u)f(s[u],c);(0,i.D)(c,(function(e,t){(0,i.D)(t,(function(t,n){n[0].on(e,n[1])}))}))}delete a[t],n.backlog[t]=null,n.emit("drain-"+t,[])}}n.every((e=>{let[t,n]=e;return n.staged}))&&(n.sort(((e,t)=>e[1].priority-t[1].priority)),n.forEach((e=>{let[t]=e;a(t)})))}function f(e,t){var n=e[1];(0,i.D)(t[n],(function(t,n){var r=e[0];if(n[0]===r){var i=n[1],o=e[3],a=e[2];i.apply(o,a)}}))}},3752:(e,t,n)=>{n.d(t,{ee:()=>u});var r=n(6797),i=n(3916),o=n(7022),a=n(2919),s="nr@context";let c=(0,r.fP)();var u;function d(){}function f(){return new d}function l(){u.aborted=!0,u.backlog={}}c.ee?u=c.ee:(u=function e(t,n){var r={},c={},g={},h=!1;try{h=16===n.length&&(0,a.OP)(n).isolatedBacklog}catch(e){}var v={on:b,addEventListener:b,removeEventListener:w,emit:m,get:A,listeners:y,context:p,buffer:x,abort:l,aborted:!1,isBuffering:_,debugId:n,backlog:h?{}:t&&"object"==typeof t.backlog?t.backlog:{}};return v;function p(e){return e&&e instanceof d?e:e?(0,i.X)(e,s,f):f()}function m(e,n,r,i,o){if(!1!==o&&(o=!0),!u.aborted||i){t&&o&&t.emit(e,n,r);for(var a=p(r),s=y(e),d=s.length,f=0;f<d;f++)s[f].apply(a,n);var l=j()[c[e]];return l&&l.push([v,e,n,a]),a}}function b(e,t){r[e]=y(e).concat(t)}function w(e,t){var n=r[e];if(n)for(var i=0;i<n.length;i++)n[i]===t&&n.splice(i,1)}function y(e){return r[e]||[]}function A(t){return g[t]=g[t]||e(v,t)}function x(e,t){var n=j();v.aborted||(0,o.D)(e,(function(e,r){t=t||"feature",c[r]=t,t in n||(n[t]=[])}))}function _(e){return!!j()[c[e]]}function j(){return v.backlog}}(void 0,"globalEE"),c.ee=u)},9252:(e,t,n)=>{n.d(t,{E:()=>r,p:()=>i});var r=n(3752).ee.get("handle");function i(e,t,n,i,o){o?(o.buffer([e],i),o.emit(e,t,n)):(r.buffer([e],i),r.emit(e,t,n))}},4045:(e,t,n)=>{n.d(t,{X:()=>o});var r=n(9252);o.on=a;var i=o.handlers={};function o(e,t,n,o){a(o||r.E,i,e,t,n)}function a(e,t,n,i,o){o||(o="feature"),e||(e=r.E);var a=t[o]=t[o]||{};(a[n]=a[n]||[]).push([e,i])}},8544:(e,t,n)=>{n.d(t,{bP:()=>s,iz:()=>c,m$:()=>a});var r=n(2374);let i=!1,o=!1;try{const e={get passive(){return i=!0,!1},get signal(){return o=!0,!1}};r._A.addEventListener("test",null,e),r._A.removeEventListener("test",null,e)}catch(e){}function a(e,t){return i||o?{capture:!!e,passive:i,signal:t}:!!e}function s(e,t){let n=arguments.length>2&&void 0!==arguments[2]&&arguments[2],r=arguments.length>3?arguments[3]:void 0;window.addEventListener(e,t,a(n,r))}function c(e,t){let n=arguments.length>2&&void 0!==arguments[2]&&arguments[2],r=arguments.length>3?arguments[3]:void 0;document.addEventListener(e,t,a(n,r))}},5526:(e,t,n)=>{n.d(t,{Rl:()=>a,ky:()=>s});var r=n(2374);const i="xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx";function o(e,t){return e?15&e[t]:16*Math.random()|0}function a(){const e=r._A?.crypto||r._A?.msCrypto;let t,n=0;return e&&e.getRandomValues&&(t=e.getRandomValues(new Uint8Array(31))),i.split("").map((e=>"x"===e?o(t,++n).toString(16):"y"===e?(3&o()|8).toString(16):e)).join("")}function s(e){const t=r._A?.crypto||r._A?.msCrypto;let n,i=0;t&&t.getRandomValues&&(n=t.getRandomValues(new Uint8Array(31)));const a=[];for(var s=0;s<e;s++)a.push(o(n,++i).toString(16));return a.join("")}},2797:(e,t,n)=>{n.d(t,{Bq:()=>r,Hb:()=>o,oD:()=>i});const r="NRBA",i=144e5,o=18e5},2053:(e,t,n)=>{function r(){return Math.round(performance.now())}n.d(t,{z:()=>r})},8610:(e,t,n)=>{function r(e,t){"function"==typeof console.warn&&(console.warn("New Relic: ".concat(e)),t&&console.warn(t))}n.d(t,{Z:()=>r})},3916:(e,t,n)=>{n.d(t,{X:()=>i});var r=Object.prototype.hasOwnProperty;function i(e,t,n){if(r.call(e,t))return e[t];var i=n();if(Object.defineProperty&&Object.keys)try{return Object.defineProperty(e,t,{value:i,writable:!0,enumerable:!1}),i}catch(e){}return e[t]=i,i}},2374:(e,t,n)=>{n.d(t,{_A:()=>o,il:()=>r,v6:()=>i});const r=Boolean("undefined"!=typeof window&&window.document),i=Boolean("undefined"!=typeof WorkerGlobalScope&&self.navigator instanceof WorkerNavigator);let o=(()=>{if(r)return window;if(i){if("undefined"!=typeof globalThis&&globalThis instanceof WorkerGlobalScope)return globalThis;if(self instanceof WorkerGlobalScope)return self}throw new Error('New Relic browser agent shutting down due to error: Unable to locate global scope. This is possibly due to code redefining browser global variables like "self" and "window".')})()},7022:(e,t,n)=>{n.d(t,{D:()=>r});const r=(e,t)=>Object.entries(e||{}).map((e=>{let[n,r]=e;return t(n,r)}))},2438:(e,t,n)=>{n.d(t,{P:()=>o});var r=n(3752);const i=()=>{const e=new WeakSet;return(t,n)=>{if("object"==typeof n&&null!==n){if(e.has(n))return;e.add(n)}return n}};function o(e){try{return JSON.stringify(e,i())}catch(e){try{r.ee.emit("internal-error",[e])}catch(e){}}}},2650:(e,t,n)=>{n.d(t,{K:()=>a,b:()=>o});var r=n(8544);function i(){return"undefined"==typeof document||"complete"===document.readyState}function o(e,t){if(i())return e();(0,r.bP)("load",e,t)}function a(e){if(i())return e();(0,r.iz)("DOMContentLoaded",e)}},6797:(e,t,n)=>{n.d(t,{EZ:()=>u,Qy:()=>c,ce:()=>o,fP:()=>a,gG:()=>d,mF:()=>s});var r=n(2053),i=n(2374);const o={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net"};function a(){return i._A.NREUM||(i._A.NREUM={}),void 0===i._A.newrelic&&(i._A.newrelic=i._A.NREUM),i._A.NREUM}function s(){let e=a();return e.o||(e.o={ST:i._A.setTimeout,SI:i._A.setImmediate,CT:i._A.clearTimeout,XHR:i._A.XMLHttpRequest,REQ:i._A.Request,EV:i._A.Event,PR:i._A.Promise,MO:i._A.MutationObserver,FETCH:i._A.fetch}),e}function c(e,t,n){let i=a();const o=i.initializedAgents||{},s=o[e]||{};return Object.keys(s).length||(s.initializedAt={ms:(0,r.z)(),date:new Date}),i.initializedAgents={...o,[e]:{...s,[n]:t}},i}function u(e,t){a()[e]=t}function d(){return function(){let e=a();const t=e.info||{};e.info={beacon:o.beacon,errorBeacon:o.errorBeacon,...t}}(),function(){let e=a();const t=e.init||{};e.init={...t}}(),s(),function(){let e=a();const t=e.loader_config||{};e.loader_config={...t}}(),a()}},6998:(e,t,n)=>{n.d(t,{N:()=>i});var r=n(8544);function i(e){let t=arguments.length>1&&void 0!==arguments[1]&&arguments[1],n=arguments.length>2?arguments[2]:void 0,i=arguments.length>3?arguments[3]:void 0;return void(0,r.iz)("visibilitychange",(function(){if(t)return void("hidden"==document.visibilityState&&e());e(document.visibilityState)}),n,i)}},6034:(e,t,n)=>{n.d(t,{gF:()=>o,mY:()=>i,t9:()=>r,vz:()=>s,xS:()=>a});const r=n(2325).D.metrics,i="sm",o="cm",a="storeSupportabilityMetrics",s="storeEventMetrics"},2484:(e,t,n)=>{n.d(t,{Dz:()=>i,OJ:()=>a,qw:()=>o,t9:()=>r});const r=n(2325).D.pageViewEvent,i="firstbyte",o="domcontent",a="windowload"},6382:(e,t,n)=>{n.d(t,{t:()=>r});const r=n(2325).D.pageViewTiming},1509:(e,t,n)=>{n.d(t,{W:()=>s});var r=n(2919),i=n(3752),o=n(2384),a=n(6797);class s{constructor(e,t,n){this.agentIdentifier=e,this.aggregator=t,this.ee=i.ee.get(e,(0,r.OP)(this.agentIdentifier).isolatedBacklog),this.featureName=n,this.blocked=!1,this.checkConfiguration()}checkConfiguration(){if(!(0,r.lF)(this.agentIdentifier)){let e={...(0,a.gG)().info?.jsAttributes};try{e={...e,...(0,r.C5)(this.agentIdentifier)?.jsAttributes}}catch(e){}(0,o.j)(this.agentIdentifier,{...(0,a.gG)(),info:{...(0,a.gG)().info,jsAttributes:e}})}}}},2384:(e,t,n)=>{n.d(t,{j:()=>b});var r=n(2325),i=n(2919),o=n(9252),a=n(3752),s=n(2053),c=n(4329),u=n(2650),d=n(2374),f=n(8610),l=n(6034),g=n(6797);function h(){const e=(0,g.gG)();["setErrorHandler","finished","addToTrace","inlineHit","addRelease","addPageAction","setCurrentRouteName","setPageViewName","setCustomAttribute","interaction","noticeError","setUserId"].forEach((t=>{e[t]=function(){for(var n=arguments.length,r=new Array(n),i=0;i<n;i++)r[i]=arguments[i];return function(t){for(var n=arguments.length,r=new Array(n>1?n-1:0),i=1;i<n;i++)r[i-1]=arguments[i];let o=[];return Object.values(e.initializedAgents).forEach((e=>{e.exposed&&e.api[t]&&o.push(e.api[t](...r))})),o.length>1?o:o[0]}(t,...r)}}))}var v=n(7022);const p={stn:[r.D.sessionTrace],err:[r.D.jserrors,r.D.metrics],ins:[r.D.pageAction],spa:[r.D.spa]};const m={};function b(e){let t=arguments.length>1&&void 0!==arguments[1]?arguments[1]:{},b=arguments.length>2?arguments[2]:void 0,w=arguments.length>3?arguments[3]:void 0,{init:y,info:A,loader_config:x,runtime:_={loaderType:b},exposed:j=!0}=t;const D=(0,g.gG)();A||(y=D.init,A=D.info,x=D.loader_config),A.jsAttributes??={},d.v6&&(A.jsAttributes.isWorker=!0),(0,i.CX)(e,A),(0,i.Dg)(e,y||{}),(0,i.GE)(e,x||{}),(0,i.sU)(e,_),h();const E=function(e,t){t||(0,c.R)(e,"api");const g={};var h=a.ee.get(e),v=h.get("tracer"),p="api-",m=p+"ixn-";function b(t,n,r,o){const a=(0,i.C5)(e);return null===n?delete a.jsAttributes[t]:(0,i.CX)(e,{...a,jsAttributes:{...a.jsAttributes,[t]:n}}),A(p,r,!0,o||null===n?"session":void 0)(t,n)}function w(){}["setErrorHandler","finished","addToTrace","inlineHit","addRelease"].forEach((e=>g[e]=A(p,e,!0,"api"))),g.addPageAction=A(p,"addPageAction",!0,r.D.pageAction),g.setCurrentRouteName=A(p,"routeName",!0,r.D.spa),g.setPageViewName=function(t,n){if("string"==typeof t)return"/"!==t.charAt(0)&&(t="/"+t),(0,i.OP)(e).customTransaction=(n||"http://custom.transaction")+t,A(p,"setPageViewName",!0)()},g.setCustomAttribute=function(e,t){let n=arguments.length>2&&void 0!==arguments[2]&&arguments[2];if("string"==typeof e){if(["string","number"].includes(typeof t)||null===t)return b(e,t,"setCustomAttribute",n);(0,f.Z)("Failed to execute setCustomAttribute.\nNon-null value must be a string or number type, but a type of <".concat(typeof t,"> was provided."))}else(0,f.Z)("Failed to execute setCustomAttribute.\nName must be a string type, but a type of <".concat(typeof e,"> was provided."))},g.setUserId=function(e){if("string"==typeof e||null===e)return b("enduser.id",e,"setUserId",!0);(0,f.Z)("Failed to execute setUserId.\nNon-null value must be a string type, but a type of <".concat(typeof e,"> was provided."))},g.interaction=function(){return(new w).get()};var y=w.prototype={createTracer:function(e,t){var n={},i=this,a="function"==typeof t;return(0,o.p)(m+"tracer",[(0,s.z)(),e,n],i,r.D.spa,h),function(){if(v.emit((a?"":"no-")+"fn-start",[(0,s.z)(),i,a],n),a)try{return t.apply(this,arguments)}catch(e){throw v.emit("fn-err",[arguments,this,"string"==typeof e?new Error(e):e],n),e}finally{v.emit("fn-end",[(0,s.z)()],n)}}}};function A(e,t,n,i){return function(){return(0,o.p)(l.xS,["API/"+t+"/called"],void 0,r.D.metrics,h),i&&(0,o.p)(e+t,[(0,s.z)(),...arguments],n?null:this,i,h),n?void 0:this}}function x(){n.e(439).then(n.bind(n,5692)).then((t=>{let{setAPI:n}=t;n(e),(0,c.L)(e,"api")})).catch((()=>(0,f.Z)("Downloading runtime APIs failed...")))}return["actionText","setName","setAttribute","save","ignore","onEnd","getContext","end","get"].forEach((e=>{y[e]=A(m,e,void 0,r.D.spa)})),g.noticeError=function(e,t){"string"==typeof e&&(e=new Error(e)),(0,o.p)(l.xS,["API/noticeError/called"],void 0,r.D.metrics,h),(0,o.p)("err",[e,(0,s.z)(),!1,t],void 0,r.D.jserrors,h)},d.v6?x():(0,u.b)((()=>x()),!0),g}(e,w);return(0,g.Qy)(e,E,"api"),(0,g.Qy)(e,j,"exposed"),(0,g.EZ)("activatedFeatures",m),(0,g.EZ)("setToken",(t=>function(e,t){var n=a.ee.get(t);e&&"object"==typeof e&&((0,v.D)(e,(function(e,t){if(!t)return(p[e]||[]).forEach((t=>{(0,o.p)("block-"+e,[],void 0,t,n)}));m[e]||((0,o.p)("feat-"+e,[],void 0,p[e],n),m[e]=!0)})),(0,c.L)(t,r.D.pageViewEvent))}(t,e))),E}},909:(e,t,n)=>{n.d(t,{Z:()=>i,q:()=>o});var r=n(2325);function i(e){switch(e){case r.D.ajax:return[r.D.jserrors];case r.D.sessionTrace:return[r.D.ajax,r.D.pageViewEvent];case r.D.pageViewTiming:return[r.D.pageViewEvent];default:return[]}}function o(e){return e===r.D.jserrors?[]:["auto"]}},2325:(e,t,n)=>{n.d(t,{D:()=>r,p:()=>i});const r={ajax:"ajax",jserrors:"jserrors",metrics:"metrics",pageAction:"page_action",pageViewEvent:"page_view_event",pageViewTiming:"page_view_timing",sessionTrace:"session_trace",spa:"spa"},i={[r.pageViewEvent]:1,[r.pageViewTiming]:2,[r.metrics]:3,[r.jserrors]:4,[r.ajax]:5,[r.sessionTrace]:6,[r.pageAction]:7,[r.spa]:8}}},r={};function i(e){var t=r[e];if(void 0!==t)return t.exports;var o=r[e]={exports:{}};return n[e](o,o.exports,i),o.exports}i.m=n,i.n=e=>{var t=e&&e.__esModule?()=>e.default:()=>e;return i.d(t,{a:t}),t},i.d=(e,t)=>{for(var n in t)i.o(t,n)&&!i.o(e,n)&&Object.defineProperty(e,n,{enumerable:!0,get:t[n]})},i.f={},i.e=e=>Promise.all(Object.keys(i.f).reduce(((t,n)=>(i.f[n](e,t),t)),[])),i.u=e=>(({78:"page_action-aggregate",147:"metrics-aggregate",193:"session_trace-aggregate",242:"session-manager",317:"jserrors-aggregate",348:"page_view_timing-aggregate",439:"async-api",729:"lazy-loader",786:"page_view_event-aggregate",873:"spa-aggregate",898:"ajax-aggregate"}[e]||e)+"."+{78:"64dc4751",147:"c2ad263a",193:"c0ef217a",242:"2a8d47d1",317:"017d6ea4",348:"ddd91465",439:"ad3273bd",729:"c8cd494b",786:"5a238c1f",873:"342172b1",875:"2c240adb",898:"666f66ea"}[e]+"-1.232.0.min.js"),i.o=(e,t)=>Object.prototype.hasOwnProperty.call(e,t),e={},t="NRBA:",i.l=(n,r,o,a)=>{if(e[n])e[n].push(r);else{var s,c;if(void 0!==o)for(var u=document.getElementsByTagName("script"),d=0;d<u.length;d++){var f=u[d];if(f.getAttribute("src")==n||f.getAttribute("data-webpack")==t+o){s=f;break}}s||(c=!0,(s=document.createElement("script")).charset="utf-8",s.timeout=120,i.nc&&s.setAttribute("nonce",i.nc),s.setAttribute("data-webpack",t+o),s.src=n),e[n]=[r];var l=(t,r)=>{s.onerror=s.onload=null,clearTimeout(g);var i=e[n];if(delete e[n],s.parentNode&&s.parentNode.removeChild(s),i&&i.forEach((e=>e(r))),t)return t(r)},g=setTimeout(l.bind(null,void 0,{type:"timeout",target:s}),12e4);s.onerror=l.bind(null,s.onerror),s.onload=l.bind(null,s.onload),c&&document.head.appendChild(s)}},i.r=e=>{"undefined"!=typeof Symbol&&Symbol.toStringTag&&Object.defineProperty(e,Symbol.toStringTag,{value:"Module"}),Object.defineProperty(e,"__esModule",{value:!0})},i.j=71,i.p="https://js-agent.newrelic.com/",(()=>{var e={71:0,131:0};i.f.j=(t,n)=>{var r=i.o(e,t)?e[t]:void 0;if(0!==r)if(r)n.push(r[2]);else{var o=new Promise(((n,i)=>r=e[t]=[n,i]));n.push(r[2]=o);var a=i.p+i.u(t),s=new Error;i.l(a,(n=>{if(i.o(e,t)&&(0!==(r=e[t])&&(e[t]=void 0),r)){var o=n&&("load"===n.type?"missing":n.type),a=n&&n.target&&n.target.src;s.message="Loading chunk "+t+" failed.\n("+o+": "+a+")",s.name="ChunkLoadError",s.type=o,s.request=a,r[1](s)}}),"chunk-"+t,t)}};var t=(t,n)=>{var r,o,[a,s,c]=n,u=0;if(a.some((t=>0!==e[t]))){for(r in s)i.o(s,r)&&(i.m[r]=s[r]);if(c)c(i)}for(t&&t(n);u<a.length;u++)o=a[u],i.o(e,o)&&e[o]&&e[o][0](),e[o]=0},n=window.webpackChunkNRBA=window.webpackChunkNRBA||[];n.forEach(t.bind(null,0)),n.push=t.bind(null,n.push.bind(n))})();var o={};(()=>{i.r(o);var e=i(2325),t=i(2919);const n=Object.values(e.D);function r(e){const r={};return n.forEach((n=>{r[n]=function(e,n){return!1!==(0,t.Mt)(n,"".concat(e,".enabled"))}(n,e)})),r}var a=i(2384),s=i(909),c=i(9252),u=i(8768),d=i(4329),f=i(1509),l=i(2650),g=i(2374),h=i(8610);class v extends f.W{constructor(e,t,n){let r=!(arguments.length>3&&void 0!==arguments[3])||arguments[3];super(e,t,n),this.hasAggregator=!1,this.auto=r,this.abortHandler,r&&(0,d.R)(e,n)}importAggregator(){if(this.hasAggregator||!this.auto)return;this.hasAggregator=!0;const e=async()=>{try{const{setupAgentSession:e}=await i.e(242).then(i.bind(i,2011));e(this.agentIdentifier);const{lazyLoader:t}=await i.e(729).then(i.bind(i,8110)),{Aggregate:n}=await t(this.featureName,"aggregate");new n(this.agentIdentifier,this.aggregator)}catch(e){(0,h.Z)("Downloading ".concat(this.featureName," failed..."),e),this.abortHandler?.()}};g.v6?e():(0,l.b)((()=>e()),!0)}}var p=i(2484),m=i(2053);class b extends v{static featureName=p.t9;constructor(n,r){let i=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];if(super(n,r,p.t9,i),("undefined"==typeof PerformanceNavigationTiming||u.T)&&"undefined"!=typeof PerformanceTiming){const r=(0,t.OP)(n);r[p.Dz]=Math.max(Date.now()-r.offset,0),(0,l.K)((()=>r[p.qw]=Math.max((0,m.z)()-r[p.Dz],0))),(0,l.b)((()=>{const t=(0,m.z)();r[p.OJ]=Math.max(t-r[p.Dz],0),(0,c.p)("timing",["load",t],void 0,e.D.pageViewTiming,this.ee)}))}this.importAggregator()}}var w=i(9557),y=i(7022);class A extends w.w{constructor(e){super(e),this.aggregatedData={}}store(e,t,n,r,i){var o=this.getBucket(e,t,n,i);return o.metrics=function(e,t){t||(t={count:0});return t.count+=1,(0,y.D)(e,(function(e,n){t[e]=x(n,t[e])})),t}(r,o.metrics),o}merge(e,t,n,r,i){var o=this.getBucket(e,t,r,i);if(o.metrics){var a=o.metrics;a.count+=n.count,(0,y.D)(n,(function(e,t){if("count"!==e){var r=a[e],i=n[e];i&&!i.c?a[e]=x(i.t,r):a[e]=function(e,t){if(!t)return e;t.c||(t=_(t.t));return t.min=Math.min(e.min,t.min),t.max=Math.max(e.max,t.max),t.t+=e.t,t.sos+=e.sos,t.c+=e.c,t}(i,a[e])}}))}else o.metrics=n}storeMetric(e,t,n,r){var i=this.getBucket(e,t,n);return i.stats=x(r,i.stats),i}getBucket(e,t,n,r){this.aggregatedData[e]||(this.aggregatedData[e]={});var i=this.aggregatedData[e][t];return i||(i=this.aggregatedData[e][t]={params:n||{}},r&&(i.custom=r)),i}get(e,t){return t?this.aggregatedData[e]&&this.aggregatedData[e][t]:this.aggregatedData[e]}take(e){for(var t={},n="",r=!1,i=0;i<e.length;i++)t[n=e[i]]=j(this.aggregatedData[n]),t[n].length&&(r=!0),delete this.aggregatedData[n];return r?t:null}}function x(e,t){return null==e?function(e){e?e.c++:e={c:1};return e}(t):t?(t.c||(t=_(t.t)),t.c+=1,t.t+=e,t.sos+=e*e,e>t.max&&(t.max=e),e<t.min&&(t.min=e),t):{t:e}}function _(e){return{t:e,min:e,max:e,sos:e*e,c:1}}function j(e){return"object"!=typeof e?[]:(0,y.D)(e,D)}function D(e,t){return t}var E=i(6797),k=i(5526),S=i(2438);var T=i(6998),P=i(8544),N=i(6382);class I extends v{static featureName=N.t;constructor(e,n){let r=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];super(e,n,N.t,r),g.il&&((0,t.OP)(e).initHidden=Boolean("hidden"===document.visibilityState),(0,T.N)((()=>(0,c.p)("docHidden",[(0,m.z)()],void 0,N.t,this.ee)),!0),(0,P.bP)("pagehide",(()=>(0,c.p)("winPagehide",[(0,m.z)()],void 0,N.t,this.ee))),this.importAggregator())}}const C=Boolean(g._A?.Worker),O=Boolean(g._A?.SharedWorker),R=Boolean(g._A?.navigator?.serviceWorker);let M,B,z;var q=i(6034);class W extends v{static featureName=q.t9;constructor(t,n){let r=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];super(t,n,q.t9,r),function(e){if(!M){if(C){M=Worker;try{g._A.Worker=n(M,"Dedicated")}catch(e){o(e,"Dedicated")}if(O){B=SharedWorker;try{g._A.SharedWorker=n(B,"Shared")}catch(e){o(e,"Shared")}}else r("Shared");if(R){z=navigator.serviceWorker.register;try{g._A.navigator.serviceWorker.register=(t=z,function(){for(var e=arguments.length,n=new Array(e),r=0;r<e;r++)n[r]=arguments[r];return i("Service",n[1]?.type),t.apply(navigator.serviceWorker,n)})}catch(e){o(e,"Service")}}else r("Service");var t;return}r("All")}function n(e,t){return"undefined"==typeof Proxy?e:new Proxy(e,{construct:(e,n)=>(i(t,n[1]?.type),new e(...n))})}function r(t){g.v6||e("Workers/".concat(t,"/Unavailable"))}function i(t,n){e("Workers/".concat(t,"module"===n?"/Module":"/Classic"))}function o(t,n){e("Workers/".concat(n,"/SM/Unsupported")),(0,h.Z)("NR Agent: Unable to capture ".concat(n," workers."),t)}}((t=>(0,c.p)(q.xS,[t],void 0,e.D.metrics,this.ee))),this.importAggregator()}}new class{constructor(e){let t=arguments.length>1&&void 0!==arguments[1]?arguments[1]:(0,k.ky)(16);this.agentIdentifier=t,this.sharedAggregator=new A({agentIdentifier:this.agentIdentifier}),this.features={},this.desiredFeatures=new Set(e.features||[]),this.desiredFeatures.add(b),Object.assign(this,(0,a.j)(this.agentIdentifier,e,e.loaderType||"agent")),this.start()}get config(){return{info:(0,t.C5)(this.agentIdentifier),init:(0,t.P_)(this.agentIdentifier),loader_config:(0,t.DL)(this.agentIdentifier),runtime:(0,t.OP)(this.agentIdentifier)}}start(){const t="features";try{const n=r(this.agentIdentifier),i=Array.from(this.desiredFeatures);i.sort(((t,n)=>e.p[t.featureName]-e.p[n.featureName])),i.forEach((t=>{if(n[t.featureName]||t.featureName===e.D.pageViewEvent){const e=(0,s.Z)(t.featureName);e.every((e=>n[e]))||(0,h.Z)("".concat(t.featureName," is enabled but one or more dependent features has been disabled (").concat((0,S.P)(e),"). This may cause unintended consequences or missing data...")),this.features[t.featureName]=new t(this.agentIdentifier,this.sharedAggregator)}})),(0,E.Qy)(this.agentIdentifier,this.features,t)}catch(e){(0,h.Z)("Failed to initialize all enabled instrument classes (agent aborted) -",e);for(const e in this.features)this.features[e].abortHandler?.();const n=(0,E.fP)();return delete n.initializedAgents[this.agentIdentifier]?.api,delete n.initializedAgents[this.agentIdentifier]?.[t],delete this.sharedAggregator,n.ee?.abort(),delete n.ee?.get(this.agentIdentifier),!1}}}({features:[b,I,W],loaderType:"lite"})})(),window.NRBA=o})();</script>
<link rel="canonical" href="https://www.ogilvy.com/cn/eng">
<meta http-equiv="content-language" content="cn">
<link rel="shortlink" href="https://www.ogilvy.com/cn/eng">
<meta name="description" content="At Ogilvy, we design the brand; we turn the brand into an experience; and we communicate the brand’s story. We make brands matter. Learn more about Ogilvy’s capabilities at Ogilvy.com.">
<link rel="mask-icon" href="/safari-pinned-tab.svg" color="#eb3f43">
<link rel="icon" sizes="16x16" href="/favicon-16x16.png">
<link rel="icon" sizes="32x32" href="/favicon-32x32.png">
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<meta name="theme-color" content="#eb3f43">
<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=0">
<meta property="og:site_name" content="Ogilvy China">
<meta property="og:url" content="https://www.ogilvy.com/cn/eng">
<meta property="og:title" content="Ogilvy">
<meta property="og:description" content="At Ogilvy, we design the brand; we turn the brand into an experience; and we communicate the brand’s story. We make brands matter. Learn more about Ogilvy’s capabilities at Ogilvy.com.">
<meta name="msapplication-tilecolor" content="#eb3f43">
<meta name="title" content="Ogilvy">
<meta name="Generator" content="Drupal 9 (https://www.drupal.org)">
<meta name="MobileOptimized" content="width">
<meta name="HandheldFriendly" content="true">
<style>div#sliding-popup, div#sliding-popup .eu-cookie-withdraw-banner, .eu-cookie-withdraw-tab {background: #eac5cc} div#sliding-popup.eu-cookie-withdraw-wrapper { background: transparent; } #sliding-popup h1, #sliding-popup h2, #sliding-popup h3, #sliding-popup p, #sliding-popup label, #sliding-popup div, .eu-cookie-compliance-more-button, .eu-cookie-compliance-secondary-button, .eu-cookie-withdraw-tab { color: #000;} .eu-cookie-withdraw-tab { border-color: #000;}</style>
<script src="/cn/sites/g/files/dhpsjz236/files/google_tag/gtm/google_tag.script.js?rufoss" defer="" type="text/javascript"></script>
<script type="text/javascript">window.a2a_config=window.a2a_config||{};a2a_config.callbacks=[];a2a_config.overlays=[];a2a_config.templates={};a2a_config.templates.twitter = "${title} ${link} via @Ogilvy";</script>
<title>Ogilvy</title>
<link rel="stylesheet" media="all" href="/cn/sites/g/files/dhpsjz236/files/css/css_tJZ1fElHnhKYI2RYJ8EP9ikXV-LXGZbWvos-yqqO6P8.css">
<link rel="stylesheet" media="all" href="/cn/sites/g/files/dhpsjz236/files/css/css_fSMk63AawuMkAMz5UHbFiQnNQceZpDasr7nzc-2VaSs.css">
<noscript><style>label.option{display:none;}.noscriptCSS{display:none;}</style></noscript>
<style>.x-jtc-recorder-btn {
	position: fixed;
	z-index: 999999999998;

	display: none;
	justify-content: space-between;
	align-items: center;
	width: 170px;
}
.x-jtc-recorder-btn button {
	width: 80px;
	border-radius: 3px;
	background-color: rgba(255, 255, 255, 0.8);
	color: rgba(0, 0, 0, 0.8);
	line-height: 30px;
	height: 30px;
	cursor: pointer;
	font-size: 15px;
	border: 0;
	outline: none;
}
.x-jtc-recorder-btn button:hover {
	background-color: rgba(48, 13, 241, 0.5);
	color: rgba(255, 255, 255, 0.8);
}
</style><script src="moz-extension://08913641-811f-4535-96f1-7230c2f1def3/js/page.js"></script><script src="https://static.addtoany.com/menu/modules/core.26680508.js" type="module"></script><style>
.youdao_tans_modal {
    display: none;
    position: fixed;
    background-color: #fff;
    max-width: 400px;
    max-height: 400px;
    overflow-y: auto;
    padding: 16px;
    border-radius: 2px;
    border: 1px solid #35a1d4;
    font-size: 12px;
    line-height: 1.6;
    color: #434343;
    box-shadow: 0 3px 6px -4px rgba(0,0,0,.12), 0 6px 16px 0 rgba(0,0,0,.08), 0 9px 28px 8px rgba(0,0,0,.05);
    z-index: 9999999999;
    font-family: -apple-system,BlinkMacSystemFont,Segoe UI,PingFang SC,Hiragino Sans GB,Microsoft YaHei,Helvetica Neue,Helvetica,Arial,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol;
}

.youdao_tans_modal a{
    color: #35a1d4;
}

.youdao_tans_modal b{
    color: #638c0b;
}

.youdao_tans_modal p{
    margin: 0;
}

.youdao_tans_modal ul{
    list-style-type: none;
}

.youdao_tans_modal h1,h2,h3{
    font-size: 16px;
    margin-top: 16px;
}

.youdao_tans_modal a[href^='#'],a:not([href]),a[href='']{
    color: #434343;
}

.youdao_tans_modal .video,.more{
    display: none;
}

.youdao_tans_modal .title{
    font-weight: bold;
    font-size: 14px;
}
</style></head>
<body class="path-frontpage scrollbar_inActive eu-cookie-compliance-popup-open eu-cookie-compliance-status-null" data-eu-cookie-compliance-once="true">
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-M84H4M7&gtm_auth=mWf3dmo8Co1XPgTHpo5Smg&gtm_preview=env-196&gtm_cookies_win=x" height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<header role="banner">
<div class="container">
<a href="https://www.ogilvy.com/cn/#work" title="work" class="branding" aria-label="work" style="--logo-scroll-color: rgb(104,28,29); --logo-scroll-position: -26.66666666666667%; --logo-scroll-margin: 26.66666666666667px;">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 700 273.7" class="branding__logo" style="--logo-scroll-width: 17.888888888888893vw;"><path d="M99.1 8.8C45.5 8.8 0 47.1 0 106c0 53 40.5 95 98.5 95 53.5 0 99.1-38.3 99.1-97.2 0-52.9-40.5-95-98.5-95zm0 180.8c-34.9 0-59.9-35.7-59.9-84.9 0-47.1 23.7-84.4 59.4-84.4 34.9 0 59.9 35.7 59.9 84.9-.1 47.1-23.8 84.4-59.4 84.4zM654.5 81.7v8l10.7 2.1c3.7.8 4.8 3.7 2.4 9.6L643 160.6c-1.1 2.4-2.4 2.4-3.2 0l-22.9-59.1c-2.4-6.1-1.1-8.8 2.7-9.6l10.6-2.1v-8h-94.8v8l10.7 2.1c3.7.8 5.1 3.7 2.7 9.6l-23.7 62.3c-1.1 2.4-2.4 2.4-3.2 0l-24-62.3c-2.1-6.1-1.1-8.8 2.7-9.6l10.6-2.1v-8H451V90l5.9 1.3c4 .8 6.4 2.9 8 6.7l40.7 100.1H524L564.7 98c2.1-5.3 4.5-7.5 8.8-7.5h1.6c3.5 0 6.1 1.3 8.3 6.4L626 200.8 614.6 228c-7.5 18.1-13 21.3-20 21.3-2.9 0-6.1-.5-9.3-.5-8.3 0-13.3 5.9-13.3 12.2 0 7.2 5.9 12.3 15.2 12.3 13.3 0 26.4-10.7 37.3-36.2l58-136.1c2.7-6.1 6.1-8.8 11.7-9.9L700 90v-8.3h-45.5zm-373.3 106l-44.5 5.6c-14.6 1.9-19.2-2.9-19.2-10.4 0-8.8 9.6-15.7 42.9-15.7h.5c24.2 0 52.7-14.6 52.7-46.3 0-10.1-3.7-19.4-10.7-26.9a34.5 34.5 0 0 1-3.2-16.5c0-23.4 16-36.7 32.5-36.7 6.9 0 9.1 1.1 9.1 5.9 0 1.3-.3 2.4-.3 4 0 8.3 6.9 16 16.8 16 10.1 0 16.5-8 16.5-16.8 0-13.3-12-23.2-34.1-23.2-30.4 0-53.8 19.7-53.8 49.8 0 2.4.3 4.3.3 6.1a64.4 64.4 0 0 0-24.8-4.8c-24 0-52.7 14.6-52.7 46.3 0 14.6 8.3 28.2 22.6 36.2-21.3 2.9-33.5 14.4-33.5 32.2 0 18.1 14.4 31.2 41.3 28l38.9-4.8c19.4-2.4 25.8 4.5 25.8 14.6 0 17.6-16.5 31.7-42.9 31.7-21 0-28.8-7.5-28.8-18.1l.3-5.3c0-6.4-4-10.9-10.4-11.2-7.5 0-12 5.3-12 13 0 17.6 16.8 33.3 51.1 33.3 38.6 0 63.1-25 63.1-53.8.1-22.9-18.2-35.4-43.5-32.2zm-20-100.4c12.5 0 22.6 14.1 22.6 35.7 0 18.6-8.5 34.6-21.8 34.6-12.8 0-22.9-14.1-22.9-35.7 0-18.3 8.5-34.6 22.1-34.6z"></path><path d="M440.7 184.3V0l-46.9 12v5.6l13.3 4.3c2.1.8 2.9 2.4 2.9 4.5v157.1c0 2.9-2.4 5.1-5.9 5.1l-11.9.2-12.6-.2c-3.5 0-5.9-2.1-5.9-5.1V77.2l-46.9 12v5.6l13.3 4.3c2.1.8 2.9 2.4 2.9 4.5v80.7c0 2.4-1.3 3.7-3.2 4l-10.9 1.3v8.5h127.8v-8.5l-13-1.3c-1.7-.3-3-1.6-3-4z"></path></svg> <h1 class="branding__wordmark is-visually-hidden">奥美</h1>
</a>
<input type="checkbox" id="menu-toggle" class="checkbox-toggle js-checkbox-toggle" tabindex="0" data-html-toggle="menu-active">
<label for="menu-toggle" class="site-nav__btn burger">
<span class="burger__inner"><i class="sr-only">Menu Toggle</i></span>
</label>
<nav role="navigation" class="site-nav js-site-nav">
<ul class="site-nav__list">
<li class="site-nav__item site-nav__item--work">
<ul class="site-nav__sub-list">
<li class="work-scroll site-nav__sub-item">
<a href="/cn/work" data-drupal-link-system-path="work">作品</a>
</li>
<li class="site-nav__sub-item scrollMenu">
<a href="/cn/about" data-drupal-link-system-path="about">主页</a>
</li>
<li class="none-mb site-nav__sub-item scrollMenu">
<a href="/cn/team" data-drupal-link-system-path="team">团队</a>
</li>
<li class="none-mb site-nav__sub-item scrollMenu">
<a href="/cn/ideas" class="ideas-link-mn" data-drupal-link-system-path="ideas">专题</a>
</li>
<li class="site-nav__mob-item site-nav__sub-item scrollMenu">
<a href="/cn/careers" data-drupal-link-system-path="careers">Careers</a>
</li>
</ul>
</li>
<li class="site-nav__item">
<a href="/cn/contact" data-drupal-link-system-path="contact">联系我们</a>
</li>
</ul>
</nav>
<div class="container-lan">
<ul class="links languages-list desktop-languages"><li hreflang="en" data-drupal-link-system-path="home" class="site-nav__sub-item scrollMenu" desk-title="English"><a href="/cn/eng/home" class="language-link" hreflang="en" data-drupal-link-system-path="home">English</a></li><li hreflang="zh-hans" data-drupal-link-system-path="home" class="site-nav__sub-item scrollMenu is-active" desk-title="Chinese, Simplified"><a href="/cn/home" class="language-link is-active" hreflang="zh-hans" data-drupal-link-system-path="home">Chinese, Simplified</a></li></ul>
</div>
</div>
</header>
<main id="main" class="site-main">
<div data-drupal-messages-fallback="" class="hidden"></div>
<div class="block-region-content">
<section class="splash__wrapper section--red" style="">
<div class="splash__scroll dragscroll">
<div class="splash" style="width: 467.738px; margin-left: 0px;">
<div class="splash__projects splash__projects--orig" style="position: relative; height: 412.801px;">
<div class="splash__project splash__project--vertical" data-order="8" style="position: absolute; left: 0px; top: 0px;">
<a href="/cn/work/laigejintongjiuqile" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/KFC%202023%20CNY%20Splash%20Image.png?itok=jvEkWrHI 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/KFC%202023%20CNY%20Splash%20Image.png?itok=ZV9wzElm 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/KFC%202023%20CNY%20Splash%20Image.png?itok=QJTfRLq-" alt="">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
肯德基
<span>来个金桶就齐了
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 190.683px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-190.683px, 11.4667px, 0px);">
<a href="/cn/work/suiyuezaibian-tuanjudemeimiaobubian" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Coca-Cola%202023%20CNY%20Splash%20Image.png?itok=phj9Lh7Y 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Coca-Cola%202023%20CNY%20Splash%20Image.png?itok=p5idAWEW 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Coca-Cola%202023%20CNY%20Splash%20Image.png?itok=ofyMxtKi" alt="">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
可口可乐
<span>岁月在变 团聚的美妙不变
</span>
</p>
</div>
<div class="splash__project" data-order="13" style="position: absolute; left: 381.366px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-381.366px, 22.9334px, 0px);">
<a href="/cn/work/fenxiangkele" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Share-a-Coke_Splash-image.jpg?itok=gxMaiyKU 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Share-a-Coke_Splash-image.jpg?itok=gRuJpley 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Share-a-Coke_Splash-image.jpg?itok=QwJmWWGJ" alt="">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
可口可乐
<span>分享可乐
</span>
</p>
</div>
<div class="splash__project" data-order="16" style="position: absolute; left: 572.049px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-572.049px, 34.4001px, 0px);">
<a href="/cn/work/xuebiwutang" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Sprite%20Zero%20Sugar%20Splash%20Image.png?itok=l0MYZ6tA 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Sprite%20Zero%20Sugar%20Splash%20Image.png?itok=PfCxnwDu 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Sprite%20Zero%20Sugar%20Splash%20Image.png?itok=KBE_wQhK" alt="雪碧无糖">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
雪碧
<span>雪碧无糖
</span>
</p>
</div>
<div class="splash__project" data-order="12" style="position: absolute; left: 762.732px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-762.732px, 45.8668px, 0px);">
<a href="/cn/work/zizaichaoqun" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Mobile%20Image%20-%201200x800.jpg?itok=rnkLfe3f 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Mobile%20Image%20-%201200x800.jpg?itok=cV49JeWb 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Mobile%20Image%20-%201200x800.jpg?itok=wB5Q8PEe" alt="儿童数字人 谷雨">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
巴拉巴拉
<span>自在超裙
</span>
</p>
</div>
<div class="splash__project" data-order="19" style="position: absolute; left: 953.415px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-953.415px, 57.3335px, 0px);">
<a href="/cn/work/huniantuanju-jinshimeimiao" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/splash%20image%20-Cocacola%20CNY%202.png?itok=ZqE7sks0 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/splash%20image%20-Cocacola%20CNY%202.png?itok=IDrCrDF0 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/splash%20image%20-Cocacola%20CNY%202.png?itok=36LAK8Pe" alt="虎年团聚 尽释美妙">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
可口可乐
<span>虎年团聚 尽释美妙
</span>
</p>
</div>
<div class="splash__project" data-order="14" style="position: absolute; left: 1144.1px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1144.1px, 68.8002px, 0px);">
<a href="/cn/work/lelingma" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/splash%3Ahome%20page.jpg?itok=oqBF1h7w 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/splash%3Ahome%20page.jpg?itok=X1Gfz2OM 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/splash%3Ahome%20page.jpg?itok=2FWrBgaP" alt="乐龄码 Care Code">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
中共上海市委老干部局
<span>乐龄码
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 1334.78px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1334.78px, 80.2669px, 0px);">
<a href="/cn/work/meihaoshenghuo-gongtongxiangwang" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Tmall%2011.11%20Splash%20Image%20Regular.png?itok=0gXPf7u2 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Tmall%2011.11%20Splash%20Image%20Regular.png?itok=3Dzbs9rQ 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Tmall%2011.11%20Splash%20Image%20Regular.png?itok=KttnMzF3" alt="美好生活 共同向往 2021 天猫 双十一">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
天猫
<span>美好生活 共同向往
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="8" style="position: absolute; left: 1525.46px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1525.46px, 91.7336px, 0px);">
<a href="/cn/work/chunxiangwujin" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Nescafe%20Splash%20Image.png?itok=6S8B9tNI 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Nescafe%20Splash%20Image.png?itok=QI5qEssx 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Nescafe%20Splash%20Image.png?itok=4SPXfjWj" alt="Nescafe - 醇香无尽">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
雀巢咖啡
<span>醇香无尽
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="21" style="position: absolute; left: 0px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(0px, -23.9167px, 0px);">
<a href="/cn/work/xuniyouxiyimiao" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Portrait%20-%20InGameVaccine.png?itok=LzH5SOF5 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Portrait%20-%20InGameVaccine.png?itok=1m3h36aY 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Portrait%20-%20InGameVaccine.png?itok=rGLDCp1K" alt="">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
辉瑞
<span>虚拟游戏疫苗
</span>
</p>
</div>
<div class="splash__project" data-order="10" style="position: absolute; left: 190.683px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-190.683px, -12.45px, 0px);">
<a href="/cn/work/zheyuanbuzhishiyizhijibailiguanggao-2021" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Cadbury%20Splash%20Image%20Regular.png?itok=noeH4eT4 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Cadbury%20Splash%20Image%20Regular.png?itok=MTuTa3XS 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Cadbury%20Splash%20Image%20Regular.png?itok=xO4MevLx" alt="Cadbury - Not Just a Cadbury Ad 2021">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Cadbury
<span>这远不止是一支吉百利广告 2021
</span>
</p>
</div>
<div class="splash__project" data-order="9" style="position: absolute; left: 381.366px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-381.366px, -0.9833px, 0px);">
<a href="/cn/work/yishengwanwuwanwuguiyi" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%E6%A8%AA.jpg?itok=U7YlhHC2 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%E6%A8%AA.jpg?itok=oFhdLiC7 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%E6%A8%AA.jpg?itok=pRzjdMkd" alt="Huawei HarmonyOS">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
华为
<span>一生万物，万物归一
</span>
</p>
</div>
<div class="splash__project" data-order="4" style="position: absolute; left: 572.049px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-572.049px, 10.4834px, 0px);">
<a href="/cn/work/voice-doodler" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Voice%20Doodler%20Splash%20Image_0.jpg?itok=LbxoGuxF 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Voice%20Doodler%20Splash%20Image_0.jpg?itok=uTtCuN87 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Voice%20Doodler%20Splash%20Image_0.jpg?itok=eNP08hG0" alt="Wyeth Illuma - Voice Doodler">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
惠氏 Illuma
<span>绘声赋色
</span>
</p>
</div>
<div class="splash__project" data-order="10" style="position: absolute; left: 762.732px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-762.732px, 21.9501px, 0px);">
<a href="/cn/work/5g-kung-fu-showdown" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/5G%20KFSD.png?itok=pOtEWU3z 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/5G%20KFSD.png?itok=fMzWppwg 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/5G%20KFSD.png?itok=1WThMPdn" alt="Huawei 5G Kung Fu Showdown">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
华为
<span>华为 5G 功夫
</span>
</p>
</div>
<div class="splash__project" data-order="2" style="position: absolute; left: 953.415px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-953.415px, 33.4168px, 0px);">
<a href="/cn/work/muqindetanzi" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Mother%20Blanket%20Splash%20Image.png?itok=PjF_xxT- 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Mother%20Blanket%20Splash%20Image.png?itok=h5_IVm0x 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Mother%20Blanket%20Splash%20Image.png?itok=llIbs5NA" alt="Mother Blanket">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Fundación Vivir &amp; CCPDA
<span>母亲的毯子
</span>
</p>
</div>
<div class="splash__project" data-order="13" style="position: absolute; left: 1144.1px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1144.1px, 44.8835px, 0px);">
<a href="/cn/work/find-your-place" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Kfc_%E4%BD%8D%E5%AD%90_Splash%20Image.jpg?itok=ZNkWg8OD 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Kfc_%E4%BD%8D%E5%AD%90_Splash%20Image.jpg?itok=zC55JqlN 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Kfc_%E4%BD%8D%E5%AD%90_Splash%20Image.jpg?itok=M7K_2WEk" alt="KFC - Find Your Place">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
肯德基
<span>位子
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 1334.78px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1334.78px, 56.3502px, 0px);">
<a href="/cn/work/vr-yimiao" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/VR%20Vaccine%20Splash%20Image.png?itok=ZpzOQbDo 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/VR%20Vaccine%20Splash%20Image.png?itok=JArNgkQ0 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/VR%20Vaccine%20Splash%20Image.png?itok=sSngb261" alt="VR Vaccine">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Hermes Pardini
<span>VR 疫苗
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 1525.46px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1525.46px, 67.8169px, 0px);">
<a href="/cn/work/guangtoukatong" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Bald%20Cartoons%20Splash%20Image.png?itok=dOFDk66B 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Bald%20Cartoons%20Splash%20Image.png?itok=38DfnqD0 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Bald%20Cartoons%20Splash%20Image.png?itok=bYscBAP_" alt="Bald Cartoons">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
GRAACC
<span>光头卡通
</span>
</p>
</div>
<div class="splash__project" data-order="11" style="position: absolute; left: 0px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(0px, -47.8334px, 0px);">
<a href="/cn/work/hwailai-wine-region" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_4.jpg?itok=f0Cc_Bda 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_4.jpg?itok=igyf29DS 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_4.jpg?itok=_QV-ubct" alt="Hwailai Wine Region">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
怀来
<span>张家口市怀来产区品牌塑造
</span>
</p>
</div>
<div class="splash__project" data-order="20" style="position: absolute; left: 190.683px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-190.683px, -36.3667px, 0px);">
<a href="/cn/work/can-great-wall-motors-survive-next-year" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_3.jpg?itok=i0wZ2N0X 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_3.jpg?itok=aizU75Kt 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_3.jpg?itok=ooBHR76t" alt="Great Wall Motors">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
长城汽车
<span>长城汽车挺得过明年吗？
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="15" style="position: absolute; left: 381.366px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-381.366px, -24.9px, 0px);">
<a href="/cn/work/ghibli-hybrid-china-launch" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Maserati_Splash-image_0.jpg?itok=xo5v6jOG 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Maserati_Splash-image_0.jpg?itok=oLBhfZIQ 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Maserati_Splash-image_0.jpg?itok=eovw0JiX" alt="Maserati - Ghibli Fenice Reveal">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
玛莎拉蒂
<span>锋芒初现
</span>
</p>
</div>
<div class="splash__project" data-order="11" style="position: absolute; left: 572.049px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-572.049px, -13.4333px, 0px);">
<a href="/cn/work/street-it-all" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_1.jpg?itok=EtWEPa_x 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_1.jpg?itok=NWKrhWIO 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_1.jpg?itok=UYC0FE6Y" alt="Zalando - Street It All">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Zalando
<span>尽在街头
</span>
</p>
</div>
<div class="splash__project" data-order="4" style="position: absolute; left: 762.732px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-762.732px, -1.9666px, 0px);">
<a href="/cn/work/shop-endless-wonders" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_0.jpg?itok=tHJNDWFh 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_0.jpg?itok=JIqZILTZ 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_0.jpg?itok=o8yZJGNZ" alt="Shop Endless Wonders">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
全球速卖通
<span>无限精彩的购物体验
</span>
</p>
</div>
<div class="splash__project" data-order="20" style="position: absolute; left: 953.415px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-953.415px, 9.5001px, 0px);">
<a href="/cn/work/buick-2021-chinese-new-year-campaign-family-reunions" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA.jpg?itok=JTrxQV7U 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA.jpg?itok=uqitdjK8 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA.jpg?itok=CK9gt6b2" alt="Buick 2021 CNY Campaign">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
别克
<span>天下别克的新春一刻
</span>
</p>
</div>
<div class="splash__project" data-order="5" style="position: absolute; left: 1144.1px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1144.1px, 20.9668px, 0px);">
<a href="/cn/work/green-instructions" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/LEGO%20Green%20Instructions%20Splash%20Image_0.jpg?itok=tx90fNfV 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/LEGO%20Green%20Instructions%20Splash%20Image_0.jpg?itok=rg5hqxiT 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/LEGO%20Green%20Instructions%20Splash%20Image_0.jpg?itok=2Ml5yQnC" alt="Green instructions - LEGO">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
LEGO
<span>绿色说明书
</span>
</p>
</div>
<div class="splash__project" data-order="20" style="position: absolute; left: 1334.78px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1334.78px, 32.4335px, 0px);">
<a href="/cn/work/sanchakou" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/spalsh%20image_huawei.jpg?itok=FwyGYg58 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/spalsh%20image_huawei.jpg?itok=jjTmN0h4 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/spalsh%20image_huawei.jpg?itok=NVwvxiB0" alt="Sanchakou - Huawei">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
华为
<span>三岔口
</span>
</p>
</div>
<div class="splash__project" data-order="18" style="position: absolute; left: 1525.46px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1525.46px, 43.9002px, 0px);">
<a href="/cn/work/when-theres-love-theres-way" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/splash%20image_benz.jpg?itok=UDlXznUK 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/splash%20image_benz.jpg?itok=ZZ5mjBwv 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/splash%20image_benz.jpg?itok=YLSxkPiI" alt="心之所向 - Mercedes Benz">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
梅赛德斯奔驰
<span>心之所向
</span>
</p>
</div>
<div class="splash__project" data-order="19" style="position: absolute; left: 0px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(0px, -71.7501px, 0px);">
<a href="/cn/work/not-just-cadbury-ad" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/cadbury_Splash%20Image.jpg?itok=kwhdthfb 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/cadbury_Splash%20Image.jpg?itok=kIZypQ47 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/cadbury_Splash%20Image.jpg?itok=_jANllXb" alt="Not Just a Cadbury Ad">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Cadbury
<span>这远不止是一支吉百利广告
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="12" style="position: absolute; left: 190.683px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-190.683px, -60.2834px, 0px);">
<a href="/cn/work/power-beginnings-2021" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Splash%20Image%20portrait_kfc%20jpg.jpg?itok=ipXfNFvE 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Splash%20Image%20portrait_kfc%20jpg.jpg?itok=MDHsz_Og 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Splash%20Image%20portrait_kfc%20jpg.jpg?itok=Kq-_7avl" alt="The Power of Beginnings 2021">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
肯德基
<span>2021 开始的力量
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 381.366px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-381.366px, -48.8167px, 0px);">
<a href="/cn/work/go-freshman" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/CHANDO%20Splash%20Image.jpg?itok=R7SmwNw1 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/CHANDO%20Splash%20Image.jpg?itok=i7_vEm6J 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/CHANDO%20Splash%20Image.jpg?itok=T8jBcKjz" alt="Chando 小朋友">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
自然堂
<span>冲吧！小朋友
</span>
</p>
</div>
<div class="splash__project" data-order="8" style="position: absolute; left: 572.049px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-572.049px, -37.35px, 0px);">
<a href="/cn/work/portraits-completed" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/kiwi_Splash%20Image.jpg?itok=2fJyRpRi 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/kiwi_Splash%20Image.jpg?itok=F7TPHfz8 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/kiwi_Splash%20Image.jpg?itok=1FXX0NOi" alt="SC Johnson - Portraits Completed">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
强生
<span>名画的下半身
</span>
</p>
</div>
<div class="splash__project" data-order="6" style="position: absolute; left: 762.732px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-762.732px, -25.8833px, 0px);">
<a href="/cn/work/52-mayors-danzhai" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/wanda_Splash%20Image.jpg?itok=5R_WL2rV 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/wanda_Splash%20Image.jpg?itok=36h4aF_V 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/wanda_Splash%20Image.jpg?itok=7hclcOa8" alt="Wanda - 52 Mayors of Danzhai">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
万达
<span>52 个镇长
</span>
</p>
</div>
<div class="splash__project" data-order="23" style="position: absolute; left: 953.415px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-953.415px, -14.4166px, 0px);">
<a href="/cn/work/buick-excelle-honest-test-drive" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Buick_Splash%20Image.jpg?itok=UUNqVFuX 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Buick_Splash%20Image.jpg?itok=8Zig10eH 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Buick_Splash%20Image.jpg?itok=nqKy8omf" alt="Buick - Buick Excelle 'Honest' Test Drive">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
别克
<span>别克英朗三缸诚实试驾
</span>
</p>
</div>
<div class="splash__project" data-order="5" style="position: absolute; left: 1144.1px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1144.1px, -2.9499px, 0px);">
<a href="/cn/work/dad" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash_Mobile_Dad-On.jpg?itok=U7fz0QPi 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash_Mobile_Dad-On.jpg?itok=bi5rWbUT 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash_Mobile_Dad-On.jpg?itok=6k0xBpHA" alt="Dove - Dad On">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
多芬
<span>认真的爸爸
</span>
</p>
</div>
<div class="splash__project" data-order="9" style="position: absolute; left: 1334.78px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1334.78px, 8.5168px, 0px);">
<a href="/cn/work/shes-mercedes" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/benz_Splash%20Image_2.jpg?itok=l6I6StZG 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/benz_Splash%20Image_2.jpg?itok=qGJ3rqZC 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/benz_Splash%20Image_2.jpg?itok=y0JTO9an" alt="Mercedes Benz - She's Mercedes">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
梅赛德斯奔驰
<span>She's Mercedes
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="22" style="position: absolute; left: 1525.46px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1525.46px, 19.9835px, 0px);">
<a href="/cn/work/we-make-today" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Splash%20Image%20%E7%AB%96.jpg?itok=pSLTXdYt 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Splash%20Image%20%E7%AB%96.jpg?itok=qb26pPID 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Splash%20Image%20%E7%AB%96.jpg?itok=nIKpW8o8" alt="Instagram - We Make Today">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Instagram
<span>我们创造今天
</span>
</p>
</div>
</div>
<div class="splash__projects splash__projects--clone" style="position: relative; height: 412.801px;">
<div class="splash__project splash__project--vertical" data-order="8" style="position: absolute; left: 0px; top: 0px;">
<a href="/cn/work/laigejintongjiuqile" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/KFC%202023%20CNY%20Splash%20Image.png?itok=jvEkWrHI 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/KFC%202023%20CNY%20Splash%20Image.png?itok=ZV9wzElm 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/KFC%202023%20CNY%20Splash%20Image.png?itok=QJTfRLq-" alt="">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
肯德基
<span>来个金桶就齐了
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 190.683px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-190.683px, 11.4667px, 0px);">
<a href="/cn/work/suiyuezaibian-tuanjudemeimiaobubian" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Coca-Cola%202023%20CNY%20Splash%20Image.png?itok=phj9Lh7Y 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Coca-Cola%202023%20CNY%20Splash%20Image.png?itok=p5idAWEW 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Coca-Cola%202023%20CNY%20Splash%20Image.png?itok=ofyMxtKi" alt="">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
可口可乐
<span>岁月在变 团聚的美妙不变
</span>
</p>
</div>
<div class="splash__project" data-order="13" style="position: absolute; left: 381.366px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-381.366px, 22.9334px, 0px);">
<a href="/cn/work/fenxiangkele" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Share-a-Coke_Splash-image.jpg?itok=gxMaiyKU 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Share-a-Coke_Splash-image.jpg?itok=gRuJpley 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Share-a-Coke_Splash-image.jpg?itok=QwJmWWGJ" alt="">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
可口可乐
<span>分享可乐
</span>
</p>
</div>
<div class="splash__project" data-order="16" style="position: absolute; left: 572.049px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-572.049px, 34.4001px, 0px);">
<a href="/cn/work/xuebiwutang" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Sprite%20Zero%20Sugar%20Splash%20Image.png?itok=l0MYZ6tA 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Sprite%20Zero%20Sugar%20Splash%20Image.png?itok=PfCxnwDu 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Sprite%20Zero%20Sugar%20Splash%20Image.png?itok=KBE_wQhK" alt="雪碧无糖">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
雪碧
<span>雪碧无糖
</span>
</p>
</div>
<div class="splash__project" data-order="12" style="position: absolute; left: 762.732px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-762.732px, 45.8668px, 0px);">
<a href="/cn/work/zizaichaoqun" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Mobile%20Image%20-%201200x800.jpg?itok=rnkLfe3f 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Mobile%20Image%20-%201200x800.jpg?itok=cV49JeWb 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Mobile%20Image%20-%201200x800.jpg?itok=wB5Q8PEe" alt="儿童数字人 谷雨">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
巴拉巴拉
<span>自在超裙
</span>
</p>
</div>
<div class="splash__project" data-order="19" style="position: absolute; left: 953.415px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-953.415px, 57.3335px, 0px);">
<a href="/cn/work/huniantuanju-jinshimeimiao" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/splash%20image%20-Cocacola%20CNY%202.png?itok=ZqE7sks0 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/splash%20image%20-Cocacola%20CNY%202.png?itok=IDrCrDF0 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/splash%20image%20-Cocacola%20CNY%202.png?itok=36LAK8Pe" alt="虎年团聚 尽释美妙">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
可口可乐
<span>虎年团聚 尽释美妙
</span>
</p>
</div>
<div class="splash__project" data-order="14" style="position: absolute; left: 1144.1px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1144.1px, 68.8002px, 0px);">
<a href="/cn/work/lelingma" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/splash%3Ahome%20page.jpg?itok=oqBF1h7w 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/splash%3Ahome%20page.jpg?itok=X1Gfz2OM 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/splash%3Ahome%20page.jpg?itok=2FWrBgaP" alt="乐龄码 Care Code">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
中共上海市委老干部局
<span>乐龄码
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 1334.78px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1334.78px, 80.2669px, 0px);">
<a href="/cn/work/meihaoshenghuo-gongtongxiangwang" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Tmall%2011.11%20Splash%20Image%20Regular.png?itok=0gXPf7u2 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Tmall%2011.11%20Splash%20Image%20Regular.png?itok=3Dzbs9rQ 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Tmall%2011.11%20Splash%20Image%20Regular.png?itok=KttnMzF3" alt="美好生活 共同向往 2021 天猫 双十一">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
天猫
<span>美好生活 共同向往
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="8" style="position: absolute; left: 1525.46px; top: 0px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1525.46px, 91.7336px, 0px);">
<a href="/cn/work/chunxiangwujin" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Nescafe%20Splash%20Image.png?itok=6S8B9tNI 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Nescafe%20Splash%20Image.png?itok=QI5qEssx 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Nescafe%20Splash%20Image.png?itok=4SPXfjWj" alt="Nescafe - 醇香无尽">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
雀巢咖啡
<span>醇香无尽
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="21" style="position: absolute; left: 0px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(0px, -23.9167px, 0px);">
<a href="/cn/work/xuniyouxiyimiao" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Portrait%20-%20InGameVaccine.png?itok=LzH5SOF5 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Portrait%20-%20InGameVaccine.png?itok=1m3h36aY 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Portrait%20-%20InGameVaccine.png?itok=rGLDCp1K" alt="">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
辉瑞
<span>虚拟游戏疫苗
</span>
</p>
</div>
<div class="splash__project" data-order="10" style="position: absolute; left: 190.683px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-190.683px, -12.45px, 0px);">
<a href="/cn/work/zheyuanbuzhishiyizhijibailiguanggao-2021" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Cadbury%20Splash%20Image%20Regular.png?itok=noeH4eT4 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Cadbury%20Splash%20Image%20Regular.png?itok=MTuTa3XS 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Cadbury%20Splash%20Image%20Regular.png?itok=xO4MevLx" alt="Cadbury - Not Just a Cadbury Ad 2021">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Cadbury
<span>这远不止是一支吉百利广告 2021
</span>
</p>
</div>
<div class="splash__project" data-order="9" style="position: absolute; left: 381.366px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-381.366px, -0.9833px, 0px);">
<a href="/cn/work/yishengwanwuwanwuguiyi" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%E6%A8%AA.jpg?itok=U7YlhHC2 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%E6%A8%AA.jpg?itok=oFhdLiC7 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%E6%A8%AA.jpg?itok=pRzjdMkd" alt="Huawei HarmonyOS">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
华为
<span>一生万物，万物归一
</span>
</p>
</div>
<div class="splash__project" data-order="4" style="position: absolute; left: 572.049px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-572.049px, 10.4834px, 0px);">
<a href="/cn/work/voice-doodler" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Voice%20Doodler%20Splash%20Image_0.jpg?itok=LbxoGuxF 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Voice%20Doodler%20Splash%20Image_0.jpg?itok=uTtCuN87 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Voice%20Doodler%20Splash%20Image_0.jpg?itok=eNP08hG0" alt="Wyeth Illuma - Voice Doodler">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
惠氏 Illuma
<span>绘声赋色
</span>
</p>
</div>
<div class="splash__project" data-order="10" style="position: absolute; left: 762.732px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-762.732px, 21.9501px, 0px);">
<a href="/cn/work/5g-kung-fu-showdown" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/5G%20KFSD.png?itok=pOtEWU3z 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/5G%20KFSD.png?itok=fMzWppwg 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/5G%20KFSD.png?itok=1WThMPdn" alt="Huawei 5G Kung Fu Showdown">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
华为
<span>华为 5G 功夫
</span>
</p>
</div>
<div class="splash__project" data-order="2" style="position: absolute; left: 953.415px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-953.415px, 33.4168px, 0px);">
<a href="/cn/work/muqindetanzi" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Mother%20Blanket%20Splash%20Image.png?itok=PjF_xxT- 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Mother%20Blanket%20Splash%20Image.png?itok=h5_IVm0x 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Mother%20Blanket%20Splash%20Image.png?itok=llIbs5NA" alt="Mother Blanket">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Fundación Vivir &amp; CCPDA
<span>母亲的毯子
</span>
</p>
</div>
<div class="splash__project" data-order="13" style="position: absolute; left: 1144.1px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1144.1px, 44.8835px, 0px);">
<a href="/cn/work/find-your-place" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Kfc_%E4%BD%8D%E5%AD%90_Splash%20Image.jpg?itok=ZNkWg8OD 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Kfc_%E4%BD%8D%E5%AD%90_Splash%20Image.jpg?itok=zC55JqlN 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Kfc_%E4%BD%8D%E5%AD%90_Splash%20Image.jpg?itok=M7K_2WEk" alt="KFC - Find Your Place">
 </a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
肯德基
<span>位子
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 1334.78px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1334.78px, 56.3502px, 0px);">
<a href="/cn/work/vr-yimiao" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/VR%20Vaccine%20Splash%20Image.png?itok=ZpzOQbDo 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/VR%20Vaccine%20Splash%20Image.png?itok=JArNgkQ0 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/VR%20Vaccine%20Splash%20Image.png?itok=sSngb261" alt="VR Vaccine">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Hermes Pardini
<span>VR 疫苗
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 1525.46px; top: 127.117px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1525.46px, 67.8169px, 0px);">
<a href="/cn/work/guangtoukatong" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Bald%20Cartoons%20Splash%20Image.png?itok=dOFDk66B 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Bald%20Cartoons%20Splash%20Image.png?itok=38DfnqD0 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Bald%20Cartoons%20Splash%20Image.png?itok=bYscBAP_" alt="Bald Cartoons">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
GRAACC
<span>光头卡通
</span>
</p>
</div>
<div class="splash__project" data-order="11" style="position: absolute; left: 0px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(0px, -47.8334px, 0px);">
<a href="/cn/work/hwailai-wine-region" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_4.jpg?itok=f0Cc_Bda 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_4.jpg?itok=igyf29DS 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_4.jpg?itok=_QV-ubct" alt="Hwailai Wine Region">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
怀来
<span>张家口市怀来产区品牌塑造
</span>
</p>
</div>
<div class="splash__project" data-order="20" style="position: absolute; left: 190.683px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-190.683px, -36.3667px, 0px);">
<a href="/cn/work/can-great-wall-motors-survive-next-year" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_3.jpg?itok=i0wZ2N0X 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_3.jpg?itok=aizU75Kt 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_3.jpg?itok=ooBHR76t" alt="Great Wall Motors">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
长城汽车
<span>长城汽车挺得过明年吗？
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="15" style="position: absolute; left: 381.366px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-381.366px, -24.9px, 0px);">
<a href="/cn/work/ghibli-hybrid-china-launch" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Maserati_Splash-image_0.jpg?itok=xo5v6jOG 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Maserati_Splash-image_0.jpg?itok=oLBhfZIQ 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Maserati_Splash-image_0.jpg?itok=eovw0JiX" alt="Maserati - Ghibli Fenice Reveal">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
玛莎拉蒂
<span>锋芒初现
</span>
</p>
</div>
<div class="splash__project" data-order="11" style="position: absolute; left: 572.049px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-572.049px, -13.4333px, 0px);">
<a href="/cn/work/street-it-all" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_1.jpg?itok=EtWEPa_x 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_1.jpg?itok=NWKrhWIO 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_1.jpg?itok=UYC0FE6Y" alt="Zalando - Street It All">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Zalando
<span>尽在街头
</span>
</p>
</div>
<div class="splash__project" data-order="4" style="position: absolute; left: 762.732px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-762.732px, -1.9666px, 0px);">
<a href="/cn/work/shop-endless-wonders" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_0.jpg?itok=tHJNDWFh 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_0.jpg?itok=JIqZILTZ 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_0.jpg?itok=o8yZJGNZ" alt="Shop Endless Wonders">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
全球速卖通
<span>无限精彩的购物体验
</span>
</p>
</div>
<div class="splash__project" data-order="20" style="position: absolute; left: 953.415px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-953.415px, 9.5001px, 0px);">
<a href="/cn/work/buick-2021-chinese-new-year-campaign-family-reunions" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA.jpg?itok=JTrxQV7U 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA.jpg?itok=uqitdjK8 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA.jpg?itok=CK9gt6b2" alt="Buick 2021 CNY Campaign">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
别克
<span>天下别克的新春一刻
</span>
</p>
</div>
<div class="splash__project" data-order="5" style="position: absolute; left: 1144.1px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1144.1px, 20.9668px, 0px);">
<a href="/cn/work/green-instructions" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/LEGO%20Green%20Instructions%20Splash%20Image_0.jpg?itok=tx90fNfV 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/LEGO%20Green%20Instructions%20Splash%20Image_0.jpg?itok=rg5hqxiT 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/LEGO%20Green%20Instructions%20Splash%20Image_0.jpg?itok=2Ml5yQnC" alt="Green instructions - LEGO">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
LEGO
<span>绿色说明书
</span>
</p>
</div>
<div class="splash__project" data-order="20" style="position: absolute; left: 1334.78px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1334.78px, 32.4335px, 0px);">
<a href="/cn/work/sanchakou" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/spalsh%20image_huawei.jpg?itok=FwyGYg58 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/spalsh%20image_huawei.jpg?itok=jjTmN0h4 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/spalsh%20image_huawei.jpg?itok=NVwvxiB0" alt="Sanchakou - Huawei">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
华为
<span>三岔口
</span>
</p>
</div>
<div class="splash__project" data-order="18" style="position: absolute; left: 1525.46px; top: 254.234px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1525.46px, 43.9002px, 0px);">
<a href="/cn/work/when-theres-love-theres-way" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/splash%20image_benz.jpg?itok=UDlXznUK 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/splash%20image_benz.jpg?itok=ZZ5mjBwv 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/splash%20image_benz.jpg?itok=YLSxkPiI" alt="心之所向 - Mercedes Benz">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
梅赛德斯奔驰
<span>心之所向
</span>
</p>
</div>
<div class="splash__project" data-order="19" style="position: absolute; left: 0px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(0px, -71.7501px, 0px);">
<a href="/cn/work/not-just-cadbury-ad" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/cadbury_Splash%20Image.jpg?itok=kwhdthfb 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/cadbury_Splash%20Image.jpg?itok=kIZypQ47 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/cadbury_Splash%20Image.jpg?itok=_jANllXb" alt="Not Just a Cadbury Ad">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Cadbury
<span>这远不止是一支吉百利广告
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="12" style="position: absolute; left: 190.683px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-190.683px, -60.2834px, 0px);">
<a href="/cn/work/power-beginnings-2021" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Splash%20Image%20portrait_kfc%20jpg.jpg?itok=ipXfNFvE 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Splash%20Image%20portrait_kfc%20jpg.jpg?itok=MDHsz_Og 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Splash%20Image%20portrait_kfc%20jpg.jpg?itok=Kq-_7avl" alt="The Power of Beginnings 2021">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
肯德基
<span>2021 开始的力量
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 381.366px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-381.366px, -48.8167px, 0px);">
<a href="/cn/work/go-freshman" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/CHANDO%20Splash%20Image.jpg?itok=R7SmwNw1 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/CHANDO%20Splash%20Image.jpg?itok=i7_vEm6J 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/CHANDO%20Splash%20Image.jpg?itok=T8jBcKjz" alt="Chando 小朋友">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
自然堂
<span>冲吧！小朋友
</span>
</p>
</div>
<div class="splash__project" data-order="8" style="position: absolute; left: 572.049px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-572.049px, -37.35px, 0px);">
<a href="/cn/work/portraits-completed" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/kiwi_Splash%20Image.jpg?itok=2fJyRpRi 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/kiwi_Splash%20Image.jpg?itok=F7TPHfz8 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/kiwi_Splash%20Image.jpg?itok=1FXX0NOi" alt="SC Johnson - Portraits Completed">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
强生
<span>名画的下半身
</span>
</p>
</div>
<div class="splash__project" data-order="6" style="position: absolute; left: 762.732px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-762.732px, -25.8833px, 0px);">
<a href="/cn/work/52-mayors-danzhai" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/wanda_Splash%20Image.jpg?itok=5R_WL2rV 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/wanda_Splash%20Image.jpg?itok=36h4aF_V 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/wanda_Splash%20Image.jpg?itok=7hclcOa8" alt="Wanda - 52 Mayors of Danzhai">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
万达
<span>52 个镇长
</span>
</p>
</div>
<div class="splash__project" data-order="23" style="position: absolute; left: 953.415px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-953.415px, -14.4166px, 0px);">
<a href="/cn/work/buick-excelle-honest-test-drive" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Buick_Splash%20Image.jpg?itok=UUNqVFuX 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Buick_Splash%20Image.jpg?itok=8Zig10eH 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Buick_Splash%20Image.jpg?itok=nqKy8omf" alt="Buick - Buick Excelle 'Honest' Test Drive">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
别克
<span>别克英朗三缸诚实试驾
</span>
</p>
</div>
<div class="splash__project" data-order="5" style="position: absolute; left: 1144.1px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1144.1px, -2.9499px, 0px);">
<a href="/cn/work/dad" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash_Mobile_Dad-On.jpg?itok=U7fz0QPi 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash_Mobile_Dad-On.jpg?itok=bi5rWbUT 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash_Mobile_Dad-On.jpg?itok=6k0xBpHA" alt="Dove - Dad On">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
多芬
<span>认真的爸爸
</span>
</p>
</div>
<div class="splash__project" data-order="9" style="position: absolute; left: 1334.78px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1334.78px, 8.5168px, 0px);">
<a href="/cn/work/shes-mercedes" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/benz_Splash%20Image_2.jpg?itok=l6I6StZG 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/benz_Splash%20Image_2.jpg?itok=qGJ3rqZC 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/benz_Splash%20Image_2.jpg?itok=y0JTO9an" alt="Mercedes Benz - She's Mercedes">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
梅赛德斯奔驰
<span>She's Mercedes
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="22" style="position: absolute; left: 1525.46px; top: 381.351px; transition-property: opacity, transform; transition-duration: 1s; transition-delay: 0ms; transform: translate3d(-1525.46px, 19.9835px, 0px);">
<a href="/cn/work/we-make-today" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Splash%20Image%20%E7%AB%96.jpg?itok=pSLTXdYt 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Splash%20Image%20%E7%AB%96.jpg?itok=qb26pPID 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Splash%20Image%20%E7%AB%96.jpg?itok=nIKpW8o8" alt="Instagram - We Make Today">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Instagram
<span>我们创造今天
</span>
</p>
</div>
</div>
<div class="splash__projects splash__projects--clone2" style="position: relative; height: 3782.41px;">
<div class="splash__project splash__project--vertical" data-order="8" style="position: absolute; left: 0px; top: 0px;">
<a href="/cn/work/laigejintongjiuqile" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/KFC%202023%20CNY%20Splash%20Image.png?itok=jvEkWrHI 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/KFC%202023%20CNY%20Splash%20Image.png?itok=ZV9wzElm 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/KFC%202023%20CNY%20Splash%20Image.png?itok=QJTfRLq-" alt="">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
肯德基
<span>来个金桶就齐了
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 0px; top: 105.067px;">
<a href="/cn/work/suiyuezaibian-tuanjudemeimiaobubian" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Coca-Cola%202023%20CNY%20Splash%20Image.png?itok=phj9Lh7Y 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Coca-Cola%202023%20CNY%20Splash%20Image.png?itok=p5idAWEW 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Coca-Cola%202023%20CNY%20Splash%20Image.png?itok=ofyMxtKi" alt="">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
可口可乐
<span>岁月在变 团聚的美妙不变
</span>
</p>
</div>
<div class="splash__project" data-order="13" style="position: absolute; left: 0px; top: 210.134px;">
<a href="/cn/work/fenxiangkele" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Share-a-Coke_Splash-image.jpg?itok=gxMaiyKU 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Share-a-Coke_Splash-image.jpg?itok=gRuJpley 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Share-a-Coke_Splash-image.jpg?itok=QwJmWWGJ" alt="">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
可口可乐
<span>分享可乐
</span>
</p>
</div>
<div class="splash__project" data-order="16" style="position: absolute; left: 0px; top: 315.201px;">
<a href="/cn/work/xuebiwutang" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Sprite%20Zero%20Sugar%20Splash%20Image.png?itok=l0MYZ6tA 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Sprite%20Zero%20Sugar%20Splash%20Image.png?itok=PfCxnwDu 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Sprite%20Zero%20Sugar%20Splash%20Image.png?itok=KBE_wQhK" alt="雪碧无糖">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
雪碧
<span>雪碧无糖
</span>
</p>
</div>
<div class="splash__project" data-order="12" style="position: absolute; left: 0px; top: 420.268px;">
<a href="/cn/work/zizaichaoqun" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Mobile%20Image%20-%201200x800.jpg?itok=rnkLfe3f 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Mobile%20Image%20-%201200x800.jpg?itok=cV49JeWb 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Mobile%20Image%20-%201200x800.jpg?itok=wB5Q8PEe" alt="儿童数字人 谷雨">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
巴拉巴拉
<span>自在超裙
</span>
</p>
</div>
<div class="splash__project" data-order="19" style="position: absolute; left: 0px; top: 525.335px;">
<a href="/cn/work/huniantuanju-jinshimeimiao" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/splash%20image%20-Cocacola%20CNY%202.png?itok=ZqE7sks0 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/splash%20image%20-Cocacola%20CNY%202.png?itok=IDrCrDF0 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/splash%20image%20-Cocacola%20CNY%202.png?itok=36LAK8Pe" alt="虎年团聚 尽释美妙">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
可口可乐
<span>虎年团聚 尽释美妙
</span>
</p>
</div>
<div class="splash__project" data-order="14" style="position: absolute; left: 0px; top: 630.402px;">
<a href="/cn/work/lelingma" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/splash%3Ahome%20page.jpg?itok=oqBF1h7w 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/splash%3Ahome%20page.jpg?itok=X1Gfz2OM 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/splash%3Ahome%20page.jpg?itok=2FWrBgaP" alt="乐龄码 Care Code">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
中共上海市委老干部局
<span>乐龄码
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 0px; top: 735.469px;">
<a href="/cn/work/meihaoshenghuo-gongtongxiangwang" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Tmall%2011.11%20Splash%20Image%20Regular.png?itok=0gXPf7u2 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Tmall%2011.11%20Splash%20Image%20Regular.png?itok=3Dzbs9rQ 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Tmall%2011.11%20Splash%20Image%20Regular.png?itok=KttnMzF3" alt="美好生活 共同向往 2021 天猫 双十一">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
天猫
<span>美好生活 共同向往
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="8" style="position: absolute; left: 0px; top: 840.536px;">
<a href="/cn/work/chunxiangwujin" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Nescafe%20Splash%20Image.png?itok=6S8B9tNI 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Nescafe%20Splash%20Image.png?itok=QI5qEssx 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Nescafe%20Splash%20Image.png?itok=4SPXfjWj" alt="Nescafe - 醇香无尽">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
雀巢咖啡
<span>醇香无尽
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="21" style="position: absolute; left: 0px; top: 945.603px;">
<a href="/cn/work/xuniyouxiyimiao" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Portrait%20-%20InGameVaccine.png?itok=LzH5SOF5 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Portrait%20-%20InGameVaccine.png?itok=1m3h36aY 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Portrait%20-%20InGameVaccine.png?itok=rGLDCp1K" alt="">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
辉瑞
<span>虚拟游戏疫苗
</span>
</p>
</div>
<div class="splash__project" data-order="10" style="position: absolute; left: 0px; top: 1050.67px;">
<a href="/cn/work/zheyuanbuzhishiyizhijibailiguanggao-2021" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Cadbury%20Splash%20Image%20Regular.png?itok=noeH4eT4 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Cadbury%20Splash%20Image%20Regular.png?itok=MTuTa3XS 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Cadbury%20Splash%20Image%20Regular.png?itok=xO4MevLx" alt="Cadbury - Not Just a Cadbury Ad 2021">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Cadbury
<span>这远不止是一支吉百利广告 2021
</span>
</p>
</div>
<div class="splash__project" data-order="9" style="position: absolute; left: 0px; top: 1155.74px;">
<a href="/cn/work/yishengwanwuwanwuguiyi" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%E6%A8%AA.jpg?itok=U7YlhHC2 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%E6%A8%AA.jpg?itok=oFhdLiC7 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%E6%A8%AA.jpg?itok=pRzjdMkd" alt="Huawei HarmonyOS">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
华为
<span>一生万物，万物归一
</span>
</p>
</div>
<div class="splash__project" data-order="4" style="position: absolute; left: 0px; top: 1260.8px;">
<a href="/cn/work/voice-doodler" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Voice%20Doodler%20Splash%20Image_0.jpg?itok=LbxoGuxF 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Voice%20Doodler%20Splash%20Image_0.jpg?itok=uTtCuN87 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Voice%20Doodler%20Splash%20Image_0.jpg?itok=eNP08hG0" alt="Wyeth Illuma - Voice Doodler">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
惠氏 Illuma
<span>绘声赋色
</span>
</p>
</div>
<div class="splash__project" data-order="10" style="position: absolute; left: 0px; top: 1365.87px;">
<a href="/cn/work/5g-kung-fu-showdown" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/5G%20KFSD.png?itok=pOtEWU3z 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/5G%20KFSD.png?itok=fMzWppwg 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/5G%20KFSD.png?itok=1WThMPdn" alt="Huawei 5G Kung Fu Showdown">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
华为
<span>华为 5G 功夫
</span>
</p>
</div>
<div class="splash__project" data-order="2" style="position: absolute; left: 0px; top: 1470.94px;">
<a href="/cn/work/muqindetanzi" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Mother%20Blanket%20Splash%20Image.png?itok=PjF_xxT- 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Mother%20Blanket%20Splash%20Image.png?itok=h5_IVm0x 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Mother%20Blanket%20Splash%20Image.png?itok=llIbs5NA" alt="Mother Blanket">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Fundación Vivir &amp; CCPDA
<span>母亲的毯子
</span>
</p>
</div>
<div class="splash__project" data-order="13" style="position: absolute; left: 0px; top: 1576.01px;">
<a href="/cn/work/find-your-place" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Kfc_%E4%BD%8D%E5%AD%90_Splash%20Image.jpg?itok=ZNkWg8OD 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Kfc_%E4%BD%8D%E5%AD%90_Splash%20Image.jpg?itok=zC55JqlN 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Kfc_%E4%BD%8D%E5%AD%90_Splash%20Image.jpg?itok=M7K_2WEk" alt="KFC - Find Your Place">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
肯德基
<span>位子
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 0px; top: 1681.07px;">
<a href="/cn/work/vr-yimiao" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/VR%20Vaccine%20Splash%20Image.png?itok=ZpzOQbDo 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/VR%20Vaccine%20Splash%20Image.png?itok=JArNgkQ0 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/VR%20Vaccine%20Splash%20Image.png?itok=sSngb261" alt="VR Vaccine">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Hermes Pardini
<span>VR 疫苗
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 0px; top: 1786.14px;">
<a href="/cn/work/guangtoukatong" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Bald%20Cartoons%20Splash%20Image.png?itok=dOFDk66B 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Bald%20Cartoons%20Splash%20Image.png?itok=38DfnqD0 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Bald%20Cartoons%20Splash%20Image.png?itok=bYscBAP_" alt="Bald Cartoons">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
GRAACC
<span>光头卡通
</span>
</p>
</div>
<div class="splash__project" data-order="11" style="position: absolute; left: 0px; top: 1891.21px;">
<a href="/cn/work/hwailai-wine-region" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_4.jpg?itok=f0Cc_Bda 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_4.jpg?itok=igyf29DS 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_4.jpg?itok=_QV-ubct" alt="Hwailai Wine Region">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
怀来
<span>张家口市怀来产区品牌塑造
</span>
</p>
</div>
<div class="splash__project" data-order="20" style="position: absolute; left: 0px; top: 1996.27px;">
<a href="/cn/work/can-great-wall-motors-survive-next-year" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_3.jpg?itok=i0wZ2N0X 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_3.jpg?itok=aizU75Kt 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_3.jpg?itok=ooBHR76t" alt="Great Wall Motors">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
长城汽车
<span>长城汽车挺得过明年吗？
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="15" style="position: absolute; left: 0px; top: 2101.34px;">
<a href="/cn/work/ghibli-hybrid-china-launch" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Maserati_Splash-image_0.jpg?itok=xo5v6jOG 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Maserati_Splash-image_0.jpg?itok=oLBhfZIQ 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Maserati_Splash-image_0.jpg?itok=eovw0JiX" alt="Maserati - Ghibli Fenice Reveal">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
玛莎拉蒂
<span>锋芒初现
</span>
</p>
</div>
<div class="splash__project" data-order="11" style="position: absolute; left: 0px; top: 2206.41px;">
<a href="/cn/work/street-it-all" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_1.jpg?itok=EtWEPa_x 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_1.jpg?itok=NWKrhWIO 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_1.jpg?itok=UYC0FE6Y" alt="Zalando - Street It All">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Zalando
<span>尽在街头
</span>
</p>
</div>
<div class="splash__project" data-order="4" style="position: absolute; left: 0px; top: 2311.47px;">
<a href="/cn/work/shop-endless-wonders" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_0.jpg?itok=tHJNDWFh 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_0.jpg?itok=JIqZILTZ 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA_0.jpg?itok=o8yZJGNZ" alt="Shop Endless Wonders">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
全球速卖通
<span>无限精彩的购物体验
</span>
</p>
</div>
<div class="splash__project" data-order="20" style="position: absolute; left: 0px; top: 2416.54px;">
<a href="/cn/work/buick-2021-chinese-new-year-campaign-family-reunions" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash%20Image%20%E6%A8%AA.jpg?itok=JTrxQV7U 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash%20Image%20%E6%A8%AA.jpg?itok=uqitdjK8 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash%20Image%20%E6%A8%AA.jpg?itok=CK9gt6b2" alt="Buick 2021 CNY Campaign">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
别克
<span>天下别克的新春一刻
</span>
</p>
</div>
<div class="splash__project" data-order="5" style="position: absolute; left: 0px; top: 2521.61px;">
<a href="/cn/work/green-instructions" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/LEGO%20Green%20Instructions%20Splash%20Image_0.jpg?itok=tx90fNfV 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/LEGO%20Green%20Instructions%20Splash%20Image_0.jpg?itok=rg5hqxiT 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/LEGO%20Green%20Instructions%20Splash%20Image_0.jpg?itok=2Ml5yQnC" alt="Green instructions - LEGO">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
LEGO
<span>绿色说明书
</span>
</p>
</div>
<div class="splash__project" data-order="20" style="position: absolute; left: 0px; top: 2626.68px;">
<a href="/cn/work/sanchakou" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/spalsh%20image_huawei.jpg?itok=FwyGYg58 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/spalsh%20image_huawei.jpg?itok=jjTmN0h4 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/spalsh%20image_huawei.jpg?itok=NVwvxiB0" alt="Sanchakou - Huawei">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
华为
<span>三岔口
</span>
</p>
</div>
<div class="splash__project" data-order="18" style="position: absolute; left: 0px; top: 2731.74px;">
<a href="/cn/work/when-theres-love-theres-way" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/splash%20image_benz.jpg?itok=UDlXznUK 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/splash%20image_benz.jpg?itok=ZZ5mjBwv 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/splash%20image_benz.jpg?itok=YLSxkPiI" alt="心之所向 - Mercedes Benz">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
梅赛德斯奔驰
<span>心之所向
</span>
</p>
</div>
<div class="splash__project" data-order="19" style="position: absolute; left: 0px; top: 2836.81px;">
<a href="/cn/work/not-just-cadbury-ad" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/cadbury_Splash%20Image.jpg?itok=kwhdthfb 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/cadbury_Splash%20Image.jpg?itok=kIZypQ47 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/cadbury_Splash%20Image.jpg?itok=_jANllXb" alt="Not Just a Cadbury Ad">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Cadbury
<span>这远不止是一支吉百利广告
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="12" style="position: absolute; left: 0px; top: 2941.88px;">
<a href="/cn/work/power-beginnings-2021" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Splash%20Image%20portrait_kfc%20jpg.jpg?itok=ipXfNFvE 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Splash%20Image%20portrait_kfc%20jpg.jpg?itok=MDHsz_Og 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Splash%20Image%20portrait_kfc%20jpg.jpg?itok=Kq-_7avl" alt="The Power of Beginnings 2021">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
肯德基
<span>2021 开始的力量
</span>
</p>
</div>
<div class="splash__project" data-order="17" style="position: absolute; left: 0px; top: 3046.94px;">
<a href="/cn/work/go-freshman" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/CHANDO%20Splash%20Image.jpg?itok=R7SmwNw1 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/CHANDO%20Splash%20Image.jpg?itok=i7_vEm6J 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/CHANDO%20Splash%20Image.jpg?itok=T8jBcKjz" alt="Chando 小朋友">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
自然堂
<span>冲吧！小朋友
</span>
</p>
</div>
<div class="splash__project" data-order="8" style="position: absolute; left: 0px; top: 3152.01px;">
<a href="/cn/work/portraits-completed" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/kiwi_Splash%20Image.jpg?itok=2fJyRpRi 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/kiwi_Splash%20Image.jpg?itok=F7TPHfz8 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/kiwi_Splash%20Image.jpg?itok=1FXX0NOi" alt="SC Johnson - Portraits Completed">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
强生
<span>名画的下半身
</span>
</p>
</div>
<div class="splash__project" data-order="6" style="position: absolute; left: 0px; top: 3257.08px;">
<a href="/cn/work/52-mayors-danzhai" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/wanda_Splash%20Image.jpg?itok=5R_WL2rV 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/wanda_Splash%20Image.jpg?itok=36h4aF_V 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/wanda_Splash%20Image.jpg?itok=7hclcOa8" alt="Wanda - 52 Mayors of Danzhai">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
万达
<span>52 个镇长
</span>
</p>
</div>
<div class="splash__project" data-order="23" style="position: absolute; left: 0px; top: 3362.14px;">
<a href="/cn/work/buick-excelle-honest-test-drive" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Buick_Splash%20Image.jpg?itok=UUNqVFuX 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Buick_Splash%20Image.jpg?itok=8Zig10eH 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Buick_Splash%20Image.jpg?itok=nqKy8omf" alt="Buick - Buick Excelle 'Honest' Test Drive">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
别克
<span>别克英朗三缸诚实试驾
</span>
</p>
</div>
<div class="splash__project" data-order="5" style="position: absolute; left: 0px; top: 3467.21px;">
<a href="/cn/work/dad" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/Splash_Mobile_Dad-On.jpg?itok=U7fz0QPi 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/Splash_Mobile_Dad-On.jpg?itok=bi5rWbUT 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/Splash_Mobile_Dad-On.jpg?itok=6k0xBpHA" alt="Dove - Dad On">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
多芬
<span>认真的爸爸
</span>
</p>
</div>
<div class="splash__project" data-order="9" style="position: absolute; left: 0px; top: 3572.28px;">
<a href="/cn/work/shes-mercedes" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_regular_images_small/public/work/splash/regular/benz_Splash%20Image_2.jpg?itok=l6I6StZG 300w, /cn/sites/g/files/dhpsjz236/files/styles/splash_image_thumbnail/public/work/splash/regular/benz_Splash%20Image_2.jpg?itok=qGJ3rqZC 720w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_image_medium/public/work/splash/regular/benz_Splash%20Image_2.jpg?itok=y0JTO9an" alt="Mercedes Benz - She's Mercedes">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
梅赛德斯奔驰
<span>She's Mercedes
</span>
</p>
</div>
<div class="splash__project splash__project--vertical" data-order="22" style="position: absolute; left: 0px; top: 3677.35px;">
<a href="/cn/work/we-make-today" class="splash__img " tabindex="-1">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_images_small/public/work/splash/portrait/Splash%20Image%20%E7%AB%96.jpg?itok=pSLTXdYt 200w, /cn/sites/g/files/dhpsjz236/files/styles/splash_portrait_image_480x720/public/work/splash/portrait/Splash%20Image%20%E7%AB%96.jpg?itok=qb26pPID 480w" sizes="50vw" src="/cn/sites/g/files/dhpsjz236/files/styles/splash_small_image/public/work/splash/portrait/Splash%20Image%20%E7%AB%96.jpg?itok=nIKpW8o8" alt="Instagram - We Make Today">
</a>
<div class="splash__overlay undefined"></div>
<p class="splash__description">
Instagram
<span>我们创造今天
</span>
</p>
</div>
</div></div>
</div>
<div class="slider__wrapper slider__wrapper--splash">
<svg class="slider__in--splash" width="30" height="20" viewBox="0 0 31 20" xmlns="http://www.w3.org/2000/svg" alt="zoom-in"><path d="M1 1h29v19H1z" fill="none" fill-rule="evenodd"></path></svg>
<label for="slider">Change Zoom</label>
<span class="slider__left">|</span>
<input type="range" min="1" max="64" value="1" class="slider" id="slider" autocomplete="off">
<span class="slider__right">|</span>
<svg class="slider__out--splash" width="30" height="20" viewBox="0 0 29 20" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd" alt="zoom-out"><path d="M1 1h12v7H1zM1 12h12v7H1zM16 1h12v7H16zM16 12h12v7H16z"></path></g></svg>
</div>
</section>
<div class="section--locker js-locker section--red is-locked" style="height: 0px;">
<section class="section section--v-center hero hero--red section--lockee js-lockee ">
<div class="section__mask"></div>
<div class="container">
<div class="hero--con">
<p>如今人们对品牌的期望比过往任何时候都多，他们期望品牌能够超越界限。我们在世界众多的交集之处不断创新，为客户提供最佳的增长方案。奥美启发品牌和人们去影响世界。</p>
</div>
</div>
</section>
</div>
<div class="has-sticky section--default">
<section id="work" class="local-market section section--sticky work js-home2 js-view-dom-id-f88a551654ef7fb7b646c718afb7afa17a6bdb3853c03d6d8798a2c9378190bc" data-once="ajax-pager">
<div class="section__mask"></div>
<div class="container">
<form class="views-exposed-form bef-exposed-form" data-bef-auto-submit-full-form="" data-bef-auto-submit="" data-bef-auto-submit-delay="500" data-drupal-selector="views-exposed-form-our-work-grid-our-work-grid" action="/cn/home" method="get" id="views-exposed-form-our-work-grid-our-work-grid" accept-charset="UTF-8" data-once="exposed-form bef-auto-submit">
<ul id="edit-field-category-target-id" class="section__grid-filters work__categories" style="--work-scroll-opacity: 1;"><li> <label class="js-form-item form-item js-work-cat-toggles js-form-type-radio form-item-field-category-target-id js-form-item-field-category-target-id">
<input data-drupal-selector="edit-field-category-target-id-all" type="radio" id="edit-field-category-target-id-all" name="field_category_target_id" value="All" checked="checked" class="form-radio" data-url="/">
<span for="edit-field-category-target-id-all" class="option">- 任意 -</span><span>&nbsp;</span>
</label>
<label class="js-form-item form-item js-work-cat-toggles js-form-type-radio form-item-field-category-target-id js-form-item-field-category-target-id">
<noscript><a href="/cn/work/advertising" title="advertising">advertising</a></noscript>
<input data-drupal-selector="edit-field-category-target-id-1" type="radio" id="edit-field-category-target-id-1" name="field_category_target_id" value="1" class="form-radio" data-url="/cn/work/advertising/">
<span for="edit-field-category-target-id-1" class="option">广告</span><span>&nbsp;</span>
</label>
<label class="js-form-item form-item js-work-cat-toggles js-form-type-radio form-item-field-category-target-id js-form-item-field-category-target-id">
<noscript><a href="/cn/work/pr" title="pr">pr</a></noscript>
<input data-drupal-selector="edit-field-category-target-id-11" type="radio" id="edit-field-category-target-id-11" name="field_category_target_id" value="11" class="form-radio" data-url="/cn/work/pr/">
<span for="edit-field-category-target-id-11" class="option">公关</span><span>&nbsp;</span>
</label>
<label class="js-form-item form-item js-work-cat-toggles js-form-type-radio form-item-field-category-target-id js-form-item-field-category-target-id">
<noscript><a href="/cn/work/experience" title="experience">experience</a></noscript>
<input data-drupal-selector="edit-field-category-target-id-31" type="radio" id="edit-field-category-target-id-31" name="field_category_target_id" value="31" class="form-radio" data-url="/cn/work/experience/">
<span for="edit-field-category-target-id-31" class="option">消费者体验</span><span>&nbsp;</span>
</label>
<label class="js-form-item form-item js-work-cat-toggles js-form-type-radio form-item-field-category-target-id js-form-item-field-category-target-id">
<noscript><a href="/cn/work/health" title="health">health</a></noscript>
<input data-drupal-selector="edit-field-category-target-id-36" type="radio" id="edit-field-category-target-id-36" name="field_category_target_id" value="36" class="form-radio" data-url="/cn/work/health/">
<span for="edit-field-category-target-id-36" class="option">健康</span><span>&nbsp;</span>
</label>
<label class="js-form-item form-item js-work-cat-toggles js-form-type-radio form-item-field-category-target-id js-form-item-field-category-target-id">
<noscript><a href="/cn/work/consulting" title="consulting">consulting</a></noscript>
<input data-drupal-selector="edit-field-category-target-id-21" type="radio" id="edit-field-category-target-id-21" name="field_category_target_id" value="21" class="form-radio" data-url="/cn/work/consulting/">
<span for="edit-field-category-target-id-21" class="option">咨询</span><span>&nbsp;</span>
</label>
</li></ul>
<div class="section__grid-work-search" style="">
<ul class="section__grid-utilities section__grid-utilities--mobile" style="opacity: 1;">
<li class="search-form-wrap">
<div class="section__search-form js-work-search  " style="" data-search-category="Work">
<div class="input">
<input data-bef-auto-submit-exclude="" data-drupal-selector="edit-combine" type="text" id="edit-combine" name="combine" value="" size="30" maxlength="128" class="form-text" aria-label="Search work">
</div>
<button class="section__grid-utility">
<svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 14 14" role="img" aria-labelledby="worksearch"><title id="worksearch">Search</title><path fill="none" stroke="currentColor" stroke-width=".75" d="M10.93 5.57a4.95 4.95 0 0 1-4.97 4.94A4.95 4.95 0 0 1 1 5.57 4.95 4.95 0 0 1 5.96.64a4.96 4.96 0 0 1 4.97 4.93zM9.37 9.35L13.04 13 9.37 9.35z"></path></svg>
</button>
<button class="section__grid-utility" type="reset">
<svg xmlns="http://www.w3.org/2000/svg" width="17" height="15" viewBox="0 0 17 15" role="img" aria-labelledby="workreset"><title id="workreset">Reset</title><path fill="none" stroke="currentColor" d="M15.64.8L1.43 15m14.14 0L1.36.8"></path></svg>
</button>
</div>
<div class="search-form-showing section__grid-right section__grid-page js-section-page-view search-icons is-home">
<p><span class="show">Showing:</span> <a href="javascript:;" class="section__page-view-link js-section-page-link"><span class="js-section-page-view-text">cn</span> <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 20.1 20.1"><path fill="none" d="M10.1 0v20.1m10-10H0"></path></svg></a></p>
</div>
<div class="search-form-showing section__grid-right section__grid-page js-section-page-view is-home">
<p>Showing: <a href="/#work" class="section__page-view-link js-section-page-link" target="_blank" rel="nofollow noreferrer"><span class="js-section-page-view-text">All</span> <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 20.1 20.1"><path fill="none" d="M10.1 0v20.1m10-10H0"></path></svg></a></p>
</div>
<ul class="adv-search-list" style="">
<li class="adv-search-mob-icon">
<svg style="display: none" xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 14 14" role="img" aria-labelledby="worksearch">
<title id="worksearch">Search</title>
<path fill="none" stroke="currentColor" stroke-width=".75" d="M10.93 5.57a4.95 4.95 0 0 1-4.97 4.94A4.95 4.95 0 0 1 1 5.57 4.95 4.95 0 0 1 5.96.64a4.96 4.96 0 0 1 4.97 4.93zM9.37 9.35L13.04 13 9.37 9.35z"></path>
</svg>
</li>
<li><a class="industries " href="#search-industries">产业领域,</a> </li>
<li><a class="clients " href="#search-clients">客户群</a> </li>
</ul>
<span class="adv-search-wrk-icon adv-search-icon advsearchicon " style="">
 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%">
<path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path>
</svg>
</span>
<div id="search-capabilities" class="adv-search-list-con" style="display: none">
</div>
<div id="search-industries" class="adv-search-list-con" style="display: none">
<ul data-drupal-selector="edit-field-industry-target-id" id="edit-field-industry-target-id--wrapper" class="fieldgroup form-composite form-checkboxes grid small--grid--2up large--grid--3up" name="field_industry_target_id">
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-6181" type="checkbox" id="edit-field-industry-target-id-6181" name="field_industry_target_id[6181]" value="6181" class="form-checkbox">
<label for="edit-field-industry-target-id-6181" class="option"> <a class="subcategories" title="automobile">automobile <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-226" type="checkbox" id="edit-field-industry-target-id-226" name="field_industry_target_id[226]" value="226" class="form-checkbox">
<label for="edit-field-industry-target-id-226" class="option"> <a class="subcategories" title="汽车业">汽车业 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-236" type="checkbox" id="edit-field-industry-target-id-236" name="field_industry_target_id[236]" value="236" class="form-checkbox">
<label for="edit-field-industry-target-id-236" class="option"> <a class="subcategories" title="饮料业">饮料业 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-246" type="checkbox" id="edit-field-industry-target-id-246" name="field_industry_target_id[246]" value="246" class="form-checkbox">
<label for="edit-field-industry-target-id-246" class="option"> <a class="subcategories" title="慈善组织">慈善组织 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-256" type="checkbox" id="edit-field-industry-target-id-256" name="field_industry_target_id[256]" value="256" class="form-checkbox">
<label for="edit-field-industry-target-id-256" class="option"> <a class="subcategories" title="服装">服装 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-71" type="checkbox" id="edit-field-industry-target-id-71" name="field_industry_target_id[71]" value="71" class="form-checkbox">
<label for="edit-field-industry-target-id-71" class="option"> <a class="subcategories" title="建筑业">建筑业 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-281" type="checkbox" id="edit-field-industry-target-id-281" name="field_industry_target_id[281]" value="281" class="form-checkbox">
<label for="edit-field-industry-target-id-281" class="option"> <a class="subcategories" title="消费类电子产品">消费类电子产品 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-286" type="checkbox" id="edit-field-industry-target-id-286" name="field_industry_target_id[286]" value="286" class="form-checkbox">
<label for="edit-field-industry-target-id-286" class="option"> <a class="subcategories" title="消费品">消费品 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-291" type="checkbox" id="edit-field-industry-target-id-291" name="field_industry_target_id[291]" value="291" class="form-checkbox">
<label for="edit-field-industry-target-id-291" class="option"> <a class="subcategories" title="化妆品">化妆品 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-321" type="checkbox" id="edit-field-industry-target-id-321" name="field_industry_target_id[321]" value="321" class="form-checkbox">
<label for="edit-field-industry-target-id-321" class="option"> <a class="subcategories" title="餐饮">餐饮 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-326" type="checkbox" id="edit-field-industry-target-id-326" name="field_industry_target_id[326]" value="326" class="form-checkbox">
<label for="edit-field-industry-target-id-326" class="option"> <a class="subcategories" title="政府">政府 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-331" type="checkbox" id="edit-field-industry-target-id-331" name="field_industry_target_id[331]" value="331" class="form-checkbox">
<label for="edit-field-industry-target-id-331" class="option"> <a class="subcategories" title="卫生保健">卫生保健 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-381" type="checkbox" id="edit-field-industry-target-id-381" name="field_industry_target_id[381]" value="381" class="form-checkbox">
<label for="edit-field-industry-target-id-381" class="option"> <a class="subcategories" title="医药品">医药品 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-396" type="checkbox" id="edit-field-industry-target-id-396" name="field_industry_target_id[396]" value="396" class="form-checkbox">
<label for="edit-field-industry-target-id-396" class="option"> <a class="subcategories" title="零售业">零售业 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-401" type="checkbox" id="edit-field-industry-target-id-401" name="field_industry_target_id[401]" value="401" class="form-checkbox">
<label for="edit-field-industry-target-id-401" class="option"> <a class="subcategories" title="技术">技术 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-industry-target-id-406" type="checkbox" id="edit-field-industry-target-id-406" name="field_industry_target_id[406]" value="406" class="form-checkbox">
<label for="edit-field-industry-target-id-406" class="option"> <a class="subcategories" title="电信业">电信业 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
</ul>
</div>
<div id="search-clients" class="adv-search-list-con" style="display: none">
<ul data-drupal-selector="edit-field-clients-target-id" id="edit-field-clients-target-id--wrapper" class="fieldgroup form-composite form-checkboxes grid small--grid--2up large--grid--3up" name="field_clients_target_id">
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1076" type="checkbox" id="edit-field-clients-target-id-1076" name="field_clients_target_id[1076]" value="1076" class="form-checkbox">
<label for="edit-field-clients-target-id-1076" class="option"> <a class="subcategories" title="Cadbury">Cadbury <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1401" type="checkbox" id="edit-field-clients-target-id-1401" name="field_clients_target_id[1401]" value="1401" class="form-checkbox">
<label for="edit-field-clients-target-id-1401" class="option"> <a class="subcategories" title="Fundación Vivir &amp; CCPDA">Fundación Vivir &amp; CCPDA <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1431" type="checkbox" id="edit-field-clients-target-id-1431" name="field_clients_target_id[1431]" value="1431" class="form-checkbox">
<label for="edit-field-clients-target-id-1431" class="option"> <a class="subcategories" title="GRAACC">GRAACC <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-876" type="checkbox" id="edit-field-clients-target-id-876" name="field_clients_target_id[876]" value="876" class="form-checkbox">
<label for="edit-field-clients-target-id-876" class="option"> <a class="subcategories" title="Greenpeace">Greenpeace <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1421" type="checkbox" id="edit-field-clients-target-id-1421" name="field_clients_target_id[1421]" value="1421" class="form-checkbox">
<label for="edit-field-clients-target-id-1421" class="option"> <a class="subcategories" title="Hermes Pardini">Hermes Pardini <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1331" type="checkbox" id="edit-field-clients-target-id-1331" name="field_clients_target_id[1331]" value="1331" class="form-checkbox">
<label for="edit-field-clients-target-id-1331" class="option"> <a class="subcategories" title="Instagram">Instagram <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1266" type="checkbox" id="edit-field-clients-target-id-1266" name="field_clients_target_id[1266]" value="1266" class="form-checkbox">
<label for="edit-field-clients-target-id-1266" class="option"> <a class="subcategories" title="LEGO">LEGO <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-846" type="checkbox" id="edit-field-clients-target-id-846" name="field_clients_target_id[846]" value="846" class="form-checkbox">
<label for="edit-field-clients-target-id-846" class="option"> <a class="subcategories" title="Petz">Petz <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-886" type="checkbox" id="edit-field-clients-target-id-886" name="field_clients_target_id[886]" value="886" class="form-checkbox">
<label for="edit-field-clients-target-id-886" class="option"> <a class="subcategories" title="Savlon">Savlon <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1321" type="checkbox" id="edit-field-clients-target-id-1321" name="field_clients_target_id[1321]" value="1321" class="form-checkbox">
<label for="edit-field-clients-target-id-1321" class="option"> <a class="subcategories" title="Zalando">Zalando <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1051" type="checkbox" id="edit-field-clients-target-id-1051" name="field_clients_target_id[1051]" value="1051" class="form-checkbox">
<label for="edit-field-clients-target-id-1051" class="option"> <a class="subcategories" title="万达">万达 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1571" type="checkbox" id="edit-field-clients-target-id-1571" name="field_clients_target_id[1571]" value="1571" class="form-checkbox">
<label for="edit-field-clients-target-id-1571" class="option"> <a class="subcategories" title="中共上海市委老干部局">中共上海市委老干部局 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1381" type="checkbox" id="edit-field-clients-target-id-1381" name="field_clients_target_id[1381]" value="1381" class="form-checkbox">
<label for="edit-field-clients-target-id-1381" class="option"> <a class="subcategories" title="全球速卖通">全球速卖通 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1006" type="checkbox" id="edit-field-clients-target-id-1006" name="field_clients_target_id[1006]" value="1006" class="form-checkbox">
<label for="edit-field-clients-target-id-1006" class="option"> <a class="subcategories" title="分众晶视">分众晶视 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1071" type="checkbox" id="edit-field-clients-target-id-1071" name="field_clients_target_id[1071]" value="1071" class="form-checkbox">
<label for="edit-field-clients-target-id-1071" class="option"> <a class="subcategories" title="别克">别克 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1011" type="checkbox" id="edit-field-clients-target-id-1011" name="field_clients_target_id[1011]" value="1011" class="form-checkbox">
<label for="edit-field-clients-target-id-1011" class="option"> <a class="subcategories" title="华为">华为 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1001" type="checkbox" id="edit-field-clients-target-id-1001" name="field_clients_target_id[1001]" value="1001" class="form-checkbox">
<label for="edit-field-clients-target-id-1001" class="option"> <a class="subcategories" title="可口可乐">可口可乐 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-991" type="checkbox" id="edit-field-clients-target-id-991" name="field_clients_target_id[991]" value="991" class="form-checkbox">
<label for="edit-field-clients-target-id-991" class="option"> <a class="subcategories" title="多芬">多芬 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1621" type="checkbox" id="edit-field-clients-target-id-1621" name="field_clients_target_id[1621]" value="1621" class="form-checkbox">
<label for="edit-field-clients-target-id-1621" class="option"> <a class="subcategories" title="天猫">天猫 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1796" type="checkbox" id="edit-field-clients-target-id-1796" name="field_clients_target_id[1796]" value="1796" class="form-checkbox">
<label for="edit-field-clients-target-id-1796" class="option"> <a class="subcategories" title="巴拉巴拉">巴拉巴拉 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1056" type="checkbox" id="edit-field-clients-target-id-1056" name="field_clients_target_id[1056]" value="1056" class="form-checkbox">
<label for="edit-field-clients-target-id-1056" class="option"> <a class="subcategories" title="强生">强生 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1376" type="checkbox" id="edit-field-clients-target-id-1376" name="field_clients_target_id[1376]" value="1376" class="form-checkbox">
<label for="edit-field-clients-target-id-1376" class="option"> <a class="subcategories" title="怀来">怀来 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-981" type="checkbox" id="edit-field-clients-target-id-981" name="field_clients_target_id[981]" value="981" class="form-checkbox">
<label for="edit-field-clients-target-id-981" class="option"> <a class="subcategories" title="惠氏 Illuma">惠氏 Illuma <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1466" type="checkbox" id="edit-field-clients-target-id-1466" name="field_clients_target_id[1466]" value="1466" class="form-checkbox">
<label for="edit-field-clients-target-id-1466" class="option"> <a class="subcategories" title="挪威电信">挪威电信 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-996" type="checkbox" id="edit-field-clients-target-id-996" name="field_clients_target_id[996]" value="996" class="form-checkbox">
<label for="edit-field-clients-target-id-996" class="option"> <a class="subcategories" title="李宁">李宁 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1126" type="checkbox" id="edit-field-clients-target-id-1126" name="field_clients_target_id[1126]" value="1126" class="form-checkbox">
<label for="edit-field-clients-target-id-1126" class="option"> <a class="subcategories" title="梅赛德斯奔驰">梅赛德斯奔驰 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1386" type="checkbox" id="edit-field-clients-target-id-1386" name="field_clients_target_id[1386]" value="1386" class="form-checkbox">
<label for="edit-field-clients-target-id-1386" class="option"> <a class="subcategories" title="玛莎拉蒂">玛莎拉蒂 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1541" type="checkbox" id="edit-field-clients-target-id-1541" name="field_clients_target_id[1541]" value="1541" class="form-checkbox">
<label for="edit-field-clients-target-id-1541" class="option"> <a class="subcategories" title="给家长的脐带血捐献指南">给家长的脐带血捐献指南 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-986" type="checkbox" id="edit-field-clients-target-id-986" name="field_clients_target_id[986]" value="986" class="form-checkbox">
<label for="edit-field-clients-target-id-986" class="option"> <a class="subcategories" title="肯德基">肯德基 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1096" type="checkbox" id="edit-field-clients-target-id-1096" name="field_clients_target_id[1096]" value="1096" class="form-checkbox">
<label for="edit-field-clients-target-id-1096" class="option"> <a class="subcategories" title="自然堂">自然堂 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1641" type="checkbox" id="edit-field-clients-target-id-1641" name="field_clients_target_id[1641]" value="1641" class="form-checkbox">
<label for="edit-field-clients-target-id-1641" class="option"> <a class="subcategories" title="辉瑞">辉瑞 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1387" type="checkbox" id="edit-field-clients-target-id-1387" name="field_clients_target_id[1387]" value="1387" class="form-checkbox">
<label for="edit-field-clients-target-id-1387" class="option"> <a class="subcategories" title="长城汽车">长城汽车 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1561" type="checkbox" id="edit-field-clients-target-id-1561" name="field_clients_target_id[1561]" value="1561" class="form-checkbox">
<label for="edit-field-clients-target-id-1561" class="option"> <a class="subcategories" title="雀巢咖啡">雀巢咖啡 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
<li class="grid__item is__active">
<input data-drupal-selector="edit-field-clients-target-id-1811" type="checkbox" id="edit-field-clients-target-id-1811" name="field_clients_target_id[1811]" value="1811" class="form-checkbox">
<label for="edit-field-clients-target-id-1811" class="option"> <a class="subcategories" title="雪碧">雪碧 <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
</li>
</ul>
</div>
</li>
</ul>
</div>
<input data-drupal-selector="edit-open" type="hidden" name="open" value="">
<div data-drupal-selector="edit-actions" class="form-actions js-form-wrapper form-wrapper" id="edit-actions"><input data-bef-auto-submit-click="" class="js-hide button js-form-submit form-submit" data-drupal-selector="edit-submit-our-work-grid" type="submit" id="edit-submit-our-work-grid" value="Apply">
</div>
</form>
<ul class="work__grid js-work-grid">
<li class="work__item work__item--small js-work-item cat-" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/laigejintongjiuqile" data-category-title="">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_280x400/public/work/grid/small/KFC%202023%20CNY%20Homepage.png?itok=FjalKeZs 280w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_420x600/public/work/grid/small/KFC%202023%20CNY%20Homepage.png?itok=GHxkLD3t 420w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_560x800/public/work/grid/small/KFC%202023%20CNY%20Homepage.png?itok=udB03eGS 560w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/KFC%202023%20CNY%20-%20Homepage%20Grid%20Image.png?itok=IgxR90z3 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/KFC%202023%20CNY%20-%20Homepage%20Grid%20Image.png?itok=TCZynAUe 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/KFC%202023%20CNY%20-%20Homepage%20Grid%20Image.png?itok=8fDfebqu 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/KFC%202023%20CNY%20-%20Homepage%20Grid%20Image.png?itok=IgxR90z3" alt="">
</picture>
<h3 class="work__item-title">
<span>来个金桶就齐了
<span class="work__item-client">肯德基
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--large js-work-item cat-" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/suiyuezaibian-tuanjudemeimiaobubian" data-category-title="">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_920x400/public/work/grid/large/Coca-Cola%202023%20CNY%20-%20Homepage%20Grid%20Image%20Large_0.png?itok=W54WiY-0 920w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1380x600/public/work/grid/large/Coca-Cola%202023%20CNY%20-%20Homepage%20Grid%20Image%20Large_0.png?itok=_gpr9ytt 1380w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1840x800/public/work/grid/large/Coca-Cola%202023%20CNY%20-%20Homepage%20Grid%20Image%20Large_0.png?itok=vzRogB83 1840w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Coca-Cola%202023%20CNY%20-%20Homepage%20Grid%20Image.png?itok=ZdMIyBde 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Coca-Cola%202023%20CNY%20-%20Homepage%20Grid%20Image.png?itok=h2w0JxRH 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Coca-Cola%202023%20CNY%20-%20Homepage%20Grid%20Image.png?itok=bD1Lr6ZZ 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Coca-Cola%202023%20CNY%20-%20Homepage%20Grid%20Image.png?itok=ZdMIyBde" alt="">
</picture>
<h3 class="work__item-title">
<span>岁月在变 团聚的美妙不变
<span class="work__item-client">可口可乐
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/fenxiangkele" data-category-title="">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Share-a-Coke_Splash-image.jpg?itok=RvtIwUkS 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Share-a-Coke_Splash-image.jpg?itok=dRmiQSKM 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Share-a-Coke_Splash-image.jpg?itok=r45fzQXd 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Share-a-Coke_Splash-image.jpg?itok=_VLVxgLP 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Share-a-Coke_Splash-image.jpg?itok=6BFlM0ee 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Share-a-Coke_Splash-image.jpg?itok=L5RV0lRA 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Share-a-Coke_Splash-image.jpg?itok=_VLVxgLP" alt="">
</picture>
<h3 class="work__item-title">
<span>分享可乐
<span class="work__item-client">可口可乐
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/xuebiwutang" data-category-title="">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Sprite%20Zero%20Sugar%20-%20Homepage%20Grid%20Image.png?itok=1cn8dUrn 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Sprite%20Zero%20Sugar%20-%20Homepage%20Grid%20Image.png?itok=47OiI5sr 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Sprite%20Zero%20Sugar%20-%20Homepage%20Grid%20Image.png?itok=6V0ObqZK 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Sprite%20Zero%20Sugar%20Splash%20Image.png?itok=bX31TMeY 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Sprite%20Zero%20Sugar%20Splash%20Image.png?itok=oOQ0lrd4 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Sprite%20Zero%20Sugar%20Splash%20Image.png?itok=8A3bAJCC 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Sprite%20Zero%20Sugar%20Splash%20Image.png?itok=bX31TMeY" alt="雪碧无糖" title="雪碧无糖">
</picture>
<h3 class="work__item-title">
<span>雪碧无糖
<span class="work__item-client">雪碧
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/lelingma" data-category-title="">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/splash%3Ahome%20page.jpg?itok=QSwE6kCF 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/splash%3Ahome%20page.jpg?itok=61LDRq4H 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/splash%3Ahome%20page.jpg?itok=fEb3nj3n 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/mobile.jpg?itok=KAFZf1Bw 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/mobile.jpg?itok=31r69Jhk 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/mobile.jpg?itok=HCsIlq57 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/mobile.jpg?itok=KAFZf1Bw" alt="乐龄码 Care Code" title="乐龄码 Care Code">
</picture>
<h3 class="work__item-title">
<span>乐龄码
<span class="work__item-client">中共上海市委老干部局
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--small js-work-item cat-" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/zizaichaoqun" data-category-title="">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_280x400/public/work/grid/small/Gu%20Yu%20x%20Balabala.png?itok=NpKQbbBL 280w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_420x600/public/work/grid/small/Gu%20Yu%20x%20Balabala.png?itok=y6tJvmue 420w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_560x800/public/work/grid/small/Gu%20Yu%20x%20Balabala.png?itok=-biiUeh8 560w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20Image%20-%201200x800.jpg?itok=KkrPVaCj 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Mobile%20Image%20-%201200x800.jpg?itok=Rg-XWAep 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Mobile%20Image%20-%201200x800.jpg?itok=QEwxWPUG 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20Image%20-%201200x800.jpg?itok=KkrPVaCj" alt="儿童数字人 谷雨" title="儿童数字人 谷雨">
</picture>
<h3 class="work__item-title">
<span>自在超裙
<span class="work__item-client">巴拉巴拉
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--large js-work-item cat-" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/huniantuanju-jinshimeimiao" data-category-title="">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_920x400/public/work/grid/large/homepage%20grid%20image-Cocacola%20CNY-LARGE.png?itok=9so1J2cE 920w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1380x600/public/work/grid/large/homepage%20grid%20image-Cocacola%20CNY-LARGE.png?itok=2JqXtqXf 1380w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1840x800/public/work/grid/large/homepage%20grid%20image-Cocacola%20CNY-LARGE.png?itok=Lqm4eTIM 1840w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/mobile%20image%20-Cocacola%20CNY%202.png?itok=4uZ0ePJM 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/mobile%20image%20-Cocacola%20CNY%202.png?itok=fKZ96cMa 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/mobile%20image%20-Cocacola%20CNY%202.png?itok=VNUYxlSY 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/mobile%20image%20-Cocacola%20CNY%202.png?itok=4uZ0ePJM" alt="虎年团聚 尽释美妙" title="虎年团聚 尽释美妙">
</picture>
<h3 class="work__item-title">
<span>虎年团聚 尽释美妙
<span class="work__item-client">可口可乐
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/meihaoshenghuo-gongtongxiangwang" data-category-title="">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Tmall%2011.11%20Mobile%20Image.png?itok=A5uH2zoy 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Tmall%2011.11%20Mobile%20Image.png?itok=M1fGrkQ1 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Tmall%2011.11%20Mobile%20Image.png?itok=QJN3J4C5 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Tmall%2011.11%20Mobile%20Image.png?itok=8oMxl_gF 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Tmall%2011.11%20Mobile%20Image.png?itok=Ip-ogPyk 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Tmall%2011.11%20Mobile%20Image.png?itok=mrRvm-H_ 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Tmall%2011.11%20Mobile%20Image.png?itok=8oMxl_gF" alt="美好生活 共同向往 2021 天猫 双十一" title="美好生活 共同向往 2021 天猫 双十一">
</picture>
<h3 class="work__item-title">
<span>美好生活 共同向往
<span class="work__item-client">天猫
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--large js-work-item cat-Experience" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/voice-doodler" data-category-title="体验">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_920x400/public/work/grid/large/Voice%20Doodler%20Large_0.png?itok=DU0jX2UY 920w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1380x600/public/work/grid/large/Voice%20Doodler%20Large_0.png?itok=mmQ9P7Fp 1380w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1840x800/public/work/grid/large/Voice%20Doodler%20Large_0.png?itok=DIsmThny 1840w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Voice%20Doodler%20Splash%20Image_0.jpg?itok=I4R7Wg1l 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Voice%20Doodler%20Splash%20Image_0.jpg?itok=tjaLEqOb 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Voice%20Doodler%20Splash%20Image_0.jpg?itok=fqxzvX96 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Voice%20Doodler%20Splash%20Image_0.jpg?itok=I4R7Wg1l" alt="Wyeth Illuma - Voice Doodler" title="Wyeth Illuma - Voice Doodler">
</picture>
<h3 class="work__item-title">
<span>绘声赋色
<span class="work__item-client">惠氏 Illuma
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--small js-work-item cat-Experience" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/xuniyouxiyimiao" data-category-title="">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_280x400/public/work/grid/small/Small%20-%20InGameVaccine.png?itok=B3MN7h4h 280w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_420x600/public/work/grid/small/Small%20-%20InGameVaccine.png?itok=mOG8IMjP 420w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_560x800/public/work/grid/small/Small%20-%20InGameVaccine.png?itok=40EEAa6q 560w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20image1.jpg?itok=4XjvenoU 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Mobile%20image1.jpg?itok=wkpxpg-Q 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Mobile%20image1.jpg?itok=WbxJ7CIN 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20image1.jpg?itok=4XjvenoU" alt="">
</picture>
<h3 class="work__item-title">
<span>虚拟游戏疫苗
<span class="work__item-client">辉瑞
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--large js-work-item cat-Experience" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/chunxiangwujin" data-category-title="">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_920x400/public/work/grid/large/Nescafe%20Homepage%20Grid%20Image.png?itok=iTy0Gz6T 920w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1380x600/public/work/grid/large/Nescafe%20Homepage%20Grid%20Image.png?itok=LqlRY-dp 1380w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1840x800/public/work/grid/large/Nescafe%20Homepage%20Grid%20Image.png?itok=Gl9IjwdP 1840w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Nescafe%20Mobile%20Image.png?itok=uOEk1BBi 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Nescafe%20Mobile%20Image.png?itok=WOLnWc3o 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Nescafe%20Mobile%20Image.png?itok=5a3-N8qH 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Nescafe%20Mobile%20Image.png?itok=uOEk1BBi" alt="">
</picture>
<h3 class="work__item-title">
<span>醇香无尽
<span class="work__item-client">雀巢咖啡
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Experience" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/5g-kung-fu-showdown" data-category-title="体验">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/5G%20Kung%20Fu%20Showdown.png?itok=lf4CiVRR 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/5G%20Kung%20Fu%20Showdown.png?itok=Z8BSoyf3 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/5G%20Kung%20Fu%20Showdown.png?itok=pk7mOAWw 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Splash%20Image%20-%20Landscape%20Template_0.jpg?itok=yk1kdIsa 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Splash%20Image%20-%20Landscape%20Template_0.jpg?itok=t0O8jBFu 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Splash%20Image%20-%20Landscape%20Template_0.jpg?itok=PUzyKzKy 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Splash%20Image%20-%20Landscape%20Template_0.jpg?itok=yk1kdIsa" alt="Huawei 5G Kung Fu Showdown" title="Huawei 5G Kung Fu Showdown">
</picture>
<h3 class="work__item-title">
<span>华为 5G 功夫
<span class="work__item-client">华为
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Experience" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/zheyuanbuzhishiyizhijibailiguanggao-2021" data-category-title="">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Cadbury%20Mobile%20Image.png?itok=lM3-y95_ 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Cadbury%20Mobile%20Image.png?itok=weXxm-Rj 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Cadbury%20Mobile%20Image.png?itok=cytv4B-6 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Cadbury%20Mobile%20Image.png?itok=oLdSRsZB 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Cadbury%20Mobile%20Image.png?itok=9t1CEjEb 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Cadbury%20Mobile%20Image.png?itok=gVXGqR-- 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Cadbury%20Mobile%20Image.png?itok=oLdSRsZB" alt="Cadbury - Not Just a Cadbury Ad 2021" title="Cadbury - Not Just a Cadbury Ad 2021">
</picture>
<h3 class="work__item-title">
<span>这远不止是一支吉百利广告 2021
<span class="work__item-client">Cadbury
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Experience" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/yishengwanwuwanwuguiyi" data-category-title="">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Mobile%20Image.jpg?itok=qTgZvWc7 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Mobile%20Image.jpg?itok=XmyA4gE_ 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Mobile%20Image.jpg?itok=2PgeHNA7 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20Image.jpg?itok=DaKdEtBr 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Mobile%20Image.jpg?itok=frysSpwG 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Mobile%20Image.jpg?itok=PygvUHHN 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20Image.jpg?itok=DaKdEtBr" alt="Huawei HarmonyOS">
</picture>
<h3 class="work__item-title">
<span>一生万物，万物归一
<span class="work__item-client">华为
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Experience" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/zuinianqingdejuanxianzhe" data-category-title="">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Youngest%20Donor%20Splash%20Image%20Regular.png?itok=iwSRi2Fb 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Youngest%20Donor%20Splash%20Image%20Regular.png?itok=HeNRSkqD 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Youngest%20Donor%20Splash%20Image%20Regular.png?itok=UsQFUes- 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Youngest%20Donor%20website%20images_Mobile%20Image--_0.jpg?itok=-Q5nsNWc 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Youngest%20Donor%20website%20images_Mobile%20Image--_0.jpg?itok=yJ8FDOlz 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Youngest%20Donor%20website%20images_Mobile%20Image--_0.jpg?itok=eIoFLXdI 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Youngest%20Donor%20website%20images_Mobile%20Image--_0.jpg?itok=-Q5nsNWc" alt="Youngest Donor" title="Youngest Donor">
</picture>
<h3 class="work__item-title">
<span>最年轻的捐献者
<span class="work__item-client">给家长的脐带血捐献指南
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/when-theres-love-theres-way" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Homepage%20Grid%20Image_%20Medium_%20benz.jpg?itok=geAMlzv4 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Homepage%20Grid%20Image_%20Medium_%20benz.jpg?itok=Z3yxtfl7 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Homepage%20Grid%20Image_%20Medium_%20benz.jpg?itok=qpBHBahx 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20Image_%20benz.jpg?itok=p_UAuHa9 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Mobile%20Image_%20benz.jpg?itok=nerG3WMS 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Mobile%20Image_%20benz.jpg?itok=4K09WTnB 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20Image_%20benz.jpg?itok=p_UAuHa9" alt="心之所向 - Mercedes Benz" title="心之所向 - Mercedes Benz">
</picture>
<h3 class="work__item-title">
<span>心之所向
<span class="work__item-client">梅赛德斯奔驰
</span>
</span>
</h3>
</a>
</li>

<li class="work__item js-work-item cat-Design" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/muqindetanzi" data-category-title="设计">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Mother%20Blanket%20Grid%20Image.png?itok=qEMnfoD1 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Mother%20Blanket%20Grid%20Image.png?itok=bMxuHvks 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Mother%20Blanket%20Grid%20Image.png?itok=NFgCCfFq 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mother%20Blanket%20Grid%20Image.png?itok=Xj1u_ICb 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Mother%20Blanket%20Grid%20Image.png?itok=kSyyB0u1 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Mother%20Blanket%20Grid%20Image.png?itok=e74S7Zzp 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mother%20Blanket%20Grid%20Image.png?itok=Xj1u_ICb" alt="Mother Blanket" title="Mother Blanket">
</picture>
<h3 class="work__item-title">
<span>母亲的毯子
<span class="work__item-client">Fundación Vivir &amp; CCPDA
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--large js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/go-freshman" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_920x400/public/work/grid/large/CHANDO%20LARGE.jpg?itok=fXbzCemw 920w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1380x600/public/work/grid/large/CHANDO%20LARGE.jpg?itok=TZmwdIyj 1380w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1840x800/public/work/grid/large/CHANDO%20LARGE.jpg?itok=iZ34Mb_- 1840w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Chando_Mobile%20Image.jpg?itok=JEMIu3RC 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Chando_Mobile%20Image.jpg?itok=FkTXHMJl 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Chando_Mobile%20Image.jpg?itok=LHC5n1fO 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Chando_Mobile%20Image.jpg?itok=JEMIu3RC" alt="Chando - 小朋友" title="Chando - 小朋友">
</picture>
<h3 class="work__item-title">
<span>冲吧！小朋友
<span class="work__item-client">自然堂
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/green-instructions" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Homepage%20image%20-%20LEGO%20Green%20instructions_0.jpg?itok=v9oC2hzY 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Homepage%20image%20-%20LEGO%20Green%20instructions_0.jpg?itok=Tqn2jUcf 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Homepage%20image%20-%20LEGO%20Green%20instructions_0.jpg?itok=fcyMPn-9 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Homepage%20image%20-%20LEGO%20Green%20instructions_0.jpg?itok=qXF0aoeK 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Homepage%20image%20-%20LEGO%20Green%20instructions_0.jpg?itok=a_OAANpj 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Homepage%20image%20-%20LEGO%20Green%20instructions_0.jpg?itok=QJasCXjm 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Homepage%20image%20-%20LEGO%20Green%20instructions_0.jpg?itok=qXF0aoeK" alt="Green instructions - LEGO" title="Green instructions - LEGO">
</picture>
<h3 class="work__item-title">
<span>绿色说明书
<span class="work__item-client">LEGO
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--small js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/shuzichushengdengji" data-category-title="">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_280x400/public/work/grid/small/Small%20Homepage%20Grid%20Image.jpg?itok=BMzY2-Uw 280w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_420x600/public/work/grid/small/Small%20Homepage%20Grid%20Image.jpg?itok=EtnpJTMm 420w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_560x800/public/work/grid/small/Small%20Homepage%20Grid%20Image.jpg?itok=kyl8ZNx4 560w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20Image_0.jpg?itok=8O_pN1f- 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Mobile%20Image_0.jpg?itok=RaoxB3Kq 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Mobile%20Image_0.jpg?itok=eq51HeIu 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20Image_0.jpg?itok=8O_pN1f-" alt="Naming the Invisible by Digital Birth Registration">
</picture>
<h3 class="work__item-title">
<span> 数字出生登记
<span class="work__item-client">挪威电信
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--large js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/sanchakou" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_920x400/public/work/grid/large/Homepage%20Grid%20Image_%20Large_huawei.jpg?itok=T8JveWvJ 920w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1380x600/public/work/grid/large/Homepage%20Grid%20Image_%20Large_huawei.jpg?itok=A_ObNeNl 1380w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1840x800/public/work/grid/large/Homepage%20Grid%20Image_%20Large_huawei.jpg?itok=fNFQIx3g 1840w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20Image_%20huawei.jpg?itok=LktU4qBv 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Mobile%20Image_%20huawei.jpg?itok=aZE34qFZ 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Mobile%20Image_%20huawei.jpg?itok=BfWNVa4i 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20Image_%20huawei.jpg?itok=LktU4qBv" alt="Sanchakou - Huawei" title="Sanchakou - Huawei">
</picture>
<h3 class="work__item-title">
<span>三岔口
<span class="work__item-client">华为
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--portrait js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/power-beginnings-2021" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_portrait_600x840/public/work/grid/portrait/Homepage%20Grid%20Image_%20Portrait_kfc.jpg?itok=EejjGJGU 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_portrait_900x1260/public/work/grid/portrait/Homepage%20Grid%20Image_%20Portrait_kfc.jpg?itok=xWxFxe7q 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_portrait_1200x1680/public/work/grid/portrait/Homepage%20Grid%20Image_%20Portrait_kfc.jpg?itok=qggNC8xc 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20Image_%20kfc.jpg?itok=tjugAQcl 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Mobile%20Image_%20kfc.jpg?itok=S9RBHeFd 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Mobile%20Image_%20kfc.jpg?itok=mXJqCS9B 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20Image_%20kfc.jpg?itok=tjugAQcl" alt="The Power of Beginnings 2021" title="The Power of Beginnings 2021">
</picture>
<h3 class="work__item-title">
<span>2021 开始的力量
<span class="work__item-client">肯德基
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--small js-work-item cat-Experience" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/street-it-all" data-category-title="体验">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_280x400/public/work/grid/small/Homepage%20Grid%20Image%20small.jpg?itok=qDd9dFiw 280w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_420x600/public/work/grid/small/Homepage%20Grid%20Image%20small.jpg?itok=mvnFYpSU 420w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_560x800/public/work/grid/small/Homepage%20Grid%20Image%20small.jpg?itok=ba1mE5Za 560w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/%20mobile%20image_1.jpg?itok=KKUYdPIg 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/%20mobile%20image_1.jpg?itok=dFZj-sr- 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/%20mobile%20image_1.jpg?itok=rhyZUTzd 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/%20mobile%20image_1.jpg?itok=KKUYdPIg" alt="Zalando - Street It All" title="Zalando - Street It All">
</picture>
<h3 class="work__item-title">
<span>尽在街头
<span class="work__item-client">Zalando
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/buick-2021-chinese-new-year-campaign-family-reunions" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Homepage%20Grid%20Image%20.Medium.jpg?itok=UCHv4ukA 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Homepage%20Grid%20Image%20.Medium.jpg?itok=VYpfGs3J 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Homepage%20Grid%20Image%20.Medium.jpg?itok=NDT4O436 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/%20mobile%20image.jpg?itok=HFHFouSZ 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/%20mobile%20image.jpg?itok=fTmNAmmt 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/%20mobile%20image.jpg?itok=PuSk-Lcq 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/%20mobile%20image.jpg?itok=HFHFouSZ" alt="Buick 2021 CNY Campaign" title="Buick 2021 CNY Campaign">
</picture>
<h3 class="work__item-title">
<span>天下别克的新春一刻
<span class="work__item-client">别克
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/can-great-wall-motors-survive-next-year" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Homepage%20Grid%20Image%20.Medium_2.jpg?itok=DrJhUB9p 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Homepage%20Grid%20Image%20.Medium_2.jpg?itok=fcm0ZoIy 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Homepage%20Grid%20Image%20.Medium_2.jpg?itok=HN2PAlO5 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/%20mobile%20image_5.jpg?itok=cwRONPMt 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/%20mobile%20image_5.jpg?itok=FkvzE6Sc 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/%20mobile%20image_5.jpg?itok=j1DdZGqq 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/%20mobile%20image_5.jpg?itok=cwRONPMt" alt="Great Wall Motors" title="Great Wall Motors">
</picture>
<h3 class="work__item-title">
<span>长城汽车挺得过明年吗？
<span class="work__item-client">长城汽车
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/ghibli-hybrid-china-launch" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Maserati_Homepage-Gird-image_Medium_0.jpg?itok=sPfXK4Ak 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Maserati_Homepage-Gird-image_Medium_0.jpg?itok=dXsK9BKl 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Maserati_Homepage-Gird-image_Medium_0.jpg?itok=yy4xkVth 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Maserati_Mobile-image_0.jpg?itok=BmeAd5Hf 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Maserati_Mobile-image_0.jpg?itok=q8WuCeMy 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Maserati_Mobile-image_0.jpg?itok=66-MrWW- 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Maserati_Mobile-image_0.jpg?itok=BmeAd5Hf" alt="Maserati - Ghibli Fenice Reveal" title="Maserati - Ghibli Fenice Reveal">
</picture>
<h3 class="work__item-title">
<span>锋芒初现
<span class="work__item-client">玛莎拉蒂
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--large js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/shop-endless-wonders" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_920x400/public/work/grid/large/Homepage%20Grid%20Image%20Large.jpg?itok=qF1VOPdR 920w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1380x600/public/work/grid/large/Homepage%20Grid%20Image%20Large.jpg?itok=TNsjyEVj 1380w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1840x800/public/work/grid/large/Homepage%20Grid%20Image%20Large.jpg?itok=__D-KXJX 1840w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/%20mobile%20image_0.jpg?itok=l16TJKmL 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/%20mobile%20image_0.jpg?itok=wG41OR_T 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/%20mobile%20image_0.jpg?itok=drYfpZ7k 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/%20mobile%20image_0.jpg?itok=l16TJKmL" alt="Shop Endless Wonders" title="Shop Endless Wonders">
</picture>
<h3 class="work__item-title">
<span>无限精彩的购物体验
<span class="work__item-client">全球速卖通
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--large js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/shes-mercedes" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_920x400/public/work/grid/large/benz%20_Homepage%20large%20Grid%20Image_%20%281%29.jpg?itok=Ijs2PoR6 920w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1380x600/public/work/grid/large/benz%20_Homepage%20large%20Grid%20Image_%20%281%29.jpg?itok=scbNbHV3 1380w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1840x800/public/work/grid/large/benz%20_Homepage%20large%20Grid%20Image_%20%281%29.jpg?itok=AtqYPRUj 1840w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/benz%20_Mobile%20Image__0.jpg?itok=sxRdIiSX 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/benz%20_Mobile%20Image__0.jpg?itok=NC5D3rDH 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/benz%20_Mobile%20Image__0.jpg?itok=oJ-aDFlk 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/benz%20_Mobile%20Image__0.jpg?itok=sxRdIiSX" alt="Mercedes Benz - She's Mercedes" title="She's Mercedes">
</picture>
<h3 class="work__item-title">
<span>She's Mercedes
<span class="work__item-client">梅赛德斯奔驰
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--small js-work-item cat-Experience" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/guangtoukatong" data-category-title="体验">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_280x400/public/work/grid/small/Bald%20Cartoons%20Small_0.png?itok=JFsELbJc 280w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_420x600/public/work/grid/small/Bald%20Cartoons%20Small_0.png?itok=H7risHvP 420w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_560x800/public/work/grid/small/Bald%20Cartoons%20Small_0.png?itok=xQFDqt2R 560w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Bald%20Cartoons%20-%20Home.png?itok=H3oAeWGL 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Bald%20Cartoons%20-%20Home.png?itok=rroV9BYJ 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Bald%20Cartoons%20-%20Home.png?itok=qnMOfkek 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Bald%20Cartoons%20-%20Home.png?itok=H3oAeWGL" alt="Bald Cartoons" title="Bald Cartoons">
</picture>
<h3 class="work__item-title">
<span>光头卡通
<span class="work__item-client">GRAACC
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Experience" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/not-just-cadbury-ad" data-category-title="体验">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/cadbury_Splash%20Image.jpg?itok=1EEx_4Ha 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/cadbury_Splash%20Image.jpg?itok=jyyefFJi 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/cadbury_Splash%20Image.jpg?itok=-pMkyllg 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/cadbury%20_Mobile%20Image_.jpg?itok=NOuR7D3x 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/cadbury%20_Mobile%20Image_.jpg?itok=sV0tM6wB 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/cadbury%20_Mobile%20Image_.jpg?itok=Q-Ae4Ec6 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/cadbury%20_Mobile%20Image_.jpg?itok=NOuR7D3x" alt="Not Just a Cadbury Ad" title="Not Just a Cadbury Ad">
</picture>
<h3 class="work__item-title">
<span>这远不止是一支吉百利广告
<span class="work__item-client">Cadbury
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/find-your-place" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Kfc_Homepage%20medium%20.jpg?itok=TrYOnRRy 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Kfc_Homepage%20medium%20.jpg?itok=MCdZaDvn 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Kfc_Homepage%20medium%20.jpg?itok=0VCr9IC0 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/kfc%20weizi%20_Mobile%20Image_.jpg?itok=-p6raW_K 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/kfc%20weizi%20_Mobile%20Image_.jpg?itok=LLRJPtk5 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/kfc%20weizi%20_Mobile%20Image_.jpg?itok=PziuUoJD 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/kfc%20weizi%20_Mobile%20Image_.jpg?itok=-p6raW_K" alt="KFC - Find Your Place" title="KFC - Find Your Place">
</picture>
<h3 class="work__item-title">
<span>位子
<span class="work__item-client">肯德基
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/hwailai-wine-region" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Homepage%20Grid%20Image%20.Medium_3.jpg?itok=3oyCFhz_ 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Homepage%20Grid%20Image%20.Medium_3.jpg?itok=KfuyQy7I 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Homepage%20Grid%20Image%20.Medium_3.jpg?itok=gaoZt7Zx 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/%20mobile%20image_6.jpg?itok=Wbm6uP5m 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/%20mobile%20image_6.jpg?itok=00EJP1Mg 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/%20mobile%20image_6.jpg?itok=WciPzVU3 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/%20mobile%20image_6.jpg?itok=Wbm6uP5m" alt="Hwailai Wine Region" title="Hwailai Wine Region">
</picture>
<h3 class="work__item-title">
<span>张家口市怀来产区品牌塑造
<span class="work__item-client">怀来
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/we-make-today" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Homepage%20Grid%20Image%20.Medium_0.jpg?itok=2VIRxFrh 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Homepage%20Grid%20Image%20.Medium_0.jpg?itok=-hrG93N5 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Homepage%20Grid%20Image%20.Medium_0.jpg?itok=nGeOtfM8 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/%20mobile%20image_2.jpg?itok=D0HDFjKD 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/%20mobile%20image_2.jpg?itok=HGiGQjhh 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/%20mobile%20image_2.jpg?itok=I6rqk0Hx 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/%20mobile%20image_2.jpg?itok=D0HDFjKD" alt="Instagram - We Make Today" title="Instagram - We Make Today">
</picture>
<h3 class="work__item-title">
<span>我们创造今天
<span class="work__item-client">Instagram
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--large js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/52-mayors-danzhai" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_920x400/public/work/grid/large/wanda%20_Homepage%20large_0.jpg?itok=o8RccCdF 920w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1380x600/public/work/grid/large/wanda%20_Homepage%20large_0.jpg?itok=aOgcPkWx 1380w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_large_1840x800/public/work/grid/large/wanda%20_Homepage%20large_0.jpg?itok=XSahxbg- 1840w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/wanda%20_Mobile%20Image_.jpg?itok=uo9Mq1yX 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/wanda%20_Mobile%20Image_.jpg?itok=cPtXjxr2 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/wanda%20_Mobile%20Image_.jpg?itok=gdGZMFnA 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/wanda%20_Mobile%20Image_.jpg?itok=uo9Mq1yX" alt="Wanda - 52 Mayors of Danzhai" title="Wanda - 52 Mayors of Danzhai">
</picture>
<h3 class="work__item-title">
<span>52 个镇长
<span class="work__item-client">万达
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/portraits-completed" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/kiwi%20_Homepage%20medium.jpg?itok=udWyWEjU 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/kiwi%20_Homepage%20medium.jpg?itok=TqCs4QVA 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/kiwi%20_Homepage%20medium.jpg?itok=HCdwdwfB 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/kiwi%20_Homepage%20medium.jpg?itok=MLzBqNLY 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/kiwi%20_Homepage%20medium.jpg?itok=ILMtBgkX 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/kiwi%20_Homepage%20medium.jpg?itok=3sdgPNpf 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/kiwi%20_Homepage%20medium.jpg?itok=MLzBqNLY" alt="SC Johnson - Portraits Completed" title="SC Johnson - Portraits Completed">
</picture>
<h3 class="work__item-title">
<span>名画的下半身
<span class="work__item-client">强生
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Experience" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/vr-yimiao" data-category-title="体验">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/VR%20Vaccine%20-%20Home.png?itok=KY5EUo9W 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/VR%20Vaccine%20-%20Home.png?itok=_aPojHFO 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/VR%20Vaccine%20-%20Home.png?itok=ZmjAMakS 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/VR%20Vaccine%20-%20Home.png?itok=LAAHITH4 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/VR%20Vaccine%20-%20Home.png?itok=NNtFTnWN 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/VR%20Vaccine%20-%20Home.png?itok=zVEWtryb 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/VR%20Vaccine%20-%20Home.png?itok=LAAHITH4" alt="VR Vaccine" title="VR Vaccine">
</picture>
<h3 class="work__item-title">
<span>VR 疫苗
<span class="work__item-client">Hermes Pardini
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--small js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/dad" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_280x400/public/work/grid/small/Home_Small_Dad%20On.jpg?itok=gC8XZdcA 280w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_420x600/public/work/grid/small/Home_Small_Dad%20On.jpg?itok=A3kSUb7R 420w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_560x800/public/work/grid/small/Home_Small_Dad%20On.jpg?itok=2SaZkZUM 560w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Splash_Mobile_Dad-On.jpg?itok=5w-pKMLn 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Splash_Mobile_Dad-On.jpg?itok=1RdPFvdz 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Splash_Mobile_Dad-On.jpg?itok=PC4lQ752 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Splash_Mobile_Dad-On.jpg?itok=5w-pKMLn" alt="Dove - Dad On" title="Dove - Dad On">
</picture>
<h3 class="work__item-title">
<span>认真的爸爸
<span class="work__item-client">多芬
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/buick-excelle-honest-test-drive" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/buick%20_Mobile%20Image_.jpg?itok=57c6W2D_ 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/buick%20_Mobile%20Image_.jpg?itok=UAyG1PYz 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/buick%20_Mobile%20Image_.jpg?itok=WSijv98l 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Buick%20_Homepage%20medium.jpg?itok=eqtuWJB4 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Buick%20_Homepage%20medium.jpg?itok=cWJbmESr 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Buick%20_Homepage%20medium.jpg?itok=Gec1HECd 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Buick%20_Homepage%20medium.jpg?itok=eqtuWJB4" alt="Buick - Buick Excelle 'Honest' Test Drive" title="Buick - Buick Excelle 'Honest' Test Drive">
</picture>
<h3 class="work__item-title">
<span>别克英朗三缸诚实试驾
<span class="work__item-client">别克
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Design" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/healthy-hands-chalk-sticks" data-category-title="设计">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Spalsh_Mobile_Healthy%20Hands%20Chalk%20Sticks_0.jpg?itok=fziXpho5 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Spalsh_Mobile_Healthy%20Hands%20Chalk%20Sticks_0.jpg?itok=D5LleONl 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Spalsh_Mobile_Healthy%20Hands%20Chalk%20Sticks_0.jpg?itok=JPohHzUD 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Spalsh_Healthy-Hands-Chalk-Sticks.jpg?itok=fNrWxiwn 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Spalsh_Healthy-Hands-Chalk-Sticks.jpg?itok=ep48K0I8 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Spalsh_Healthy-Hands-Chalk-Sticks.jpg?itok=gcJJwRmG 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Spalsh_Healthy-Hands-Chalk-Sticks.jpg?itok=fNrWxiwn" alt="Savlon Healthy Hands Chalk Sticks" title="Savlon Healthy Hands Chalk Sticks">
</picture>
<h3 class="work__item-title">
<span>可以洗手的粉笔
<span class="work__item-client">Savlon
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--portrait js-work-item cat-Design" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/cupping-my-creed" data-category-title="设计">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_portrait_600x840/public/work/grid/portrait/Home_Portait_Cupping-My-Creed_0.jpg?itok=4iw4G8x- 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_portrait_900x1260/public/work/grid/portrait/Home_Portait_Cupping-My-Creed_0.jpg?itok=nwSnYB8T 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_portrait_1200x1680/public/work/grid/portrait/Home_Portait_Cupping-My-Creed_0.jpg?itok=EHszZOFp 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile_Cupping-My-Creed.jpg?itok=u3OfZkwb 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Mobile_Cupping-My-Creed.jpg?itok=pTECzufH 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Mobile_Cupping-My-Creed.jpg?itok=1Ch9tasm 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile_Cupping-My-Creed.jpg?itok=u3OfZkwb" alt="Lining - Cupping My Creed" title="Lining - Cupping My Creed">
</picture>
<h3 class="work__item-title">
<span>拔罐宣言
<span class="work__item-client">李宁
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--small js-work-item cat-Experience" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/last-tree-standing" data-category-title="体验">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_280x400/public/work/grid/small/Last%20Tree%20Standing_Grid_Small_0.jpg?itok=bxf7Ckck 280w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_420x600/public/work/grid/small/Last%20Tree%20Standing_Grid_Small_0.jpg?itok=uDyd8b8S 420w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_560x800/public/work/grid/small/Last%20Tree%20Standing_Grid_Small_0.jpg?itok=6GIDJQAM 560w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Splash_Home_Mobile_Last-Tree-Standing.jpg?itok=qD6bMkR2 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Splash_Home_Mobile_Last-Tree-Standing.jpg?itok=EG_qypmH 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Splash_Home_Mobile_Last-Tree-Standing.jpg?itok=wC2P8dUx 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Splash_Home_Mobile_Last-Tree-Standing.jpg?itok=qD6bMkR2" alt="Greenpeace Last Tree Standing" title="Greenpeace Last Tree Standing">
</picture>
<h3 class="work__item-title">
<span>致最后一棵树
<span class="work__item-client">Greenpeace
</span>
</span>
</h3>
</a>
</li>
<li class="work__item work__item--small js-work-item cat-Experience" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/piracy-blockr" data-category-title="体验">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_280x400/public/work/grid/small/Home_Portait_Piracy%20Blockr_Focus%20Film%20Media.png?itok=OCnF4rTL 280w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_420x600/public/work/grid/small/Home_Portait_Piracy%20Blockr_Focus%20Film%20Media.png?itok=z9AdJVvT 420w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_small_560x800/public/work/grid/small/Home_Portait_Piracy%20Blockr_Focus%20Film%20Media.png?itok=zVR2bdpr 560w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20Image_Piracy%20Blockr_Focus%20Film%20Media.jpg?itok=CrLpONSt 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Mobile%20Image_Piracy%20Blockr_Focus%20Film%20Media.jpg?itok=5EJaxhiV 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Mobile%20Image_Piracy%20Blockr_Focus%20Film%20Media.jpg?itok=XlPlz0vl 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Mobile%20Image_Piracy%20Blockr_Focus%20Film%20Media.jpg?itok=CrLpONSt" alt="Focus Film Media-Piracy Blockr" title="Focus Film Media-Piracy Blockr">
</picture>
<h3 class="work__item-title">
<span>盗版拦截器
<span class="work__item-client">分众晶视
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Design" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/coke-fanta" data-category-title="设计">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Splash_Home_Mobile_This%20Coke%20is%20a%20Fanta_0.jpg?itok=ZcXBAnNq 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Splash_Home_Mobile_This%20Coke%20is%20a%20Fanta_0.jpg?itok=mhbQS1Gr 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Splash_Home_Mobile_This%20Coke%20is%20a%20Fanta_0.jpg?itok=ryyzb9ZF 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Splash_Home_Mobile_This%20Coke%20is%20a%20Fanta_0.jpg?itok=Z5WqSjBD 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Splash_Home_Mobile_This%20Coke%20is%20a%20Fanta_0.jpg?itok=XCgAlZiv 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Splash_Home_Mobile_This%20Coke%20is%20a%20Fanta_0.jpg?itok=RLC10C2F 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Splash_Home_Mobile_This%20Coke%20is%20a%20Fanta_0.jpg?itok=Z5WqSjBD" alt="Coca-Cola - This Coke is a Fanta" title="Coca-Cola - This Coke is a Fanta">
</picture>
<h3 class="work__item-title">
<span>这瓶可乐是芬达
<span class="work__item-client">可口可乐
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Communication" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/turn-food-meal" data-category-title="传播">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/kfc_Homepage%20medium%20.jpg?itok=UsX4EXoj 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/kfc_Homepage%20medium%20.jpg?itok=S3MzEumT 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/kfc_Homepage%20medium%20.jpg?itok=nEWk4fcR 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/kfc%20_Mobile%20Image_.jpg?itok=AHi_hRSH 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/kfc%20_Mobile%20Image_.jpg?itok=i8vFdvCO 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/kfc%20_Mobile%20Image_.jpg?itok=luP78p9X 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/kfc%20_Mobile%20Image_.jpg?itok=AHi_hRSH" alt="Coca Cola - Turn food into a meal" title="Coca Cola - Turn food into a meal">
</picture>
<h3 class="work__item-title">
<span>将食物变成一顿饭
<span class="work__item-client">可口可乐
</span>
</span>
</h3>
</a>
</li>
<li class="work__item js-work-item cat-Experience" style="opacity: 1; transform: matrix(1, 0, 0, 1, 0, 0);"><a href="/cn/work/pet-commerce" data-category-title="体验">
<picture>
<source srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/medium/Splash_Home_Mobile_Pet-Commerce.jpg?itok=2E9YxcQJ 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/medium/Splash_Home_Mobile_Pet-Commerce.jpg?itok=bG8SMtwO 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/medium/Splash_Home_Mobile_Pet-Commerce.jpg?itok=w9XX4ZlD 1200w" media="(min-width: 720px)" sizes="30vw">
<img srcset="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Splash_Home_Mobile_Pet-Commerce.jpg?itok=tm9r5Q4P 600w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_900x600/public/work/grid/mobile/Splash_Home_Mobile_Pet-Commerce.jpg?itok=XRGYCrI9 900w, /cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_1200x800/public/work/grid/mobile/Splash_Home_Mobile_Pet-Commerce.jpg?itok=jwTiG9ma 1200w" sizes="(min-width:720px) 30vw, 100vw" src="/cn/sites/g/files/dhpsjz236/files/styles/our_work_grid_medium_600x400/public/work/grid/mobile/Splash_Home_Mobile_Pet-Commerce.jpg?itok=tm9r5Q4P" alt="Pet Commerce" title="Pet Commerce">
</picture>
<h3 class="work__item-title">
<span>宠物电商
<span class="work__item-client">Petz
</span>
</span>
</h3>
</a>
</li>
</ul></div>
<section>
</section></section></div>
</div>
</main>
<footer class="site-footer" role="contentinfo">
<div class="container">
<ul class="site-footer__primary-nav">
<li>
<a href="/cn/privacy-policy" data-drupal-link-system-path="node/616">隐私政策</a>
</li>
<li>
<a href="/cn/cookies" data-drupal-link-system-path="node/611">Cookies</a>
</li>
<li>
<a href="https://beian.miit.gov.cn/" target="_blank">京ICP备05003121号-1</a>
</li>
</ul>
<ul class="social-nav footer-right-nav">
<li class="social-list">
<a href="javascript:void(0);" title="">
关注我们</a>
<ul class="social-nav-list">
<li>
<span><a href="javascript:void(0);" title="" data-modal-id="winpopup-we-chat">
微信</a></span>
<span><a href="javascript:void(0);" title="" data-modal-id="winpopup-weibo">
微博</a></span>
<span>
<a href="https://www.linkedin.com/company/ogilvychina" title="领英" rel="noopener noreferrer" target="_blank">
领英
</a>
</span>
</li>
</ul>
</li>
<li>
<a href="https://www.ogilvy.com/" title="" target="">
全球网站</a>
</li>
</ul>
<div>
</div></div></footer>
<div class="feed-crm-pop_wrapper connect-crm-wrap">
<div class="feed-modal">
<div class="container container--s">
<div class="feed-modal__content-wrapper">
<article class="post">
<div class="post__header connect-pop-header">
<div class="feed-post__close js-post-close">
<div class="post__close-button">
<svg id="close-icon" viewBox="0 0 14.6 14.6" width="100%" height="100%">
<path fill="none" stroke="currentColor" stroke-width=".8" d="M.3.3l14 14m0-14l-14 14"></path>
</svg>
</div>
</div>
</div>
<h5 class="post__title ideas_title">no title</h5>
<h5 class="post__title static_title">Subscribe to stay up to date with our latest thinking</h5>
<div class="post__wrapper connect-form-wrapper">
<div class="post__meta-wrapper connect-pop-copy">
<p class="gated-content">欢迎下载并填写信息订阅奥美最新资讯及前沿观点。
请在您的浏览器中设置启用弹窗功能。</p>
<p class="nongated-content">David Ogilvy founded our company to be the teaching hospital of advertising. We continue that legacy by providing unmatched insights into what makes brands matter in today's fast-moving world. Subscribe to receive our latest thinking directly to your inbox.</p>
<p class="only-email-content">请输入您的邮箱地址以访问或下载该内容。请在您的浏览器中设置启用弹窗功能。</p>
</div>
<div class="post__text text">
<div class="connect-form">
<form class="content-entity-file-utility-add-form content-entity-file-utility-form" data-drupal-selector="content-entity-file-utility-add-form" action="/cn/" method="post" id="content-entity-file-utility-add-form" accept-charset="UTF-8">
<div class="field--type-string field--name-field-name field--widget-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-name-wrapper" id="edit-field-name-wrapper"> <div class="js-form-item form-item js-form-type-textfield form-item-field-name-0-value js-form-item-field-name-0-value">
<label for="edit-field-name-0-value" class="js-form-required invisible form-required">Name</label>
<input class="js-text-full text-full form-text required" data-drupal-selector="edit-field-name-0-value" type="text" id="edit-field-name-0-value" name="field_name[0][value]" value="" size="60" maxlength="255" placeholder="姓名" required="required" aria-required="true">
</div>
</div>
<span class="field_name_error error"></span><input data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-honeypot-time" type="hidden" name="honeypot_time" value="mGp7WThtTQTANeV97FYjppWGSQ3OV9Jye-C_wK6_sTU">
<input autocomplete="off" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="form-esnmmjb94c5jvyjx28znundd0dcecyauplpiocknkmm" type="hidden" name="form_build_id" value="form-eSNmmjB94c5JVyJX28znundD0DcEcyAUplpiocknkmM">
<span class="form_build_id_error error"></span><input data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-content-entity-file-utility-add-form" type="hidden" name="form_id" value="content_entity_file_utility_add_form">
<span class="form_id_error error"></span><div class="field--type-string field--name-field-title field--widget-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-title-wrapper" id="edit-field-title-wrapper"> <div class="js-form-item form-item js-form-type-textfield form-item-field-title-0-value js-form-item-field-title-0-value">
<label for="edit-field-title-0-value" class="js-form-required invisible form-required"><a class="subcategories" title="Title">Title <svg id="plus-icon" viewBox="0 0 20.1 20.1" width="100%" height="100%"><path fill="none" stroke="currentColor" d="M10.1 0v20.1m10-10H0"></path></svg></a></label>
<input class="js-text-full text-full form-text required" data-drupal-selector="edit-field-title-0-value" type="text" id="edit-field-title-0-value" name="field_title[0][value]" value="" size="60" maxlength="255" placeholder="职务" required="required" aria-required="true">
</div>
</div>
<span class="field_title_error error"></span><div class="field--type-string field--name-field-account-name field--widget-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-account-name-wrapper" id="edit-field-account-name-wrapper"> <div class="js-form-item form-item js-form-type-textfield form-item-field-account-name-0-value js-form-item-field-account-name-0-value">
<label for="edit-field-account-name-0-value" class="js-form-required invisible form-required">Account Name</label>
<input class="js-text-full text-full form-text required" data-drupal-selector="edit-field-account-name-0-value" type="text" id="edit-field-account-name-0-value" name="field_account_name[0][value]" value="" size="60" maxlength="255" placeholder="公司" required="required" aria-required="true">
</div>
</div>
<span class="field_account_name_error error"></span><div class="field--type-entity-reference field--name-field-crm-industries field--widget-select2-entity-reference js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-crm-industries-wrapper" id="edit-field-crm-industries-wrapper"><div class="js-form-item form-item js-form-type-select form-item-field-crm-industries js-form-item-field-crm-industries">
<label for="edit-field-crm-industries" class="js-form-required invisible form-required">行业</label>
<select data-drupal-selector="edit-field-crm-industries" id="edit-field-crm-industries" name="field_crm_industries" class="form-select required select2-widget select2-hidden-accessible" required="required" aria-required="true" data-select2-config="{&quot;multiple&quot;:false,&quot;placeholder&quot;:{&quot;id&quot;:&quot;&quot;,&quot;text&quot;:&quot;- \u9009\u62e9 -&quot;},&quot;allowClear&quot;:false,&quot;dir&quot;:&quot;ltr&quot;,&quot;language&quot;:&quot;zh-hans&quot;,&quot;tags&quot;:false,&quot;theme&quot;:&quot;default&quot;,&quot;maximumSelectionLength&quot;:0,&quot;tokenSeparators&quot;:[],&quot;selectOnClose&quot;:false,&quot;width&quot;:&quot;100%&quot;}" data-select2-publish-default="true" data-once="select2-init" tabindex="-1" aria-hidden="true" data-select2-id="edit-field-crm-industries"><option value="" data-select2-id="238"></option><option value="5821" data-published="true">航天业</option><option value="5826" data-published="true">农业</option><option value="5846" data-published="true">汽车业</option><option value="5851" data-published="true">银行业</option><option value="5871" data-published="true">商业服务</option><option value="5876" data-published="true">慈善组织</option><option value="5881" data-published="true">化学制品</option><option value="5886" data-published="true">计算机硬件</option><option value="5891" data-published="true">计算机服务</option><option value="5896" data-published="true">计算机软件</option><option value="5906" data-published="true">建筑业</option><option value="5911" data-published="true">消费类电子产品</option><option value="5926" data-published="true">文化机构</option><option value="5936" data-published="true">教育</option><option value="5951" data-published="true">娱乐</option><option value="5966" data-published="true">金融服务</option><option value="5971" data-published="true">餐饮</option><option value="5981" data-published="true">政府</option><option value="6006" data-published="true">工业制造</option><option value="6011" data-published="true">保险</option><option value="6016" data-published="true">法律</option><option value="6026" data-published="true">奢侈品</option><option value="6041" data-published="true">媒体</option><option value="6061" data-published="true">音乐</option><option value="6081" data-published="true">医药品</option><option value="6091" data-published="true">出版业</option><option value="6111" data-published="true">餐厅</option><option value="6116" data-published="true">零售业</option><option value="6141" data-published="true">技术</option><option value="6146" data-published="true">电信业</option></select><span class="select2 select2-container select2-container--default" dir="ltr" data-select2-id="237" style="width: 100%;"><span class="selection"><span class="select2-selection select2-selection--single" role="combobox" aria-haspopup="true" aria-expanded="false" tabindex="0" aria-disabled="false" aria-labelledby="select2-edit-field-crm-industries-container"><span class="select2-selection__rendered" id="select2-edit-field-crm-industries-container" role="textbox" aria-readonly="true"><span class="select2-selection__placeholder">行业</span></span><span class="select2-selection__arrow" role="presentation"><b role="presentation"></b></span></span></span><span class="dropdown-wrapper" aria-hidden="true"></span></span>
<div class="industrySuggestions"></div>
</div>
</div>
<span class="field_crm_industries_error error"></span><div class="field--type-entity-reference field--name-field-country-c field--widget-select2-entity-reference js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-country-c-wrapper" id="edit-field-country-c-wrapper"><div class="js-form-item form-item js-form-type-select form-item-field-country-c js-form-item-field-country-c">
<label for="edit-field-country-c" class="js-form-required invisible form-required">地区</label>
<select data-drupal-selector="edit-field-country-c" id="edit-field-country-c" name="field_country_c" class="form-select required select2-widget select2-hidden-accessible" required="required" aria-required="true" data-select2-config="{&quot;multiple&quot;:false,&quot;placeholder&quot;:{&quot;id&quot;:&quot;&quot;,&quot;text&quot;:&quot;- \u9009\u62e9 -&quot;},&quot;allowClear&quot;:false,&quot;dir&quot;:&quot;ltr&quot;,&quot;language&quot;:&quot;zh-hans&quot;,&quot;tags&quot;:false,&quot;theme&quot;:&quot;default&quot;,&quot;maximumSelectionLength&quot;:0,&quot;tokenSeparators&quot;:[],&quot;selectOnClose&quot;:false,&quot;width&quot;:&quot;100%&quot;}" data-select2-publish-default="true" data-once="select2-init" tabindex="-1" aria-hidden="true" data-select2-id="edit-field-country-c"><option value="" data-select2-id="206"></option><option value="2961" data-published="true">阿富汗</option><option value="2966" data-published="true">亚美尼亚</option><option value="2971" data-published="true">澳大利亚</option><option value="2976" data-published="true">孟加拉国</option><option value="2981" data-published="true">不丹</option><option value="2986" data-published="true">文莱</option><option value="2991" data-published="true">柬埔寨</option><option value="2996" data-published="true">中国</option><option value="3001" data-published="true">斐济</option><option value="3006" data-published="true">乔治亚</option><option value="3011" data-published="true">中国香港</option><option value="3016" data-published="true">印度</option><option value="3021" data-published="true">印度尼西亚</option><option value="3026" data-published="true">伊朗</option><option value="3031" data-published="true">伊拉克</option><option value="3036" data-published="true">日本</option><option value="3041" data-published="true">约旦</option><option value="3046" data-published="true">基里巴斯</option><option value="3051" data-published="true">吉尔吉斯斯坦</option><option value="3056" data-published="true">中国澳门</option><option value="3061" data-published="true">马来西亚</option><option value="3066" data-published="true">马尔代夫</option><option value="3071" data-published="true">马耳他</option><option value="3076" data-published="true">马绍尔群岛</option><option value="3081" data-published="true">毛里求斯</option><option value="3086" data-published="true">密克罗尼西亚</option><option value="3091" data-published="true">蒙古</option><option value="3096" data-published="true">缅甸</option><option value="3101" data-published="true">瑙鲁</option><option value="3106" data-published="true">尼泊尔</option><option value="3111" data-published="true">新西兰</option><option value="3116" data-published="true">朝鲜</option><option value="3121" data-published="true">阿曼</option><option value="3126" data-published="true">巴基斯坦</option><option value="3131" data-published="true">帕劳</option><option value="3136" data-published="true">巴勒斯坦</option><option value="3141" data-published="true">巴布亚新几内亚</option><option value="3146" data-published="true">菲律宾</option><option value="3151" data-published="true">波多黎各</option><option value="3156" data-published="true">卡塔尔</option><option value="3161" data-published="true">新加坡</option><option value="3166" data-published="true">所罗门群岛</option><option value="3171" data-published="true">韩国</option><option value="3176" data-published="true">斯里兰卡</option><option value="3181" data-published="true">中国台湾</option><option value="3186" data-published="true">塔吉克斯坦</option><option value="3191" data-published="true">泰国</option><option value="3196" data-published="true">东帝汶</option><option value="3201" data-published="true">多哥</option><option value="3206" data-published="true">托克劳</option><option value="3211" data-published="true">汤加</option><option value="3216" data-published="true">土库曼斯坦</option><option value="3221" data-published="true">图瓦卢</option><option value="3226" data-published="true">瓦努阿图</option><option value="3231" data-published="true">越南</option><option value="3236" data-published="true">也门</option><option value="3241" data-published="true">阿尔巴尼亚</option><option value="3246" data-published="true">阿尔及利亚</option><option value="3251" data-published="true">安道尔</option><option value="3256" data-published="true">安哥拉</option><option value="3261" data-published="true">奥地利</option><option value="3266" data-published="true">阿塞拜疆</option><option value="3271" data-published="true">巴林</option><option value="3276" data-published="true">白俄罗斯</option><option value="3281" data-published="true">比利时</option><option value="3286" data-published="true">贝宁</option><option value="3291" data-published="true">波斯尼亚和黑塞哥维那</option><option value="3296" data-published="true">博茨瓦纳</option><option value="3301" data-published="true">保加利亚</option><option value="3306" data-published="true">布基纳法索</option><option value="3311" data-published="true">布隆迪</option><option value="3316" data-published="true">佛得角</option><option value="3321" data-published="true">中非共和国</option><option value="3326" data-published="true">乍得</option><option value="3331" data-published="true">科摩罗</option><option value="3336" data-published="true">刚果民主共和国</option><option value="3341" data-published="true">刚果共和国</option><option value="3346" data-published="true">象牙海岸</option><option value="3351" data-published="true">克罗地亚</option><option value="3361" data-published="true">捷克共和国</option><option value="3366" data-published="true">丹麦</option><option value="3371" data-published="true">吉布提</option><option value="3376" data-published="true">埃及</option><option value="3381" data-published="true">赤道几内亚</option><option value="3386" data-published="true">厄立特里亚</option><option value="3391" data-published="true">在斯威士兰</option><option value="3396" data-published="true">埃塞俄比亚</option><option value="3401" data-published="true">芬兰</option><option value="3406" data-published="true">法国</option><option value="3411" data-published="true">冈比亚</option><option value="3416" data-published="true">德国</option><option value="3421" data-published="true">希腊</option><option value="3426" data-published="true">几内亚</option><option value="3431" data-published="true">几内亚比绍</option><option value="3436" data-published="true">匈牙利</option><option value="3441" data-published="true">冰岛</option><option value="3446" data-published="true">爱尔兰</option><option value="3451" data-published="true">以色列</option><option value="3456" data-published="true">意大利</option><option value="3461" data-published="true">哈萨克斯坦</option><option value="3466" data-published="true">肯尼亚</option><option value="3471" data-published="true">科索沃</option><option value="3476" data-published="true">科威特</option><option value="3481" data-published="true">拉脱维亚</option><option value="3486" data-published="true">黎巴嫩</option><option value="3491" data-published="true">莱索托</option><option value="3496" data-published="true">利比里亚</option><option value="3501" data-published="true">利比亚</option><option value="3506" data-published="true">列支敦士登</option><option value="3511" data-published="true">立陶宛</option><option value="3516" data-published="true">卢森堡</option><option value="3521" data-published="true">马达加斯加</option><option value="3526" data-published="true">马拉维</option><option value="3531" data-published="true">马里</option><option value="3536" data-published="true">毛里塔尼亚</option><option value="3541" data-published="true">马约特</option><option value="3546" data-published="true">摩尔达维亚</option><option value="3551" data-published="true">摩纳哥</option><option value="3556" data-published="true">黑山</option><option value="3561" data-published="true">摩洛哥</option><option value="3566" data-published="true">莫桑比克</option><option value="3571" data-published="true">纳米比亚</option><option value="3576" data-published="true">荷兰</option><option value="3581" data-published="true">尼日尔</option><option value="3586" data-published="true">尼日利亚</option><option value="3591" data-published="true">挪威</option><option value="3596" data-published="true">波兰</option><option value="3601" data-published="true">葡萄牙</option><option value="3606" data-published="true">留尼汪岛</option><option value="3611" data-published="true">罗马尼亚</option><option value="3616" data-published="true">俄罗斯</option><option value="3621" data-published="true">卢旺达</option><option value="3626" data-published="true">圣马力诺</option><option value="3631" data-published="true">圣多美和普林西比</option><option value="3636" data-published="true">沙特阿拉伯</option><option value="3641" data-published="true">塞内加尔</option><option value="3646" data-published="true">塞尔维亚</option><option value="3651" data-published="true">塞舌尔</option><option value="3656" data-published="true">塞拉利昂</option><option value="3661" data-published="true">斯洛伐克</option><option value="3666" data-published="true">斯洛文尼亚</option><option value="3671" data-published="true">索马里</option><option value="3676" data-published="true">南非</option><option value="3681" data-published="true">南苏丹</option><option value="3686" data-published="true">西班牙</option><option value="3691" data-published="true">苏丹</option><option value="3696" data-published="true">瑞典</option><option value="3701" data-published="true">瑞士</option><option value="3706" data-published="true">叙利亚</option><option value="3711" data-published="true">坦桑尼亚</option><option value="3716" data-published="true">土耳其</option><option value="3721" data-published="true">乌干达</option><option value="3726" data-published="true">乌克兰</option><option value="3731" data-published="true">阿拉伯联合酋长国</option><option value="3736" data-published="true">英国</option><option value="3741" data-published="true">乌兹别克斯坦</option><option value="3746" data-published="true">赞比亚</option><option value="3751" data-published="true">津巴布韦</option><option value="3756" data-published="true">伯利兹</option><option value="3761" data-published="true">加拿大</option><option value="3766" data-published="true">哥斯达黎加</option><option value="3771" data-published="true">多明尼加共和国</option><option value="3776" data-published="true">萨尔瓦多</option><option value="3781" data-published="true">加纳</option><option value="3786" data-published="true">危地马拉</option><option value="3791" data-published="true">洪都拉斯</option><option value="3796" data-published="true">牙买加</option><option value="3801" data-published="true">墨西哥</option><option value="3806" data-published="true">尼加拉瓜</option><option value="3811" data-published="true">巴拿马</option><option value="3816" data-published="true">特立尼达和多巴哥</option><option value="3821" data-published="true">美国</option><option value="3826" data-published="true">安提瓜和巴布达</option><option value="3831" data-published="true">阿根廷</option><option value="3836" data-published="true">巴哈马</option><option value="3841" data-published="true">巴巴多斯</option><option value="3846" data-published="true">玻利维亚</option><option value="3851" data-published="true">巴西</option><option value="3856" data-published="true">喀麦隆</option><option value="3861" data-published="true">智利</option><option value="3866" data-published="true">哥伦比亚</option><option value="3871" data-published="true">古巴</option><option value="3876" data-published="true">厄瓜多尔</option><option value="3881" data-published="true">爱沙尼亚</option><option value="3886" data-published="true">加蓬</option><option value="3896" data-published="true">圭亚那</option><option value="3901" data-published="true">海地</option><option value="3906" data-published="true">北马其顿</option><option value="3911" data-published="true">巴拉圭</option><option value="3916" data-published="true">秘鲁</option><option value="3921" data-published="true">圣基茨和尼维斯</option><option value="3926" data-published="true">圣卢西亚</option><option value="3931" data-published="true">圣文森特和格林纳丁斯</option><option value="3936" data-published="true">萨摩亚</option><option value="3941" data-published="true">苏里南</option><option value="3946" data-published="true">突尼斯</option><option value="3951" data-published="true">乌拉圭</option><option value="3956" data-published="true">委内瑞拉</option><option value="4211" data-published="true">马其顿</option><option value="4216" data-published="true">梵蒂冈</option></select><span class="select2 select2-container select2-container--default" dir="ltr" data-select2-id="205" style="width: 100%;"><span class="selection"><span class="select2-selection select2-selection--single" role="combobox" aria-haspopup="true" aria-expanded="false" tabindex="0" aria-disabled="false" aria-labelledby="select2-edit-field-country-c-container"><span class="select2-selection__rendered" id="select2-edit-field-country-c-container" role="textbox" aria-readonly="true"><span class="select2-selection__placeholder">地区</span></span><span class="select2-selection__arrow" role="presentation"><b role="presentation"></b></span></span></span><span class="dropdown-wrapper" aria-hidden="true"></span></span>
<div class="countrySuggestions"></div>
</div>
</div>
<span class="field_country_c_error error"></span><div class="field--type-string field--name-email field--widget-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-email-wrapper" id="edit-email-wrapper"> <div class="js-form-item form-item js-form-type-textfield form-item-email-0-value js-form-item-email-0-value">
<label for="edit-email-0-value" class="js-form-required invisible form-required">电子邮件</label>
<input class="js-text-full text-full form-text required" data-drupal-selector="edit-email-0-value" type="text" id="edit-email-0-value" name="email[0][value]" value="" size="60" maxlength="255" placeholder="电子邮件" required="required" aria-required="true">
</div>
</div>
<span class="email_error error"></span><div class="field--type-string field--name-field-action-url field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-action-url-wrapper" id="edit-field-action-url-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-action-url-0-value" type="hidden" name="field_action_url[0][value]" value="https://ogilvygroupsbox.sugarondemand.com/index.php?entryPoint=WebToLeadCapture">
</div>
<span class="field_action_url_error error"></span><div class="field--type-string field--name-field-source-c field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-source-c-wrapper" id="edit-field-source-c-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-source-c-0-value" type="hidden" name="field_source_c[0][value]" value="Web Site">
</div>
<span class="field_source_c_error error"></span><div class="field--type-string field--name-field-source-group-c field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-source-group-c-wrapper" id="edit-field-source-group-c-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-source-group-c-0-value" type="hidden" name="field_source_group_c[0][value]" value="Ogilvy">
</div>
<span class="field_source_group_c_error error"></span><div class="field--type-string field--name-field-sourceitem-c field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-sourceitem-c-wrapper" id="edit-field-sourceitem-c-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-sourceitem-c-0-value" type="hidden" name="field_sourceitem_c[0][value]" value="TBD">
</div>
<span class="field_sourceitem_c_error error"></span><div class="field--type-string field--name-field-status field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-status-wrapper" id="edit-field-status-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-status-0-value" type="hidden" name="field_status[0][value]" value="New">
</div>
<span class="field_status_error error"></span><div class="field--type-string field--name-field-f-path field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-f-path-wrapper" id="edit-field-f-path-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-f-path-0-value" type="hidden" name="field_f_path[0][value]" value="">
</div>
<span class="field_f_path_error error"></span><div class="field--type-string field--name-field-customer field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-customer-wrapper" id="edit-field-customer-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-customer-0-value" type="hidden" name="field_customer[0][value]" value="ch000097311eArad">
</div>
<span class="field_customer_error error"></span><div class="field--type-string field--name-field-dialogid field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-dialogid-wrapper" id="edit-field-dialogid-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-dialogid-0-value" type="hidden" name="field_dialogid[0][value]" value="200">
</div>
<span class="field_dialogid_error error"></span><div class="field--type-string field--name-field-cke field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-cke-wrapper" id="edit-field-cke-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-cke-0-value" type="hidden" name="field_cke[0][value]" value="1">
</div>
<span class="field_cke_error error"></span><div class="field--type-string field--name-field-assigned-user-id field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-assigned-user-id-wrapper" id="edit-field-assigned-user-id-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-assigned-user-id-0-value" type="hidden" name="field_assigned_user_id[0][value]" value="1">
</div>
<span class="field_assigned_user_id_error error"></span><div class="field--type-string field--name-field-campaign-id field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-campaign-id-wrapper" id="edit-field-campaign-id-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-campaign-id-0-value" type="hidden" name="field_campaign_id[0][value]" value="0b20b7a8-5089-11e9-a3ae-022cc35525d8">
</div>
<span class="field_campaign_id_error error"></span><div class="field--type-string field--name-field-hidden-submit-from-website field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-hidden-submit-from-website-wrapper" id="edit-field-hidden-submit-from-website-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-hidden-submit-from-website-0-value" type="hidden" name="field_hidden_submit_from_website[0][value]" value="WebToLead">
</div>
<span class="field_hidden_submit_from_website_error error"></span><div class="field--type-string field--name-field-redirect-url field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-redirect-url-wrapper" id="edit-field-redirect-url-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-redirect-url-0-value" type="hidden" name="field_redirect_url[0][value]" value="https://www.ogilvy.com">
</div>
<span class="field_redirect_url_error error"></span><div class="field--type-string field--name-field-team-set-id field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-team-set-id-wrapper" id="edit-field-team-set-id-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-team-set-id-0-value" type="hidden" name="field_team_set_id[0][value]" value="1">
</div>
<span class="field_team_set_id_error error"></span><div class="field--type-string field--name-field-footer-connect-action-url field--widget-field-hidden-string-textfield js-form-wrapper form-wrapper" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-field-footer-connect-action-url-wrapper" id="edit-field-footer-connect-action-url-wrapper"> <input class="js-text-full text-full field-hidden-string" data-drupal-selector="edit-field-footer-connect-action-url-0-value" type="hidden" name="field_footer_connect_action_url[0][value]" value="https://crmemails.ogilvy.com/api/forms/submit">
</div>
<span class="field_footer_connect_action_url_error error"></span><div data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-actions" class="form-actions js-form-wrapper form-wrapper" id="edit-actions--2"><input class="use-ajax button js-form-submit form-submit" data-drupal-selector="edit-send" type="submit" id="edit-send" name="op" value="提交" data-once="drupal-ajax ajax">
</div>
<span class="actions_error error"></span><div class="url-textfield js-form-wrapper form-wrapper" style="display: none !important;"><div class="js-form-item form-item js-form-type-textfield form-item-url js-form-item-url">
<label for="edit-url">Leave this field blank</label>
<input autocomplete="off" data-twig-suggestion="content-entity-file-utility-add-form" data-drupal-selector="edit-url" type="text" id="edit-url" name="url" value="" size="20" maxlength="128" class="form-text">
</div>
</div>
<div class="error-message error"></div>
<div class="privacy-policy connect-legal-privacyPolicy">请阅读我们的 <a target="_blank" href="/cn/privacy-policy">隐私政策</a>, 以了解我们如何使用您的个人信息。</div> </form>
</div>
</div>
</div>
</article>
</div>
</div>
<div class="popup-cookies-wrap is_active">
<div class="cookies_clumn">
<p>为了与此功能交互，您必须打开功能性 Cookie。在下方更改您的 cookie 偏好，以及&nbsp;<a class="cookie_page_link" href="/cn//cookies/">点击这里</a>&nbsp;阅读更多关于我们如何使用 cookie 的信息</p> <div target="1" class="cookies_ani-border is_active active" id="form-functional-cookies-id"><span></span>
<p style="">Off</p>
</div>
</div>
</div>
<progress id="progress_bar" class="progress_bar_error" value="0" max="100"></progress>
<div id="success-message" class="success-message nongated-success-message" style="display:none"><span>Thank you. You'll hear from us soon.</span></div>
<div id="success-message" class="success-message gated-success-message" style="display:none"><span>谢谢你。您请求的内容将出现在新窗口中</span></div>
</div>
</div>
<div class="feed-crm-pop_wrapper-new connect-crm-wrap-new">
<div class="feed-modal-new"></div>
</div>
<div class="container">
<div id="winpopup-we-chat" class="modal-box pointPop-content">
<div class="ogilvy-sitemodal-overlay"></div>
<div class="sm-container">
<div class="sm-content win-popup">
<button class="win-close js-modal-close">
<span class="cookies__close">
<svg id="close-icon" viewBox="0 0 14.6 14.6" width="100%" height="100%">
<path fill="none" stroke="currentColor" stroke-width="1" d="M.3.3l14 14m0-14l-14 14"></path>
</svg>
</span>
</button>
<div class="pop-content">
<div class="content-wrp">
<div class="content-sec">
<h2>
<div>欢迎关注奥美中国官方微信</div>
</h2>
<p>
</p>
</div>
<div> <img loading="lazy" src="/cn/sites/g/files/dhpsjz236/files/2021-03/WeChat%20QR%20Code%20Ogilvy%20China_0.jpg" alt="Wechat QR Code">
</div>
</div>
</div>
</div>
</div>
</div>
</div>
<div class="container">
<div id="winpopup-weibo" class="modal-box pointPop-content">
<div class="ogilvy-sitemodal-overlay"></div>
<div class="sm-container">
<div class="sm-content win-popup">
<button class="win-close js-modal-close">
<span class="cookies__close">
<svg id="close-icon" viewBox="0 0 14.6 14.6" width="100%" height="100%">
<path fill="none" stroke="currentColor" stroke-width="1" d="M.3.3l14 14m0-14l-14 14"></path>
</svg>
</span>
</button>
<div class="pop-content">
<div class="content-wrp">
<div class="content-sec">
<h2>
<div>欢迎关注奥美中国官方微博</div>
</h2>
<p>
</p>
</div>
<div> <img loading="lazy" src="/cn/sites/g/files/dhpsjz236/files/2021-03/Weibo%20QR%20Code%20Ogilvy%20China_1.jpg" alt="Weibo QR Code">
</div>
</div>
</div>
</div>
</div>
</div>
</div>
<script type="application/json" data-drupal-selector="drupal-settings-json">{"path":{"baseUrl":"\/cn\/","scriptPath":null,"pathPrefix":"","currentPath":"home","currentPathIsAdmin":false,"isFront":true,"currentLanguage":"zh-hans"},"pluralDelimiter":"\u0003","suppressDeprecationErrors":true,"ajaxPageState":{"libraries":"addtoany\/addtoany.front,better_exposed_filters\/auto_submit,better_exposed_filters\/general,better_exposed_filters\/select_all_none,blazy\/bio.ajax,core\/internal.jquery.form,core\/picturefill,eu_cookie_compliance\/eu_cookie_compliance_default,field_hidden\/drupal.field_hidden,file_utility\/file_utility_js,formtips\/formtips,formtips\/hoverintent,layout_discovery\/onecol,ogilvy\/custom-styling,ogilvy\/splash-styling,ogilvy_geo_cookie\/ogilvy_geo_cookie,select2\/select2,select2\/select2.i18n.zh-hans,select2_publish\/select2.publish,system\/base,views\/views.ajax,views\/views.module,views_ajax_get\/ajax_get","theme":"ogilvy","theme_token":null},"ajaxTrustedUrl":{"form_action_p_pvdeGsVG5zNF_XLGPTvYSKCf43t8qZYSwcfZl2uzM":true,"\/cn\/home?ajax_form=1":true,"\/cn\/home":true},"dialogid_region_crm":"616","dialogid_footer_crm":"617","dialogid_idea_crm":"615","dialogid_idea_email_crm":"937","idea_page_path":"ideas","current_alias_path":"\/home","errorcode":"0","ajax":{"edit-send":{"callback":[{"mailManager":{}},"submitUserInfoFormAjax"],"event":"click","url":"\/cn\/home?ajax_form=1","dialogType":"ajax","submit":{"_triggering_element_name":"op","_triggering_element_value":"\u63d0\u4ea4"}}},"formtips":{"selectors":[""],"interval":500,"sensitivity":3,"timeout":1000,"max_width":"500px","trigger_action":"hover"},"open_model_file":0,"file_force_download":1,"allowed_content_types":"ideas|feeds","allowed_file_extensions":"pdf","geo_cookie_lifetime":30,"geo_cookie_fc_default":{"af":1,"ax":1,"al":1,"dz":1,"as":1,"ad":1,"ao":1,"ai":1,"ag":1,"ar":1,"am":1,"aw":1,"au":1,"at":1,"az":1,"bs":1,"bh":1,"bd":1,"bb":1,"by":1,"be":1,"bz":1,"bj":1,"bm":1,"bt":1,"bo":1,"bq":1,"ba":1,"bw":1,"bv":1,"br":1,"io":1,"bn":1,"bg":1,"bf":1,"bi":1,"cv":1,"kh":1,"cm":1,"ca":1,"ky":1,"cf":1,"td":1,"cl":1,"cn":1,"cx":1,"cc":1,"co":1,"km":1,"cd":1,"cg":1,"ck":1,"cr":1,"hr":1,"cu":1,"cw":1,"cy":1,"cz":1,"dk":1,"dj":1,"dm":1,"do":1,"ec":1,"eg":1,"sv":1,"gq":1,"er":1,"ee":1,"sz":1,"et":1,"fk":1,"fo":1,"fj":1,"fi":1,"fr":1,"gf":1,"pf":1,"tf":1,"ga":1,"gm":1,"ge":1,"de":1,"gh":1,"gi":1,"gr":1,"gl":1,"gd":1,"gp":1,"gu":1,"gt":1,"gg":1,"gn":1,"gw":1,"gy":1,"ht":1,"hm":1,"va":1,"hn":1,"hk":1,"hu":1,"is":1,"in":1,"id":1,"ir":1,"iq":1,"ie":1,"im":1,"il":1,"it":1,"jm":1,"jp":1,"je":1,"jo":1,"kz":1,"ke":1,"ki":1,"kw":1,"kg":1,"la":1,"lv":1,"lb":1,"ls":1,"lr":1,"ly":1,"li":1,"lt":1,"lu":1,"mo":1,"mg":1,"mw":1,"my":1,"mv":1,"ml":1,"mt":1,"mh":1,"mq":1,"mr":1,"mu":1,"yt":1,"mx":1,"fm":1,"md":1,"mc":1,"mn":1,"me":1,"ms":1,"ma":1,"mz":1,"mm":1,"na":1,"nr":1,"np":1,"nl":1,"nc":1,"nz":1,"ni":1,"ne":1,"ng":1,"nu":1,"nf":1,"mk":1,"mp":1,"no":1,"om":1,"pk":1,"pw":1,"ps":1,"pa":1,"pg":1,"py":1,"pe":1,"ph":1,"pn":1,"pl":1,"pt":1,"pr":1,"qa":1,"ro":1,"ru":1,"rw":1,"re":1,"bl":1,"sh":1,"kn":1,"lc":1,"mf":1,"vc":1,"ws":1,"sm":1,"st":1,"sa":1,"sn":1,"rs":1,"sc":1,"sl":1,"sg":1,"sx":1,"sk":1,"si":1,"sb":1,"so":1,"za":1,"gs":1,"kr":1,"ss":1,"es":1,"lk":1,"sd":1,"sr":1,"sj":1,"se":1,"ch":1,"sy":1,"tw":1,"tj":1,"tz":1,"th":1,"tl":1,"tg":1,"tk":1,"to":1,"tt":1,"tn":1,"tr":1,"tm":1,"tc":1,"tv":1,"ug":1,"ua":1,"ae":1,"gb":1,"us":1,"um":1,"uy":1,"uz":1,"vu":1,"ve":1,"vn":1,"vg":1,"vi":1,"wf":1,"eh":1,"ye":1,"zm":1,"zw":1},"geo_cookie_pc_default":{"af":1,"ax":1,"al":0,"dz":1,"as":1,"ad":0,"ao":1,"ai":1,"ag":1,"ar":1,"am":0,"aw":1,"au":1,"at":0,"az":0,"bs":1,"bh":0,"bd":1,"bb":1,"by":0,"be":0,"bz":1,"bj":1,"bm":1,"bt":1,"bo":1,"bq":1,"ba":0,"bw":1,"bv":1,"br":1,"io":1,"bn":1,"bg":0,"bf":1,"bi":1,"cv":1,"kh":1,"cm":1,"ca":1,"ky":1,"cf":1,"td":1,"cl":1,"cn":1,"cx":1,"cc":1,"co":1,"km":1,"cd":1,"cg":1,"ck":1,"cr":1,"hr":0,"cu":1,"cw":1,"cy":0,"cz":0,"dk":0,"dj":1,"dm":1,"do":1,"ec":1,"eg":1,"sv":1,"gq":1,"er":1,"ee":0,"sz":1,"et":1,"fk":1,"fo":1,"fj":1,"fi":0,"fr":0,"gf":1,"pf":1,"tf":1,"ga":1,"gm":1,"ge":0,"de":0,"gh":1,"gi":1,"gr":0,"gl":1,"gd":1,"gp":1,"gu":1,"gt":1,"gg":1,"gn":1,"gw":1,"gy":1,"ht":1,"hm":1,"va":1,"hn":1,"hk":1,"hu":0,"is":0,"in":1,"id":1,"ir":1,"iq":1,"ie":0,"im":1,"il":1,"it":0,"jm":1,"jp":1,"je":1,"jo":1,"kz":1,"ke":1,"ki":1,"kw":1,"kg":1,"la":1,"lv":0,"lb":1,"ls":1,"lr":1,"ly":1,"li":0,"lt":0,"lu":0,"mo":1,"mg":1,"mw":1,"my":1,"mv":1,"ml":1,"mt":0,"mh":1,"mq":1,"mr":1,"mu":1,"yt":1,"mx":1,"fm":1,"md":0,"mc":0,"mn":1,"me":0,"ms":1,"ma":1,"mz":1,"mm":1,"na":1,"nr":1,"np":1,"nl":0,"nc":1,"nz":1,"ni":1,"ne":1,"ng":1,"nu":1,"nf":1,"mk":0,"mp":1,"no":0,"om":1,"pk":1,"pw":1,"ps":1,"pa":1,"pg":1,"py":1,"pe":1,"ph":1,"pn":1,"pl":0,"pt":0,"pr":1,"qa":1,"ro":0,"ru":0,"rw":1,"re":1,"bl":1,"sh":1,"kn":1,"lc":1,"mf":1,"vc":1,"ws":1,"sm":0,"st":1,"sa":1,"sn":1,"rs":0,"sc":1,"sl":1,"sg":1,"sx":1,"sk":0,"si":0,"sb":1,"so":1,"za":1,"gs":1,"kr":1,"ss":1,"es":0,"lk":1,"sd":1,"sr":1,"sj":1,"se":0,"ch":0,"sy":1,"tw":1,"tj":1,"tz":1,"th":1,"tl":1,"tg":1,"tk":1,"to":1,"tt":1,"tn":1,"tr":0,"tm":1,"tc":1,"tv":1,"ug":1,"ua":0,"ae":1,"gb":0,"us":1,"um":1,"uy":1,"uz":1,"vu":1,"ve":1,"vn":1,"vg":1,"vi":1,"wf":1,"eh":1,"ye":1,"zm":1,"zw":1},"geo_website_urls":{"af":"","ax":"","al":"https:\/\/ogilvy.al\/","dz":"","as":"","ad":"","ao":"","ai":"","ag":"","ar":"","am":"","aw":"","au":"https:\/\/www.ogilvy.com.au\/","at":"https:\/\/ogilvy.at\/","az":"","bs":"","bh":"https:\/\/www.memacogilvy.com\/","bd":"","bb":"","by":"","be":"https:\/\/ogilvy-sociallab.be\/","bz":"","bj":"","bm":"","bt":"","bo":"https:\/\/ogilvy.com.bo\/","bq":"","ba":"","bw":"","bv":"","br":"http:\/\/www.ogilvy.com.br\/","io":"","bn":"","bg":"","bf":"","bi":"","cv":"","kh":"","cm":"","ca":"https:\/\/www.ogilvy.com\/ca\/","ky":"","cf":"","td":"","cl":"","cn":"https:\/\/www.ogilvy.com\/cn\/","cx":"","cc":"","co":"","km":"","cd":"","cg":"","ck":"","cr":"","hr":"","cu":"","cw":"","cy":"","cz":"https:\/\/www.ogilvy.cz\/en\/","dk":"https:\/\/www.ogilvy.dk\/","dj":"","dm":"","do":"https:\/\/ogilvyrd.com\/","ec":"","eg":"https:\/\/www.memacogilvy.com\/","sv":"","gq":"","er":"","ee":"","sz":"","et":"","fk":"","fo":"","fj":"","fi":"","fr":"https:\/\/www.ogilvy.com\/fr\/fre","gf":"","pf":"","tf":"","ga":"","gm":"","ge":"","de":"https:\/\/www.ogilvy.com\/de\/","gh":"","gi":"","gr":"https:\/\/ogilvy.gr\/","gl":"","gd":"","gp":"","gu":"","gt":"https:\/\/ogilvyguatemala.com\/","gg":"","gn":"","gw":"","gy":"","ht":"","hm":"","va":"","hn":"","hk":"","hu":"http:\/\/ogilvy.hu\/","is":"","in":"http:\/\/www.ogilvyindia.com\/","id":"","ir":"","iq":"","ie":"https:\/\/www.ogilvy.ie","im":"","il":"","it":"https:\/\/www.ogilvy.com\/it\/","jm":"","jp":"https:\/\/www.ogilvy.co.jp","je":"","jo":"https:\/\/www.memacogilvy.com\/","kz":"","ke":"https:\/\/ogilvy.africa\/","ki":"","kw":"https:\/\/www.memacogilvy.com\/","kg":"","la":"","lv":"https:\/\/www.ogilvypr.lv\/","lb":"https:\/\/www.memacogilvy.com\/","ls":"","lr":"","ly":"","li":"","lt":"https:\/\/www.ogilvy.lt\/","lu":"","mo":"","mg":"","mw":"","my":"","mv":"","ml":"","mt":"","mh":"","mq":"","mr":"","mu":"","yt":"","mx":"https:\/\/www.ogilvy.com.mx\/","fm":"","md":"","mc":"","mn":"","me":"","ms":"","ma":"","mz":"","mm":"","na":"http:\/\/www.ogilvy.com.na\/","nr":"","np":"","nl":"https:\/\/www.ogilvy.nl\/","nc":"","nz":"","ni":"https:\/\/ogilvy.com.ni\/","ne":"","ng":"","nu":"","nf":"","mk":"","mp":"","no":"","om":"","pk":"","pw":"","ps":"","pa":"http:\/\/www.p4ogilvy.com\/","pg":"","py":"","pe":"","ph":"","pn":"","pl":"https:\/\/www.ogilvy.pl\/pl\/strona-glowna\/","pt":"https:\/\/barogilvy.pt\/","pr":"","qa":"https:\/\/www.memacogilvy.com\/","ro":"","ru":"http:\/\/www.ogilvyrussia.ru\/","rw":"http:\/\/www.ogilvyrussia.ru\/","re":"","bl":"","sh":"","kn":"","lc":"","mf":"","vc":"","ws":"","sm":"","st":"","sa":"https:\/\/www.memacogilvy.com\/","sn":"","rs":"https:\/\/fullhouseogilvy.rs\/","sc":"","sl":"","sg":"https:\/\/ogilvy.sg\/","sx":"","sk":"","si":"","sb":"","so":"","za":"https:\/\/www.ogilvy.co.za\/","gs":"","kr":"http:\/\/www.ogilvy.co.kr\/kr","ss":"","es":"https:\/\/www.ogilvy.com\/es\/","lk":"http:\/\/ogilvy.lk\/","sd":"","sr":"","sj":"","se":"","ch":"https:\/\/www.ogilvy.ch\/","sy":"","tw":"https:\/\/www.ogilvy.com\/tw\/","tj":"","tz":"","th":"","tl":"","tg":"","tk":"","to":"","tt":"http:\/\/www.ogilvycaribbean.com\/","tn":"https:\/\/www.memacogilvy.com\/","tr":"https:\/\/www.ogilvy.com.tr\/","tm":"","tc":"","tv":"","ug":"","ua":"","ae":"https:\/\/www.ogilvy.com\/ae\/","gb":"https:\/\/www.ogilvy.com\/uk\/","us":"https:\/\/www.ogilvy.com\/","um":"","uy":"https:\/\/www.puntoogilvy.com.uy\/","uz":"","vu":"","ve":"","vn":"","vg":"","vi":"","wf":"","eh":"","ye":"","zm":"","zw":""},"default_cookies_for_others":1,"base_url":"https:\/\/www.ogilvy.com\/cn","geo_redirection_disable_option":1,"bots_list_to_disable_geo_redirection":"Googlebot|Googlebot-News|Googlebot-Image|Googlebot-Video|Mediapartners-Google|AdsBot-Google|AdsBot-Google-Mobile-Apps|Bingbot|Slurp|DuckDuckBot|Baiduspider|YandexBot|Sogou|Exabot|Facebot|facebookexternalhit|ia_archiver|Chrome-Lighthouse|GTmetrix|PTST","eu_cookie_compliance":{"cookie_policy_version":"1.0.0","popup_enabled":true,"popup_agreed_enabled":false,"popup_hide_agreed":false,"popup_clicking_confirmation":false,"popup_scrolling_confirmation":false,"popup_html_info":"\u003Cdiv class=\u0022eu-cookie-compliance-banner eu-cookie-compliance-banner-info eu-cookie-compliance-banner--categories\u0022\u003E\n\t\u003Cdiv class=\u0022popup-content info eu-cookie-compliance-content\u0022\u003E\n\t\t\u003Cdiv class=\u0022cookies__policy\u0022\u003E\n\t\t\t\u003Cdiv class=\u0022container\u0022\u003E\n\t\t\t\t\u003Cdiv id=\u0022eu-cookie-compliance-categories\u0022 class=\u0022cookies-wrp\u0022\u003E\n\t\t\t\t\t\u003Cdiv class=\u0022cookies_clumn\u0022\u003E\n\t\t\t\t\t\t\u003Cp\u003E\u003Cspan\u003E\u5965\u7f8e\u5982\u4f55\u4f7f\u7528 Cookies\u003C\/span\u003E\u003C\/p\u003E\u003Cp\u003E\u5965\u7f8e\uff08Ogilvy.com\uff09\u4f7f\u7528Cookies\uff0c\u662f\u4e3a\u4e86\u63d0\u4f9b\u7f51\u7ad9\u8fd0\u884c\u6240\u5fc5\u9700\u7684\u73af\u5883\uff0c\u540c\u65f6\u5e2e\u52a9\u6211\u4eec\u4e3a\u60a8\u63d0\u4f9b\u66f4\u597d\u7684\u7528\u6237\u4f53\u9a8c\u3002\u66f4\u591a\u8be6\u60c5\uff0c \u003Cbr \/\u003E\u003Ca href=\u0022\/cn\/cookies\u0022 target=\u0022_blank\u0022\u003E\u70b9\u51fb\u6b64\u5904\u3002\u003C\/a\u003E\u003C\/p\u003E\n\t\t\t\t\t\u003C\/div\u003E\n\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u003Cdiv class=\u0022cookies_clumn\u0022\u003E\n\t\t\t\t\t\t\t\t\t\u003Cspan for=\u0022cookie-category-nc\u0022\u003E\u5fc5\u8981\u6027\u7528\u9014\u7684 Cookies\u003C\/span\u003E\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u8fd9\u662f Ogilvy.com \u6b63\u5e38\u8fd0\u884c\u6240\u5fc5\u9700\u7684\uff0c\u4e14\u5bf9\u6211\u4eec\u7f51\u7ad9\u4f7f\u7528\u5176\u6838\u5fc3\u529f\u80fd\u548c\u589e\u5f3a\u529f\u80fd\u81f3\u5173\u91cd\u8981\u3002\u4e00\u65e6\u7981\u7528\uff0cOgilvy.com \u5c06\u65e0\u6cd5\u6b63\u5e38\u8fd0\u884c\u6216\u4e3a\u60a8\u63d0\u4f9b\u60a8\u6240\u9700\u8981\u7684\u670d\u52a1\u3002\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u003Cdiv class=\u0022cookies_active-border\u0022 target=\u0022nc\u0022 id=\u0022nc-popup-id\u0022 style=\u0022display:none;\u0022\u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cinput type=\u0022checkbox\u0022 class=\u0022cookies-checked\u0022 name=\u0022cookie-categories\u0022 id=\u0022cookie-category-nc\u0022 aria-labelledby =\u0022cookie-category-nc\u0022 value=\u0022nc\u0022  checked disabled \u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cspan\u003E\u0026nbsp;\u003C\/span\u003E\n\t\t\t\t\t\t\t\t\t\u003C\/div\u003E\n\t\t\t\t\t\t\t\t\u003C\/div\u003E\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u003Cdiv class=\u0022cookies_clumn\u0022\u003E\n\t\t\t\t\t\t\t\t\t\u003Cspan for=\u0022cookie-category-fc\u0022\u003E\u529f\u80fd\u6027\u7528\u9014\u7684 Cookies\u003C\/span\u003E\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u5141\u8bb8 Ogilvy.com \u8bb0\u4f4f\u60a8\u6240\u505a\u7684\u9009\u62e9\uff0c\u4ee5\u4fbf\u6839\u636e\u60a8\u7684\u504f\u597d\u63d0\u4f9b\u66f4\u597d\u7684\u529f\u80fd\u548c\u4e2a\u6027\u5316\u6a21\u5f0f\u3002\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u003Cdiv class=\u0022cookies_ani-border\u0022 target=\u0022fc\u0022 id=\u0022fc-popup-id\u0022\u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cinput type=\u0022checkbox\u0022 class=\u0022cookies-checked\u0022 name=\u0022cookie-categories\u0022 id=\u0022cookie-category-fc\u0022 aria-labelledby =\u0022cookie-category-fc\u0022 value=\u0022fc\u0022 \u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cspan\u003E\u0026nbsp;\u003C\/span\u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cp\u003EOff\u003C\/p\u003E\n\t\t\t\t\t\t\t\t\t\u003C\/div\u003E\n\t\t\t\t\t\t\t\t\u003C\/div\u003E\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u003Cdiv class=\u0022cookies_clumn\u0022\u003E\n\t\t\t\t\t\t\t\t\t\u003Cspan for=\u0022cookie-category-pc\u0022\u003E\u6027\u80fd Cookies\u003C\/span\u003E\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u901a\u8fc7\u6536\u96c6\u548c\u62a5\u544a\u6709\u5173\u60a8\u5982\u4f55\u4f7f\u7528\u7f51\u7ad9\u7684\u4fe1\u606f\uff0c\u5e2e\u52a9\u63d0\u9ad8 Ogilvy.com \u7684\u6027\u80fd\u3002\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u003Cdiv class=\u0022cookies_ani-border\u0022 target=\u0022pc\u0022 id=\u0022pc-popup-id\u0022\u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cinput type=\u0022checkbox\u0022 class=\u0022cookies-checked\u0022 name=\u0022cookie-categories\u0022 id=\u0022cookie-category-pc\u0022 aria-labelledby =\u0022cookie-category-pc\u0022 value=\u0022pc\u0022 \u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cspan\u003E\u0026nbsp;\u003C\/span\u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cp\u003EOff\u003C\/p\u003E\n\t\t\t\t\t\t\t\t\t\u003C\/div\u003E\n\t\t\t\t\t\t\t\t\u003C\/div\u003E\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u003Cdiv id=\u0022popup-buttons\u0022 class=\u0022eu-cookie-compliance-buttons eu-cookie-compliance-has-categories\u0022\u003E\n\t\t\t\t\t\t\u003Cbutton type=\u0022button\u0022 class=\u0022cookies__close agree-button\u0022 aria-labelledby=\u0022popup-buttons\u0022\u003E\n\t\t\t\t\t\t\t\u003Csvg id=\u0022close-icon\u0022 viewBox=\u00220 0 14.6 14.6\u0022 width=\u0022100%\u0022 height=\u0022100%\u0022\u003E\n\t\t\t\t\t\t\t\t\u003Cpath fill=\u0022none\u0022 stroke=\u0022currentColor\u0022 stroke-width=\u00221\u0022 d=\u0022M.3.3l14 14m0-14l-14 14\u0022\u003E\u003C\/path\u003E\n\t\t\t\t\t\t\t\u003C\/svg\u003E\n\t\t\t\t\t\t\u003C\/button\u003E\n\t\t\t\t\t\u003C\/div\u003E\n\t\t\t\t\u003C\/div\u003E\n\t\t\t\u003C\/div\u003E\n\t\t\u003C\/div\u003E\n\t\u003C\/div\u003E\n\u003C\/div\u003E","use_mobile_message":false,"mobile_popup_html_info":"\u003Cdiv class=\u0022eu-cookie-compliance-banner eu-cookie-compliance-banner-info eu-cookie-compliance-banner--categories\u0022\u003E\n\t\u003Cdiv class=\u0022popup-content info eu-cookie-compliance-content\u0022\u003E\n\t\t\u003Cdiv class=\u0022cookies__policy\u0022\u003E\n\t\t\t\u003Cdiv class=\u0022container\u0022\u003E\n\t\t\t\t\u003Cdiv id=\u0022eu-cookie-compliance-categories\u0022 class=\u0022cookies-wrp\u0022\u003E\n\t\t\t\t\t\u003Cdiv class=\u0022cookies_clumn\u0022\u003E\n\t\t\t\t\t\t\n\t\t\t\t\t\u003C\/div\u003E\n\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u003Cdiv class=\u0022cookies_clumn\u0022\u003E\n\t\t\t\t\t\t\t\t\t\u003Cspan for=\u0022cookie-category-nc\u0022\u003E\u5fc5\u8981\u6027\u7528\u9014\u7684 Cookies\u003C\/span\u003E\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u8fd9\u662f Ogilvy.com \u6b63\u5e38\u8fd0\u884c\u6240\u5fc5\u9700\u7684\uff0c\u4e14\u5bf9\u6211\u4eec\u7f51\u7ad9\u4f7f\u7528\u5176\u6838\u5fc3\u529f\u80fd\u548c\u589e\u5f3a\u529f\u80fd\u81f3\u5173\u91cd\u8981\u3002\u4e00\u65e6\u7981\u7528\uff0cOgilvy.com \u5c06\u65e0\u6cd5\u6b63\u5e38\u8fd0\u884c\u6216\u4e3a\u60a8\u63d0\u4f9b\u60a8\u6240\u9700\u8981\u7684\u670d\u52a1\u3002\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u003Cdiv class=\u0022cookies_active-border\u0022 target=\u0022nc\u0022 id=\u0022nc-popup-id\u0022 style=\u0022display:none;\u0022\u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cinput type=\u0022checkbox\u0022 class=\u0022cookies-checked\u0022 name=\u0022cookie-categories\u0022 id=\u0022cookie-category-nc\u0022 aria-labelledby =\u0022cookie-category-nc\u0022 value=\u0022nc\u0022  checked disabled \u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cspan\u003E\u0026nbsp;\u003C\/span\u003E\n\t\t\t\t\t\t\t\t\t\u003C\/div\u003E\n\t\t\t\t\t\t\t\t\u003C\/div\u003E\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u003Cdiv class=\u0022cookies_clumn\u0022\u003E\n\t\t\t\t\t\t\t\t\t\u003Cspan for=\u0022cookie-category-fc\u0022\u003E\u529f\u80fd\u6027\u7528\u9014\u7684 Cookies\u003C\/span\u003E\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u5141\u8bb8 Ogilvy.com \u8bb0\u4f4f\u60a8\u6240\u505a\u7684\u9009\u62e9\uff0c\u4ee5\u4fbf\u6839\u636e\u60a8\u7684\u504f\u597d\u63d0\u4f9b\u66f4\u597d\u7684\u529f\u80fd\u548c\u4e2a\u6027\u5316\u6a21\u5f0f\u3002\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u003Cdiv class=\u0022cookies_ani-border\u0022 target=\u0022fc\u0022 id=\u0022fc-popup-id\u0022\u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cinput type=\u0022checkbox\u0022 class=\u0022cookies-checked\u0022 name=\u0022cookie-categories\u0022 id=\u0022cookie-category-fc\u0022 aria-labelledby =\u0022cookie-category-fc\u0022 value=\u0022fc\u0022 \u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cspan\u003E\u0026nbsp;\u003C\/span\u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cp\u003EOff\u003C\/p\u003E\n\t\t\t\t\t\t\t\t\t\u003C\/div\u003E\n\t\t\t\t\t\t\t\t\u003C\/div\u003E\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u003Cdiv class=\u0022cookies_clumn\u0022\u003E\n\t\t\t\t\t\t\t\t\t\u003Cspan for=\u0022cookie-category-pc\u0022\u003E\u6027\u80fd Cookies\u003C\/span\u003E\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u901a\u8fc7\u6536\u96c6\u548c\u62a5\u544a\u6709\u5173\u60a8\u5982\u4f55\u4f7f\u7528\u7f51\u7ad9\u7684\u4fe1\u606f\uff0c\u5e2e\u52a9\u63d0\u9ad8 Ogilvy.com \u7684\u6027\u80fd\u3002\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u003Cdiv class=\u0022cookies_ani-border\u0022 target=\u0022pc\u0022 id=\u0022pc-popup-id\u0022\u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cinput type=\u0022checkbox\u0022 class=\u0022cookies-checked\u0022 name=\u0022cookie-categories\u0022 id=\u0022cookie-category-pc\u0022 aria-labelledby =\u0022cookie-category-pc\u0022 value=\u0022pc\u0022 \u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cspan\u003E\u0026nbsp;\u003C\/span\u003E\n\t\t\t\t\t\t\t\t\t\t\u003Cp\u003EOff\u003C\/p\u003E\n\t\t\t\t\t\t\t\t\t\u003C\/div\u003E\n\t\t\t\t\t\t\t\t\u003C\/div\u003E\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\u003Cdiv id=\u0022popup-buttons\u0022 class=\u0022eu-cookie-compliance-buttons eu-cookie-compliance-has-categories\u0022\u003E\n\t\t\t\t\t\t\u003Cbutton type=\u0022button\u0022 class=\u0022cookies__close agree-button\u0022 aria-labelledby=\u0022popup-buttons\u0022\u003E\n\t\t\t\t\t\t\t\u003Csvg id=\u0022close-icon\u0022 viewBox=\u00220 0 14.6 14.6\u0022 width=\u0022100%\u0022 height=\u0022100%\u0022\u003E\n\t\t\t\t\t\t\t\t\u003Cpath fill=\u0022none\u0022 stroke=\u0022currentColor\u0022 stroke-width=\u00221\u0022 d=\u0022M.3.3l14 14m0-14l-14 14\u0022\u003E\u003C\/path\u003E\n\t\t\t\t\t\t\t\u003C\/svg\u003E\n\t\t\t\t\t\t\u003C\/button\u003E\n\t\t\t\t\t\u003C\/div\u003E\n\t\t\t\t\u003C\/div\u003E\n\t\t\t\u003C\/div\u003E\n\t\t\u003C\/div\u003E\n\t\u003C\/div\u003E\n\u003C\/div\u003E","mobile_breakpoint":768,"popup_html_agreed":false,"popup_use_bare_css":false,"popup_height":"auto","popup_width":"100%","popup_delay":1000,"popup_link":"\/cn\/node\/116","popup_link_new_window":true,"popup_position":false,"fixed_top_position":true,"popup_language":"zh-hans","store_consent":false,"better_support_for_screen_readers":false,"cookie_name":"","reload_page":true,"domain":"","domain_all_sites":false,"popup_eu_only":false,"popup_eu_only_js":false,"cookie_lifetime":30,"cookie_session":0,"set_cookie_session_zero_on_disagree":0,"disagree_do_not_show_popup":false,"method":"categories","automatic_cookies_removal":true,"allowed_cookies":"is_form_submited\r\nis_first_visit\r\ncookie_agreed_countries","withdraw_markup":"\u003Cbutton type=\u0022button\u0022 class=\u0022eu-cookie-withdraw-tab\u0022\u003E\u9690\u79c1\u8bbe\u7f6e\u003C\/button\u003E\n\u003Cdiv aria-labelledby=\u0022popup-text\u0022 class=\u0022eu-cookie-withdraw-banner\u0022\u003E\n  \u003Cdiv class=\u0022popup-content info eu-cookie-compliance-content\u0022\u003E\n    \u003Cdiv id=\u0022popup-text\u0022 class=\u0022eu-cookie-compliance-message\u0022 role=\u0022document\u0022\u003E\n      \n    \u003C\/div\u003E\n    \u003Cdiv id=\u0022popup-buttons\u0022 class=\u0022eu-cookie-compliance-buttons\u0022\u003E\n      \u003Cbutton type=\u0022button\u0022 class=\u0022eu-cookie-withdraw-button \u0022\u003E\u64a4\u56de\u540c\u610f\u003C\/button\u003E\n    \u003C\/div\u003E\n  \u003C\/div\u003E\n\u003C\/div\u003E","withdraw_enabled":false,"reload_options":0,"reload_routes_list":"","withdraw_button_on_info_popup":false,"cookie_categories":["nc","fc","pc"],"cookie_categories_details":{"nc":{"uuid":"f4c074b5-41e2-4efe-aaf9-abead1265620","langcode":"en","status":true,"dependencies":[],"id":"nc","label":"\u5fc5\u8981\u6027\u7528\u9014\u7684 Cookies","description":"\u8fd9\u662f Ogilvy.com \u6b63\u5e38\u8fd0\u884c\u6240\u5fc5\u9700\u7684\uff0c\u4e14\u5bf9\u6211\u4eec\u7f51\u7ad9\u4f7f\u7528\u5176\u6838\u5fc3\u529f\u80fd\u548c\u589e\u5f3a\u529f\u80fd\u81f3\u5173\u91cd\u8981\u3002\u4e00\u65e6\u7981\u7528\uff0cOgilvy.com \u5c06\u65e0\u6cd5\u6b63\u5e38\u8fd0\u884c\u6216\u4e3a\u60a8\u63d0\u4f9b\u60a8\u6240\u9700\u8981\u7684\u670d\u52a1\u3002","checkbox_default_state":"required","weight":0},"fc":{"uuid":"2b4b71a8-28d7-43f3-9778-97ee121f7ebf","langcode":"en","status":true,"dependencies":[],"id":"fc","label":"\u529f\u80fd\u6027\u7528\u9014\u7684 Cookies","description":"\u5141\u8bb8 Ogilvy.com \u8bb0\u4f4f\u60a8\u6240\u505a\u7684\u9009\u62e9\uff0c\u4ee5\u4fbf\u6839\u636e\u60a8\u7684\u504f\u597d\u63d0\u4f9b\u66f4\u597d\u7684\u529f\u80fd\u548c\u4e2a\u6027\u5316\u6a21\u5f0f\u3002","checkbox_default_state":"unchecked","weight":1},"pc":{"uuid":"6bb0111c-9ec2-4d3f-a6db-a11b6ccce350","langcode":"en","status":true,"dependencies":[],"id":"pc","label":"\u6027\u80fd Cookies","description":"\u901a\u8fc7\u6536\u96c6\u548c\u62a5\u544a\u6709\u5173\u60a8\u5982\u4f55\u4f7f\u7528\u7f51\u7ad9\u7684\u4fe1\u606f\uff0c\u5e2e\u52a9\u63d0\u9ad8 Ogilvy.com \u7684\u6027\u80fd\u3002","checkbox_default_state":"unchecked","weight":2}},"enable_save_preferences_button":false,"cookie_value_disagreed":"0","cookie_value_agreed_show_thank_you":"1","cookie_value_agreed":"2","containing_element":"body","settings_tab_enabled":false,"olivero_primary_button_classes":"","olivero_secondary_button_classes":"","close_button_action":"close_banner","open_by_default":true,"modules_allow_popup":true,"hide_the_banner":false,"geoip_match":true},"viewsAjaxGet":{"our_work_grid":"our_work_grid"},"views":{"ajax_path":"\/cn\/views\/ajax","ajaxViews":{"views_dom_id:f88a551654ef7fb7b646c718afb7afa17a6bdb3853c03d6d8798a2c9378190bc":{"view_name":"our_work_grid","view_display_id":"our_work_grid","view_args":"","view_path":"\/home","view_base_path":null,"view_dom_id":"f88a551654ef7fb7b646c718afb7afa17a6bdb3853c03d6d8798a2c9378190bc","pager_element":0},"views_dom_id:cfd1d288ace5d3b81a36e9cdddaa84181fb994009c00abfe4845453ee717a621":{"view_name":"splash_image_list","view_display_id":"splash_image","view_args":"","view_path":"\/home","view_base_path":null,"view_dom_id":"cfd1d288ace5d3b81a36e9cdddaa84181fb994009c00abfe4845453ee717a621","pager_element":0}}},"user":{"uid":0,"permissionsHash":"fc3d4c744343966a6e587f1ef6227de17a57bedf2dfc83281009fcbd48863f18"}}</script>
<script src="/cn/sites/g/files/dhpsjz236/files/js/js_RU2OIyyzxaQUrSUeKMN41o3P30WefI8-O7YZ-AqJkVw.js" type="text/javascript"></script>
<script async="" src="https://static.addtoany.com/menu/page.js" type="text/javascript"></script>
<script src="/cn/sites/g/files/dhpsjz236/files/js/js_OA_3XcIkwaydE6N7md3BK_M1yfaxrvbDVYndYhqh53w.js" type="text/javascript"></script>
<script src="https://player.vimeo.com/api/player.js" type="text/javascript"></script>
<script src="/cn/sites/g/files/dhpsjz236/files/js/js_w7YWZfjfJEf9CEZvH8mtuwlmnn7Gu5tYJMCX0AbALLI.js" type="text/javascript"></script>
<script src="/cn/modules/contrib/eu_cookie_compliance/js/eu_cookie_compliance.js?v=9.5.8" defer="" type="text/javascript"></script>
<script src="/cn/sites/g/files/dhpsjz236/files/js/js_J-7F-nltFoyLiAZhARGm2Tyg2vLrhVD6IdzQcSuOHFc.js" type="text/javascript"></script>
<script type="text/javascript" src="https://secure.link5view.com/js/191680.js"></script>
<noscript><img alt="" src="https://secure.link5view.com/191680.png" style="display:none;" /></noscript>
<script type="text/javascript">window.NREUM||(NREUM={});NREUM.info={"beacon":"bam.nr-data.net","licenseKey":"290a3572ee","applicationID":"213500175","transactionName":"YwNRbEZQCEMCABZdDFpJcltAWAleTCcQQRNVCm97W0MDbCYNFl0XTTpwV1pFFF8PDwdGP3EIR1FASDBZBhQhWw1AFFxUWFQUHV0VC1EU","queueTime":4,"applicationTime":2812,"atts":"T0RSGg5KG00=","errorBeacon":"bam.nr-data.net","agent":""}</script>

<div style="position: static;"><div style="height: 1px; width: 1px; position: absolute; z-index: 100000; top: 0px; visibility: hidden;"><iframe id="a2a_sm_ifr" style="height: 1px; width: 1px; border: 0px none; left: 0px; top: 0px; position: absolute; z-index: 100000; display: none;" title="AddToAny Utility Frame" transparency="true" allowtransparency="true" src="https://static.addtoany.com/menu/sm.24.html#type=core&amp;event=load" frameborder="0"></iframe></div></div><div class="youdao_tans_modal"></div><div id="drupal-modal" class="ui-front" style="display: none;"></div><div id="sliding-popup" role="alertdialog" aria-describedby="popup-text" style="height: auto; width: 100%; bottom: 0px;" class="sliding-popup-bottom"><div class="eu-cookie-compliance-banner eu-cookie-compliance-banner-info eu-cookie-compliance-banner--categories" aria-hidden="false">
	<div class="popup-content info eu-cookie-compliance-content">
		<div class="cookies__policy">
			<div class="container">
				<div id="eu-cookie-compliance-categories" class="cookies-wrp">
					<div class="cookies_clumn">
						<p><span>奥美如何使用 Cookies</span></p><p>奥美（Ogilvy.com）使用Cookies，是为了提供网站运行所必需的环境，同时帮助我们为您提供更好的用户体验。更多详情， <br><a href="/cn/cookies" target="_blank" tabindex="0">点击此处。</a></p>
					</div>

																										<div class="cookies_clumn">
									<span for="cookie-category-nc">必要性用途的 Cookies</span>
																			这是 Ogilvy.com 正常运行所必需的，且对我们网站使用其核心功能和增强功能至关重要。一旦禁用，Ogilvy.com 将无法正常运行或为您提供您所需要的服务。																		<div class="cookies_active-border" target="nc" id="nc-popup-id" style="display:none;">
										<input type="checkbox" class="cookies-checked" name="cookie-categories" id="cookie-category-nc" aria-labelledby="cookie-category-nc" value="nc" checked="" disabled="" tabindex="0">
										<span>&nbsp;</span>
									</div>
								</div>
																												<div class="cookies_clumn">
									<span for="cookie-category-fc">功能性用途的 Cookies</span>
																			允许 Ogilvy.com 记住您所做的选择，以便根据您的偏好提供更好的功能和个性化模式。																		<div class="cookies_ani-border is_active active" target="fc" id="fc-popup-id">
										<input type="checkbox" class="cookies-checked" name="cookie-categories" id="cookie-category-fc" aria-labelledby="cookie-category-fc" value="fc" tabindex="0">
										<span>&nbsp;</span>
										<p style="">On</p>
									</div>
								</div>
																												<div class="cookies_clumn">
									<span for="cookie-category-pc">性能 Cookies</span>
																			通过收集和报告有关您如何使用网站的信息，帮助提高 Ogilvy.com 的性能。																		<div class="cookies_ani-border is_active active" target="pc" id="pc-popup-id">
										<input type="checkbox" class="cookies-checked" name="cookie-categories" id="cookie-category-pc" aria-labelledby="cookie-category-pc" value="pc" tabindex="0">
										<span>&nbsp;</span>
										<p style="">On</p>
									</div>
								</div>
																							<div id="popup-buttons" class="eu-cookie-compliance-buttons eu-cookie-compliance-has-categories">
						<button type="button" class="cookies__close agree-button" aria-labelledby="popup-buttons" tabindex="0">
							<svg id="close-icon" viewBox="0 0 14.6 14.6" width="100%" height="100%">
								<path fill="none" stroke="currentColor" stroke-width="1" d="M.3.3l14 14m0-14l-14 14"></path>
							</svg>
						</button>
					</div>
				</div>
			</div>
		</div>
	</div>
</div></div></body></html>
