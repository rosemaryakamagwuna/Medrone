(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
var n;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function r(a,b){if(b)a:{for(var c=da,d=a.split("."),e=0;e<d.length-1;e++){var f=d[e];if(!(f in c))break a;c=c[f]}d=d[d.length-1];e=c[d];f=b(e);f!=e&&null!=f&&ba(c,d,{configurable:!0,writable:!0,value:f})}}
r("Symbol",function(a){function b(e){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c("jscomp_symbol_"+(e||"")+"_"+d++,e)}
function c(e,f){this.f=e;ba(this,"description",{configurable:!0,writable:!0,value:f})}
if(a)return a;c.prototype.toString=function(){return this.f};
var d=0;return b});
r("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ea(aa(this))}})}return a});
function ea(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function u(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function fa(a){for(var b,c=[];!(b=a.next()).done;)c.push(b.value);return c}
var ha="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},ia=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ha(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),ja;
if("function"==typeof Object.setPrototypeOf)ja=Object.setPrototypeOf;else{var ka;a:{var la={a:!0},ma={};try{ma.__proto__=la;ka=ma.a;break a}catch(a){}ka=!1}ja=ka?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var na=ja;
function v(a,b){a.prototype=ha(b.prototype);a.prototype.constructor=a;if(na)na(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.P=b.prototype}
function oa(){this.m=!1;this.i=null;this.g=void 0;this.f=1;this.j=this.l=0;this.u=this.h=null}
function pa(a){if(a.m)throw new TypeError("Generator is already running");a.m=!0}
oa.prototype.B=function(a){this.g=a};
function qa(a,b){a.h={Fa:b,ra:!0};a.f=a.l||a.j}
oa.prototype["return"]=function(a){this.h={"return":a};this.f=this.j};
function w(a,b,c){a.f=c;return{value:b}}
oa.prototype.I=function(a){this.f=a};
function ra(a){a.l=2;a.j=3}
function sa(a){a.l=0;a.h=null}
function ta(a){a.u=[a.h];a.l=0;a.j=0}
function ua(a){var b=a.u.splice(0)[0];(b=a.h=a.h||b)?b.ra?a.f=a.l||a.j:void 0!=b.I&&a.j<b.I?(a.f=b.I,a.h=null):a.f=a.j:a.f=0}
function va(a){this.f=new oa;this.g=a}
function wa(a,b){pa(a.f);var c=a.f.i;if(c)return xa(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.f["return"]);
a.f["return"](b);return ya(a)}
function xa(a,b,c,d){try{var e=b.call(a.f.i,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.f.m=!1,e;var f=e.value}catch(g){return a.f.i=null,qa(a.f,g),ya(a)}a.f.i=null;d.call(a.f,f);return ya(a)}
function ya(a){for(;a.f.f;)try{var b=a.g(a.f);if(b)return a.f.m=!1,{value:b.value,done:!1}}catch(c){a.f.g=void 0,qa(a.f,c)}a.f.m=!1;if(a.f.h){b=a.f.h;a.f.h=null;if(b.ra)throw b.Fa;return{value:b["return"],done:!0}}return{value:void 0,done:!0}}
function za(a){this.next=function(b){pa(a.f);a.f.i?b=xa(a,a.f.i.next,b,a.f.B):(a.f.B(b),b=ya(a));return b};
this["throw"]=function(b){pa(a.f);a.f.i?b=xa(a,a.f.i["throw"],b,a.f.B):(qa(a.f,b),b=ya(a));return b};
this["return"]=function(b){return wa(a,b)};
this[Symbol.iterator]=function(){return this}}
function x(a,b){var c=new za(new va(b));na&&a.prototype&&na(c,a.prototype);return c}
r("Reflect",function(a){return a?a:{}});
r("Reflect.construct",function(){return ia});
r("Reflect.setPrototypeOf",function(a){return a?a:na?function(b,c){try{return na(b,c),!0}catch(d){return!1}}:null});
function Aa(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
r("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Aa(this,b,"endsWith");b+="";void 0===c&&(c=d.length);for(var e=Math.max(0,Math.min(c|0,d.length)),f=b.length;0<f&&0<e;)if(d[--e]!=b[--f])return!1;return 0>=f}});
r("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Aa(this,b,"startsWith");b+="";for(var e=d.length,f=b.length,g=Math.max(0,Math.min(c|0,d.length)),h=0;h<f&&g<e;)if(d[g++]!=b[h++])return!1;return h>=f}});
r("Object.setPrototypeOf",function(a){return a||na});
function Ba(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var Ca="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)Ba(d,e)&&(a[e]=d[e])}return a};
r("Object.assign",function(a){return a||Ca});
r("Promise",function(a){function b(g){this.g=0;this.h=void 0;this.f=[];var h=this.i();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.f=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.g=function(g){if(null==this.f){this.f=[];var h=this;this.h(function(){h.j()})}this.f.push(g)};
var e=da.setTimeout;c.prototype.h=function(g){e(g,0)};
c.prototype.j=function(){for(;this.f&&this.f.length;){var g=this.f;this.f=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.i(l)}}}this.f=null};
c.prototype.i=function(g){this.h(function(){throw g;})};
b.prototype.i=function(){function g(l){return function(m){k||(k=!0,l.call(h,m))}}
var h=this,k=!1;return{resolve:g(this.C),reject:g(this.j)}};
b.prototype.C=function(g){if(g===this)this.j(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.F(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.u(g):this.l(g)}};
b.prototype.u=function(g){var h=void 0;try{h=g.then}catch(k){this.j(k);return}"function"==typeof h?this.G(h,g):this.l(g)};
b.prototype.j=function(g){this.m(2,g)};
b.prototype.l=function(g){this.m(1,g)};
b.prototype.m=function(g,h){if(0!=this.g)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.g);this.g=g;this.h=h;this.B()};
b.prototype.B=function(){if(null!=this.f){for(var g=0;g<this.f.length;++g)f.g(this.f[g]);this.f=null}};
var f=new c;b.prototype.F=function(g){var h=this.i();g.da(h.resolve,h.reject)};
b.prototype.G=function(g,h){var k=this.i();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(t,q){return"function"==typeof t?function(A){try{l(t(A))}catch(D){m(D)}}:q}
var l,m,p=new b(function(t,q){l=t;m=q});
this.da(k(g,l),k(h,m));return p};
b.prototype["catch"]=function(g){return this.then(void 0,g)};
b.prototype.da=function(g,h){function k(){switch(l.g){case 1:g(l.h);break;case 2:h(l.h);break;default:throw Error("Unexpected state: "+l.g);}}
var l=this;null==this.f?f.g(k):this.f.push(k)};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=u(g),m=l.next();!m.done;m=l.next())d(m.value).da(h,k)})};
b.all=function(g){var h=u(g),k=h.next();return k.done?d([]):new b(function(l,m){function p(A){return function(D){t[A]=D;q--;0==q&&l(t)}}
var t=[],q=0;do t.push(void 0),q++,d(k.value).da(p(t.length-1),m),k=h.next();while(!k.done)})};
return b});
function Da(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
r("Array.prototype.keys",function(a){return a?a:function(){return Da(this,function(b){return b})}});
r("Array.prototype.values",function(a){return a?a:function(){return Da(this,function(b,c){return c})}});
r("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
r("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length,f=c||0;for(0>f&&(f=Math.max(f+e,0));f<e;f++){var g=d[f];if(g===b||Object.is(g,b))return!0}return!1}});
r("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Aa(this,b,"includes").indexOf(b,c||0)}});
r("WeakMap",function(a){function b(k){this.f=(h+=Math.random()+1).toString();if(k){k=u(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!Ba(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(m){if(m instanceof c)return m;Object.isExtensible(m)&&e(m);return l(m)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),m=new a([[k,2],[l,3]]);if(2!=m.get(k)||3!=m.get(l))return!1;m["delete"](k);m.set(l,4);return!m.has(k)&&4==m.get(l)}catch(p){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!Ba(k,g))throw Error("WeakMap key fail: "+k);k[g][this.f]=l;return this};
b.prototype.get=function(k){return d(k)&&Ba(k,g)?k[g][this.f]:void 0};
b.prototype.has=function(k){return d(k)&&Ba(k,g)&&Ba(k[g],this.f)};
b.prototype["delete"]=function(k){return d(k)&&Ba(k,g)&&Ba(k[g],this.f)?delete k[g][this.f]:!1};
return b});
r("Array.prototype.entries",function(a){return a?a:function(){return Da(this,function(b,c){return[b,c]})}});
r("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h.f;return ea(function(){if(l){for(;l.head!=h.f;)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var m=h.g[l];if(m&&Ba(h.g,l))for(var p=0;p<m.length;p++){var t=m[p];if(k!==k&&t.key!==t.key||k===t.key)return{id:l,list:m,index:p,A:t}}return{id:l,list:m,index:-1,A:void 0}}
function e(h){this.g={};this.f=b();this.size=0;if(h){h=u(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(u([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),m=l.next();if(m.done||m.value[0]!=h||"s"!=m.value[1])return!1;m=l.next();return m.done||4!=m.value[0].x||"t"!=m.value[1]||!l.next().done?!1:!0}catch(p){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this.g[l.id]=[]);l.A?l.A.value=k:(l.A={next:this.f,previous:this.f.previous,head:this.f,key:h,value:k},l.list.push(l.A),this.f.previous.next=l.A,this.f.previous=l.A,this.size++);return this};
e.prototype["delete"]=function(h){h=d(this,h);return h.A&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.g[h.id],h.A.previous.next=h.A.next,h.A.next.previous=h.A.previous,h.A.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.g={};this.f=this.f.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).A};
e.prototype.get=function(h){return(h=d(this,h).A)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),m;!(m=l.next()).done;)m=m.value,h.call(k,m[1],m[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
r("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)Ba(b,d)&&c.push([d,b[d]]);return c}});
r("Set",function(a){function b(c){this.f=new Map;if(c){c=u(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.f.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(u([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.f.set(c,c);this.size=this.f.size;return this};
b.prototype["delete"]=function(c){c=this.f["delete"](c);this.size=this.f.size;return c};
b.prototype.clear=function(){this.f.clear();this.size=0};
b.prototype.has=function(c){return this.f.has(c)};
b.prototype.entries=function(){return this.f.entries()};
b.prototype.values=function(){return this.f.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.f.forEach(function(f){return c.call(d,f,f,e)})};
return b});
var y=this||self;function z(a,b,c){a=a.split(".");c=c||y;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
var Ea=/^[\w+/_-]+[=]{0,2}$/,Fa=null;function Ga(a){return(a=a.querySelector&&a.querySelector("script[nonce]"))&&(a=a.nonce||a.getAttribute("nonce"))&&Ea.test(a)?a:""}
function B(a,b){for(var c=a.split("."),d=b||y,e=0;e<c.length;e++)if(d=d[c[e]],null==d)return null;return d}
function Ha(){}
function Ia(a){a.la=void 0;a.getInstance=function(){return a.la?a.la:a.la=new a}}
function Ja(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Ka(a){var b=Ja(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function La(a){return"function"==Ja(a)}
function Ma(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Na(a){return Object.prototype.hasOwnProperty.call(a,Oa)&&a[Oa]||(a[Oa]=++Pa)}
var Oa="closure_uid_"+(1E9*Math.random()>>>0),Pa=0;function Qa(a,b,c){return a.call.apply(a.bind,arguments)}
function Ra(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function C(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?C=Qa:C=Ra;return C.apply(null,arguments)}
function Sa(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
var E=Date.now;function Ta(a,b){z(a,b,void 0)}
function F(a,b){function c(){}
c.prototype=b.prototype;a.P=b.prototype;a.prototype=new c;a.prototype.constructor=a}
function Ua(a){return a}
;function G(a){if(Error.captureStackTrace)Error.captureStackTrace(this,G);else{var b=Error().stack;b&&(this.stack=b)}a&&(this.message=String(a))}
F(G,Error);G.prototype.name="CustomError";function Va(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.h=!b&&/[?&]ae=1(&|$)/.test(a);this.i=!b&&/[?&]ae=2(&|$)/.test(a);if((this.f=/[?&]adurl=([^&]*)/.exec(a))&&this.f[1]){try{var c=decodeURIComponent(this.f[1])}catch(d){c=null}this.g=c}}
;function Xa(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var Ya=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},H=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},Za=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},$a=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},ab=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
H(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function bb(a,b){a:{var c=a.length;for(var d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){c=e;break a}c=-1}return 0>c?null:"string"===typeof a?a.charAt(c):a[c]}
function cb(a,b){var c=Ya(a,b);0<=c&&Array.prototype.splice.call(a,c,1)}
function db(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function eb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Ka(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function fb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function gb(a,b){var c=Ka(b),d=c?b:arguments;for(c=c?0:1;c<d.length;c++){if(null==a)return;a=a[d[c]]}return a}
function hb(a){var b=ib,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function jb(a){for(var b in a)return!1;return!0}
function kb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function lb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function mb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function nb(a){var b=Ja(a);if("object"==b||"array"==b){if(La(a.clone))return a.clone();b="array"==b?[]:{};for(var c in a)b[c]=nb(a[c]);return b}return a}
var ob="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function pb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<ob.length;f++)c=ob[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var qb;function rb(){if(void 0===qb){var a=null,b=y.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:Ua,createScript:Ua,createScriptURL:Ua})}catch(c){y.console&&y.console.error(c.message)}qb=a}else qb=a}return qb}
;function sb(a,b){this.f=b===tb?a:""}
sb.prototype.O=!0;sb.prototype.M=function(){return this.f.toString()};
sb.prototype.ka=!0;sb.prototype.ha=function(){return 1};
function ub(a){if(a instanceof sb&&a.constructor===sb)return a.f;Ja(a);return"type_error:TrustedResourceUrl"}
var tb={};var vb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function wb(a,b){if(b)a=a.replace(xb,"&amp;").replace(yb,"&lt;").replace(zb,"&gt;").replace(Ab,"&quot;").replace(Bb,"&#39;").replace(Cb,"&#0;");else{if(!Db.test(a))return a;-1!=a.indexOf("&")&&(a=a.replace(xb,"&amp;"));-1!=a.indexOf("<")&&(a=a.replace(yb,"&lt;"));-1!=a.indexOf(">")&&(a=a.replace(zb,"&gt;"));-1!=a.indexOf('"')&&(a=a.replace(Ab,"&quot;"));-1!=a.indexOf("'")&&(a=a.replace(Bb,"&#39;"));-1!=a.indexOf("\x00")&&(a=a.replace(Cb,"&#0;"))}return a}
var xb=/&/g,yb=/</g,zb=/>/g,Ab=/"/g,Bb=/'/g,Cb=/\x00/g,Db=/[\x00&<>"']/;function I(a,b){this.f=b===Eb?a:""}
I.prototype.O=!0;I.prototype.M=function(){return this.f.toString()};
I.prototype.ka=!0;I.prototype.ha=function(){return 1};
function Fb(a){if(a instanceof I&&a.constructor===I)return a.f;Ja(a);return"type_error:SafeUrl"}
var Gb=/^(?:audio\/(?:3gpp2|3gpp|aac|L16|midi|mp3|mp4|mpeg|oga|ogg|opus|x-m4a|x-matroska|x-wav|wav|webm)|font\/\w+|image\/(?:bmp|gif|jpeg|jpg|png|tiff|webp|x-icon)|text\/csv|video\/(?:mpeg|mp4|ogg|webm|quicktime|x-matroska))(?:;\w+=(?:\w+|"[\w;,= ]+"))*$/i,Hb=/^data:(.*);base64,[a-z0-9+\/]+=*$/i,Ib=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i;function Jb(a){if(a instanceof I)return a;a="object"==typeof a&&a.O?a.M():String(a);Ib.test(a)||(a="about:invalid#zClosurez");return new I(a,Eb)}
var Eb={},Kb=new I("about:invalid#zClosurez",Eb);var Lb;a:{var Mb=y.navigator;if(Mb){var Nb=Mb.userAgent;if(Nb){Lb=Nb;break a}}Lb=""}function J(a){return-1!=Lb.indexOf(a)}
;function Ob(a,b,c){this.f=c===Pb?a:"";this.g=b}
Ob.prototype.ka=!0;Ob.prototype.ha=function(){return this.g};
Ob.prototype.O=!0;Ob.prototype.M=function(){return this.f.toString()};
var Pb={};function Qb(a,b){var c=rb();c=c?c.createHTML(a):a;return new Ob(c,b,Pb)}
;function Rb(a,b){var c=b instanceof I?b:Jb(b);a.href=Fb(c)}
function Sb(a,b){a.src=ub(b);var c;(c=a.ownerDocument&&a.ownerDocument.defaultView)&&c!=y?c=Ga(c.document):(null===Fa&&(Fa=Ga(y.document)),c=Fa);c&&a.setAttribute("nonce",c)}
;function Tb(a){return a=wb(a,void 0)}
function Ub(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var Vb=/^(?:([^:/?#.]+):)?(?:\/\/(?:([^\\/?#]*)@)?([^\\/?#]*?)(?::([0-9]+))?(?=[\\/?#]|$))?([^?#]+)?(?:\?([^#]*))?(?:#([\s\S]*))?$/;function Xb(a){return a?decodeURI(a):a}
function K(a){return Xb(a.match(Vb)[3]||null)}
function Yb(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)Yb(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function Zb(a){var b=[],c;for(c in a)Yb(c,a[c],b);return b.join("&")}
function $b(a,b){var c=Zb(b);if(c){var d=a.indexOf("#");0>d&&(d=a.length);var e=a.indexOf("?");if(0>e||e>d){e=d;var f=""}else f=a.substring(e+1,d);d=[a.substr(0,e),f,a.substr(d)];e=d[1];d[1]=c?e?e+"&"+c:c:e;c=d[0]+(d[1]?"?"+d[1]:"")+d[2]}else c=a;return c}
var ac=/#|$/;function L(a,b){var c=void 0;return new (c||(c=Promise))(function(d,e){function f(k){try{h(b.next(k))}catch(l){e(l)}}
function g(k){try{h(b["throw"](k))}catch(l){e(l)}}
function h(k){k.done?d(k.value):(new c(function(l){l(k.value)})).then(f,g)}
h((b=b.apply(a,void 0)).next())})}
;var bc=J("Opera"),cc=J("Trident")||J("MSIE"),dc=J("Edge"),ec=J("Gecko")&&!(-1!=Lb.toLowerCase().indexOf("webkit")&&!J("Edge"))&&!(J("Trident")||J("MSIE"))&&!J("Edge"),fc=-1!=Lb.toLowerCase().indexOf("webkit")&&!J("Edge");function gc(){var a=y.document;return a?a.documentMode:void 0}
var hc;a:{var ic="",jc=function(){var a=Lb;if(ec)return/rv:([^\);]+)(\)|;)/.exec(a);if(dc)return/Edge\/([\d\.]+)/.exec(a);if(cc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(fc)return/WebKit\/(\S+)/.exec(a);if(bc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
jc&&(ic=jc?jc[1]:"");if(cc){var kc=gc();if(null!=kc&&kc>parseFloat(ic)){hc=String(kc);break a}}hc=ic}var lc=hc,mc;if(y.document&&cc){var nc=gc();mc=nc?nc:parseInt(lc,10)||void 0}else mc=void 0;var oc=mc;var pc=J("iPhone")&&!J("iPod")&&!J("iPad")||J("iPod"),qc=J("iPad");var rc={},sc=null;var M=window;function tc(a){var b=B("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||y.$googDebugFname||b}catch(g){e="Not available",c=!0}b=uc(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,vc[c])c=vc[c];else{c=String(c);if(!vc[c]){var f=/function\s+([^\(]+)/m.exec(c);vc[c]=f?f[1]:"[Anonymous]"}c=vc[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return a}
function uc(a,b){b||(b={});b[wc(a)]=!0;var c=a.stack||"",d=a.wb;d&&!b[wc(d)]&&(c+="\nCaused by: ",d.stack&&0==d.stack.indexOf(d.toString())||(c+="string"===typeof d?d:d.message+"\n"),c+=uc(d,b));return c}
function wc(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var vc={};function xc(a){this.f=a||{cookie:""}}
n=xc.prototype;n.isEnabled=function(){return navigator.cookieEnabled};
n.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Cb;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.sa}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(E()+1E3*h)).toUTCString();this.f.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+e:
"")};
n.get=function(a,b){for(var c=a+"=",d=(this.f.cookie||"").split(";"),e=0,f;e<d.length;e++){f=vb(d[e]);if(0==f.lastIndexOf(c,0))return f.substr(c.length);if(f==a)return""}return b};
n.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{sa:0,path:b,domain:c});return d};
n.isEmpty=function(){return!this.f.cookie};
n.clear=function(){for(var a=(this.f.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=vb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var yc=new xc("undefined"==typeof document?null:document);var zc=!cc||9<=Number(oc);function Ac(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
n=Ac.prototype;n.clone=function(){return new Ac(this.x,this.y)};
n.equals=function(a){return a instanceof Ac&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
n.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
n.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
n.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};function Bc(a,b){this.width=a;this.height=b}
n=Bc.prototype;n.clone=function(){return new Bc(this.width,this.height)};
n.aspectRatio=function(){return this.width/this.height};
n.isEmpty=function(){return!(this.width*this.height)};
n.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
n.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
n.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};function Cc(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function Dc(a,b){fb(b,function(c,d){c&&"object"==typeof c&&c.O&&(c=c.M());"style"==d?a.style.cssText=c:"class"==d?a.className=c:"for"==d?a.htmlFor=c:Ec.hasOwnProperty(d)?a.setAttribute(Ec[d],c):0==d.lastIndexOf("aria-",0)||0==d.lastIndexOf("data-",0)?a.setAttribute(d,c):a[d]=c})}
var Ec={cellpadding:"cellPadding",cellspacing:"cellSpacing",colspan:"colSpan",frameborder:"frameBorder",height:"height",maxlength:"maxLength",nonce:"nonce",role:"role",rowspan:"rowSpan",type:"type",usemap:"useMap",valign:"vAlign",width:"width"};
function Fc(a,b,c){var d=arguments,e=document,f=String(d[0]),g=d[1];if(!zc&&g&&(g.name||g.type)){f=["<",f];g.name&&f.push(' name="',Tb(g.name),'"');if(g.type){f.push(' type="',Tb(g.type),'"');var h={};pb(h,g);delete h.type;g=h}f.push(">");f=f.join("")}f=Gc(e,f);g&&("string"===typeof g?f.className=g:Array.isArray(g)?f.className=g.join(" "):Dc(f,g));2<d.length&&Hc(e,f,d);return f}
function Hc(a,b,c){function d(g){g&&b.appendChild("string"===typeof g?a.createTextNode(g):g)}
for(var e=2;e<c.length;e++){var f=c[e];!Ka(f)||Ma(f)&&0<f.nodeType?d(f):H(Ic(f)?db(f):f,d)}}
function Gc(a,b){b=String(b);"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function Ic(a){if(a&&"number"==typeof a.length){if(Ma(a))return"function"==typeof a.item||"string"==typeof a.item;if(La(a))return"function"==typeof a.item}return!1}
function Jc(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function Kc(a){Lc();var b=rb();a=b?b.createScriptURL(a):a;return new sb(a,tb)}
var Lc=Ha;function Mc(a){var b=Nc;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a.call(void 0,b[c],c,b)}
function Oc(){var a=[];Mc(function(b){a.push(b)});
return a}
var Nc={jb:"allow-forms",kb:"allow-modals",lb:"allow-orientation-lock",mb:"allow-pointer-lock",nb:"allow-popups",ob:"allow-popups-to-escape-sandbox",pb:"allow-presentation",qb:"allow-same-origin",rb:"allow-scripts",sb:"allow-top-navigation",tb:"allow-top-navigation-by-user-activation"},Pc=Xa(function(){return Oc()});
function Qc(){var a=Gc(document,"IFRAME"),b={};H(Pc(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
;function N(){this.g=this.g;this.B=this.B}
N.prototype.g=!1;N.prototype.dispose=function(){this.g||(this.g=!0,this.o())};
function Rc(a,b){a.g?b():(a.B||(a.B=[]),a.B.push(b))}
N.prototype.o=function(){if(this.B)for(;this.B.length;)this.B.shift()()};
function Sc(a){a&&"function"==typeof a.dispose&&a.dispose()}
function Tc(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Ka(d)?Tc.apply(null,d):Sc(d)}}
;var Uc={};function Vc(){}
function Wc(a,b){if(b!==Uc)throw Error("Bad secret");this.f=a}
v(Wc,Vc);Wc.prototype.toString=function(){return this.f};new Wc("about:blank",Uc);new Wc("about:invalid#zTSz",Uc);function Xc(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var Yc=(new Date).getTime();function Zc(a){if(!a)return"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));a=a.substring(0,a.indexOf("://"));if("http"!==a&&"https"!==a&&"chrome-extension"!==a&&"moz-extension"!==a&&"file"!==a&&"android-app"!==a&&"chrome-search"!==a&&"chrome-untrusted"!==a&&"chrome"!==a&&"app"!==a&&"devtools"!==a)throw Error("Invalid URI scheme in origin: "+
a);c="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===a&&"80"!==e||"https"===a&&"443"!==e)c=":"+e}return a+"://"+b+c}
;function $c(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;m=l=0}
function b(p){for(var t=g,q=0;64>q;q+=4)t[q/4]=p[q]<<24|p[q+1]<<16|p[q+2]<<8|p[q+3];for(q=16;80>q;q++)p=t[q-3]^t[q-8]^t[q-14]^t[q-16],t[q]=(p<<1|p>>>31)&4294967295;p=e[0];var A=e[1],D=e[2],V=e[3],id=e[4];for(q=0;80>q;q++){if(40>q)if(20>q){var Wa=V^A&(D^V);var Wb=1518500249}else Wa=A^D^V,Wb=1859775393;else 60>q?(Wa=A&D|V&(A|D),Wb=2400959708):(Wa=A^D^V,Wb=3395469782);Wa=((p<<5|p>>>27)&4294967295)+Wa+id+Wb+t[q]&4294967295;id=V;V=D;D=(A<<30|A>>>2)&4294967295;A=p;p=Wa}e[0]=e[0]+p&4294967295;e[1]=e[1]+
A&4294967295;e[2]=e[2]+D&4294967295;e[3]=e[3]+V&4294967295;e[4]=e[4]+id&4294967295}
function c(p,t){if("string"===typeof p){p=unescape(encodeURIComponent(p));for(var q=[],A=0,D=p.length;A<D;++A)q.push(p.charCodeAt(A));p=q}t||(t=p.length);q=0;if(0==l)for(;q+64<t;)b(p.slice(q,q+64)),q+=64,m+=64;for(;q<t;)if(f[l++]=p[q++],m++,64==l)for(l=0,b(f);q+64<t;)b(p.slice(q,q+64)),q+=64,m+=64}
function d(){var p=[],t=8*m;56>l?c(h,56-l):c(h,64-(l-56));for(var q=63;56<=q;q--)f[q]=t&255,t>>>=8;b(f);for(q=t=0;5>q;q++)for(var A=24;0<=A;A-=8)p[t++]=e[q]>>A&255;return p}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,m;a();return{reset:a,update:c,digest:d,Ea:function(){for(var p=d(),t="",q=0;q<p.length;q++)t+="0123456789ABCDEF".charAt(Math.floor(p[q]/16))+"0123456789ABCDEF".charAt(p[q]%16);return t}}}
;function ad(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],H(d,function(h){e.push(h)}),bd(e.join(" "));
var f=[],g=[];H(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];H(d,function(h){e.push(h)});
a=bd(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function bd(a){var b=$c();b.update(a);return b.Ea().toLowerCase()}
;function cd(a){var b=Zc(String(y.location.href)),c;(c=y.__SAPISID||y.__APISID||y.__OVERRIDE_SID)?c=!0:(c=new xc(document),c=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID"),c=!!c);if(c&&(c=(b=0==b.indexOf("https:")||0==b.indexOf("chrome-extension:")||0==b.indexOf("moz-extension:"))?y.__SAPISID:y.__APISID,c||(c=new xc(document),c=c.get(b?"SAPISID":"APISID")||c.get("__Secure-3PAPISID")),c)){b=b?"SAPISIDHASH":"APISIDHASH";var d=String(y.location.href);return d&&c&&b?[b,ad(Zc(d),
c,a||null)].join(" "):null}return null}
;function dd(){this.g=[];this.f=-1}
dd.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&0===a%1&&this.g[a]!=b&&(this.g[a]=b,this.f=-1)};
dd.prototype.get=function(a){return!!this.g[a]};
function ed(a){-1==a.f&&(a.f=ab(a.g,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.f}
;function fd(a,b){this.h=a;this.i=b;this.g=0;this.f=null}
fd.prototype.get=function(){if(0<this.g){this.g--;var a=this.f;this.f=a.next;a.next=null}else a=this.h();return a};
function gd(a,b){a.i(b);100>a.g&&(a.g++,b.next=a.f,a.f=b)}
;function hd(a){y.setTimeout(function(){throw a;},0)}
var jd;
function kd(){var a=y.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!J("Presto")&&(a=function(){var e=Gc(document,"IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=C(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!J("Trident")&&!J("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.qa;c.qa=null;e()}};
return function(e){d.next={qa:e};d=d.next;b.port2.postMessage(0)}}return function(e){y.setTimeout(e,0)}}
;function ld(){this.g=this.f=null}
var nd=new fd(function(){return new md},function(a){a.reset()});
ld.prototype.add=function(a,b){var c=nd.get();c.set(a,b);this.g?this.g.next=c:this.f=c;this.g=c};
ld.prototype.remove=function(){var a=null;this.f&&(a=this.f,this.f=this.f.next,this.f||(this.g=null),a.next=null);return a};
function md(){this.next=this.scope=this.f=null}
md.prototype.set=function(a,b){this.f=a;this.scope=b;this.next=null};
md.prototype.reset=function(){this.next=this.scope=this.f=null};function od(a,b){pd||qd();rd||(pd(),rd=!0);sd.add(a,b)}
var pd;function qd(){if(y.Promise&&y.Promise.resolve){var a=y.Promise.resolve(void 0);pd=function(){a.then(td)}}else pd=function(){var b=td;
!La(y.setImmediate)||y.Window&&y.Window.prototype&&!J("Edge")&&y.Window.prototype.setImmediate==y.setImmediate?(jd||(jd=kd()),jd(b)):y.setImmediate(b)}}
var rd=!1,sd=new ld;function td(){for(var a;a=sd.remove();){try{a.f.call(a.scope)}catch(b){hd(b)}gd(nd,a)}rd=!1}
;function ud(){this.g=-1}
;function vd(){this.g=64;this.f=[];this.l=[];this.m=[];this.i=[];this.i[0]=128;for(var a=1;a<this.g;++a)this.i[a]=0;this.j=this.h=0;this.reset()}
F(vd,ud);vd.prototype.reset=function(){this.f[0]=1732584193;this.f[1]=4023233417;this.f[2]=2562383102;this.f[3]=271733878;this.f[4]=3285377520;this.j=this.h=0};
function wd(a,b,c){c||(c=0);var d=a.m;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.f[0];c=a.f[1];var g=a.f[2],h=a.f[3],k=a.f[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.f[0]=a.f[0]+b&4294967295;a.f[1]=a.f[1]+c&4294967295;a.f[2]=a.f[2]+g&4294967295;a.f[3]=a.f[3]+h&4294967295;a.f[4]=a.f[4]+k&4294967295}
vd.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.g,d=0,e=this.l,f=this.h;d<b;){if(0==f)for(;d<=c;)wd(this,a,d),d+=this.g;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.g){wd(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.g){wd(this,e);f=0;break}}this.h=f;this.j+=b}};
vd.prototype.digest=function(){var a=[],b=8*this.j;56>this.h?this.update(this.i,56-this.h):this.update(this.i,this.g-(this.h-56));for(var c=this.g-1;56<=c;c--)this.l[c]=b&255,b/=256;wd(this,this.l);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.f[c]>>d&255,++b;return a};var xd="StopIteration"in y?y.StopIteration:{message:"StopIteration",stack:""};function yd(){}
yd.prototype.next=function(){throw xd;};
yd.prototype.H=function(){return this};
function zd(a){if(a instanceof yd)return a;if("function"==typeof a.H)return a.H(!1);if(Ka(a)){var b=0,c=new yd;c.next=function(){for(;;){if(b>=a.length)throw xd;if(b in a)return a[b++];b++}};
return c}throw Error("Not implemented");}
function Ad(a,b){if(Ka(a))try{H(a,b,void 0)}catch(c){if(c!==xd)throw c;}else{a=zd(a);try{for(;;)b.call(void 0,a.next(),void 0,a)}catch(c){if(c!==xd)throw c;}}}
function Bd(a){if(Ka(a))return db(a);a=zd(a);var b=[];Ad(a,function(c){b.push(c)});
return b}
;function Cd(a,b){this.h={};this.f=[];this.J=this.g=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof Cd)for(c=Dd(a),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
function Dd(a){Ed(a);return a.f.concat()}
n=Cd.prototype;n.equals=function(a,b){if(this===a)return!0;if(this.g!=a.g)return!1;var c=b||Fd;Ed(this);for(var d,e=0;d=this.f[e];e++)if(!c(this.get(d),a.get(d)))return!1;return!0};
function Fd(a,b){return a===b}
n.isEmpty=function(){return 0==this.g};
n.clear=function(){this.h={};this.J=this.g=this.f.length=0};
n.remove=function(a){return Object.prototype.hasOwnProperty.call(this.h,a)?(delete this.h[a],this.g--,this.J++,this.f.length>2*this.g&&Ed(this),!0):!1};
function Ed(a){if(a.g!=a.f.length){for(var b=0,c=0;b<a.f.length;){var d=a.f[b];Object.prototype.hasOwnProperty.call(a.h,d)&&(a.f[c++]=d);b++}a.f.length=c}if(a.g!=a.f.length){var e={};for(c=b=0;b<a.f.length;)d=a.f[b],Object.prototype.hasOwnProperty.call(e,d)||(a.f[c++]=d,e[d]=1),b++;a.f.length=c}}
n.get=function(a,b){return Object.prototype.hasOwnProperty.call(this.h,a)?this.h[a]:b};
n.set=function(a,b){Object.prototype.hasOwnProperty.call(this.h,a)||(this.g++,this.f.push(a),this.J++);this.h[a]=b};
n.forEach=function(a,b){for(var c=Dd(this),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
n.clone=function(){return new Cd(this)};
n.H=function(a){Ed(this);var b=0,c=this.J,d=this,e=new yd;e.next=function(){if(c!=d.J)throw Error("The map has changed since the iterator was created");if(b>=d.f.length)throw xd;var f=d.f[b++];return a?f:d.h[f]};
return e};function Gd(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Hd(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Id(a,b){if(a.classList)var c=a.classList.contains(b);else c=a.classList?a.classList:Gd(a).match(/\S+/g)||[],c=0<=Ya(c,b);return c}
function Jd(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Id(a,"inverted-hdpi")&&Hd(a,Za(a.classList?a.classList:Gd(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;function Kd(a){var b=[];Ld(new Md,a,b);return b.join("")}
function Md(){}
function Ld(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Ld(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),Nd(d,c),c.push(":"),Ld(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Nd(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Od={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\x0B":"\\u000b"},Pd=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Nd(a,b){b.push('"',a.replace(Pd,function(c){var d=Od[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).substr(1),Od[c]=d);return d}),'"')}
;function Qd(a){if(!a)return!1;try{return!!a.$goog_Thenable}catch(b){return!1}}
;function O(a){this.f=0;this.m=void 0;this.i=this.g=this.h=null;this.j=this.l=!1;if(a!=Ha)try{var b=this;a.call(void 0,function(c){Rd(b,2,c)},function(c){Rd(b,3,c)})}catch(c){Rd(this,3,c)}}
function Sd(){this.next=this.context=this.onRejected=this.g=this.f=null;this.h=!1}
Sd.prototype.reset=function(){this.context=this.onRejected=this.g=this.f=null;this.h=!1};
var Td=new fd(function(){return new Sd},function(a){a.reset()});
function Ud(a,b,c){var d=Td.get();d.g=a;d.onRejected=b;d.context=c;return d}
function Vd(a){if(a instanceof O)return a;var b=new O(Ha);Rd(b,2,a);return b}
function Wd(a){return new O(function(b,c){c(a)})}
O.prototype.then=function(a,b,c){return Xd(this,La(a)?a:null,La(b)?b:null,c)};
O.prototype.$goog_Thenable=!0;function Yd(a,b){return Xd(a,null,b,void 0)}
O.prototype.cancel=function(a){if(0==this.f){var b=new Zd(a);od(function(){$d(this,b)},this)}};
function $d(a,b){if(0==a.f)if(a.h){var c=a.h;if(c.g){for(var d=0,e=null,f=null,g=c.g;g&&(g.h||(d++,g.f==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.f&&1==d?$d(c,b):(f?(d=f,d.next==c.i&&(c.i=d),d.next=d.next.next):ae(c),be(c,e,3,b)))}a.h=null}else Rd(a,3,b)}
function ce(a,b){a.g||2!=a.f&&3!=a.f||de(a);a.i?a.i.next=b:a.g=b;a.i=b}
function Xd(a,b,c,d){var e=Ud(null,null,null);e.f=new O(function(f,g){e.g=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof Zd?g(h):f(k)}catch(l){g(l)}}:g});
e.f.h=a;ce(a,e);return e.f}
O.prototype.u=function(a){this.f=0;Rd(this,2,a)};
O.prototype.C=function(a){this.f=0;Rd(this,3,a)};
function Rd(a,b,c){if(0==a.f){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.f=1;a:{var d=c,e=a.u,f=a.C;if(d instanceof O){ce(d,Ud(e||Ha,f||null,a));var g=!0}else if(Qd(d))d.then(e,f,a),g=!0;else{if(Ma(d))try{var h=d.then;if(La(h)){ee(d,h,e,f,a);g=!0;break a}}catch(k){f.call(a,k);g=!0;break a}g=!1}}g||(a.m=c,a.f=b,a.h=null,de(a),3!=b||c instanceof Zd||fe(a,c))}}
function ee(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function de(a){a.l||(a.l=!0,od(a.B,a))}
function ae(a){var b=null;a.g&&(b=a.g,a.g=b.next,b.next=null);a.g||(a.i=null);return b}
O.prototype.B=function(){for(var a;a=ae(this);)be(this,a,this.f,this.m);this.l=!1};
function be(a,b,c,d){if(3==c&&b.onRejected&&!b.h)for(;a&&a.j;a=a.h)a.j=!1;if(b.f)b.f.h=null,ge(b,c,d);else try{b.h?b.g.call(b.context):ge(b,c,d)}catch(e){he.call(null,e)}gd(Td,b)}
function ge(a,b,c){2==b?a.g.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function fe(a,b){a.j=!0;od(function(){a.j&&he.call(null,b)})}
var he=hd;function Zd(a){G.call(this,a)}
F(Zd,G);Zd.prototype.name="cancel";function P(a){N.call(this);this.l=1;this.i=[];this.j=0;this.f=[];this.h={};this.m=!!a}
F(P,N);n=P.prototype;n.subscribe=function(a,b,c){var d=this.h[a];d||(d=this.h[a]=[]);var e=this.l;this.f[e]=a;this.f[e+1]=b;this.f[e+2]=c;this.l=e+3;d.push(e);return e};
function ie(a,b,c,d){if(b=a.h[b]){var e=a.f;(b=bb(b,function(f){return e[f+1]==c&&e[f+2]==d}))&&a.R(b)}}
n.R=function(a){var b=this.f[a];if(b){var c=this.h[b];0!=this.j?(this.i.push(a),this.f[a+1]=Ha):(c&&cb(c,a),delete this.f[a],delete this.f[a+1],delete this.f[a+2])}return!!b};
n.N=function(a,b){var c=this.h[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.m)for(e=0;e<c.length;e++){var g=c[e];je(this.f[g+1],this.f[g+2],d)}else{this.j++;try{for(e=0,f=c.length;e<f;e++)g=c[e],this.f[g+1].apply(this.f[g+2],d)}finally{if(this.j--,0<this.i.length&&0==this.j)for(;c=this.i.pop();)this.R(c)}}return 0!=e}return!1};
function je(a,b,c){od(function(){a.apply(b,c)})}
n.clear=function(a){if(a){var b=this.h[a];b&&(H(b,this.R,this),delete this.h[a])}else this.f.length=0,this.h={}};
n.o=function(){P.P.o.call(this);this.clear();this.i.length=0};function ke(a){this.f=a}
ke.prototype.set=function(a,b){void 0===b?this.f.remove(a):this.f.set(a,Kd(b))};
ke.prototype.get=function(a){try{var b=this.f.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
ke.prototype.remove=function(a){this.f.remove(a)};function le(a){this.f=a}
F(le,ke);function me(a){this.data=a}
function ne(a){return void 0===a||a instanceof me?a:new me(a)}
le.prototype.set=function(a,b){le.P.set.call(this,a,ne(b))};
le.prototype.g=function(a){a=le.P.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
le.prototype.get=function(a){if(a=this.g(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function oe(a){this.f=a}
F(oe,le);oe.prototype.set=function(a,b,c){if(b=ne(b)){if(c){if(c<E()){oe.prototype.remove.call(this,a);return}b.expiration=c}b.creation=E()}oe.P.set.call(this,a,b)};
oe.prototype.g=function(a){var b=oe.P.g.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<E()||c&&c>E())oe.prototype.remove.call(this,a);else return b}};function pe(){}
;function qe(){}
F(qe,pe);qe.prototype.clear=function(){var a=Bd(this.H(!0)),b=this;H(a,function(c){b.remove(c)})};function re(a){this.f=a}
F(re,qe);n=re.prototype;n.isAvailable=function(){if(!this.f)return!1;try{return this.f.setItem("__sak","1"),this.f.removeItem("__sak"),!0}catch(a){return!1}};
n.set=function(a,b){try{this.f.setItem(a,b)}catch(c){if(0==this.f.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
n.get=function(a){a=this.f.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
n.remove=function(a){this.f.removeItem(a)};
n.H=function(a){var b=0,c=this.f,d=new yd;d.next=function(){if(b>=c.length)throw xd;var e=c.key(b++);if(a)return e;e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
n.clear=function(){this.f.clear()};
n.key=function(a){return this.f.key(a)};function se(){var a=null;try{a=window.localStorage||null}catch(b){}this.f=a}
F(se,re);function te(a,b){this.g=a;this.f=null;if(cc&&!(9<=Number(oc))){ue||(ue=new Cd);this.f=ue.get(a);this.f||(b?this.f=document.getElementById(b):(this.f=document.createElement("userdata"),this.f.addBehavior("#default#userData"),document.body.appendChild(this.f)),ue.set(a,this.f));try{this.f.load(this.g)}catch(c){this.f=null}}}
F(te,qe);var ve={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},ue=null;function we(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return ve[b]})}
n=te.prototype;n.isAvailable=function(){return!!this.f};
n.set=function(a,b){this.f.setAttribute(we(a),b);xe(this)};
n.get=function(a){a=this.f.getAttribute(we(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
n.remove=function(a){this.f.removeAttribute(we(a));xe(this)};
n.H=function(a){var b=0,c=this.f.XMLDocument.documentElement.attributes,d=new yd;d.next=function(){if(b>=c.length)throw xd;var e=c[b++];if(a)return decodeURIComponent(e.nodeName.replace(/\./g,"%")).substr(1);e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
n.clear=function(){for(var a=this.f.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);xe(this)};
function xe(a){try{a.f.save(a.g)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function ye(a,b){this.g=a;this.f=b+"::"}
F(ye,qe);ye.prototype.set=function(a,b){this.g.set(this.f+a,b)};
ye.prototype.get=function(a){return this.g.get(this.f+a)};
ye.prototype.remove=function(a){this.g.remove(this.f+a)};
ye.prototype.H=function(a){var b=this.g.H(!0),c=this,d=new yd;d.next=function(){for(var e=b.next();e.substr(0,c.f.length)!=c.f;)e=b.next();return a?e.substr(c.f.length):c.g.get(e)};
return d};function ze(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var Ae=window.yt&&window.yt.config_||window.ytcfg&&window.ytcfg.data_||{};z("yt.config_",Ae,void 0);function Q(a){ze(Ae,arguments)}
function R(a,b){return a in Ae?Ae[a]:b}
function Be(){return R("PLAYER_CONFIG",{})}
;var Ce=[];function De(a){Ce.forEach(function(b){return b(a)})}
function Ee(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){S(b),De(b)}}:a}
function S(a){var b=B("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0):(b=R("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0]),Q("ERRORS",b))}
function Fe(a){var b=B("yt.logging.errors.log");b?b(a,"WARNING",void 0,void 0,void 0):(b=R("ERRORS",[]),b.push([a,"WARNING",void 0,void 0,void 0]),Q("ERRORS",b))}
;var Ge=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};z("yt.msgs_",Ge,void 0);function He(a){ze(Ge,arguments)}
;function Ie(a,b,c,d){yc.set(""+a,b,{sa:c,path:"/",domain:void 0===d?"youtube.com":d,secure:!1})}
;function T(a){a=Je(a);return"string"===typeof a&&"false"===a?!1:!!a}
function Ke(a,b){var c=Je(a);return void 0===c&&void 0!==b?b:Number(c||0)}
function Je(a){var b=R("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:R("EXPERIMENT_FLAGS",{})[a]}
;function Le(a){a&&(a.dataset?a.dataset[Me("loaded")]="true":a.setAttribute("data-loaded","true"))}
function Ne(a,b){return a?a.dataset?a.dataset[Me(b)]:a.getAttribute("data-"+b):null}
var Oe={};function Me(a){return Oe[a]||(Oe[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;function U(a,b){"function"===typeof a&&(a=Ee(a));return window.setTimeout(a,b)}
function Pe(a){window.clearTimeout(a)}
;var Qe=y.ytPubsubPubsubInstance||new P,Re=y.ytPubsubPubsubSubscribedKeys||{},Se=y.ytPubsubPubsubTopicToKeys||{},Te=y.ytPubsubPubsubIsSynchronous||{};function Ue(a,b){var c=Ve();if(c){var d=c.subscribe(a,function(){var e=arguments;var f=function(){Re[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{Te[a]?f():U(f,0)}catch(g){S(g)}},void 0);
Re[d]=!0;Se[a]||(Se[a]=[]);Se[a].push(d);return d}return 0}
function We(a){var b=Ve();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),H(a,function(c){b.unsubscribeByKey(c);delete Re[c]}))}
function Xe(a,b){var c=Ve();c&&c.publish.apply(c,arguments)}
function Ye(a){var b=Ve();if(b)if(b.clear(a),a)Ze(a);else for(var c in Se)Ze(c)}
function Ve(){return y.ytPubsubPubsubInstance}
function Ze(a){Se[a]&&(a=Se[a],H(a,function(b){Re[b]&&delete Re[b]}),a.length=0)}
P.prototype.subscribe=P.prototype.subscribe;P.prototype.unsubscribeByKey=P.prototype.R;P.prototype.publish=P.prototype.N;P.prototype.clear=P.prototype.clear;z("ytPubsubPubsubInstance",Qe,void 0);z("ytPubsubPubsubTopicToKeys",Se,void 0);z("ytPubsubPubsubIsSynchronous",Te,void 0);z("ytPubsubPubsubSubscribedKeys",Re,void 0);var $e=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,af=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function bf(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace($e,""),c=c.replace(af,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else cf(a,b,c)}
function cf(a,b,c){c=void 0===c?null:c;var d=df(a),e=document.getElementById(d),f=e&&Ne(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=Ue(d,b),b=""+Na(b),ef[b]=f),g||(e=ff(a,d,function(){Ne(e,"loaded")||(Le(e),Xe(d),U(Sa(Ye,d),0))},c)))}
function ff(a,b,c,d){d=void 0===d?null:d;var e=Gc(document,"SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Sb(e,Kc(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function gf(a){a=df(a);var b=document.getElementById(a);b&&(Ye(a),b.parentNode.removeChild(b))}
function hf(a,b){if(a&&b){var c=""+Na(b);(c=ef[c])&&We(c)}}
function df(a){var b=document.createElement("a");Rb(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+Ub(a)}
var ef={};function jf(){}
function kf(a,b){return lf(a,0,b)}
function mf(a,b){return lf(a,1,b)}
;function nf(){}
v(nf,jf);function lf(a,b,c){isNaN(c)&&(c=void 0);var d=B("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):U(a,c||0)}
function of(a){if(!isNaN(a)){var b=B("yt.scheduler.instance.cancelJob");b?b(a):Pe(a)}}
nf.prototype.start=function(){var a=B("yt.scheduler.instance.start");a&&a()};
nf.prototype.pause=function(){var a=B("yt.scheduler.instance.pause");a&&a()};
Ia(nf);nf.getInstance();var pf=[],qf=!1;function rf(){if(!T("disable_ad_status_on_html5_clients")&&(!T("condition_ad_status_fetch_on_consent_cookie_html5_clients")||yc.get("CONSENT","").startsWith("YES+"))&&"1"!=gb(Be(),"args","privembed")){var a=function(){qf=!0;"google_ad_status"in window?Q("DCLKSTAT",1):Q("DCLKSTAT",2)};
bf("//static.doubleclick.net/instream/ad_status.js",a);pf.push(mf(function(){qf||"google_ad_status"in window||(hf("//static.doubleclick.net/instream/ad_status.js",a),qf=!0,Q("DCLKSTAT",3))},5E3))}}
function sf(){return parseInt(R("DCLKSTAT",0),10)}
;var tf=0;z("ytDomDomGetNextId",B("ytDomDomGetNextId")||function(){return++tf},void 0);var uf={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function vf(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.clientY=this.clientX=0;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in uf||(this[b]=a[b]);var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==
this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.f=a.pageX;this.g=a.pageY}}catch(e){}}
function wf(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.f=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.g=a.clientY+b}}
vf.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
vf.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
vf.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var ib=y.ytEventsEventsListeners||{};z("ytEventsEventsListeners",ib,void 0);var xf=y.ytEventsEventsCounter||{count:0};z("ytEventsEventsCounter",xf,void 0);
function yf(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return hb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Ma(e[4])&&Ma(d)&&lb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var zf=Xa(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function Af(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=yf(a,b,c,d);if(e)return e;e=++xf.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new vf(h);if(!Jc(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new vf(h);
h.currentTarget=a;return c.call(a,h)};
g=Ee(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),zf()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);ib[e]=[a,b,c,g,d];return e}
function Bf(a){a&&("string"==typeof a&&(a=[a]),H(a,function(b){if(b in ib){var c=ib[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?zf()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete ib[b]}}))}
;var Cf=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function Df(a){this.u=a;this.f=null;this.j=0;this.m=null;this.l=0;this.h=[];for(a=0;4>a;a++)this.h.push(0);this.i=0;this.F=Af(window,"mousemove",C(this.G,this));a=C(this.C,this);"function"===typeof a&&(a=Ee(a));this.L=window.setInterval(a,25)}
F(Df,N);Df.prototype.G=function(a){void 0===a.f&&wf(a);var b=a.f;void 0===a.g&&wf(a);this.f=new Ac(b,a.g)};
Df.prototype.C=function(){if(this.f){var a=Cf();if(0!=this.j){var b=this.m,c=this.f,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.j);this.h[this.i]=.5<Math.abs((d-this.l)/this.l)?1:0;for(c=b=0;4>c;c++)b+=this.h[c]||0;3<=b&&this.u();this.l=d}this.j=a;this.m=this.f;this.i=(this.i+1)%4}};
Df.prototype.o=function(){window.clearInterval(this.L);Bf(this.F)};var Ef={};
function Ff(a){var b=void 0===a?{}:a;a=void 0===b.Ka?!0:b.Ka;b=void 0===b.Wa?!1:b.Wa;if(null==B("_lact",window)){var c=parseInt(R("LACT"),10);c=isFinite(c)?E()-Math.max(c,0):-1;z("_lact",c,window);z("_fact",c,window);-1==c&&Gf();Af(document,"keydown",Gf);Af(document,"keyup",Gf);Af(document,"mousedown",Gf);Af(document,"mouseup",Gf);a&&(b?Af(window,"touchmove",function(){Hf("touchmove",200)},{passive:!0}):(Af(window,"resize",function(){Hf("resize",200)}),Af(window,"scroll",function(){Hf("scroll",200)})));
new Df(function(){Hf("mouse",100)});
Af(document,"touchstart",Gf,{passive:!0});Af(document,"touchend",Gf,{passive:!0})}}
function Hf(a,b){Ef[a]||(Ef[a]=!0,mf(function(){Gf();Ef[a]=!1},b))}
function Gf(){null==B("_lact",window)&&Ff();var a=E();z("_lact",a,window);-1==B("_fact",window)&&z("_fact",a,window);(a=B("ytglobal.ytUtilActivityCallback_"))&&a()}
function If(){var a=B("_lact",window),b;null==a?b=-1:b=Math.max(E()-a,0);return b}
;var Jf=window,W=Jf.ytcsi&&Jf.ytcsi.now?Jf.ytcsi.now:Jf.performance&&Jf.performance.timing&&Jf.performance.now&&Jf.performance.timing.navigationStart?function(){return Jf.performance.timing.navigationStart+Jf.performance.now()}:function(){return(new Date).getTime()};var Kf=Ke("initial_gel_batch_timeout",1E3),Lf=Math.pow(2,16)-1,Mf=null,Nf=0,Of=void 0,Pf=0,Qf=0,Rf=0,Sf=!0,Tf=y.ytLoggingTransportLogPayloadsQueue_||{};z("ytLoggingTransportLogPayloadsQueue_",Tf,void 0);var Uf=y.ytLoggingTransportGELQueue_||new Map;z("ytLoggingTransportGELQueue_",Uf,void 0);var Vf=y.ytLoggingTransportTokensToCttTargetIds_||{};z("ytLoggingTransportTokensToCttTargetIds_",Vf,void 0);
function Wf(){Pe(Pf);Pe(Qf);Qf=0;Of&&Of.isReady()?(Xf(Uf),"log_event"in Tf&&Xf(Object.entries(Tf.log_event)),Uf.clear(),delete Tf.log_event):Yf()}
function Yf(){T("web_gel_timeout_cap")&&!Qf&&(Qf=U(Wf,6E4));Pe(Pf);var a=R("LOGGING_BATCH_TIMEOUT",Ke("web_gel_debounce_ms",1E4));T("shorten_initial_gel_batch_timeout")&&Sf&&(a=Kf);Pf=U(Wf,a)}
function Xf(a){var b=Of,c=Math.round(W());a=u(a);for(var d=a.next();!d.done;d=a.next()){var e=u(d.value);d=e.next().value;var f=e.next().value;e=nb({context:Zf(b.f||$f())});e.events=f;(f=Vf[d])&&ag(e,d,f);delete Vf[d];bg(e,c);cg(b,"log_event",e,{retry:!0,onSuccess:function(){Nf=Math.round(W()-c)}});
Sf=!1}}
function bg(a,b){a.requestTimeMs=String(b);T("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);var c=R("EVENT_ID",void 0);if(c){var d=R("BATCH_CLIENT_COUNTER",void 0)||0;!d&&T("web_client_counter_random_seed")&&(d=Math.floor(Math.random()*Lf/2));d++;d>Lf&&(d=1);Q("BATCH_CLIENT_COUNTER",d);c={serializedEventId:c,clientCounter:String(d)};a.serializedClientEventId=c;Mf&&Nf&&T("log_gel_rtt_web")&&(a.previousBatchInfo={serializedClientEventId:Mf,roundtripMs:String(Nf)});Mf=c;Nf=0}}
function ag(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
;var dg=y.ytLoggingGelSequenceIdObj_||{};z("ytLoggingGelSequenceIdObj_",dg,void 0);
function eg(a,b,c,d){d=void 0===d?{}:d;var e={};e.eventTimeMs=Math.round(d.timestamp||W());e[a]=b;e.context={lastActivityMs:String(d.timestamp?-1:If())};T("log_sequence_info_on_gel_web")&&d.T&&(a=e.context,b=d.T,dg[b]=b in dg?dg[b]+1:0,a.sequence={index:dg[b],groupKey:b},d.yb&&delete dg[d.T]);d=d.ga;a="";d&&(a={},d.videoId?a.videoId=d.videoId:d.playlistId&&(a.playlistId=d.playlistId),Vf[d.token]=a,a=d.token);d=Uf.get(a)||[];Uf.set(a,d);d.push(e);c&&(Of=new c);c=Ke("web_logging_max_batch")||100;e=
W();d.length>=c?Wf():10<=e-Rf&&(Yf(),Rf=e)}
;function fg(){var a=gg;B("yt.ads.biscotti.getId_")||z("yt.ads.biscotti.getId_",a,void 0)}
function hg(a){z("yt.ads.biscotti.lastId_",a,void 0)}
;function ig(a){a=a.split("&");for(var b={},c=0,d=a.length;c<d;c++){var e=a[c].split("=");if(1==e.length&&e[0]||2==e.length)try{var f=decodeURIComponent((e[0]||"").replace(/\+/g," ")),g=decodeURIComponent((e[1]||"").replace(/\+/g," "));f in b?Array.isArray(b[f])?eb(b[f],g):b[f]=[b[f],g]:b[f]=g}catch(k){if("q"!=e[0]){var h=Error("Error decoding URL component");h.params={key:e[0],value:e[1]};S(h)}}}return b}
function jg(a){var b=[];fb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];H(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function kg(a){"?"==a.charAt(0)&&(a=a.substr(1));return ig(a)}
function lg(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=kg(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return $b(a,e)+d}
;function mg(a){var b=ng;a=void 0===a?B("yt.ads.biscotti.lastId_")||"":a;b=Object.assign(og(b),pg(b));b.ca_type="image";a&&(b.bid=a);return b}
function og(a){var b={};b.dt=Yc;b.flash="0";a:{try{var c=a.f.top.location.href}catch(f){a=2;break a}a=c?c===a.g.location.href?0:1:2}b=(b.frm=a,b);b.u_tz=-(new Date).getTimezoneOffset();var d=void 0===d?M:d;try{var e=d.history.length}catch(f){e=0}b.u_his=e;b.u_java=!!M.navigator&&"unknown"!==typeof M.navigator.javaEnabled&&!!M.navigator.javaEnabled&&M.navigator.javaEnabled();M.screen&&(b.u_h=M.screen.height,b.u_w=M.screen.width,b.u_ah=M.screen.availHeight,b.u_aw=M.screen.availWidth,b.u_cd=M.screen.colorDepth);
M.navigator&&M.navigator.plugins&&(b.u_nplug=M.navigator.plugins.length);M.navigator&&M.navigator.mimeTypes&&(b.u_nmime=M.navigator.mimeTypes.length);return b}
function pg(a){var b=a.f;try{var c=b.screenX;var d=b.screenY}catch(p){}try{var e=b.outerWidth;var f=b.outerHeight}catch(p){}try{var g=b.innerWidth;var h=b.innerHeight}catch(p){}b=[b.screenLeft,b.screenTop,c,d,b.screen?b.screen.availWidth:void 0,b.screen?b.screen.availTop:void 0,e,f,g,h];c=a.f.top;try{var k=(c||window).document,l="CSS1Compat"==k.compatMode?k.documentElement:k.body;var m=(new Bc(l.clientWidth,l.clientHeight)).round()}catch(p){m=new Bc(-12245933,-12245933)}k=m;m={};l=new dd;y.SVGElement&&
y.document.createElementNS&&l.set(0);c=Qc();c["allow-top-navigation-by-user-activation"]&&l.set(1);c["allow-popups-to-escape-sandbox"]&&l.set(2);y.crypto&&y.crypto.subtle&&l.set(3);y.TextDecoder&&y.TextEncoder&&l.set(4);l=ed(l);m.bc=l;m.bih=k.height;m.biw=k.width;m.brdim=b.join();a=a.g;return m.vis={visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[a.visibilityState||a.webkitVisibilityState||a.mozVisibilityState||""]||0,m.wgl=!!M.WebGLRenderingContext,m}
var ng=new function(){var a=window.document;this.f=window;this.g=a};
z("yt.ads_.signals_.getAdSignalsString",function(a){return jg(mg(a))},void 0);E();var qg="XMLHttpRequest"in y?function(){return new XMLHttpRequest}:null;
function rg(){if(!qg)return null;var a=qg();return"open"in a?a:null}
function sg(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;var tg={Authorization:"AUTHORIZATION","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL","X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},ug="app debugcss debugjs expflag force_ad_params force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" "),
vg=!1;
function wg(a,b){b=void 0===b?{}:b;if(!c)var c=window.location.href;var d=a.match(Vb)[1]||null,e=K(a);d&&e?(d=c,c=a.match(Vb),d=d.match(Vb),c=c[3]==d[3]&&c[1]==d[1]&&c[4]==d[4]):c=e?K(c)==e&&(Number(c.match(Vb)[4]||null)||null)==(Number(a.match(Vb)[4]||null)||null):!0;d=T("web_ajax_ignore_global_headers_if_set");for(var f in tg)e=R(tg[f]),!e||!c&&K(a)||d&&void 0!==b[f]||(b[f]=e);if(c||!K(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());(c||!K(a))&&(f="undefined"!=typeof Intl?(new Intl.DateTimeFormat).resolvedOptions().timeZone:
null)&&(b["X-YouTube-Time-Zone"]=f);if(c||!K(a))b["X-YouTube-Ad-Signals"]=jg(mg(void 0));return b}
function xg(a){var b=window.location.search,c=K(a),d=Xb(a.match(Vb)[5]||null);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=kg(b),f={};H(ug,function(g){e[g]&&(f[g]=e[g])});
return lg(a,f||{},!1)}
function yg(a,b){if(window.fetch&&"XML"!=b.format){var c={method:b.method||"GET",credentials:"same-origin"};b.headers&&(c.headers=b.headers);a=zg(a,b);var d=Ag(a,b);d&&(c.body=d);b.withCredentials&&(c.credentials="include");var e=!1,f;fetch(a,c).then(function(g){if(!e){e=!0;f&&Pe(f);var h=g.ok,k=function(l){l=l||{};var m=b.context||y;h?b.onSuccess&&b.onSuccess.call(m,l,g):b.onError&&b.onError.call(m,l,g);b.ma&&b.ma.call(m,l,g)};
"JSON"==(b.format||"JSON")&&(h||400<=g.status&&500>g.status)?g.json().then(k,function(){k(null)}):k(null)}});
b.wa&&0<b.timeout&&(f=U(function(){e||(e=!0,Pe(f),b.wa.call(b.context||y))},b.timeout))}else Bg(a,b)}
function Bg(a,b){var c=b.format||"JSON";a=zg(a,b);var d=Ag(a,b),e=!1,f=Cg(a,function(k){if(!e){e=!0;h&&Pe(h);var l=sg(k),m=null,p=400<=k.status&&500>k.status,t=500<=k.status&&600>k.status;if(l||p||t)m=Dg(a,c,k,b.xb);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(m&&m.return_code,10);break a;case "RAW":l=!0;break a}l=!!m}m=m||{};p=b.context||y;l?b.onSuccess&&b.onSuccess.call(p,k,m):b.onError&&b.onError.call(p,k,m);b.ma&&b.ma.call(p,k,m)}},b.method,d,b.headers,b.responseType,
b.withCredentials);
if(b.S&&0<b.timeout){var g=b.S;var h=U(function(){e||(e=!0,f.abort(),Pe(h),g.call(b.context||y,f))},b.timeout)}return f}
function zg(a,b){b.Ab&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=R("XSRF_FIELD_NAME",void 0),d=b.ib;d&&(d[c]&&delete d[c],a=lg(a,d||{},!0));return a}
function Ag(a,b){var c=R("XSRF_FIELD_NAME",void 0),d=R("XSRF_TOKEN",void 0),e=b.postBody||"",f=b.D,g=R("XSRF_FIELD_NAME",void 0),h;b.headers&&(h=b.headers["Content-Type"]);b.zb||K(a)&&!b.withCredentials&&K(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.D&&b.D[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=kg(e),pb(e,f),e=b.xa&&"JSON"==b.xa?JSON.stringify(e):Zb(e));f=e||f&&!jb(f);!vg&&f&&"POST"!=b.method&&(vg=!0,S(Error("AJAX request with postData should use POST")));
return e}
function Dg(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Fe(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Eg(a):null)e={},H(a.getElementsByTagName("*"),function(g){e[g.tagName]=Fg(g)})}d&&Gg(e);
return e}
function Gg(a){if(Ma(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d=Qb(a[b],null);a[c]=d}else Gg(a[b])}}
function Eg(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function Fg(a){var b="";H(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Cg(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&Ee(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=rg();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;T("debug_forward_web_query_parameters")&&(a=xg(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=wg(a,e))for(var l in e)k.setRequestHeader(l,e[l]),"content-type"==l.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;function Hg(){for(var a={},b=u(Object.entries(kg(R("DEVICE","")))),c=b.next();!c.done;c=b.next()){var d=u(c.value);c=d.next().value;d=d.next().value;"cbrand"===c?a.deviceMake=d:"cmodel"===c?a.deviceModel=d:"cbr"===c?a.browserName=d:"cbrver"===c?a.browserVersion=d:"cos"===c?a.osName=d:"cosver"===c?a.osVersion=d:"cplatform"===c&&(a.platform=d)}return a}
;function Ig(){return"INNERTUBE_API_KEY"in Ae&&"INNERTUBE_API_VERSION"in Ae}
function $f(){return{innertubeApiKey:R("INNERTUBE_API_KEY",void 0),innertubeApiVersion:R("INNERTUBE_API_VERSION",void 0),La:R("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),Ma:R("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),innertubeContextClientVersion:R("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0),Oa:R("INNERTUBE_CONTEXT_HL",void 0),Na:R("INNERTUBE_CONTEXT_GL",void 0),Pa:R("INNERTUBE_HOST_OVERRIDE",void 0)||"",Ra:!!R("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Qa:!!R("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1)}}
function Zf(a){a={client:{hl:a.Oa,gl:a.Na,clientName:a.Ma,clientVersion:a.innertubeContextClientVersion,configInfo:a.La}};var b=window.devicePixelRatio;b&&1!=b&&(a.client.screenDensityFloat=String(b));b=R("EXPERIMENTS_TOKEN","");""!==b&&(a.client.experimentsToken=b);b=[];var c=R("EXPERIMENTS_FORCED_FLAGS",{});for(d in c)b.push({key:d,value:String(c[d])});var d=R("EXPERIMENT_FLAGS",{});for(var e in d)e.startsWith("force_")&&void 0===c[e]&&b.push({key:e,value:String(d[e])});0<b.length&&(a.request={internalExperimentFlags:b});
R("DELEGATED_SESSION_ID")&&!T("pageid_as_header_web")&&(a.user={onBehalfOfUser:R("DELEGATED_SESSION_ID")});a.client=Object.assign(a.client,Hg());return a}
function Jg(a,b,c){c=void 0===c?{}:c;var d={"X-Goog-Visitor-Id":c.visitorData||R("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.vb||R("AUTHORIZATION"))||(a?b="Bearer "+B("gapi.auth.getToken")().ub:b=cd([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=R("SESSION_INDEX",0),T("pageid_as_header_web")&&(d["X-Goog-PageId"]=R("DELEGATED_SESSION_ID")));return d}
;function Kg(a){a=Object.assign({},a);delete a.Authorization;var b=cd();if(b){var c=new vd;c.update(R("INNERTUBE_API_KEY",void 0));c.update(b);b=c.digest();c=3;Ka(b);void 0===c&&(c=0);if(!sc){sc={};for(var d="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),e=["+/=","+/","-_=","-_.","-_"],f=0;5>f;f++){var g=d.concat(e[f].split(""));rc[f]=g;for(var h=0;h<g.length;h++){var k=g[h];void 0===sc[k]&&(sc[k]=h)}}}c=rc[c];d=[];for(e=0;e<b.length;e+=3){var l=b[e],m=(f=e+1<b.length)?
b[e+1]:0;k=(g=e+2<b.length)?b[e+2]:0;h=l>>2;l=(l&3)<<4|m>>4;m=(m&15)<<2|k>>6;k&=63;g||(k=64,f||(m=64));d.push(c[h],c[l],c[m]||"",c[k]||"")}a.hash=d.join("")}return a}
function Lg(a){a=Kg(a);var b=new vd;b.update(JSON.stringify(a,Object.keys(a).sort()));a=b.digest();b="";for(var c=0;c<a.length;c++)b+="0123456789ABCDEF".charAt(Math.floor(a[c]/16))+"0123456789ABCDEF".charAt(a[c]%16);return b}
;function Mg(){var a=new se;(a=a.isAvailable()?new ye(a,"yt.innertube"):null)||(a=new te("yt.innertube"),a=a.isAvailable()?a:null);this.f=a?new oe(a):null;this.g=document.domain||window.location.hostname}
Mg.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.f)try{this.f.set(a,b,E()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(Kd(b))}catch(f){return}else e=escape(b);Ie(a,e,c,this.g)};
Mg.prototype.get=function(a,b){var c=void 0,d=!this.f;if(!d)try{c=this.f.get(a)}catch(e){d=!0}if(d&&(c=yc.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Mg.prototype.remove=function(a){this.f&&this.f.remove(a);var b=this.g;yc.remove(""+a,"/",void 0===b?"youtube.com":b)};var Ng;function Og(){Ng||(Ng=new Mg);return Ng}
function Pg(a,b,c,d){if(d)return null;d=Og().get("nextId",!0)||1;var e=Og().get("requests",!0)||{};e[d]={method:a,request:b,authState:Kg(c),requestTime:Math.round(W())};Og().set("nextId",d+1,86400,!0);Og().set("requests",e,86400,!0);return d}
function Qg(a){var b=Og().get("requests",!0)||{};delete b[a];Og().set("requests",b,86400,!0)}
function Rg(a){var b=Og().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(W())-d.requestTime)){var e=d.authState,f=Kg(Jg(!1));lb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(W())),cg(a,d.method,e,{}));delete b[c]}}Og().set("requests",b,86400,!0)}}
;function Sg(){}
;var Tg=pc||qc;function Ug(a){var b=Lb;return b?0<=b.toLowerCase().indexOf(a):!1}
;function Vg(a){if(!a)throw Error();throw a;}
function Wg(a){return a}
function X(a){var b=this;this.g=a;this.state={status:"PENDING"};this.f=[];this.onRejected=[];this.g(function(c){if("PENDING"===b.state.status){b.state={status:"FULFILLED",value:c};c=u(b.f);for(var d=c.next();!d.done;d=c.next())d=d.value,d()}},function(c){if("PENDING"===b.state.status){b.state={status:"REJECTED",
reason:c};c=u(b.onRejected);for(var d=c.next();!d.done;d=c.next())d=d.value,d()}})}
X.all=function(a){return new X(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={K:0};f.K<a.length;f={K:f.K},++f.K)Xg(X.resolve(a[f.K]).then(function(g){return function(h){d[g.K]=h;e--;0===e&&b(d)}}(f)),function(g){c(g)})})};
X.resolve=function(a){return new X(function(b,c){a instanceof X?a.then(b,c):b(a)})};
X.reject=function(a){return new X(function(b,c){c(a)})};
X.prototype.then=function(a,b){var c=this,d=null!==a&&void 0!==a?a:Wg,e=null!==b&&void 0!==b?b:Vg;return new X(function(f,g){"PENDING"===c.state.status?(c.f.push(function(){Yg(c,c,d,f,g)}),c.onRejected.push(function(){Zg(c,c,e,f,g)})):"FULFILLED"===c.state.status?Yg(c,c,d,f,g):"REJECTED"===c.state.status&&Zg(c,c,e,f,g)})};
function Xg(a,b){a.then(void 0,b)}
function Yg(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof X?$g(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Zg(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof X?$g(a,b,f,d,e):d(f)}catch(g){e(g)}}
function $g(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof X?$g(a,b,f,d,e):d(f)},function(f){e(f)})}
;function ah(){var a=Error.call(this,"Transaction was aborted");this.message=a.message;"stack"in a&&(this.stack=a.stack);Object.setPrototypeOf(this,ah.prototype)}
v(ah,Error);function bh(a){return a instanceof DOMException?"VersionError"===a.name:"DOMError"in self&&a instanceof DOMError?"VersionError"===a.name:a instanceof Object&&"message"in a?"An attempt was made to open a database using a lower version than the existing version."===a.message:!1}
function ch(a,b){return new X(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()})}
;function dh(a){return new O(function(b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){a.removeEventListener("success",e);a.removeEventListener("error",d)}
a.addEventListener("success",e);a.addEventListener("error",d)})}
function eh(a){return new X(function(b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){a.removeEventListener("success",e);a.removeEventListener("error",d)}
a.addEventListener("success",e);a.addEventListener("error",d)})}
;function fh(a){this.f=a}
n=fh.prototype;n.add=function(a,b,c){return gh(this,[a],"readwrite",function(d){return hh(d,a).add(b,c)})};
n.clear=function(a){return gh(this,[a],"readwrite",function(b){return hh(b,a).clear()})};
n.close=function(){this.f.close()};
n.count=function(a,b){return gh(this,[a],"readonly",function(c){return hh(c,a).count(b)})};
function ih(a,b,c){a=a.f.createObjectStore(b,c);return new jh(a)}
n["delete"]=function(a,b){return gh(this,[a],"readwrite",function(c){return hh(c,a)["delete"](b)})};
n.get=function(a,b){return gh(this,[a],"readwrite",function(c){return hh(c,a).get(b)})};
function kh(a,b){return gh(a,["databases"],"readwrite",function(c){return lh(hh(c,"databases"),b,void 0)})}
function gh(a,b,c,d){c=void 0===c?"readonly":c;return new O(function(e,f){var g=a.f.transaction(b,c),h=new mh(g,b);Xg(d(h).then(function(k){Yd(nh(h).then(function(){e(k)}),function(l){f(l)})}),function(k){f(k)})})}
function jh(a){this.f=a}
n=jh.prototype;n.add=function(a,b){var c=b?this.f.add(a,b):this.f.add(a);return eh(c)};
n.clear=function(){return eh(this.f.clear()).then(function(){})};
n.count=function(a){a=a?this.f.count(a):this.f.count();return eh(a)};
n["delete"]=function(a){return eh(this.f["delete"](a))};
n.get=function(a){return eh(this.f.get(a))};
n.index=function(a){return new oh(this.f.index(a))};
n.getName=function(){return this.f.name};
function lh(a,b,c){a=c?a.f.put(b,c):a.f.put(b);return eh(a)}
function mh(a){var b=this;this.f=a;this.g=new Map;this.aborted=!1;this.done=new O(function(c,d){b.f.addEventListener("complete",function(){c()});
b.f.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.f.error)});
b.f.addEventListener("abort",function(){var e=b.f.error;e?("QuotaExceededError"===e.name?Fe(Error("The current transaction exceeded its quota limitations.")):"UnknownError"===e.name&&Fe(Error("The current transaction may have failed because of exceeding quota limitations.")),d(e)):d(new ah)})})}
mh.prototype.abort=function(){this.f.abort();this.aborted=!0};
function nh(a){var b=a.f;b.commit&&!a.aborted&&b.commit();return a.done}
function hh(a,b){var c=a.f.objectStore(b),d=a.g.get(c);d||(d=new jh(c),a.g.set(c,d));return d}
function oh(a){this.f=a}
oh.prototype.count=function(a){a=a?this.f.count(a):this.f.count();return eh(a)};
oh.prototype.get=function(a){return eh(this.f.get(a))};
function ph(a,b,c){a=a.f.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return qh(a).then(function(d){return ch(d,c)})}
function rh(a,b){this.request=a;this.f=b}
function qh(a){return eh(a).then(function(b){return null===b?null:new rh(a,b)})}
rh.prototype["delete"]=function(){return eh(this.f["delete"]()).then(function(){})};
rh.prototype.getValue=function(){return this.f.value};
rh.prototype.update=function(a){return eh(this.f.update(a))};function sh(a,b,c){function d(){m||(m=new fh(f.result));return m}
var e=mh;var f=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var g=c.blocked,h=c.blocking,k=c.f,l=c.upgrade,m;l&&f.addEventListener("upgradeneeded",function(p){if(null===p.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===f.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");var t=d(),q=new e(f.transaction);l(t,p.oldVersion,p.newVersion,q)});
g&&f.addEventListener("blocked",function(){g()});
return dh(f).then(function(p){h&&p.addEventListener("versionchange",function(){h(d())});
k&&p.addEventListener("close",function(){k()});
return d()})}
function th(a,b,c){c=void 0===c?{}:c;return sh(a,b,c)}
;var uh,vh,wh=["getAll","getAllKeys","getKey","openKeyCursor"],xh=["getAll","getAllKeys","getKey","openKeyCursor"];function yh(){var a;if(a=Tg)a=/WebKit\/([0-9]+)/.exec(Lb),a=!!(a&&600<=parseInt(a[1],10));a&&(a=/WebKit\/([0-9]+)/.exec(Lb),a=!(a&&602<=parseInt(a[1],10)));return a&&!T("ytidb_allow_on_ios_safari_v8_and_v9")?!1:!!self.indexedDB}
function zh(){return new Promise(function(a){setTimeout(a,50)})}
function Ah(){return L(this,function b(){var c,d,e;return x(b,function(f){switch(f.f){case 1:if(!yh())return f["return"](!1);ra(f);d=!1;return w(f,th("yt-idb-test-do-not-use",void 0,{blocking:function(){d=!0;c&&(c.close(),c=void 0)}}),5);
case 5:return c=f.g,e=th("yt-idb-test-do-not-use",c.f.version+1).then(function(g){try{g.close()}catch(h){}}),w(f,Promise.race([e,
zh()]),6);case 6:return f["return"](d);case 3:ta(f);if(c)try{c.close()}catch(g){}ua(f);break;case 2:return sa(f),f["return"](!1)}})})}
function Bh(){return void 0!==uh?Vd(uh):new O(function(a){Ah().then(function(b){uh=b;a(b)})})}
function Ch(){return void 0!==vh?Vd(vh):Bh().then(function(a){if(!a)return!1;var b=u(wh);for(a=b.next();!a.done;a=b.next())if(!IDBObjectStore.prototype[a.value])return!1;b=u(xh);for(a=b.next();!a.done;a=b.next())if(!IDBIndex.prototype[a.value])return!1;return IDBObjectStore.prototype.getKey?!0:!1}).then(function(a){return vh=a})}
;var Dh;function Eh(){function a(b){b.close();Dh=void 0}
Dh||(Dh=Yd(th("YtIdbMeta",1,{blocking:a,upgrade:function(b,c){1>c&&ih(b,"databases",{keyPath:"actualName"})}}),function(b){return bh(b)?th("YtIdbMeta",void 0,{blocking:a}):Wd(b)}));
return Dh}
function Fh(a){return Eh().then(function(b){return b.get("databases",a.actualName).then(function(c){if(c?a.actualName!==c.actualName||a.publicName!==c.publicName||a.userIdentifier!==c.userIdentifier||a.signedIn!==c.signedIn:1)return kh(b,a)})})}
function Gh(a){return Eh().then(function(b){return b["delete"]("databases",a)})}
;function Hh(a){try{var b={actualName:"LogsDataBase",publicName:"LogsDataBase",userIdentifier:void 0,signedIn:!1}}catch(c){return Wd(c)}return Yd(Fh(b).then(function(){return a(b)}),function(c){return Yd(Gh(b.actualName),function(){}).then(function(){return Wd(c)})})}
function Ih(a,b){b=void 0===b?{}:b;return Hh(function(c){return th(c.actualName,a,b)})}
;function Jh(){X.call(this,function(){});
throw Error("Not allowed to instantiate the thennable outside of the core library.");}
v(Jh,X);Jh.reject=X.reject;Jh.resolve=X.resolve;Jh.all=X.all;var Kh;function Lh(){return L(this,function b(){return x(b,function(c){if(!Kh)try{Kh=Ih(1,{upgrade:function(d,e){1>e&&(ih(d,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0}).f.createIndex("newRequest",["status","authHash","timestamp"],{unique:!1}),ih(d,"sapisid"))}})}catch(d){if(!bh(d))return S(d),c["return"](Promise.reject(d));
Kh=Ih()}return c["return"](Kh)})})}
function Mh(a){return L(this,function c(){var d,e,f;return x(c,function(g){if(1==g.f)return w(g,Nh(),2);if(3!=g.f)return d=g.g,w(g,Lh(),3);e=g.g;f=Object.assign(Object.assign({},a),{options:JSON.parse(JSON.stringify(a.options)),authHash:d});return g["return"](e.add("LogsRequestsStore",f))})})}
function Oh(){return L(this,function b(){var c,d,e,f,g,h;return x(b,function(k){switch(k.f){case 1:return w(k,Nh(),2);case 2:return c=k.g,d=["NEW",c,0],e=["NEW",c,W()],f=IDBKeyRange.bound(d,e),w(k,Lh(),3);case 3:return g=k.g,h=void 0,w(k,gh(g,["LogsRequestsStore"],"readwrite",function(l){return ph(hh(l,"LogsRequestsStore").index("newRequest"),{query:f,direction:"prev"},function(m){m.getValue()&&(h=m.getValue(),h.status="QUEUED",m.update(h))})}),4);
case 4:return k["return"](h)}})})}
function Ph(a){return L(this,function c(){var d;return x(c,function(e){if(1==e.f)return w(e,Lh(),2);d=e.g;return e["return"](gh(d,["LogsRequestsStore"],"readwrite",function(f){var g=hh(f,"LogsRequestsStore");return g.get(a).then(function(h){if(h)return h.status="QUEUED",lh(g,h).then(function(){return h})})}))})})}
function Qh(a){return L(this,function c(){var d;return x(c,function(e){if(1==e.f)return w(e,Lh(),2);d=e.g;return e["return"](gh(d,["LogsRequestsStore"],"readwrite",function(f){var g=hh(f,"LogsRequestsStore");return g.get(a).then(function(h){return h?(h.status="NEW",h.sendCount+=1,lh(g,h).then(function(){return h})):Jh.resolve(void 0)})}))})})}
function Rh(a){return L(this,function c(){var d;return x(c,function(e){if(1==e.f)return w(e,Lh(),2);d=e.g;return e["return"](d["delete"]("LogsRequestsStore",a))})})}
function Nh(){return L(this,function b(){var c;return x(b,function(d){if(1==d.f){Sg.f||(Sg.f=new Sg);var e={};var f=cd([]);f&&(e.Authorization=f,e["X-Goog-AuthUser"]=R("SESSION_INDEX",0),"INNERTUBE_HOST_OVERRIDE"in Ae||(e["X-Origin"]=window.location.origin),T("pageid_as_header_web")&&"DELEGATED_SESSION_ID"in Ae&&(e["X-Goog-PageId"]=R("DELEGATED_SESSION_ID")));e=Vd(e);return w(d,e,2)}c=d.g;return d["return"](Lg(c))})})}
;var Sh=Ke("network_polling_interval",3E4);function Th(){this.i=0;this.f=window.navigator.onLine;Uh(this);Vh(this)}
function Wh(){Th.f||(Th.f=new Th);return Th.f}
function Xh(a){var b=Yh,c=Zh;(new O(function(d){a.g=d})).then(function(){b();
c&&(a.h=c)});
$h(a)}
function Vh(a){window.addEventListener("online",function(){a.f=!0;a.g&&a.g()})}
function Uh(a){window.addEventListener("offline",function(){a.f=!1;a.h&&a.h()})}
function $h(a){a.i||(ai(a),window.navigator.onLine&&a.g&&a.g())}
function ai(a){a.i=kf(function(){window.navigator.onLine?(!1===a.f&&S(Error("NetworkStatusManager missed online event.")),a.f=!0,a.g&&a.g()):(!0===a.f&&S(Error("NetworkStatusManager missed offline event.")),a.f=!1,a.h&&a.h());ai(a)},Sh)}
;var bi=Ke("networkless_throttle_timeout")||100,ci=Ke("networkless_retry_attempts")||1,di=0;function ei(a,b){b=void 0===b?{}:b;fi().then(function(c){if(c&&!T("networkless_bypass_write")){var d={url:a,options:b,timestamp:W(),status:"NEW",sendCount:0};Mh(d).then(function(e){d.id=e;e=Wh();e.f&&!T("networkless_always_offline")?gi(d):Xh(e)})["catch"](function(e){gi(d);
S(e)})}else Bg(a,b)})}
function Yh(){var a=this;di||(di=mf(function(){return L(a,function c(){var d;return x(c,function(e){if(1==e.f)return w(e,Oh(),2);if(3!=e.f)return d=e.g,d?w(e,gi(d),3):(Zh(),e["return"]());di=0;Yh();e.f=0})})},bi))}
function Zh(){of(di);di=0}
function gi(a){return L(this,function c(){var d;return x(c,function(e){switch(e.f){case 1:if(!a.id){e.I(2);break}return w(e,Ph(a.id),3);case 3:(d=e.g)?a=d:Fe(Error("The request cannot be found in the database."));case 2:var f=a.timestamp;if(!(2592E6<=W()-f)){e.I(4);break}Fe(Error("Networkless Logging: Stored logs request expired age limit"));if(!a.id){e.I(5);break}return w(e,Rh(a.id),5);case 5:return e["return"]();case 4:(a=hi(a))&&Bg(a.url,a.options),e.f=0}})})}
function hi(a){var b=this,c=a.options.onError?a.options.onError:function(){};
a.options.onError=function(e,f){return L(b,function h(){return x(h,function(k){if(1==k.f)return a&&a.id?a.sendCount<ci?w(k,Qh(a.id),6):w(k,Rh(a.id),2):k.I(2);2!=k.f&&Xh(Wh());c(e,f);k.f=0})})};
var d=a.options.onSuccess?a.options.onSuccess:function(){};
a.options.onSuccess=function(e,f){return L(b,function h(){return x(h,function(k){if(1==k.f)return a&&a.id?w(k,Rh(a.id),2):k.I(2);d(e,f);k.f=0})})};
return a}
function fi(){return L(this,function b(){return x(b,function(c){return T("networkless_logging")?(2===Ke("networkless_ytidb_version")&&Ch().then(function(d){return d}),c["return"](yh())):c["return"](!1)})})}
;function ii(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];d=Error.call(this,a);this.message=d.message;"stack"in d&&(this.stack=d.stack);this.args=[].concat(c instanceof Array?c:fa(u(c)))}
v(ii,Error);function ji(a){var b=this;this.f=null;a?this.f=a:Ig()&&(this.f=$f());kf(function(){Rg(b)},5E3)}
ji.prototype.isReady=function(){!this.f&&Ig()&&(this.f=$f());return!!this.f};
function cg(a,b,c,d){!R("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Fe(new ii("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var e=new ii("innertube xhrclient not ready",b,c,d);S(e);e.sampleWeight=0;throw e;}var f={headers:{"Content-Type":"application/json"},method:"POST",D:c,xa:"JSON",S:function(){d.S()},
wa:d.S,onSuccess:function(p,t){if(d.onSuccess)d.onSuccess(t)},
va:function(p){if(d.onSuccess)d.onSuccess(p)},
onError:function(p,t){if(d.onError)d.onError(t)},
Bb:function(p){if(d.onError)d.onError(p)},
timeout:d.timeout,withCredentials:!0},g="";(e=a.f.Pa)&&(g=e);var h=a.f.Ra||!1,k=Jg(h,g,d);Object.assign(f.headers,k);f.headers.Authorization&&!g&&(f.headers["x-origin"]=window.location.origin);e="/youtubei/"+a.f.innertubeApiVersion+"/"+b;var l={alt:"json"};a.f.Qa&&f.headers.Authorization||(l.key=a.f.innertubeApiKey);var m=lg(""+g+e,l||{},!0);fi().then(function(p){if(d.retry&&T("retry_web_logging_batches")&&"www.youtube-nocookie.com"!=g){if(T("networkless_gel")&&!p||!T("networkless_gel"))var t=Pg(b,
c,k,h);if(t){var q=f.onSuccess,A=f.va;f.onSuccess=function(D,V){Qg(t);q(D,V)};
c.va=function(D,V){Qg(t);A(D,V)}}}try{T("use_fetch_for_op_xhr")?yg(m,f):T("networkless_gel")&&d.retry?(f.method="POST",ei(m,f)):(f.method="POST",f.D||(f.D={}),Bg(m,f))}catch(D){if("InvalidAccessError"==D.name)t&&(Qg(t),t=0),Fe(Error("An extension is blocking network request."));
else throw D;}t&&kf(function(){Rg(a)},5E3)})}
;function ki(a,b,c){c=void 0===c?{}:c;var d=ji;R("ytLoggingEventsDefaultDisabled",!1)&&ji==ji&&(d=null);eg(a,b,d,c)}
;var li=[{ta:function(a){return"Cannot read property '"+a.key+"'"},
na:{TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,
groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]}],Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}]}},{ta:function(a){return"Cannot call '"+a.key+"'"},
na:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,
groups:["key"]}]}}];function mi(){this.f=[];this.g=[]}
var ni;var oi=new P;var pi=new Set,qi=0,ri=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function si(a){ti(a,"WARNING")}
function ti(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||R("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||R("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0);c=f||{};b=void 0===b?"ERROR":b;b=void 0===b?"ERROR":b;var g=void 0===g?!1:g;if(a&&(T("console_log_js_exceptions")&&(d=[],d.push("Name: "+a.name),d.push("Message: "+a.message),a.hasOwnProperty("params")&&d.push("Error Params: "+JSON.stringify(a.params)),d.push("File name: "+a.fileName),d.push("Stacktrace: "+a.stack),window.console.log(d.join("\n"),a)),
(window&&window.yterr||g)&&!(5<=qi)&&0!==a.sampleWeight)){var h=tc(a);g=h.message||"Unknown Error";d=h.name||"UnknownError";e=h.lineNumber||"Not available";f=h.fileName||"Not available";h=h.stack||a.f||"Not available";if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var k=0,l=0;l<a.args.length;l++){var m=a.args[l],p="params."+l;k+=p.length;if(m)if(Array.isArray(m))for(var t=c,q=0;q<m.length&&!(m[q]&&(k+=ui(q,m[q],p,t),500<k));q++);else if("object"===typeof m)for(t in t=void 0,q=c,m){if(m[t]&&
(k+=ui(t,m[t],p,q),500<k))break}else c[p]=String(JSON.stringify(m)).substring(0,500),k+=c[p].length;else c[p]=String(JSON.stringify(m)).substring(0,500),k+=c[p].length;if(500<=k)break}else if(a.hasOwnProperty("params")&&a.params)if(m=a.params,"object"===typeof a.params)for(l in p=0,m){if(m[l]&&(k="params."+l,t=String(JSON.stringify(m[l])).substr(0,500),c[k]=t,p+=k.length+t.length,500<p))break}else c.params=String(JSON.stringify(m)).substr(0,500);navigator.vendor&&!c.hasOwnProperty("vendor")&&(c.vendor=
navigator.vendor);c={message:g,name:d,lineNumber:e,fileName:f,stack:h,params:c};a=Number(a.columnNumber);isNaN(a)||(c.lineNumber=c.lineNumber+":"+a);a=u(li);for(g=a.next();!g.done;g=a.next())if(g=g.value,g.na[c.name])for(e=u(g.na[c.name]),d=e.next();!d.done;d=e.next())if(f=d.value,d=c.message.match(f.regexp)){c.params["error.original"]=d[0];e=f.groups;f={};for(h=0;h<e.length;h++)f[e[h]]=d[h+1],c.params["error."+e[h]]=d[h+1];c.message=g.ta(f);break}window.yterr&&"function"===typeof window.yterr&&window.yterr(c);
if(!(pi.has(c.message)||0<=c.stack.indexOf("/YouTubeCenter.js")||0<=c.stack.indexOf("/mytube.js"))){oi.N("handleError",c);if(T("kevlar_gel_error_routing")){a=b;a:{g=u(ri);for(d=g.next();!d.done;d=g.next())if(Ug(d.value.toLowerCase())){g=!0;break a}g=!1}if(!g){g={stackTrace:c.stack};c.fileName&&(g.filename=c.fileName);d=c.lineNumber&&c.lineNumber.split?c.lineNumber.split(":"):[];0!==d.length&&(1!==d.length||isNaN(Number(d[0]))?2!==d.length||isNaN(Number(d[0]))||isNaN(Number(d[1]))||(g.lineNumber=Number(d[0]),
g.columnNumber=Number(d[1])):g.lineNumber=Number(d[0]));d=c.message;e=c.name;ni||(ni=new mi);f=ni;a:{h=u(f.g);for(l=h.next();!l.done;l=h.next())if(l=l.value,c.message&&c.message.match(l.f)){f=l.weight;break a}f=u(f.f);for(h=f.next();!h.done;h=f.next())if(h=h.value,h.Da(c)){f=h.weight;break a}f=1}d={level:"ERROR_LEVEL_UNKNOWN",message:d,errorClassName:e,sampleWeight:f};"ERROR"===a?d.level="ERROR_LEVEL_ERROR":"WARNING"===a&&(d.level="ERROR_LEVEL_WARNNING");a={isObfuscated:!0,browserStackInfo:g};g={pageUrl:window.location.href,
kvPairs:[]};if(e=c.params)for(f=u(Object.keys(e)),h=f.next();!h.done;h=f.next())h=h.value,g.kvPairs.push({key:"client."+h,value:String(e[h])});e=R("SERVER_NAME",void 0);f=R("SERVER_VERSION",void 0);e&&f&&(g.kvPairs.push({key:"server.name",value:e}),g.kvPairs.push({key:"server.version",value:f}));ki("clientError",{errorMetadata:g,stackTrace:a,logMessage:d});Wf()}}a=c.params||{};b={ib:{a:"logerror",t:"jserror",type:c.name,msg:c.message.substr(0,250),line:c.lineNumber,level:b,"client.name":a.name},D:{url:R("PAGE_NAME",
window.location.href),file:c.fileName},method:"POST"};a.version&&(b["client.version"]=a.version);if(b.D){c.stack&&(b.D.stack=c.stack);g=u(Object.keys(a));for(d=g.next();!d.done;d=g.next())d=d.value,b.D["client."+d]=a[d];if(a=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0))for(g=u(Object.keys(a)),d=g.next();!d.done;d=g.next())d=d.value,b.D[d]=a[d];a=R("SERVER_NAME",void 0);g=R("SERVER_VERSION",void 0);a&&g&&(b.D["server.name"]=a,b.D["server.version"]=g)}Bg(R("ECATCHER_REPORT_HOST","")+"/error_204",
b);pi.add(c.message);qi++}}}
function ui(a,b,c,d){c+="."+a;a=String(JSON.stringify(b)).substr(0,500);d[c]=a;return c.length+a.length}
;function vi(){this.g=!1;this.f=null}
vi.prototype.initialize=function(a,b,c,d,e,f){var g=this;f=void 0===f?!1:f;b?(this.g=!0,bf(b,function(){g.g=!1;window.botguard?wi(g,c,d,f):(gf(b),si(new ii("Unable to load Botguard","from "+b)))},e)):a&&(eval(a),window.botguard?wi(this,c,d,f):si(Error("Unable to load Botguard from JS")))};
function wi(a,b,c,d){if(d)try{a.f=new window.botguard.bg(b,c?function(){return c(b)}:Ha)}catch(e){si(e)}else{try{a.f=new window.botguard.bg(b)}catch(e){si(e)}c&&c(b)}}
vi.prototype.dispose=function(){this.f=null};var xi=new vi;function yi(){return!!xi.f}
function zi(a){a=void 0===a?{}:a;a=void 0===a?{}:a;return xi.f?xi.f.invoke(void 0,void 0,a):null}
;var Ai=E().toString();
function Bi(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=E();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(Ai)for(a=1,b=0;b<Ai.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^Ai.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var Ci=y.ytLoggingDocDocumentNonce_||Bi();z("ytLoggingDocDocumentNonce_",Ci,void 0);var Di=1;function Ei(a){this.f=a}
Ei.prototype.getAsJson=function(){var a={};void 0!==this.f.trackingParams?a.trackingParams=this.f.trackingParams:(a.veType=this.f.veType,void 0!==this.f.veCounter&&(a.veCounter=this.f.veCounter),void 0!==this.f.elementIndex&&(a.elementIndex=this.f.elementIndex));void 0!==this.f.dataElement&&(a.dataElement=this.f.dataElement.getAsJson());void 0!==this.f.youtubeData&&(a.youtubeData=this.f.youtubeData);return a};
Ei.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
Ei.prototype.isClientVe=function(){return!this.f.trackingParams&&!!this.f.veType};function Fi(a){a=void 0===a?0:a;return 0==a?"client-screen-nonce":"client-screen-nonce."+a}
function Gi(a){a=void 0===a?0:a;return 0==a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function Hi(a){return R(Gi(void 0===a?0:a),void 0)}
z("yt_logging_screen.getRootVeType",Hi,void 0);function Ii(){var a=Hi(0),b;a?b=new Ei({veType:a,youtubeData:void 0}):b=null;return b}
function Ji(){var a=R("csn-to-ctt-auth-info");a||(a={},Q("csn-to-ctt-auth-info",a));return a}
function Ki(a){a=void 0===a?0:a;var b=R(Fi(a));if(!b&&!R("USE_CSN_FALLBACK",!0))return null;b||0!=a||(T("kevlar_client_side_screens")||T("c3_client_side_screens")?b="UNDEFINED_CSN":b=R("EVENT_ID"));return b?b:null}
z("yt_logging_screen.getCurrentCsn",Ki,void 0);function Li(a,b,c){var d=Ji();(c=Ki(c))&&delete d[c];b&&(d[a]=b)}
function Mi(a){return Ji()[a]}
z("yt_logging_screen.getCttAuthInfo",Mi,void 0);function Ni(a,b,c,d){c=void 0===c?0:c;if(a!==R(Fi(c))||b!==R(Gi(c)))if(Li(a,d,c),Q(Fi(c),a),Q(Gi(c),b),0==c||T("web_screen_associated_all_layers"))b=function(){setTimeout(function(){a&&eg("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:Ci,clientScreenNonce:a},ji)},0)},"requestAnimationFrame"in window?window.requestAnimationFrame(b):b()}
z("yt_logging_screen.setCurrentScreen",Ni,void 0);function Oi(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=R("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=R("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=K(window.location.href);g&&f.push(g);g=K(d);if(0<=Ya(f,g)||!g&&0==d.lastIndexOf("/",0))if(T("autoescape_tempdata_url")&&(f=document.createElement("a"),Rb(f,d),d=f.href),d){g=d.match(Vb);d=g[5];f=g[6];g=g[7];var h="";d&&(h+=d);f&&(h+="?"+f);g&&(h+="#"+g);d=h;f=d.indexOf("#");if(d=0>f?d:d.substr(0,f))if(e&&!b.csn&&(b.itct||b.ved)&&
(b=Object.assign({csn:Ki()},b)),k){var k=parseInt(k,10);isFinite(k)&&0<k&&(e=b,b="ST-"+Ub(d).toString(36),e=e?Zb(e):"",Ie(b,e,k||5))}else k=b,e="ST-"+Ub(d).toString(36),k=k?Zb(k):"",Ie(e,k,5)}}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var l=void 0===l?{}:l;var m=void 0===m?"":m;var p=void 0===p?window:p;c=p.location;a=$b(a,l)+m;a=a instanceof I?a:Jb(a);c.href=Fb(a)}return!0}
;function Pi(a,b){this.version=a;this.args=b}
;function Qi(a,b){this.topic=a;this.f=b}
Qi.prototype.toString=function(){return this.topic};var Ri=B("ytPubsub2Pubsub2Instance")||new P;P.prototype.subscribe=P.prototype.subscribe;P.prototype.unsubscribeByKey=P.prototype.R;P.prototype.publish=P.prototype.N;P.prototype.clear=P.prototype.clear;z("ytPubsub2Pubsub2Instance",Ri,void 0);var Si=B("ytPubsub2Pubsub2SubscribedKeys")||{};z("ytPubsub2Pubsub2SubscribedKeys",Si,void 0);var Ti=B("ytPubsub2Pubsub2TopicToKeys")||{};z("ytPubsub2Pubsub2TopicToKeys",Ti,void 0);var Ui=B("ytPubsub2Pubsub2IsAsync")||{};z("ytPubsub2Pubsub2IsAsync",Ui,void 0);
z("ytPubsub2Pubsub2SkipSubKey",null,void 0);function Vi(a,b){var c=Wi();c&&c.publish.call(c,a.toString(),a,b)}
function Xi(a){var b=Yi,c=Wi();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=B("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(Si[d])try{if(f&&b instanceof Qi&&b!=e)try{var h=b.f,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.J){var l=new h;h.J=l.version}var m=h.J}catch(p){}if(!m||k.version!=m)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{f=Reflect.construct(h,
db(k.args))}catch(p){throw p.message="yt.pubsub2.Data.deserialize(): "+p.message,p;}}catch(p){throw p.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+p.message,p;}a.call(window,f)}catch(p){S(p)}},Ui[b.toString()]?B("yt.scheduler.instance")?mf(g):U(g,0):g())});
Si[d]=!0;Ti[b.toString()]||(Ti[b.toString()]=[]);Ti[b.toString()].push(d);return d}
function Zi(){var a=$i,b=Xi(function(c){a.apply(void 0,arguments);aj(b)});
return b}
function aj(a){var b=Wi();b&&("number"===typeof a&&(a=[a]),H(a,function(c){b.unsubscribeByKey(c);delete Si[c]}))}
function Wi(){return B("ytPubsub2Pubsub2Instance")}
;function bj(a){Pi.call(this,1,arguments);this.csn=a}
v(bj,Pi);var Yi=new Qi("screen-created",bj),cj=[],dj=0;function ej(a,b,c){var d=T("use_default_events_client")?void 0:ji;b={csn:a,parentVe:b.getAsJson(),childVes:$a(c,function(f){return f.getAsJson()})};
c=u(c);for(var e=c.next();!e.done;e=c.next())e=e.value.getAsJson(),(jb(e)||!e.trackingParams&&!e.veType)&&si(Error("Child VE logged with no data"));c={ga:Mi(a),T:a};"UNDEFINED_CSN"==a?fj("visualElementAttached",b,c):d?eg("visualElementAttached",b,d,c):ki("visualElementAttached",b,c)}
function fj(a,b,c){cj.push({payloadName:a,payload:b,options:c});dj||(dj=Zi())}
function $i(a){if(cj){for(var b=u(cj),c=b.next();!c.done;c=b.next())c=c.value,c.payload&&(c.payload.csn=a.csn,eg(c.payloadName,c.payload,null,c.options));cj.length=0}dj=0}
;function gj(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||mb(b);this.assets=a.assets||{};this.attrs=a.attrs||mb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
gj.prototype.clone=function(){var a=new gj,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Ja(c)?a[b]=mb(c):a[b]=c}return a};function hj(){N.call(this);this.f=[]}
v(hj,N);hj.prototype.o=function(){for(;this.f.length;){var a=this.f.pop();a.target.removeEventListener(a.name,a.Da)}N.prototype.o.call(this)};var ij=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function jj(a){a=a||"";if(window.spf){var b=a.match(ij);spf.style.load(a,b?b[1]:"",void 0)}else kj(a)}
function kj(a){var b=lj(a),c=document.getElementById(b),d=c&&Ne(c,"loaded");d||c&&!d||(c=mj(a,b,function(){Ne(c,"loaded")||(Le(c),Xe(b),U(Sa(Ye,b),0))}))}
function mj(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=Kc(a);d.rel="stylesheet";d.href=ub(a).toString();(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function lj(a){var b=Gc(document,"A");Rb(b,new I(a,Eb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+Ub(a)}
;function nj(a,b,c,d){N.call(this);var e=this;this.m=this.aa=a;this.X=b;this.u=!1;this.api={};this.Y=this.F=null;this.G=new P;Rc(this,Sa(Sc,this.G));this.j={};this.U=this.Z=this.h=this.fa=this.f=null;this.L=!1;this.l=this.C=null;this.ba={};this.Aa=["onReady"];this.ea=null;this.oa=NaN;this.V={};this.i=d;oj(this);this.ca("WATCH_LATER_VIDEO_ADDED",this.Ta.bind(this));this.ca("WATCH_LATER_VIDEO_REMOVED",this.Ua.bind(this));this.ca("onAdAnnounce",this.Ca.bind(this));this.Ba=new hj(this);Rc(this,Sa(Sc,this.Ba));
this.W=0;c?this.W=U(function(){e.loadNewVideoConfig(c)},0):d&&(pj(this),qj(this))}
v(nj,N);n=nj.prototype;n.getId=function(){return this.X};
n.loadNewVideoConfig=function(a){if(!this.g){this.W&&(Pe(this.W),this.W=0);a instanceof gj||(a=new gj(a));this.fa=a;this.f=a.clone();pj(this);this.Z||(this.Z=rj(this,this.f.args.jsapicallback||"onYouTubePlayerReady"));this.f.args.jsapicallback=null;if(a=this.f.attrs.width)this.m.style.width=Xc(Number(a)||a);if(a=this.f.attrs.height)this.m.style.height=Xc(Number(a)||a);qj(this);this.u&&sj(this)}};
function pj(a){var b;a.i?b=a.i.rootElementId:b=a.f.attrs.id;a.h=b||a.h;"video-player"==a.h&&(a.h=a.X,a.f.attrs.id=a.X);a.m.id==a.h&&(a.h+="-player",a.f.attrs.id=a.h)}
n.Ha=function(){return this.fa};
function sj(a){a.f&&!a.f.loaded&&(a.f.loaded=!0,"0"!=a.f.args.autoplay?a.api.loadVideoByPlayerVars(a.f.args):a.api.cueVideoByPlayerVars(a.f.args))}
function tj(a){var b=!0,c=uj(a);c&&a.f&&(a=vj(a),b=Ne(c,"version")===a);return b&&!!B("yt.player.Application.create")}
function qj(a){if(!a.g&&!a.L){var b=tj(a);if(b&&"html5"==(uj(a)?"html5":null))a.U="html5",a.u||wj(a);else if(xj(a),a.U="html5",b&&a.l)a.aa.appendChild(a.l),wj(a);else{a.f&&(a.f.loaded=!0);var c=!1;a.C=function(){c=!0;var d=yj(a,"player_bootstrap_method")?B("yt.player.Application.createAlternate")||B("yt.player.Application.create"):B("yt.player.Application.create");var e=a.f?a.f.clone():void 0;d(a.aa,e,a.i);wj(a)};
a.L=!0;b?a.C():(bf(vj(a),a.C),(b=a.i?a.i.cssUrl:a.f.assets.css)&&jj(b),zj(a)&&!c&&z("yt.player.Application.create",null,void 0))}}}
function uj(a){var b=Cc(a.h);!b&&a.m&&a.m.querySelector&&(b=a.m.querySelector("#"+a.h));return b}
function wj(a){if(!a.g){var b=uj(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);c?(a.L=!1,!yj(a,"html5_remove_not_servable_check_killswitch")&&b.isNotServable&&a.f&&b.isNotServable(a.f.args.video_id)||Aj(a)):a.oa=U(function(){wj(a)},50)}}
function Aj(a){oj(a);a.u=!0;var b=uj(a);b.addEventListener&&(a.F=Bj(a,b,"addEventListener"));b.removeEventListener&&(a.Y=Bj(a,b,"removeEventListener"));var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=0;d<c.length;d++){var e=c[d];a.api[e]||(a.api[e]=Bj(a,b,e))}for(var f in a.j)a.F(f,a.j[f]);sj(a);a.Z&&a.Z(a.api);a.G.N("onReady",a.api)}
function Bj(a,b,c){var d=b[c];return function(){try{return a.ea=null,d.apply(b,arguments)}catch(e){"sendAbandonmentPing"!=c&&(e.params=c,a.ea=e,Fe(e))}}}
function oj(a){a.u=!1;if(a.Y)for(var b in a.j)a.Y(b,a.j[b]);for(var c in a.V)Pe(parseInt(c,10));a.V={};a.F=null;a.Y=null;for(var d in a.api)a.api[d]=null;a.api.addEventListener=a.ca.bind(a);a.api.removeEventListener=a.Ya.bind(a);a.api.destroy=a.dispose.bind(a);a.api.getLastError=a.Ia.bind(a);a.api.getPlayerType=a.Ja.bind(a);a.api.getCurrentVideoConfig=a.Ha.bind(a);a.api.loadNewVideoConfig=a.loadNewVideoConfig.bind(a);a.api.isReady=a.Sa.bind(a)}
n.Sa=function(){return this.u};
n.ca=function(a,b){var c=this,d=rj(this,b);if(d){if(!(0<=Ya(this.Aa,a)||this.j[a])){var e=Cj(this,a);this.F&&this.F(a,e)}this.G.subscribe(a,d);"onReady"==a&&this.u&&U(function(){d(c.api)},0)}};
n.Ya=function(a,b){if(!this.g){var c=rj(this,b);c&&ie(this.G,a,c)}};
function rj(a,b){var c=b;if("string"==typeof b){if(a.ba[b])return a.ba[b];c=function(){var d=B(b);d&&d.apply(y,arguments)};
a.ba[b]=c}return c?c:null}
function Cj(a,b){var c="ytPlayer"+b+a.X;a.j[b]=c;y[c]=function(d){var e=U(function(){if(!a.g){a.G.N(b,d);var f=a.V,g=String(e);g in f&&delete f[g]}},0);
kb(a.V,String(e))};
return c}
n.Ca=function(a){Xe("a11y-announce",a)};
n.Ta=function(a){Xe("WATCH_LATER_VIDEO_ADDED",a)};
n.Ua=function(a){Xe("WATCH_LATER_VIDEO_REMOVED",a)};
n.Ja=function(){return this.U||(uj(this)?"html5":null)};
n.Ia=function(){return this.ea};
function xj(a){a.cancel();oj(a);a.U=null;a.f&&(a.f.loaded=!1);var b=uj(a);b&&(tj(a)||!zj(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));for(a=a.aa;b=a.firstChild;)a.removeChild(b)}
n.cancel=function(){if(this.C){var a=vj(this);hf(a,this.C)}Pe(this.oa);this.L=!1};
n.o=function(){xj(this);if(this.l&&this.f&&this.l.destroy)try{this.l.destroy()}catch(b){S(b)}this.ba=null;for(var a in this.j)y[this.j[a]]=null;this.fa=this.f=this.api=null;delete this.aa;delete this.m;N.prototype.o.call(this)};
function zj(a){return a.f&&a.f.args&&a.f.args.fflags?-1!=a.f.args.fflags.indexOf("player_destroy_old_version=true"):!1}
function vj(a){return a.i?a.i.jsUrl:a.f.assets.js}
function yj(a,b){if(a.i)var c=a.i.serializedExperimentFlags;else a.f&&a.f.args&&(c=a.f.args.fflags);return"true"==ig(c||"")[b]}
;var Dj={},Ej="player_uid_"+(1E9*Math.random()>>>0);
function Fj(a,b,c){var d="player";c=void 0===c?!0:c;var e;"string"===typeof d?e=Cc(d):e=d;d=e;e=Ej+"_"+Na(d);var f=Dj[e];if(f&&c)return(b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags&&a.args.fflags.includes("web_player_remove_playerproxy=true"))?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new nj(d,e,a,b);Dj[e]=f;Xe("player-added",f.api);Rc(f,Sa(Gj,f));return f.api}
function Gj(a){delete Dj[a.getId()]}
;function Hj(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function Ij(a,b,c){"string"===typeof a&&(a={mediaContentUrl:a,startSeconds:b,suggestedQuality:c});a:{if((b=a.mediaContentUrl)&&(b=/\/([ve]|embed)\/([^#?]+)/.exec(b))&&b[2]){b=b[2];break a}b=null}a.videoId=b;return Jj(a)}
function Jj(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b=["endSeconds","startSeconds","mediaContentUrl","suggestedQuality","videoId"];c={};for(var d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}
function Kj(a,b,c,d){if(Ma(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function Lj(a){a=void 0===a?!1:a;N.call(this);this.f=new P(a);Rc(this,Sa(Sc,this.f))}
F(Lj,N);Lj.prototype.subscribe=function(a,b,c){return this.g?0:this.f.subscribe(a,b,c)};
Lj.prototype.j=function(a,b){this.g||this.f.N.apply(this.f,arguments)};function Mj(a,b,c){Lj.call(this);this.h=a;this.i=b;this.l=c}
v(Mj,Lj);function Nj(a,b,c){if(!a.g){var d=a.h;d.g||a.i!=d.f||(a={id:a.l,command:b},c&&(a.data=c),d.f.postMessage(Kd(a),d.i))}}
Mj.prototype.o=function(){this.i=this.h=null;Lj.prototype.o.call(this)};function Oj(a){N.call(this);this.f=a;this.f.subscribe("command",this.ya,this);this.h={};this.j=!1}
v(Oj,N);n=Oj.prototype;n.start=function(){this.j||this.g||(this.j=!0,Nj(this.f,"RECEIVING"))};
n.ya=function(a,b,c){if(this.j&&!this.g){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&(a=d.event,a in this.h||(c=C(this.ab,this,a),this.h[a]=c,this.addEventListener(a,c)));break;case "removeEventListener":"string"===typeof d.event&&Pj(this,d.event);break;default:this.i.isReady()&&this.i.isExternalMethodAvailable(a,c||null)&&(b=Qj(a,b||{}),c=this.i.handleExternalCall(a,b,c||null),(c=Rj(a,c))&&this.j&&!this.g&&Nj(this.f,a,c))}}};
n.ab=function(a,b){this.j&&!this.g&&Nj(this.f,a,this.ia(a,b))};
n.ia=function(a,b){if(null!=b)return{value:b}};
function Pj(a,b){b in a.h&&(a.removeEventListener(b,a.h[b]),delete a.h[b])}
n.o=function(){var a=this.f;a.g||ie(a.f,"command",this.ya,this);this.f=null;for(var b in this.h)Pj(this,b);N.prototype.o.call(this)};function Sj(a,b){Oj.call(this,b);this.i=a;this.start()}
v(Sj,Oj);Sj.prototype.addEventListener=function(a,b){this.i.addEventListener(a,b)};
Sj.prototype.removeEventListener=function(a,b){this.i.removeEventListener(a,b)};
function Qj(a,b){switch(a){case "loadVideoById":return b=Jj(b),[b];case "cueVideoById":return b=Jj(b),[b];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return b=Kj(b),[b];case "cuePlaylist":return b=Kj(b),[b];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Rj(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
Sj.prototype.ia=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return Oj.prototype.ia.call(this,a,b)};
Sj.prototype.o=function(){Oj.prototype.o.call(this);delete this.i};function Tj(a,b,c){N.call(this);var d=this;c=c||R("POST_MESSAGE_ORIGIN",void 0)||window.document.location.protocol+"//"+window.document.location.hostname;this.h=b||null;this.u="*";this.i=c;this.sessionId=null;this.channel="widget";this.C=!!a;this.m=function(e){a:if(!("*"!=d.i&&e.origin!=d.i||d.h&&e.source!=d.h||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.C&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.i=d.u=e.origin);d.h=e.source;d.sessionId=f.id;d.f&&(d.f(),d.f=null);break;case "command":d.j&&(!d.l||0<=Ya(d.l,f.func))&&d.j(f.func,f.args,e.origin)}}};
this.l=this.f=this.j=null;window.addEventListener("message",this.m)}
v(Tj,N);Tj.prototype.sendMessage=function(a,b){var c=b||this.h;if(c){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var d=JSON.stringify(a);c.postMessage(d,this.u)}catch(e){Fe(e)}}};
Tj.prototype.o=function(){window.removeEventListener("message",this.m);N.prototype.o.call(this)};function Uj(){var a=this.g=new Tj(!!R("WIDGET_ID_ENFORCE")),b=C(this.Xa,this);a.j=b;a.l=null;this.g.channel="widget";if(a=R("WIDGET_ID"))this.g.sessionId=a;this.i=[];this.l=!1;this.j={}}
n=Uj.prototype;n.Xa=function(a,b,c){"addEventListener"==a&&b?(a=b[0],this.j[a]||"onReady"==a||(this.addEventListener(a,Vj(this,a)),this.j[a]=!0)):this.ua(a,b,c)};
n.ua=function(){};
function Vj(a,b){return C(function(c){this.sendMessage(b,c)},a)}
n.addEventListener=function(){};
n.Ga=function(){this.l=!0;this.sendMessage("initialDelivery",this.ja());this.sendMessage("onReady");H(this.i,this.za,this);this.i=[]};
n.ja=function(){return null};
function Wj(a,b){a.sendMessage("infoDelivery",b)}
n.za=function(a){this.l?this.g.sendMessage(a):this.i.push(a)};
n.sendMessage=function(a,b){this.za({event:a,info:void 0==b?null:b})};
n.dispose=function(){this.g=null};function Xj(a){Uj.call(this);this.f=a;this.h=[];this.addEventListener("onReady",C(this.Va,this));this.addEventListener("onVideoProgress",C(this.fb,this));this.addEventListener("onVolumeChange",C(this.gb,this));this.addEventListener("onApiChange",C(this.Za,this));this.addEventListener("onPlaybackQualityChange",C(this.bb,this));this.addEventListener("onPlaybackRateChange",C(this.cb,this));this.addEventListener("onStateChange",C(this.eb,this));this.addEventListener("onWebglSettingsChanged",C(this.hb,
this))}
v(Xj,Uj);n=Xj.prototype;n.ua=function(a,b,c){if(this.f.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&Hj(a)){var d=b;if(Ma(d[0])&&!Array.isArray(d[0]))d=d[0];else{var e={};switch(a){case "loadVideoById":case "cueVideoById":e=Jj.apply(window,d);break;case "loadVideoByUrl":case "cueVideoByUrl":e=Ij.apply(window,d);break;case "loadPlaylist":case "cuePlaylist":e=Kj.apply(window,d)}d=e}b.length=1;b[0]=d}this.f.handleExternalCall(a,b,c);Hj(a)&&Wj(this,this.ja())}};
n.Va=function(){var a=C(this.Ga,this);this.g.f=a};
n.addEventListener=function(a,b){this.h.push({eventType:a,listener:b});this.f.addEventListener(a,b)};
n.ja=function(){if(!this.f)return null;var a=this.f.getApiInterface();cb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.f[e]();b[f]=g}catch(h){}}}b.videoData=this.f.getVideoData();b.currentTimeLastUpdated_=E()/1E3;return b};
n.eb=function(a){a={playerState:a,currentTime:this.f.getCurrentTime(),duration:this.f.getDuration(),videoData:this.f.getVideoData(),videoStartBytes:0,videoBytesTotal:this.f.getVideoBytesTotal(),videoLoadedFraction:this.f.getVideoLoadedFraction(),playbackQuality:this.f.getPlaybackQuality(),availableQualityLevels:this.f.getAvailableQualityLevels(),currentTimeLastUpdated_:E()/1E3,playbackRate:this.f.getPlaybackRate(),mediaReferenceTime:this.f.getMediaReferenceTime()};this.f.getVideoUrl&&(a.videoUrl=
this.f.getVideoUrl());this.f.getVideoContentRect&&(a.videoContentRect=this.f.getVideoContentRect());this.f.getProgressState&&(a.progressState=this.f.getProgressState());this.f.getPlaylist&&(a.playlist=this.f.getPlaylist());this.f.getPlaylistIndex&&(a.playlistIndex=this.f.getPlaylistIndex());this.f.getStoryboardFormat&&(a.storyboardFormat=this.f.getStoryboardFormat());Wj(this,a)};
n.bb=function(a){Wj(this,{playbackQuality:a})};
n.cb=function(a){Wj(this,{playbackRate:a})};
n.Za=function(){for(var a=this.f.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.f.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],l=this.f.getOption(e,k);b[e][k]=l}}this.sendMessage("apiInfoDelivery",b)};
n.gb=function(){Wj(this,{muted:this.f.isMuted(),volume:this.f.getVolume()})};
n.fb=function(a){a={currentTime:a,videoBytesLoaded:this.f.getVideoBytesLoaded(),videoLoadedFraction:this.f.getVideoLoadedFraction(),currentTimeLastUpdated_:E()/1E3,playbackRate:this.f.getPlaybackRate(),mediaReferenceTime:this.f.getMediaReferenceTime()};this.f.getProgressState&&(a.progressState=this.f.getProgressState());Wj(this,a)};
n.hb=function(){var a={sphericalProperties:this.f.getSphericalProperties()};Wj(this,a)};
n.dispose=function(){Uj.prototype.dispose.call(this);for(var a=0;a<this.h.length;a++){var b=this.h[a];this.f.removeEventListener(b.eventType,b.listener)}this.h=[]};function Yj(a,b,c){N.call(this);this.f=a;this.i=c;this.j=Af(window,"message",C(this.l,this));this.h=new Mj(this,a,b);Rc(this,Sa(Sc,this.h))}
v(Yj,N);Yj.prototype.l=function(a){var b;if(b=!this.g)if(b=a.origin==this.i)a:{b=this.f;do{b:{var c=a.source;do{if(c==b){c=!0;break b}if(c==c.parent)break;c=c.parent}while(null!=c);c=!1}if(c){b=!0;break a}b=b.opener}while(null!=b);b=!1}if(b&&(b=a.data,"string"===typeof b)){try{b=JSON.parse(b)}catch(d){return}b.command&&(c=this.h,c.g||c.j("command",b.command,b.data,a.origin))}};
Yj.prototype.o=function(){Bf(this.j);this.f=null;N.prototype.o.call(this)};function Zj(){var a=mb(ak),b;return Yd(new O(function(c,d){a.onSuccess=function(e){sg(e)?c(e):d(new bk("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new bk("Unknown request error","net.unknown",e))};
a.S=function(e){d(new bk("Request timed out","net.timeout",e))};
b=Bg("//googleads.g.doubleclick.net/pagead/id",a)}),function(c){c instanceof Zd&&b.abort();
return Wd(c)})}
function bk(a,b){G.call(this,a+", errorCode="+b);this.errorCode=b;this.name="PromiseAjaxError"}
v(bk,G);function ck(){this.g=0;this.f=null}
ck.prototype.then=function(a,b,c){return 1===this.g&&a?(a=a.call(c,this.f),Qd(a)?a:dk(a)):2===this.g&&b?(a=b.call(c,this.f),Qd(a)?a:ek(a)):this};
ck.prototype.getValue=function(){return this.f};
ck.prototype.$goog_Thenable=!0;function ek(a){var b=new ck;a=void 0===a?null:a;b.g=2;b.f=void 0===a?null:a;return b}
function dk(a){var b=new ck;a=void 0===a?null:a;b.g=1;b.f=void 0===a?null:a;return b}
;function fk(a){G.call(this,a.message||a.description||a.name);this.isMissing=a instanceof gk;this.isTimeout=a instanceof bk&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof Zd}
v(fk,G);fk.prototype.name="BiscottiError";function gk(){G.call(this,"Biscotti ID is missing from server")}
v(gk,G);gk.prototype.name="BiscottiMissingError";var ak={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},hk=null;
function gg(){if(T("disable_biscotti_fetch_on_html5_clients"))return Wd(Error("Fetching biscotti ID is disabled."));if(T("condition_biscotti_fetch_on_consent_cookie_html5_clients")&&!yc.get("CONSENT","").startsWith("YES+"))return Wd(Error("User has not consented - not fetching biscotti id."));if("1"===gb(Be(),"args","privembed"))return Wd(Error("Biscotti ID is not available in private embed mode"));hk||(hk=Yd(Zj().then(ik),function(a){return jk(2,a)}));
return hk}
function ik(a){a=a.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new gk;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new gk;a=a.id;hg(a);hk=dk(a);kk(18E5,2);return a}
function jk(a,b){var c=new fk(b);hg("");hk=ek(c);0<a&&kk(12E4,a-1);throw c;}
function kk(a,b){U(function(){Yd(Zj().then(ik,function(c){return jk(b,c)}),Ha)},a)}
function lk(){try{var a=B("yt.ads.biscotti.getId_");return a?a():gg()}catch(b){return Wd(b)}}
;function mk(a){if("1"!==gb(Be(),"args","privembed")){a&&fg();try{lk().then(function(){},function(){}),U(mk,18E5)}catch(b){S(b)}}}
;var Y=B("ytglobal.prefsUserPrefsPrefs_")||{};z("ytglobal.prefsUserPrefsPrefs_",Y,void 0);function nk(){this.f=R("ALT_PREF_COOKIE_NAME","PREF");var a=yc.get(""+this.f,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(Y[d]=c.toString())}}}
n=nk.prototype;n.get=function(a,b){ok(a);pk(a);var c=void 0!==Y[a]?Y[a].toString():null;return null!=c?c:b?b:""};
n.set=function(a,b){ok(a);pk(a);if(null==b)throw Error("ExpectedNotNull");Y[a]=b.toString()};
n.remove=function(a){ok(a);pk(a);delete Y[a]};
n.save=function(){Ie(this.f,this.dump(),63072E3)};
n.clear=function(){for(var a in Y)delete Y[a]};
n.dump=function(){var a=[],b;for(b in Y)a.push(b+"="+encodeURIComponent(String(Y[b])));return a.join("&")};
function pk(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function ok(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function qk(a){a=void 0!==Y[a]?Y[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
Ia(nk);function rk(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];if(!sk(a)||c.some(function(e){return!sk(e)}))throw Error("Only objects may be merged.");
c=u(c);for(d=c.next();!d.done;d=c.next())tk(a,d.value);return a}
function tk(a,b){for(var c in b)if(sk(b[c])){if(c in a&&!sk(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});tk(a[c],b[c])}else if(uk(b[c])){if(c in a&&!uk(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);vk(a[c],b[c])}else a[c]=b[c];return a}
function vk(a,b){for(var c=u(b),d=c.next();!d.done;d=c.next())d=d.value,sk(d)?a.push(tk({},d)):uk(d)?a.push(vk([],d)):a.push(d);return a}
function sk(a){return"object"===typeof a&&!Array.isArray(a)}
function uk(a){return"object"===typeof a&&Array.isArray(a)}
;var wk={},xk=0;
function yk(a,b,c,d,e){e=void 0===e?"":e;if(a)if(c&&!Ug("cobalt")){if(a){a instanceof I||(a="object"==typeof a&&a.O?a.M():String(a),Ib.test(a)?a=new I(a,Eb):(a=String(a),a=a.replace(/(%0A|%0D)/g,""),a=(b=a.match(Hb))&&Gb.test(b[1])?new I(a,Eb):null));a=Fb(a||Kb);if("about:invalid#zClosurez"===a||a.startsWith("data"))a="";else{if(!(a instanceof Ob)){b="object"==typeof a;var f=null;b&&a.ka&&(f=a.ha());a=Qb(wb(b&&a.O?a.M():String(a)),f)}a instanceof Ob&&a.constructor===Ob?a=a.f:(Ja(a),a="type_error:SafeHtml");
a=encodeURIComponent(String(Kd(a.toString())))}/^[\s\xa0]*$/.test(a)||(a=Fc("IFRAME",{src:'javascript:"<body><img src=\\""+'+a+'+"\\"></body>"',style:"display:none"}),(9==a.nodeType?a:a.ownerDocument||a.document).body.appendChild(a))}}else if(e)Cg(a,b,"POST",e,d);else if(R("USE_NET_AJAX_FOR_PING_TRANSPORT",!1)||d)Cg(a,b,"GET","",d);else{b:{try{var g=new Va({url:a});if(g.h&&g.g||g.i){var h=Xb(a.match(Vb)[5]||null),k;if(!(k=!h||!h.endsWith("/aclk"))){var l=a.search(ac);d:{for(c=0;0<=(c=a.indexOf("ri",
c))&&c<l;){var m=a.charCodeAt(c-1);if(38==m||63==m){var p=a.charCodeAt(c+2);if(!p||61==p||38==p||35==p){var t=c;break d}}c+=3}t=-1}if(0>t)var q=null;else{var A=a.indexOf("&",t);if(0>A||A>l)A=l;t+=3;q=decodeURIComponent(a.substr(t,A-t).replace(/\+/g," "))}k="1"!==q}f=!k;break b}}catch(D){}f=!1}f?zk(a)?(b&&b(),f=!0):f=!1:f=!1;f||Ak(a,b)}}
function zk(a,b){try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,void 0===b?"":b))return!0}catch(c){}return!1}
function Ak(a,b){var c=new Image,d=""+xk++;wk[d]=c;c.onload=c.onerror=function(){b&&wk[d]&&b();delete wk[d]};
c.src=a}
;function Bk(a,b){Pi.call(this,1,arguments)}
v(Bk,Pi);function Ck(a,b){Pi.call(this,1,arguments)}
v(Ck,Pi);var Dk=new Qi("aft-recorded",Bk),Ek=new Qi("timing-sent",Ck);var Fk=window;function Gk(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
var Hk=Fk.performance||Fk.mozPerformance||Fk.msPerformance||Fk.webkitPerformance||new Gk;var Ik=!1;C(Hk.clearResourceTimings||Hk.webkitClearResourceTimings||Hk.mozClearResourceTimings||Hk.msClearResourceTimings||Hk.oClearResourceTimings||Ha,Hk);function Jk(a){var b=Kk(a);if(b.aft)return b.aft;a=R((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=a.length,d=0;d<c;d++){var e=b[a[d]];if(e)return e}return NaN}
function Lk(a){var b;(b=B("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},Ta("ytcsi."+(a||"")+"data_",b));return b}
function Mk(a){a=Lk(a);a.info||(a.info={});return a.info}
function Kk(a){a=Lk(a);a.tick||(a.tick={});return a.tick}
function Nk(a){var b=Lk(a).nonce;b||(b=Bi(),Lk(a).nonce=b);return b}
function Ok(a){var b=Kk(a||""),c=Jk(a);c&&!Ik&&(Vi(Dk,new Bk(Math.round(c-b._start),a)),Ik=!0)}
;function Pk(){var a=B("ytcsi.debug");a||(a=[],z("ytcsi.debug",a,void 0),z("ytcsi.reference",{},void 0));return a}
function Qk(a){a=a||"";var b=B("ytcsi.reference");b||(Pk(),b=B("ytcsi.reference"));if(b[a])return b[a];var c=Pk(),d={timerName:a,info:{},tick:{},span:{}};c.push(d);return b[a]=d}
;var Rk=y.ytLoggingLatencyUsageStats_||{};z("ytLoggingLatencyUsageStats_",Rk,void 0);function Sk(){this.f=0}
function Tk(){Sk.f||(Sk.f=new Sk);return Sk.f}
Sk.prototype.tick=function(a,b,c){Uk(this,"tick_"+a+"_"+b)||ki("latencyActionTicked",{tickName:a,clientActionNonce:b},{timestamp:c})};
Sk.prototype.info=function(a,b){var c=Object.keys(a).join("");Uk(this,"info_"+c+"_"+b)||(c=Object.assign({},a),c.clientActionNonce=b,ki("latencyActionInfo",c))};
Sk.prototype.span=function(a,b){var c=Object.keys(a).join("");Uk(this,"span_"+c+"_"+b)||(a.clientActionNonce=b,ki("latencyActionSpan",a))};
function Uk(a,b){Rk[b]=Rk[b]||{count:0};var c=Rk[b];c.count++;c.time=W();a.f||(a.f=kf(function(){var d=W(),e;for(e in Rk)Rk[e]&&6E4<d-Rk[e].time&&delete Rk[e];a&&(a.f=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new ii("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||si(c)),!0):!1}
;var Z={},Vk=(Z.ad_allowed="adTypesAllowed",Z.yt_abt="adBreakType",Z.ad_cpn="adClientPlaybackNonce",Z.ad_docid="adVideoId",Z.yt_ad_an="adNetworks",Z.ad_at="adType",Z.aida="appInstallDataAgeMs",Z.browse_id="browseId",Z.p="httpProtocol",Z.t="transportProtocol",Z.cpn="clientPlaybackNonce",Z.ccs="creatorInfo.creatorCanaryState",Z.cseg="creatorInfo.creatorSegment",Z.csn="clientScreenNonce",Z.docid="videoId",Z.GetHome_rid="requestIds",Z.GetSearch_rid="requestIds",Z.GetPlayer_rid="requestIds",Z.GetWatchNext_rid=
"requestIds",Z.GetBrowse_rid="requestIds",Z.GetLibrary_rid="requestIds",Z.is_continuation="isContinuation",Z.is_nav="isNavigation",Z.b_p="kabukiInfo.browseParams",Z.is_prefetch="kabukiInfo.isPrefetch",Z.is_secondary_nav="kabukiInfo.isSecondaryNav",Z.prev_browse_id="kabukiInfo.prevBrowseId",Z.query_source="kabukiInfo.querySource",Z.voz_type="kabukiInfo.vozType",Z.yt_lt="loadType",Z.mver="creatorInfo.measurementVersion",Z.yt_ad="isMonetized",Z.nr="webInfo.navigationReason",Z.nrsu="navigationRequestedSameUrl",
Z.ncnp="webInfo.nonPreloadedNodeCount",Z.pnt="performanceNavigationTiming",Z.prt="playbackRequiresTap",Z.plt="playerInfo.playbackType",Z.pis="playerInfo.playerInitializedState",Z.paused="playerInfo.isPausedOnLoad",Z.yt_pt="playerType",Z.fmt="playerInfo.itag",Z.yt_pl="watchInfo.isPlaylist",Z.yt_pre="playerInfo.preloadType",Z.yt_ad_pr="prerollAllowed",Z.pa="previousAction",Z.yt_red="isRedSubscriber",Z.rce="mwebInfo.responseContentEncoding",Z.scrh="screenHeight",Z.scrw="screenWidth",Z.st="serverTimeMs",
Z.ssdm="shellStartupDurationMs",Z.aq="tvInfo.appQuality",Z.br_trs="tvInfo.bedrockTriggerState",Z.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",Z.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",Z.label="tvInfo.label",Z.is_mdx="tvInfo.isMdx",Z.preloaded="tvInfo.isPreloaded",Z.upg_player_vis="playerInfo.visibilityState",Z.query="unpluggedInfo.query",Z.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",Z.yt_vst="videoStreamType",Z.vph="viewportHeight",Z.vpw="viewportWidth",Z.yt_vis="isVisible",
Z.rcl="mwebInfo.responseContentLength",Z.GetSettings_rid="requestIds",Z.GetTrending_rid="requestIds",Z.GetMusicSearchSuggestions_rid="requestIds",Z.REQUEST_ID="requestIds",Z),Wk="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),
Xk={},Yk=(Xk.ccs="CANARY_STATE_",Xk.mver="MEASUREMENT_VERSION_",Xk.pis="PLAYER_INITIALIZED_STATE_",Xk.yt_pt="LATENCY_PLAYER_",Xk.pa="LATENCY_ACTION_",Xk.yt_vst="VIDEO_STREAM_TYPE_",Xk),Zk="all_vc ap c cver cbrand cmodel cplatform ctheme ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function $k(a){return!!R("FORCE_CSI_ON_GEL",!1)||T("csi_on_gel")||!!Lk(a).useGel}
function al(a){a=Lk(a);if(!("gel"in a))a.gel={gelTicks:{},gelInfos:{}};else if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}return a.gel}
;function bl(a,b,c){if(null!==b)if(Mk(c)[a]=b,$k(c)){var d=b;b=al(c);if(b.gelInfos)b.gelInfos["info_"+a]=!0;else{var e={};b.gelInfos=(e["info_"+a]=!0,e)}if(a.match("_rid")){var f=a.split("_rid")[0];a="REQUEST_ID"}if(a in Vk){b=Vk[a];0<=Ya(Wk,b)&&(d=!!d);a in Yk&&"string"===typeof d&&(d=Yk[a]+d.toUpperCase());a=d;d=b.split(".");for(var g=e={},h=0;h<d.length-1;h++){var k=d[h];g[k]={};g=g[k]}g[d[d.length-1]]="requestIds"===b?[{id:a,endpoint:f}]:a;f=rk({},e)}else 0<=Ya(Zk,a)||si(new ii("Unknown label logged with GEL CSI",
a)),f=void 0;f&&$k(c)&&(b=Qk(c||""),rk(b.info,f),b=al(c),"gelInfos"in b||(b.gelInfos={}),rk(b.gelInfos,f),c=Nk(c),Tk().info(f,c))}else Qk(c||"").info[a]=b}
function cl(a,b,c){var d=Kk(c);if(T("use_first_tick")&&dl(a,c))return d[a];if(!b&&"_"!==a[0]){var e=a;Hk.mark&&(0==e.lastIndexOf("mark_",0)||(e="mark_"+e),c&&(e+=" ("+c+")"),Hk.mark(e))}e=b||W();d[a]=e;e=al(c);e.gelTicks&&(e.gelTicks["tick_"+a]=!0);c||b||W();if($k(c)){Qk(c||"").tick[a]=b||W();e=Nk(c);if("_start"===a){var f=Tk();Uk(f,"baseline_"+e)||ki("latencyActionBaselined",{clientActionNonce:e},{timestamp:b})}else Tk().tick(a,e,b);Ok(c);e=!0}else e=!1;if(!e){if(!B("yt.timing."+(c||"")+"pingSent_")&&
(f=R((c||"")+"TIMING_ACTION",void 0),e=Kk(c),B("ytglobal.timing"+(c||"")+"ready_")&&f&&dl("_start")&&Jk(c)))if(Ok(c),c)el(c);else{f=!0;var g=R("TIMING_WAIT",[]);if(g.length)for(var h=0,k=g.length;h<k;++h)if(!(g[h]in e)){f=!1;break}f&&el(c)}Qk(c||"").tick[a]=b||W()}return d[a]}
function dl(a,b){var c=Kk(b);return a in c}
function el(a){if(!$k(a)){var b=Kk(a),c=Mk(a),d=b._start,e=R("CSI_SERVICE_NAME","youtube"),f={v:2,s:e,action:R((a||"")+"TIMING_ACTION",void 0)},g=c.srt;void 0!==b.srt&&delete c.srt;b.aft=Jk(a);var h=Kk(a),k=h.pbr,l=h.vc;h=h.pbs;k&&l&&h&&k<l&&l<h&&Mk(a).yt_pvis&&"youtube"===e&&(bl("yt_lt","hot_bg",a),e=b.vc,k=b.pbs,delete b.aft,c.aft=Math.round(k-e));for(var m in c)"_"!==m.charAt(0)&&(f[m]=c[m]);b.ps=W();m={};e=[];for(var p in b)"_"!==p.charAt(0)&&(k=Math.round(b[p]-d),m[p]=k,e.push(p+"."+k));f.rt=
e.join(",");b=!!c.ap;T("debug_csi_data")&&(c=B("yt.timing.csiData"),c||(c=[],Ta("yt.timing.csiData",c)),c.push({page:location.href,time:new Date,args:f}));c="";for(var t in f)f.hasOwnProperty(t)&&(c+="&"+t+"="+f[t]);f="/csi_204?"+c.substring(1);if(window.navigator&&window.navigator.sendBeacon&&b){var q=void 0===q?"":q;zk(f,q)||yk(f,void 0,void 0,void 0,q)}else yk(f);z("yt.timing."+(a||"")+"pingSent_",!0,void 0);Vi(Ek,new Ck(m.aft+(Number(g)||0),a))}}
var fl=window;fl.ytcsi&&(fl.ytcsi.info=bl,fl.ytcsi.tick=cl);var gl=null,hl=null,il=null,jl={};function kl(a){var b=a.id;a=a.ve_type;var c=Di++;a=new Ei({veType:a,veCounter:c,elementIndex:void 0,dataElement:void 0,youtubeData:void 0});jl[b]=a;b=Ki();c=Ii();b&&c&&ej(b,c,[a])}
function ll(){var a=gl.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function ml(a){var b=a.csn;a=a.root_ve_type;if(b&&a&&(Ni(b,a),a=Ii()))for(var c in jl){var d=jl[c];d&&ej(b,a,[d])}}
function nl(a){jl[a.id]=new Ei({trackingParams:a.tracking_params})}
function ol(a){var b=Ki(),c=jl[a.id];if(b&&c){a=T("use_default_events_client")?void 0:ji;var d="INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK";c={csn:b,ve:c.getAsJson(),gestureType:d};d={ga:Mi(b),T:b};"UNDEFINED_CSN"==b?fj("visualElementGestured",c,d):a?eg("visualElementGestured",c,a,d):ki("visualElementGestured",c,d)}}
function pl(a){a=a.ids;var b=Ki();if(b)for(var c=0;c<a.length;c++){var d=jl[a[c]];if(d){var e=b,f=T("use_default_events_client")?void 0:ji;d={csn:e,ve:d.getAsJson(),eventType:1};var g={ga:Mi(e),T:e};"UNDEFINED_CSN"==e?fj("visualElementShown",d,g):f?eg("visualElementShown",d,f,g):ki("visualElementShown",d,g)}}}
;z("yt.setConfig",Q,void 0);z("yt.config.set",Q,void 0);z("yt.setMsg",He,void 0);z("yt.msgs.set",He,void 0);z("yt.logging.errors.log",ti,void 0);
z("writeEmbed",function(){var a=R("PLAYER_CONFIG",void 0);if(!a){var b=R("PLAYER_VARS",void 0);b&&(a={args:b})}mk(!0);"gvn"==a.args.ps&&(document.body.style.backgroundColor="transparent");a.args.forced_experiments||(b=window.location.href,-1!=b.indexOf("?")?(b=(b||"").split("#")[0],b=b.split("?",2),b=kg(1<b.length?b[1]:b[0])):b={},b.forced_experiments&&(a.args.forced_experiments=b.forced_experiments));a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=R("POST_MESSAGE_ORIGIN");
window!=window.top&&c&&c!=document.URL&&(a.args.loaderUrl=c);gl=a=(c=R("WEB_PLAYER_CONTEXT_CONFIGS",void 0))&&"WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER"in c?Fj(a,c.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER,!1):Fj(a);a.addEventListener("onScreenChanged",ml);a.addEventListener("onLogClientVeCreated",kl);a.addEventListener("onLogServerVeCreated",nl);a.addEventListener("onLogVeClicked",ol);a.addEventListener("onLogVesShown",pl);a.addEventListener("onVideoDataChange",ll);c=R("POST_MESSAGE_ID","player");
R("ENABLE_JS_API")?il=new Xj(a):R("ENABLE_POST_API")&&"string"===typeof c&&"string"===typeof b&&(hl=new Yj(window.parent,c,b),il=new Sj(a,hl.h));rf()},void 0);
var ql=Ee(function(){cl("ol");var a=nk.getInstance(),b=!!((qk("f"+(Math.floor(119/31)+1))||0)&67108864),c=1<window.devicePixelRatio;if(document.body&&Id(document.body,"exp-invert-logo"))if(c&&!Id(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!Id(d,"inverted-hdpi")){var e=Gd(d);Hd(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&Id(document.body,"inverted-hdpi")&&Jd();b!=c&&(b="f"+(Math.floor(119/31)+1),d=qk(b)||0,d=c?d|67108864:
d&-67108865,0==d?delete Y[b]:(c=d.toString(16),Y[b]=c.toString()),a.save())}),rl=Ee(function(){var a=gl;
a&&a.sendAbandonmentPing&&a.sendAbandonmentPing();R("PL_ATT")&&xi.dispose();a=0;for(var b=pf.length;a<b;a++)of(pf[a]);pf.length=0;gf("//static.doubleclick.net/instream/ad_status.js");qf=!1;Q("DCLKSTAT",0);Tc(il,hl);if(a=gl)a.removeEventListener("onScreenChanged",ml),a.removeEventListener("onLogClientVeCreated",kl),a.removeEventListener("onLogServerVeCreated",nl),a.removeEventListener("onLogVeClicked",ol),a.removeEventListener("onLogVesShown",pl),a.removeEventListener("onVideoDataChange",ll),a.destroy();
jl={}});
window.addEventListener?(window.addEventListener("load",ql),window.addEventListener("unload",rl)):window.attachEvent&&(window.attachEvent("onload",ql),window.attachEvent("onunload",rl));Ta("yt.abuse.player.botguardInitialized",B("yt.abuse.player.botguardInitialized")||yi);Ta("yt.abuse.player.invokeBotguard",B("yt.abuse.player.invokeBotguard")||zi);Ta("yt.abuse.dclkstatus.checkDclkStatus",B("yt.abuse.dclkstatus.checkDclkStatus")||sf);
Ta("yt.player.exports.navigate",B("yt.player.exports.navigate")||Oi);Ta("yt.util.activity.init",B("yt.util.activity.init")||Ff);Ta("yt.util.activity.getTimeSinceActive",B("yt.util.activity.getTimeSinceActive")||If);Ta("yt.util.activity.setTimestamp",B("yt.util.activity.setTimestamp")||Gf);}).call(this);
