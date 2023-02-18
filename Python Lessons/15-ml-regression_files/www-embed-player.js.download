(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var l;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function da(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var ea=da(this);function p(a,b){if(b)a:{var c=ea;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
p("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
p("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=ea[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return fa(aa(this))}})}return a});
function fa(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function ha(a){return a.raw=a}
function r(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function ia(a){if(!(a instanceof Array)){a=r(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ka(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var la="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ka(d,e)&&(a[e]=d[e])}return a};
p("Object.assign",function(a){return a||la});
var ma="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},na=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ma(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),pa;
if("function"==typeof Object.setPrototypeOf)pa=Object.setPrototypeOf;else{var qa;a:{var ra={a:!0},ta={};try{ta.__proto__=ra;qa=ta.a;break a}catch(a){}qa=!1}pa=qa?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var ua=pa;
function v(a,b){a.prototype=ma(b.prototype);a.prototype.constructor=a;if(ua)ua(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.va=b.prototype}
function wa(){this.H=!1;this.l=null;this.i=void 0;this.h=1;this.m=this.s=0;this.A=this.j=null}
function xa(a){if(a.H)throw new TypeError("Generator is already running");a.H=!0}
wa.prototype.X=function(a){this.i=a};
function ya(a,b){a.j={od:b,yd:!0};a.h=a.s||a.m}
wa.prototype.return=function(a){this.j={return:a};this.h=this.m};
function w(a,b,c){a.h=c;return{value:b}}
wa.prototype.v=function(a){this.h=a};
function za(a,b,c){a.s=b;void 0!=c&&(a.m=c)}
function Aa(a,b){a.h=b;a.s=0}
function Ba(a){a.s=0;var b=a.j.od;a.j=null;return b}
function Ca(a){a.A=[a.j];a.s=0;a.m=0}
function Da(a){var b=a.A.splice(0)[0];(b=a.j=a.j||b)?b.yd?a.h=a.s||a.m:void 0!=b.v&&a.m<b.v?(a.h=b.v,a.j=null):a.h=a.m:a.h=0}
function Ea(a){this.h=new wa;this.i=a}
function Fa(a,b){xa(a.h);var c=a.h.l;if(c)return Ga(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ha(a)}
function Ga(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.H=!1,e;var f=e.value}catch(g){return a.h.l=null,ya(a.h,g),Ha(a)}a.h.l=null;d.call(a.h,f);return Ha(a)}
function Ha(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.H=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,ya(a.h,c)}a.h.H=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.yd)throw b.od;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ia(a){this.next=function(b){xa(a.h);a.h.l?b=Ga(a,a.h.l.next,b,a.h.X):(a.h.X(b),b=Ha(a));return b};
this.throw=function(b){xa(a.h);a.h.l?b=Ga(a,a.h.l["throw"],b,a.h.X):(ya(a.h,b),b=Ha(a));return b};
this.return=function(b){return Fa(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ja(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function x(a){return Ja(new Ia(new Ea(a)))}
function Ka(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
p("Reflect",function(a){return a?a:{}});
p("Reflect.construct",function(){return na});
p("Reflect.setPrototypeOf",function(a){return a?a:ua?function(b,c){try{return ua(b,c),!0}catch(d){return!1}}:null});
p("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.H=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.m()})}this.h.push(g)};
var e=ea.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.m=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(m){this.l(m)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(m){return function(n){k||(k=!0,m.call(h,n))}}
var h=this,k=!1;return{resolve:g(this.V),reject:g(this.m)}};
b.prototype.V=function(g){if(g===this)this.m(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.aa(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.R(g):this.s(g)}};
b.prototype.R=function(g){var h=void 0;try{h=g.then}catch(k){this.m(k);return}"function"==typeof h?this.ia(h,g):this.s(g)};
b.prototype.m=function(g){this.X(2,g)};
b.prototype.s=function(g){this.X(1,g)};
b.prototype.X=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.Z();this.A()};
b.prototype.Z=function(){var g=this;e(function(){if(g.L()){var h=ea.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.L=function(){if(this.H)return!1;var g=ea.CustomEvent,h=ea.Event,k=ea.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=ea.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.A=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.aa=function(g){var h=this.l();g.fc(h.resolve,h.reject)};
b.prototype.ia=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(m){k.reject(m)}};
b.prototype.then=function(g,h){function k(u,t){return"function"==typeof u?function(B){try{m(u(B))}catch(D){n(D)}}:t}
var m,n,q=new b(function(u,t){m=u;n=t});
this.fc(k(g,m),k(h,n));return q};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.fc=function(g,h){function k(){switch(m.h){case 1:g(m.j);break;case 2:h(m.j);break;default:throw Error("Unexpected state: "+m.h);}}
var m=this;null==this.i?f.i(k):this.i.push(k);this.H=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var m=r(g),n=m.next();!n.done;n=m.next())d(n.value).fc(h,k)})};
b.all=function(g){var h=r(g),k=h.next();return k.done?d([]):new b(function(m,n){function q(B){return function(D){u[B]=D;t--;0==t&&m(u)}}
var u=[],t=0;do u.push(void 0),t++,d(k.value).fc(q(u.length-1),n),k=h.next();while(!k.done)})};
return b});
p("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=r(k);for(var m;!(m=k.next()).done;)m=m.value,this.set(m[0],m[1])}}
function c(){}
function d(k){var m=typeof k;return"object"===m&&null!==k||"function"===m}
function e(k){if(!ka(k,g)){var m=new c;ba(k,g,{value:m})}}
function f(k){var m=Object[k];m&&(Object[k]=function(n){if(n instanceof c)return n;Object.isExtensible(n)&&e(n);return m(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),m=Object.seal({}),n=new a([[k,2],[m,3]]);if(2!=n.get(k)||3!=n.get(m))return!1;n.delete(k);n.set(m,4);return!n.has(k)&&4==n.get(m)}catch(q){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,m){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ka(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=m;return this};
b.prototype.get=function(k){return d(k)&&ka(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&ka(k,g)&&ka(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&ka(k,g)&&ka(k[g],this.h)?delete k[g][this.h]:!1};
return b});
p("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var m=h.h;return fa(function(){if(m){for(;m.head!=h.h;)m=m.previous;for(;m.next!=m.head;)return m=m.next,{done:!1,value:k(m)};m=null}return{done:!0,value:void 0}})}
function d(h,k){var m=k&&typeof k;"object"==m||"function"==m?f.has(k)?m=f.get(k):(m=""+ ++g,f.set(k,m)):m="p_"+k;var n=h.data_[m];if(n&&ka(h.data_,m))for(h=0;h<n.length;h++){var q=n[h];if(k!==k&&q.key!==q.key||k===q.key)return{id:m,list:n,index:h,entry:q}}return{id:m,list:n,index:-1,entry:void 0}}
function e(h){this.data_={};this.h=b();this.size=0;if(h){h=r(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(r([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var m=k.entries(),n=m.next();if(n.done||n.value[0]!=h||"s"!=n.value[1])return!1;n=m.next();return n.done||4!=n.value[0].x||"t"!=n.value[1]||!m.next().done?!1:!0}catch(q){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var m=d(this,h);m.list||(m.list=this.data_[m.id]=[]);m.entry?m.entry.value=k:(m.entry={next:this.h,previous:this.h.previous,head:this.h,key:h,value:k},m.list.push(m.entry),this.h.previous.next=m.entry,this.h.previous=m.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.h=this.h.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var m=this.entries(),n;!(n=m.next()).done;)n=n.value,h.call(k,n[1],n[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function La(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
p("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=La(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
p("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
p("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=La(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
p("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
p("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
p("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
p("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
function Ma(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
p("Array.prototype.entries",function(a){return a?a:function(){return Ma(this,function(b,c){return[b,c]})}});
p("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
p("Array.prototype.keys",function(a){return a?a:function(){return Ma(this,function(b){return b})}});
p("Array.prototype.values",function(a){return a?a:function(){return Ma(this,function(b,c){return c})}});
p("Array.prototype.fill",function(a){return a?a:function(b,c,d){var e=this.length||0;0>c&&(c=Math.max(0,e+c));if(null==d||d>e)d=e;d=Number(d);0>d&&(d=Math.max(0,e+d));for(c=Number(c||0);c<d;c++)this[c]=b;return this}});
function Na(a){return a?a:Array.prototype.fill}
p("Int8Array.prototype.fill",Na);p("Uint8Array.prototype.fill",Na);p("Uint8ClampedArray.prototype.fill",Na);p("Int16Array.prototype.fill",Na);p("Uint16Array.prototype.fill",Na);p("Int32Array.prototype.fill",Na);p("Uint32Array.prototype.fill",Na);p("Float32Array.prototype.fill",Na);p("Float64Array.prototype.fill",Na);p("Object.setPrototypeOf",function(a){return a||ua});
p("Set",function(a){function b(c){this.h=new Map;if(c){c=r(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(r([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
p("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ka(b,d)&&c.push([d,b[d]]);return c}});
p("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
p("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
p("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==La(this,b,"includes").indexOf(b,c||0)}});
p("globalThis",function(a){return a||ea});
p("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ka(b,d)&&c.push(b[d]);return c}});
var Oa=Oa||{},y=this||self;function z(a,b,c){a=a.split(".");c=c||y;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function A(a,b){a=a.split(".");b=b||y;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Pa(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Qa(a){var b=Pa(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Ra(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Sa(a){return Object.prototype.hasOwnProperty.call(a,Ta)&&a[Ta]||(a[Ta]=++Ua)}
var Ta="closure_uid_"+(1E9*Math.random()>>>0),Ua=0;function Va(a,b,c){return a.call.apply(a.bind,arguments)}
function Wa(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Xa(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Xa=Va:Xa=Wa;return Xa.apply(null,arguments)}
function Za(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function $a(a,b){function c(){}
c.prototype=b.prototype;a.va=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.It=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function ab(a){return a}
;function bb(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,bb);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
$a(bb,Error);bb.prototype.name="CustomError";function cb(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function db(){}
function eb(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var fb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},gb=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},hb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},ib=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},jb=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
gb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function kb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function lb(a,b){b=fb(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function mb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Qa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function nb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function ob(a){var b=pb,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function qb(a){for(var b in a)return!1;return!0}
function rb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function sb(a){return null!==a&&"privembed"in a?a.privembed:!1}
function tb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function ub(a){var b={},c;for(c in a)b[c]=a[c];return b}
function wb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);if(a instanceof Date)return new Date(a.getTime());var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=wb(a[c]);return b}
var xb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function yb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<xb.length;f++)c=xb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var zb;function Ab(){if(void 0===zb){var a=null,b=y.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:ab,createScript:ab,createScriptURL:ab})}catch(c){y.console&&y.console.error(c.message)}zb=a}else zb=a}return zb}
;function Bb(a,b){this.j=a===Cb&&b||""}
Bb.prototype.i=!0;Bb.prototype.h=function(){return this.j};
function Db(a){return new Bb(Cb,a)}
var Cb={};Db("");var Eb={};function Fb(a,b){this.j=b===Eb?a:"";this.i=!0}
Fb.prototype.toString=function(){return this.j.toString()};
Fb.prototype.h=function(){return this.j.toString()};function Gb(a,b){this.j=b===Hb?a:""}
Gb.prototype.toString=function(){return this.j+""};
Gb.prototype.i=!0;Gb.prototype.h=function(){return this.j.toString()};
function Ib(a){if(a instanceof Gb&&a.constructor===Gb)return a.j;Pa(a);return"type_error:TrustedResourceUrl"}
var Hb={};function Jb(a){var b=Ab();a=b?b.createScriptURL(a):a;return new Gb(a,Hb)}
;var Kb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function Lb(a,b){return a<b?-1:a>b?1:0}
;function Mb(a,b){this.j=b===Nb?a:""}
Mb.prototype.toString=function(){return this.j.toString()};
Mb.prototype.i=!0;Mb.prototype.h=function(){return this.j.toString()};
function Qb(a){if(a instanceof Mb&&a.constructor===Mb)return a.j;Pa(a);return"type_error:SafeUrl"}
var Rb;try{new URL("s://g"),Rb=!0}catch(a){Rb=!1}var Sb=Rb,Nb={},Tb=new Mb("about:invalid#zClosurez",Nb);function Ub(){var a=y.navigator;return a&&(a=a.userAgent)?a:""}
function C(a){return-1!=Ub().indexOf(a)}
;function Vb(){return C("Trident")||C("MSIE")}
function Wb(){return C("Firefox")||C("FxiOS")}
function Xb(){return C("Safari")&&!(Yb()||C("Coast")||C("Opera")||C("Edge")||C("Edg/")||C("OPR")||Wb()||C("Silk")||C("Android"))}
function Yb(){return(C("Chrome")||C("CriOS"))&&!C("Edge")||C("Silk")}
function Zb(){return C("Android")&&!(Yb()||Wb()||C("Opera")||C("Silk"))}
function $b(a){var b={};a.forEach(function(c){b[c[0]]=c[1]});
return function(c){return b[c.find(function(d){return d in b})]||""}}
function ac(a){var b=Ub();if("Internet Explorer"===a){if(Vb())if((a=/rv: *([\d\.]*)/.exec(b))&&a[1])b=a[1];else{a="";var c=/MSIE +([\d\.]+)/.exec(b);if(c&&c[1])if(b=/Trident\/(\d.\d)/.exec(b),"7.0"==c[1])if(b&&b[1])switch(b[1]){case "4.0":a="8.0";break;case "5.0":a="9.0";break;case "6.0":a="10.0";break;case "7.0":a="11.0"}else a="7.0";else a=c[1];b=a}else b="";return b}var d=RegExp("([A-Z][\\w ]+)/([^\\s]+)\\s*(?:\\((.*?)\\))?","g");c=[];for(var e;e=d.exec(b);)c.push([e[1],e[2],e[3]||void 0]);b=$b(c);
switch(a){case "Opera":if(C("Opera"))return b(["Version","Opera"]);if(C("OPR"))return b(["OPR"]);break;case "Microsoft Edge":if(C("Edge"))return b(["Edge"]);if(C("Edg/"))return b(["Edg"]);break;case "Chromium":if(Yb())return b(["Chrome","CriOS","HeadlessChrome"])}return"Firefox"===a&&Wb()||"Safari"===a&&Xb()||"Android Browser"===a&&Zb()||"Silk"===a&&C("Silk")?(b=c[2])&&b[1]||"":""}
function bc(a){a=ac(a);if(""===a)return NaN;a=a.split(".");return 0===a.length?NaN:Number(a[0])}
;var cc={};function dc(a){this.j=cc===cc?a:"";this.i=!0}
dc.prototype.h=function(){return this.j.toString()};
dc.prototype.toString=function(){return this.j.toString()};function ec(a,b){if(!(b instanceof Mb||b instanceof Mb)){b="object"==typeof b&&b.i?b.h():String(b);b:{var c=b;if(Sb){try{var d=new URL(c)}catch(e){c="https:";break b}c=d.protocol}else c:{d=document.createElement("a");try{d.href=c}catch(e){c=void 0;break c}c=d.protocol;c=":"===c||""===c?"https:":c}}"javascript:"!==c||(b="about:invalid#zClosurez");b=new Mb(b,Nb)}a.href=Qb(b)}
function fc(a,b){a.rel="stylesheet";a.href=Ib(b).toString();(b=gc('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function hc(){return gc("script[nonce]")}
var ic=/^[\w+/_-]+[=]{0,2}$/;function gc(a,b){b=(b||y).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&ic.test(a)?a:"":""}
;function jc(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var kc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function nc(a){return a?decodeURI(a):a}
function oc(a,b){return b.match(kc)[a]||null}
function pc(a){return nc(oc(3,a))}
function qc(a){var b=a.match(kc);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function rc(a,b){if(!b)return a;var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;return a[0]+(a[1]?"?"+a[1]:"")+a[2]}
function sc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)sc(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function tc(a,b){var c=[];for(b=b||0;b<a.length;b+=2)sc(a[b],a[b+1],c);return c.join("&")}
function uc(a){var b=[],c;for(c in a)sc(c,a[c],b);return b.join("&")}
function vc(a,b){var c=2==arguments.length?tc(arguments[1],0):tc(arguments,1);return rc(a,c)}
function wc(a,b){b=uc(b);return rc(a,b)}
function xc(a,b,c){c=null!=c?"="+encodeURIComponent(String(c)):"";return rc(a,b+c)}
function yc(a,b,c,d){for(var e=c.length;0<=(b=a.indexOf(c,b))&&b<d;){var f=a.charCodeAt(b-1);if(38==f||63==f)if(f=a.charCodeAt(b+e),!f||61==f||38==f||35==f)return b;b+=e+1}return-1}
var zc=/#|$/,Ac=/[?&]($|#)/;function Bc(a,b){for(var c=a.search(zc),d=0,e,f=[];0<=(e=yc(a,d,b,c));)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(Ac,"$1")}
;function Cc(a){y.setTimeout(function(){throw a;},0)}
;function Dc(){return C("iPhone")&&!C("iPod")&&!C("iPad")}
function Ec(){var a=Ub(),b="";C("Windows")?(b=/Windows (?:NT|Phone) ([0-9.]+)/,b=(a=b.exec(a))?a[1]:"0.0"):Dc()||C("iPad")||C("iPod")?(b=/(?:iPhone|iPod|iPad|CPU)\s+OS\s+(\S+)/,b=(a=b.exec(a))&&a[1].replace(/_/g,".")):C("Macintosh")?(b=/Mac OS X ([0-9_.]+)/,b=(a=b.exec(a))?a[1].replace(/_/g,"."):"10"):-1!=Ub().toLowerCase().indexOf("kaios")?(b=/(?:KaiOS)\/(\S+)/i,b=(a=b.exec(a))&&a[1]):C("Android")?(b=/Android\s+([^\);]+)(\)|;)/,b=(a=b.exec(a))&&a[1]):C("CrOS")&&(b=/(?:CrOS\s+(?:i686|x86_64)\s+([0-9.]+))/,
b=(a=b.exec(a))&&a[1]);a=0;b=Kb(String(b||"")).split(".");for(var c=Kb("12").split("."),d=Math.max(b.length,c.length),e=0;0==a&&e<d;e++){var f=b[e]||"",g=c[e]||"";do{f=/(\d*)(\D*)(.*)/.exec(f)||["","","",""];g=/(\d*)(\D*)(.*)/.exec(g)||["","","",""];if(0==f[0].length&&0==g[0].length)break;a=Lb(0==f[1].length?0:parseInt(f[1],10),0==g[1].length?0:parseInt(g[1],10))||Lb(0==f[2].length,0==g[2].length)||Lb(f[2],g[2]);f=f[3];g=g[3]}while(0==a)}}
;function Fc(a){Fc[" "](a);return a}
Fc[" "]=function(){};var Gc=C("Opera"),Hc=Vb(),Ic=C("Edge"),Jc=C("Gecko")&&!(-1!=Ub().toLowerCase().indexOf("webkit")&&!C("Edge"))&&!(C("Trident")||C("MSIE"))&&!C("Edge"),Kc=-1!=Ub().toLowerCase().indexOf("webkit")&&!C("Edge"),Lc=C("Android");function Pc(){var a=y.document;return a?a.documentMode:void 0}
var Qc;a:{var Rc="",Sc=function(){var a=Ub();if(Jc)return/rv:([^\);]+)(\)|;)/.exec(a);if(Ic)return/Edge\/([\d\.]+)/.exec(a);if(Hc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(Kc)return/WebKit\/(\S+)/.exec(a);if(Gc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
Sc&&(Rc=Sc?Sc[1]:"");if(Hc){var Tc=Pc();if(null!=Tc&&Tc>parseFloat(Rc)){Qc=String(Tc);break a}}Qc=Rc}var Uc=Qc,Vc;if(y.document&&Hc){var Wc=Pc();Vc=Wc?Wc:parseInt(Uc,10)||void 0}else Vc=void 0;var Xc=Vc;var Yc=Dc()||C("iPod"),Zc=C("iPad");Zb();Yb();var $c=Xb()&&!(Dc()||C("iPad")||C("iPod"));var ad={},bd=null;function cd(a,b){Qa(a);void 0===b&&(b=0);dd();b=ad[b];for(var c=Array(Math.floor(a.length/3)),d=b[64]||"",e=0,f=0;e<a.length-2;e+=3){var g=a[e],h=a[e+1],k=a[e+2],m=b[g>>2];g=b[(g&3)<<4|h>>4];h=b[(h&15)<<2|k>>6];k=b[k&63];c[f++]=""+m+g+h+k}m=0;k=d;switch(a.length-e){case 2:m=a[e+1],k=b[(m&15)<<2]||d;case 1:a=a[e],c[f]=""+b[a>>2]+b[(a&3)<<4|m>>4]+k+d}return c.join("")}
function ed(a){var b=a.length,c=3*b/4;c%3?c=Math.floor(c):-1!="=.".indexOf(a[b-1])&&(c=-1!="=.".indexOf(a[b-2])?c-2:c-1);var d=new Uint8Array(c),e=0;fd(a,function(f){d[e++]=f});
return e!==c?d.subarray(0,e):d}
function fd(a,b){function c(k){for(;d<a.length;){var m=a.charAt(d++),n=bd[m];if(null!=n)return n;if(!/^[\s\xa0]*$/.test(m))throw Error("Unknown base64 encoding at char: "+m);}return k}
dd();for(var d=0;;){var e=c(-1),f=c(0),g=c(64),h=c(64);if(64===h&&-1===e)break;b(e<<2|f>>4);64!=g&&(b(f<<4&240|g>>2),64!=h&&b(g<<6&192|h))}}
function dd(){if(!bd){bd={};for(var a="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),b=["+/=","+/","-_=","-_.","-_"],c=0;5>c;c++){var d=a.concat(b[c].split(""));ad[c]=d;for(var e=0;e<d.length;e++){var f=d[e];void 0===bd[f]&&(bd[f]=e)}}}}
;var gd="undefined"!==typeof Uint8Array,hd=!Hc&&"function"===typeof y.btoa;function id(a){if(!hd)return cd(a);for(var b="";10240<a.length;)b+=String.fromCharCode.apply(null,a.subarray(0,10240)),a=a.subarray(10240);b+=String.fromCharCode.apply(null,a);return btoa(b)}
var jd=RegExp("[-_.]","g");function kd(a){switch(a){case "-":return"+";case "_":return"/";case ".":return"=";default:return""}}
function ld(a){return gd&&null!=a&&a instanceof Uint8Array}
var md={};var nd;function od(a){if(a!==md)throw Error("illegal external caller");}
function pd(a,b){od(b);this.Aa=a;if(null!=a&&0===a.length)throw Error("ByteString should be constructed with non-empty values");}
pd.prototype.Nb=function(){return null==this.Aa};
pd.prototype.sizeBytes=function(){od(md);var a=this.Aa;if(null!=a&&!ld(a))if("string"===typeof a)if(hd){jd.test(a)&&(a=a.replace(jd,kd));a=atob(a);for(var b=new Uint8Array(a.length),c=0;c<a.length;c++)b[c]=a.charCodeAt(c);a=b}else a=ed(a);else Pa(a),a=null;return(a=null==a?a:this.Aa=a)?a.length:0};var qd="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol():void 0;function rd(a,b){if(qd)return a[qd]|=b;if(void 0!==a.Ea)return a.Ea|=b;Object.defineProperties(a,{Ea:{value:b,configurable:!0,writable:!0,enumerable:!1}});return b}
function sd(a,b){var c=E(a);(c&b)!==b&&(Object.isFrozen(a)&&(a=Array.prototype.slice.call(a)),td(a,c|b));return a}
function ud(a,b){qd?a[qd]&&(a[qd]&=~b):void 0!==a.Ea&&(a.Ea&=~b)}
function E(a){var b;qd?b=a[qd]:b=a.Ea;return null==b?0:b}
function td(a,b){qd?a[qd]=b:void 0!==a.Ea?a.Ea=b:Object.defineProperties(a,{Ea:{value:b,configurable:!0,writable:!0,enumerable:!1}})}
function vd(a){rd(a,1);return a}
function wd(a,b){td(b,(a|0)&-51)}
function xd(a,b){td(b,(a|18)&-41)}
;var yd={};function zd(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var Ad,Bd,Cd=[];td(Cd,23);Bd=Object.freeze(Cd);function Dd(a){if(E(a.P)&2)throw Error();}
function Ed(a){var b=a.length;(b=b?a[b-1]:void 0)&&zd(b)?b.g=1:(b={},a.push((b.g=1,b)))}
;function Fd(a){if(null!=a&&"number"!==typeof a)throw Error("Value of float/double field must be a number|null|undefined, found "+typeof a+": "+a);return a}
function Gd(a){return a.displayName||a.name||"unknown type name"}
function Hd(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Gd(b)+" but got "+(a&&Gd(a.constructor)));return a}
function Id(a,b){var c=E(a),d=c;0===d&&(d|=b&16);d|=b&2;d!==c&&td(a,d)}
;function Nd(a){var b=a.j+a.gb;return a.xa||(a.xa=a.P[b]={})}
function Od(a,b,c){return-1===b?null:b>=a.j?a.xa?a.xa[b]:void 0:c&&a.xa&&(c=a.xa[b],null!=c)?c:a.P[b+a.gb]}
function G(a,b,c,d){Dd(a);return Pd(a,b,c,d)}
function Pd(a,b,c,d){a.m&&(a.m=void 0);if(b>=a.j||d)return Nd(a)[b]=c,a;a.P[b+a.gb]=c;(c=a.xa)&&b in c&&delete c[b];return a}
function Qd(a,b,c,d,e){var f=Od(a,b,d);Array.isArray(f)||(f=Bd);var g=E(f);g&1||vd(f);if(e)g&2||rd(f,18),c&1||Object.freeze(f);else{e=!(c&2);var h=g&2;c&1||!h?e&&g&16&&!h&&ud(f,16):(f=vd(Array.prototype.slice.call(f)),Pd(a,b,f,d))}return f}
function Rd(a,b,c,d){Dd(a);(c=Sd(a,c))&&c!==b&&null!=d&&Pd(a,c,void 0,!1);return Pd(a,b,d)}
function Sd(a,b){for(var c=0,d=0;d<b.length;d++){var e=b[d];null!=Od(a,e)&&(0!==c&&Pd(a,c,void 0,!1),c=e)}return c}
function Td(a,b,c,d){d=void 0===d?!1:d;var e=d;var f=Od(a,c,e);var g=E(a.P),h=!1;null==f||"object"!==typeof f||(h=Array.isArray(f))||f.Lc!==yd?h?(Id(f,g),b=new b(f)):b=void 0:b=f;b!==f&&null!=b&&Pd(a,c,b,e);e=b;if(null==e)return e;E(a.P)&2||(f=Ud(e),f!==e&&(e=f,Pd(a,c,e,d)));return e}
function Vd(a,b,c,d,e){var f=!!(e&2);a.i||(a.i={});var g=a.i[c],h=Qd(a,c,3,void 0,f);if(!g){var k=h;g=[];f=!!(e&2);h=!!(E(k)&2);var m=k;!f&&h&&(k=Array.prototype.slice.call(k));var n=e|(h?2:0);e=h;for(var q=0;q<k.length;q++){var u=k[q];var t=b;Array.isArray(u)?(Id(u,n),u=new t(u)):u=void 0;void 0!==u&&(e=e||!!(2&E(u.P)),g.push(u))}a.i[c]=g;b=k;e=!e;n=E(b);k=n|33;k=e?k|8:k&-9;n!=k&&(Object.isFrozen(b)&&(b=Array.prototype.slice.call(b)),td(b,k));k=b;m!==k&&Pd(a,c,k);(f||d&&h)&&rd(g,18);d&&Object.freeze(g);
return g}f||(f=Object.isFrozen(g),d&&!f?Object.freeze(g):!d&&f&&(g=Array.prototype.slice.call(g),a.i[c]=g));return g}
function I(a,b,c,d){Dd(a);null!=d?Hd(d,b):d=void 0;return Pd(a,c,d)}
function Wd(a,b,c,d,e){Dd(a);null!=e?Hd(e,b):e=void 0;Rd(a,c,d,e)}
function Xd(a,b,c,d,e){Dd(a);var f=null==d?Bd:vd([]);if(null!=d){for(var g=!!d.length,h=0;h<d.length;h++){var k=d[h];Hd(k,b);g=g&&!(E(k.P)&2);f[h]=k.P}f=sd(f,(g?8:0)|1);a.i||(a.i={});a.i[c]=d}else a.i&&(a.i[c]=void 0);return Pd(a,c,f,e)}
function Yd(a,b,c,d){var e=E(a.P);if(e&2)throw Error();e=Vd(a,c,b,!1,e);c=null!=d?Hd(d,c):new c;a=Qd(a,b,2,void 0,!1);e.push(c);a.push(c.P);E(c.P)&2&&ud(a,8)}
function Zd(){var a=new $d;return G(a,1,1)}
function ae(a,b){return null==a?b:a}
function be(a,b){return ae(Od(a,b),"")}
;var ce;function de(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "object":if(a)if(Array.isArray(a)){if(0!==(E(a)&128))return a=Array.prototype.slice.call(a),Ed(a),a}else{if(ld(a))return id(a);if(a instanceof pd){var b=a.Aa;return null==b?"":"string"===typeof b?b:a.Aa=id(b)}}}return a}
;function ee(a,b,c,d){if(null!=a){if(Array.isArray(a))a=fe(a,b,c,void 0!==d);else if(zd(a)){var e={},f;for(f in a)e[f]=ee(a[f],b,c,d);a=e}else a=b(a,d);return a}}
function fe(a,b,c,d){var e=E(a);d=d?!!(e&16):void 0;a=Array.prototype.slice.call(a);for(var f=0;f<a.length;f++)a[f]=ee(a[f],b,c,d);c(e,a);return a}
function ge(a){return a.Lc===yd?a.toJSON():de(a)}
function he(a,b){a&128&&Ed(b)}
;function ie(a,b,c){c=void 0===c?xd:c;if(null!=a){if(gd&&a instanceof Uint8Array)return b?a:new Uint8Array(a);if(Array.isArray(a)){var d=E(a);if(d&2)return a;if(b&&!(d&32)&&(d&16||0===d))return td(a,d|18),a;a=fe(a,ie,d&4?xd:c,!0);b=E(a);b&4&&b&2&&Object.freeze(a);return a}return a.Lc===yd?je(a):a}}
function ke(a,b,c,d,e,f,g){(a=a.i&&a.i[c])?(d=0<a.length?a[0].constructor:void 0,f=E(a),f&2||(a=ib(a,je),xd(f,a),Object.freeze(a)),Xd(b,d,c,a,e)):G(b,c,ie(d,f,g),e)}
function je(a){if(E(a.P)&2)return a;a=le(a,!0);rd(a.P,18);return a}
function le(a,b){var c=a.P,d=[];rd(d,16);var e=a.constructor.h;e&&d.push(e);e=a.xa;if(e){d.length=c.length;d.fill(void 0,d.length,c.length);var f={};d[d.length-1]=f}0!==(E(c)&128)&&Ed(d);b=b||E(a.P)&2?xd:wd;f=a.constructor;E(d);ce=d;d=new f(d);ce=void 0;a.xd&&(d.xd=a.xd.slice());f=!!(E(c)&16);for(var g=e?c.length-1:c.length,h=0;h<g;h++)ke(a,d,h-a.gb,c[h],!1,f,b);if(e)for(var k in e)c=e[k],g=+k,Number.isNaN(g),ke(a,d,g,c,!0,f,b);return d}
function Ud(a){if(!(E(a.P)&2))return a;var b=le(a,!1);b.m=a;return b}
;function J(a,b,c,d){null==a&&(a=ce);ce=void 0;var e=this.constructor.h;if(null==a){a=e?[e]:[];var f=48;var g=!0;d&&(f|=128);td(a,f)}else{if(!Array.isArray(a))throw Error();if(e&&e!==a[0])throw Error();f=rd(a,0)|32;g=0!==(16&f);if(d){if(!(f&128)&&0<a.length){var h=a[a.length-1];if(zd(h)&&"g"in h){f|=128;delete h.g;var k=!0,m;for(m in h){k=!1;break}k&&a.pop()}else throw Error();}}else if(128&f)throw Error();td(a,f)}this.gb=e?0:-1;this.i=void 0;this.P=a;a:{f=this.P.length;e=f-1;if(f&&(f=this.P[e],zd(f))){this.xa=
f;this.j=e-this.gb;break a}void 0!==b&&-1<b?(this.j=Math.max(b,e+1-this.gb),this.xa=void 0):this.j=Number.MAX_VALUE}if(!d&&this.xa&&"g"in this.xa)throw Error('Unexpected "g" flag in sparse object of message that is not a group type.');if(c){b=g&&!0;d=this.j;var n;for(g=0;g<c.length;g++)e=c[g],e<d?(e+=this.gb,(f=a[e])?me(f,b):a[e]=Bd):(n||(n=Nd(this)),(f=n[e])?me(f,b):n[e]=Bd)}E(this.P)}
J.prototype.toJSON=function(){var a=this.P,b;Ad?b=a:b=fe(a,ge,he);return b};
function ne(a){Ad=!0;try{return JSON.stringify(a.toJSON(),oe)}finally{Ad=!1}}
J.prototype.clone=function(){return le(this,!1)};
function me(a,b){if(Array.isArray(a)){var c=E(a),d=1;!b||c&2||(d|=16);(c&d)!==d&&td(a,c|d)}}
J.prototype.Lc=yd;J.prototype.toString=function(){return this.P.toString()};
function oe(a,b){return de(b)}
;function pe(a){this.hd=a}
;function qe(a,b,c){this.i=a;this.l=b;this.h=c||[];this.rb=new Map}
l=qe.prototype;l.ce=function(a){var b=Ka.apply(1,arguments),c=this.Ac(b);c?c.push(new pe(a)):this.Ld(a,b)};
l.Ld=function(a){this.rb.set(this.qd(Ka.apply(1,arguments)),[new pe(a)])};
l.Ac=function(){var a=this.qd(Ka.apply(0,arguments));return this.rb.has(a)?this.rb.get(a):void 0};
l.te=function(){var a=this.Ac(Ka.apply(0,arguments));return a&&a.length?a[0]:void 0};
l.clear=function(){this.rb.clear()};
l.qd=function(){var a=Ka.apply(0,arguments);return a?a.join(","):"key"};function re(a,b){qe.call(this,a,3,b)}
v(re,qe);re.prototype.j=function(a){var b=Ka.apply(1,arguments),c=0,d=this.te(b);d&&(c=d.hd);this.Ld(c+a,b)};function se(a,b){qe.call(this,a,2,b)}
v(se,qe);se.prototype.j=function(a){this.ce(a,Ka.apply(1,arguments))};function te(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function ue(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Qa(d)?ue.apply(null,d):te(d)}}
;function K(){this.X=this.X;this.H=this.H}
K.prototype.X=!1;K.prototype.h=function(){return this.X};
K.prototype.dispose=function(){this.X||(this.X=!0,this.M())};
function ve(a,b){we(a,Za(te,b))}
function we(a,b){a.X?b():(a.H||(a.H=[]),a.H.push(b))}
K.prototype.M=function(){if(this.H)for(;this.H.length;)this.H.shift()()};function xe(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
xe.prototype.stopPropagation=function(){this.j=!0};
xe.prototype.preventDefault=function(){this.defaultPrevented=!0};function ye(a){var b=A("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||y.$googDebugFname||b}catch(g){e="Not available",c=!0}b=ze(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Ae[c])c=Ae[c];else{c=String(c);if(!Ae[c]){var f=/function\s+([^\(]+)/m.exec(c);Ae[c]=f?f[1]:"[Anonymous]"}c=Ae[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function ze(a,b){b||(b={});b[Be(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[Be(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=ze(a,b));return c}
function Be(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var Ae={};var Ce=function(){if(!y.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{y.addEventListener("test",function(){},b),y.removeEventListener("test",function(){},b)}catch(c){}return a}();function De(a,b){xe.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
$a(De,xe);var Ee={2:"touch",3:"pen",4:"mouse"};
De.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(Jc){a:{try{Fc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:Ee[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&De.va.preventDefault.call(this)};
De.prototype.stopPropagation=function(){De.va.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
De.prototype.preventDefault=function(){De.va.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var Fe="closure_listenable_"+(1E6*Math.random()|0);var Ge=0;function He(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.kc=e;this.key=++Ge;this.Rb=this.ec=!1}
function Ie(a){a.Rb=!0;a.listener=null;a.proxy=null;a.src=null;a.kc=null}
;function Je(a){this.src=a;this.listeners={};this.h=0}
Je.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=Ke(a,b,d,e);-1<g?(b=a[g],c||(b.ec=!1)):(b=new He(b,this.src,f,!!d,e),b.ec=c,a.push(b));return b};
Je.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Ke(e,b,c,d);return-1<b?(Ie(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function Le(a,b){var c=b.type;c in a.listeners&&lb(a.listeners[c],b)&&(Ie(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function Ke(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Rb&&f.listener==b&&f.capture==!!c&&f.kc==d)return e}return-1}
;var Me="closure_lm_"+(1E6*Math.random()|0),Ne={},Oe=0;function Pe(a,b,c,d,e){if(d&&d.once)Qe(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Pe(a,b[f],c,d,e);else c=Re(c),a&&a[Fe]?a.Ma(b,c,Ra(d)?!!d.capture:!!d,e):Se(a,b,c,!1,d,e)}
function Se(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Ra(e)?!!e.capture:!!e,h=Te(a);h||(a[Me]=h=new Je(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Ue();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)Ce||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Ve(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Oe++}}
function Ue(){function a(c){return b.call(a.src,a.listener,c)}
var b=We;return a}
function Qe(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Qe(a,b[f],c,d,e);else c=Re(c),a&&a[Fe]?a.l.add(String(b),c,!0,Ra(d)?!!d.capture:!!d,e):Se(a,b,c,!0,d,e)}
function Xe(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Xe(a,b[f],c,d,e);else(d=Ra(d)?!!d.capture:!!d,c=Re(c),a&&a[Fe])?a.l.remove(String(b),c,d,e):a&&(a=Te(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Ke(b,c,d,e)),(c=-1<a?b[a]:null)&&Ye(c))}
function Ye(a){if("number"!==typeof a&&a&&!a.Rb){var b=a.src;if(b&&b[Fe])Le(b.l,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Ve(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Oe--;(c=Te(b))?(Le(c,a),0==c.h&&(c.src=null,b[Me]=null)):Ie(a)}}}
function Ve(a){return a in Ne?Ne[a]:Ne[a]="on"+a}
function We(a,b){if(a.Rb)a=!0;else{b=new De(b,this);var c=a.listener,d=a.kc||a.src;a.ec&&Ye(a);a=c.call(d,b)}return a}
function Te(a){a=a[Me];return a instanceof Je?a:null}
var Ze="__closure_events_fn_"+(1E9*Math.random()>>>0);function Re(a){if("function"===typeof a)return a;a[Ze]||(a[Ze]=function(b){return a.handleEvent(b)});
return a[Ze]}
;function $e(){K.call(this);this.l=new Je(this);this.Zd=this;this.Qa=null}
$a($e,K);$e.prototype[Fe]=!0;$e.prototype.addEventListener=function(a,b,c,d){Pe(this,a,b,c,d)};
$e.prototype.removeEventListener=function(a,b,c,d){Xe(this,a,b,c,d)};
function ff(a,b){var c=a.Qa;if(c){var d=[];for(var e=1;c;c=c.Qa)d.push(c),++e}a=a.Zd;c=b.type||b;"string"===typeof b?b=new xe(b,a):b instanceof xe?b.target=b.target||a:(e=b,b=new xe(c,a),yb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=gf(g,c,!0,b)&&e}b.j||(g=b.h=a,e=gf(g,c,!0,b)&&e,b.j||(e=gf(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=gf(g,c,!1,b)&&e}
$e.prototype.M=function(){$e.va.M.call(this);if(this.l){var a=this.l,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,Ie(d[e]);delete a.listeners[c];a.h--}}this.Qa=null};
$e.prototype.Ma=function(a,b,c,d){return this.l.add(String(a),b,!1,c,d)};
function gf(a,b,c,d){b=a.l.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Rb&&g.capture==c){var h=g.listener,k=g.kc||g.src;g.ec&&Le(a.l,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function hf(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
hf.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function jf(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;function kf(a,b){return a+Math.random()*(b-a)}
;function lf(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
l=lf.prototype;l.clone=function(){return new lf(this.x,this.y)};
l.equals=function(a){return a instanceof lf&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
l.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
l.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
l.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
l.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function mf(a,b){this.width=a;this.height=b}
l=mf.prototype;l.clone=function(){return new mf(this.width,this.height)};
l.aspectRatio=function(){return this.width/this.height};
l.Nb=function(){return!(this.width*this.height)};
l.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
l.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
l.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
l.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function nf(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function of(a){var b=document;a=String(a);"application/xhtml+xml"===b.contentType&&(a=a.toLowerCase());return b.createElement(a)}
function pf(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var qf;function rf(){var a=y.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!C("Presto")&&(a=function(){var e=of("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Xa(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!Vb()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.gd;c.gd=null;e()}};
return function(e){d.next={gd:e};d=d.next;b.port2.postMessage(0)}}return function(e){y.setTimeout(e,0)}}
;function sf(){this.i=this.h=null}
sf.prototype.add=function(a,b){var c=tf.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
sf.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var tf=new hf(function(){return new uf},function(a){return a.reset()});
function uf(){this.next=this.scope=this.h=null}
uf.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
uf.prototype.reset=function(){this.next=this.scope=this.h=null};var vf,wf=!1,xf=new sf;function yf(a,b){vf||zf();wf||(vf(),wf=!0);xf.add(a,b)}
function zf(){if(y.Promise&&y.Promise.resolve){var a=y.Promise.resolve(void 0);vf=function(){a.then(Af)}}else vf=function(){var b=Af;
"function"!==typeof y.setImmediate||y.Window&&y.Window.prototype&&!C("Edge")&&y.Window.prototype.setImmediate==y.setImmediate?(qf||(qf=rf()),qf(b)):y.setImmediate(b)}}
function Af(){for(var a;a=xf.remove();){try{a.h.call(a.scope)}catch(b){Cc(b)}jf(tf,a)}wf=!1}
;function Bf(a){this.h=0;this.H=void 0;this.l=this.i=this.j=null;this.m=this.s=!1;if(a!=db)try{var b=this;a.call(void 0,function(c){Cf(b,2,c)},function(c){Cf(b,3,c)})}catch(c){Cf(this,3,c)}}
function Df(){this.next=this.context=this.i=this.j=this.h=null;this.l=!1}
Df.prototype.reset=function(){this.context=this.i=this.j=this.h=null;this.l=!1};
var Ef=new hf(function(){return new Df},function(a){a.reset()});
function Ff(a,b,c){var d=Ef.get();d.j=a;d.i=b;d.context=c;return d}
function Gf(a){return new Bf(function(b,c){c(a)})}
Bf.prototype.then=function(a,b,c){return Hf(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
Bf.prototype.$goog_Thenable=!0;l=Bf.prototype;l.vc=function(a,b){return Hf(this,null,a,b)};
l.catch=Bf.prototype.vc;l.cancel=function(a){if(0==this.h){var b=new If(a);yf(function(){Jf(this,b)},this)}};
function Jf(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.l||(d++,g.h==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?Jf(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):Kf(c),Lf(c,e,3,b)))}a.j=null}else Cf(a,3,b)}
function Mf(a,b){a.i||2!=a.h&&3!=a.h||Nf(a);a.l?a.l.next=b:a.i=b;a.l=b}
function Hf(a,b,c,d){var e=Ff(null,null,null);e.h=new Bf(function(f,g){e.j=b?function(h){try{var k=b.call(d,h);f(k)}catch(m){g(m)}}:f;
e.i=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof If?g(h):f(k)}catch(m){g(m)}}:g});
e.h.j=a;Mf(a,e);return e.h}
l.mf=function(a){this.h=0;Cf(this,2,a)};
l.nf=function(a){this.h=0;Cf(this,3,a)};
function Cf(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.mf,f=a.nf;if(d instanceof Bf){Mf(d,Ff(e||db,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(m){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Ra(d))try{var k=d.then;if("function"===typeof k){Of(d,k,e,f,a);g=!0;break a}}catch(m){f.call(a,m);g=!0;break a}g=!1}}}g||(a.H=c,a.h=b,a.j=null,Nf(a),3!=b||c instanceof If||Pf(a,c))}}
function Of(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Nf(a){a.s||(a.s=!0,yf(a.oe,a))}
function Kf(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
l.oe=function(){for(var a;a=Kf(this);)Lf(this,a,this.h,this.H);this.s=!1};
function Lf(a,b,c,d){if(3==c&&b.i&&!b.l)for(;a&&a.m;a=a.j)a.m=!1;if(b.h)b.h.j=null,Qf(b,c,d);else try{b.l?b.j.call(b.context):Qf(b,c,d)}catch(e){Rf.call(null,e)}jf(Ef,b)}
function Qf(a,b,c){2==b?a.j.call(a.context,c):a.i&&a.i.call(a.context,c)}
function Pf(a,b){a.m=!0;yf(function(){a.m&&Rf.call(null,b)})}
var Rf=Cc;function If(a){bb.call(this,a)}
$a(If,bb);If.prototype.name="cancel";function Sf(a,b){$e.call(this);this.j=a||1;this.i=b||y;this.m=Xa(this.kf,this);this.s=Date.now()}
$a(Sf,$e);l=Sf.prototype;l.enabled=!1;l.za=null;function Tf(a,b){a.j=b;a.za&&a.enabled?(a.stop(),a.start()):a.za&&a.stop()}
l.kf=function(){if(this.enabled){var a=Date.now()-this.s;0<a&&a<.8*this.j?this.za=this.i.setTimeout(this.m,this.j-a):(this.za&&(this.i.clearTimeout(this.za),this.za=null),ff(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
l.start=function(){this.enabled=!0;this.za||(this.za=this.i.setTimeout(this.m,this.j),this.s=Date.now())};
l.stop=function(){this.enabled=!1;this.za&&(this.i.clearTimeout(this.za),this.za=null)};
l.M=function(){Sf.va.M.call(this);this.stop();delete this.i};
function Uf(a,b,c){if("function"===typeof a)c&&(a=Xa(a,c));else if(a&&"function"==typeof a.handleEvent)a=Xa(a.handleEvent,a);else throw Error("Invalid listener argument");return 2147483647<Number(b)?-1:y.setTimeout(a,b||0)}
;function Vf(a){this.H=a;this.h=new Map;this.s=new Set;this.j=0;this.l=100;this.flushInterval=3E4;this.i=new Sf(this.flushInterval);this.i.Ma("tick",this.Eb,!1,this);this.m=!1}
l=Vf.prototype;l.sendIsolatedPayload=function(a){this.m=a;this.l=1};
function Wf(a){a.i.enabled||a.i.start();a.j++;a.j>=a.l&&a.Eb()}
l.Eb=function(){var a=this.h.values();a=[].concat(ia(a)).filter(function(b){return b.rb.size});
a.length&&this.H.flush(a,this.m);Xf(a);this.j=0;this.i.enabled&&this.i.stop()};
l.cd=function(a){var b=Ka.apply(1,arguments);this.h.has(a)||this.h.set(a,new re(a,b))};
l.dd=function(a){var b=Ka.apply(1,arguments);this.h.has(a)||this.h.set(a,new se(a,b))};
function Yf(a,b){return a.s.has(b)?void 0:a.h.get(b)}
l.wc=function(a){this.Xd.apply(this,[a,1].concat(ia(Ka.apply(1,arguments))))};
l.Xd=function(a,b){var c=Ka.apply(2,arguments),d=Yf(this,a);d&&d instanceof re&&(d.j(b,c),Wf(this))};
l.xc=function(a,b){var c=Ka.apply(2,arguments),d=Yf(this,a);d&&d instanceof se&&(d.j(b,c),Wf(this))};
function Xf(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function Zf(a){this.h=a;this.h.cd("/client_streamz/bg/fiec",{Mb:3,Lb:"rk"},{Mb:2,Lb:"ec"})}
function $f(a,b,c){a.h.wc("/client_streamz/bg/fiec",b,c)}
function ag(a){this.h=a;this.h.dd("/client_streamz/bg/fil",{Mb:3,Lb:"rk"})}
function bg(a){this.h=a;this.h.cd("/client_streamz/bg/fsc",{Mb:3,Lb:"rk"})}
function cg(a){this.h=a;this.h.dd("/client_streamz/bg/fsl",{Mb:3,Lb:"rk"})}
;var dg={toString:function(a){var b=[],c=0;a-=-2147483648;b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ".charAt(a%52);for(a=Math.floor(a/52);0<a;)b[c++]="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789".charAt(a%62),a=Math.floor(a/62);return b.join("")}};function eg(a){function b(){c-=d;c-=e;c^=e>>>13;d-=e;d-=c;d^=c<<8;e-=c;e-=d;e^=d>>>13;c-=d;c-=e;c^=e>>>12;d-=e;d-=c;d^=c<<16;e-=c;e-=d;e^=d>>>5;c-=d;c-=e;c^=e>>>3;d-=e;d-=c;d^=c<<10;e-=c;e-=d;e^=d>>>15}
a=fg(a);for(var c=2654435769,d=2654435769,e=314159265,f=a.length,g=f,h=0;12<=g;g-=12,h+=12)c+=gg(a,h),d+=gg(a,h+4),e+=gg(a,h+8),b();e+=f;switch(g){case 11:e+=a[h+10]<<24;case 10:e+=a[h+9]<<16;case 9:e+=a[h+8]<<8;case 8:d+=a[h+7]<<24;case 7:d+=a[h+6]<<16;case 6:d+=a[h+5]<<8;case 5:d+=a[h+4];case 4:c+=a[h+3]<<24;case 3:c+=a[h+2]<<16;case 2:c+=a[h+1]<<8;case 1:c+=a[h+0]}b();return dg.toString(e)}
function fg(a){for(var b=[],c=0;c<a.length;c++)b.push(a.charCodeAt(c));return b}
function gg(a,b){return a[b+0]+(a[b+1]<<8)+(a[b+2]<<16)+(a[b+3]<<24)}
;function hg(a){J.call(this,a)}
v(hg,J);var ig=[1,2,3];function jg(a){J.call(this,a)}
v(jg,J);var kg=[1,2,3];function lg(a){J.call(this,a,-1,mg)}
v(lg,J);var mg=[1];function ng(a){J.call(this,a,-1,og)}
v(ng,J);var og=[3,6,4];function pg(a){J.call(this,a,-1,qg)}
v(pg,J);var qg=[1];function rg(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==
c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function sg(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=m=0}
function b(q){for(var u=g,t=0;64>t;t+=4)u[t/4]=q[t]<<24|q[t+1]<<16|q[t+2]<<8|q[t+3];for(t=16;80>t;t++)q=u[t-3]^u[t-8]^u[t-14]^u[t-16],u[t]=(q<<1|q>>>31)&4294967295;q=e[0];var B=e[1],D=e[2],F=e[3],N=e[4];for(t=0;80>t;t++){if(40>t)if(20>t){var O=F^B&(D^F);var Q=1518500249}else O=B^D^F,Q=1859775393;else 60>t?(O=B&D|F&(B|D),Q=2400959708):(O=B^D^F,Q=3395469782);O=((q<<5|q>>>27)&4294967295)+O+N+Q+u[t]&4294967295;N=F;F=D;D=(B<<30|B>>>2)&4294967295;B=q;q=O}e[0]=e[0]+q&4294967295;e[1]=e[1]+B&4294967295;e[2]=
e[2]+D&4294967295;e[3]=e[3]+F&4294967295;e[4]=e[4]+N&4294967295}
function c(q,u){if("string"===typeof q){q=unescape(encodeURIComponent(q));for(var t=[],B=0,D=q.length;B<D;++B)t.push(q.charCodeAt(B));q=t}u||(u=q.length);t=0;if(0==m)for(;t+64<u;)b(q.slice(t,t+64)),t+=64,n+=64;for(;t<u;)if(f[m++]=q[t++],n++,64==m)for(m=0,b(f);t+64<u;)b(q.slice(t,t+64)),t+=64,n+=64}
function d(){var q=[],u=8*n;56>m?c(h,56-m):c(h,64-(m-56));for(var t=63;56<=t;t--)f[t]=u&255,u>>>=8;b(f);for(t=u=0;5>t;t++)for(var B=24;0<=B;B-=8)q[u++]=e[t]>>B&255;return q}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var m,n;a();return{reset:a,update:c,digest:d,ke:function(){for(var q=d(),u="",t=0;t<q.length;t++)u+="0123456789ABCDEF".charAt(Math.floor(q[t]/16))+"0123456789ABCDEF".charAt(q[t]%16);return u}}}
;function tg(a,b,c){var d=String(y.location.href);return d&&a&&b?[b,ug(rg(d),a,c||null)].join(" "):null}
function ug(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],gb(d,function(h){e.push(h)}),vg(e.join(" "));
var f=[],g=[];gb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];gb(d,function(h){e.push(h)});
a=vg(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function vg(a){var b=sg();b.update(a);return b.ke().toLowerCase()}
;var wg={};function xg(a){this.h=a||{cookie:""}}
l=xg.prototype;l.isEnabled=function(){if(!y.navigator.cookieEnabled)return!1;if(!this.Nb())return!0;this.set("TESTCOOKIESENABLED","1",{nc:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
l.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.au;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.nc}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
l.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Kb(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
l.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{nc:0,path:b,domain:c});return d};
l.Dc=function(){return yg(this).keys};
l.Nb=function(){return!this.h.cookie};
l.clear=function(){for(var a=yg(this).keys,b=a.length-1;0<=b;b--)this.remove(a[b])};
function yg(a){a=(a.h.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=Kb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var zg=new xg("undefined"==typeof document?null:document);function Ag(a){return!!wg.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function Bg(a){a=void 0===a?!1:a;var b=y.__SAPISID||y.__APISID||y.__3PSAPISID||y.__OVERRIDE_SID;Ag(a)&&(b=b||y.__1PSAPISID);if(b)return!0;var c=new xg(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID")||c.get("OSID");Ag(a)&&(b=b||c.get("__Secure-1PAPISID"));return!!b}
function Cg(a,b,c,d){(a=y[a])||(a=(new xg(document)).get(b));return a?tg(a,c,d):null}
function Dg(a,b){b=void 0===b?!1:b;var c=rg(String(y.location.href)),d=[];if(Bg(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?y.__SAPISID:y.__APISID;e||(e=new xg(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?tg(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&Ag(b)&&((b=Cg("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=Cg("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return 0==
d.length?null:d.join(" ")}
;function Eg(a){J.call(this,a,-1,Fg)}
v(Eg,J);var Fg=[2];function Gg(a){this.h=this.i=this.j=a}
Gg.prototype.reset=function(){this.h=this.i=this.j};
Gg.prototype.getValue=function(){return this.i};function Hg(a){var b=[];Ig(new Jg,a,b);return b.join("")}
function Jg(){}
function Ig(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),Ig(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),Kg(d,c),c.push(":"),Ig(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":Kg(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var Lg={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},Mg=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function Kg(a,b){b.push('"',a.replace(Mg,function(c){var d=Lg[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),Lg[c]=d);return d}),'"')}
;function Ng(){}
Ng.prototype.h=null;Ng.prototype.getOptions=function(){var a;(a=this.h)||(a={},Og(this)&&(a[0]=!0,a[1]=!0),a=this.h=a);return a};var Pg;function Qg(){}
$a(Qg,Ng);function Rg(a){return(a=Og(a))?new ActiveXObject(a):new XMLHttpRequest}
function Og(a){if(!a.i&&"undefined"==typeof XMLHttpRequest&&"undefined"!=typeof ActiveXObject){for(var b=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"],c=0;c<b.length;c++){var d=b[c];try{return new ActiveXObject(d),a.i=d}catch(e){}}throw Error("Could not create ActiveXObject. ActiveX might be disabled, or MSXML might not be installed");}return a.i}
Pg=new Qg;function Sg(a){$e.call(this);this.headers=new Map;this.V=a||null;this.i=!1;this.R=this.F=null;this.m=this.ia="";this.j=this.aa=this.A=this.Z=!1;this.s=0;this.L=null;this.Ba="";this.oa=this.qa=!1}
$a(Sg,$e);var Tg=/^https?$/i,Ug=["POST","PUT"],Vg=[];function Wg(a,b,c,d,e,f,g){var h=new Sg;Vg.push(h);b&&h.Ma("complete",b);h.l.add("ready",h.ie,!0,void 0,void 0);f&&(h.s=Math.max(0,f));g&&(h.qa=g);h.send(a,c,d,e)}
l=Sg.prototype;l.ie=function(){this.dispose();lb(Vg,this)};
l.send=function(a,b,c,d){if(this.F)throw Error("[goog.net.XhrIo] Object is active with another request="+this.ia+"; newUri="+a);b=b?b.toUpperCase():"GET";this.ia=a;this.m="";this.Z=!1;this.i=!0;this.F=this.V?Rg(this.V):Rg(Pg);this.R=this.V?this.V.getOptions():Pg.getOptions();this.F.onreadystatechange=Xa(this.Cd,this);try{this.getStatus(),this.aa=!0,this.F.open(b,String(a),!0),this.aa=!1}catch(g){this.getStatus();Xg(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===
Object.prototype)for(var e in d)c.set(e,d[e]);else if("function"===typeof d.keys&&"function"===typeof d.get){e=r(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=y.FormData&&a instanceof y.FormData;!(0<=fb(Ug,b))||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=r(c);for(d=b.next();!d.done;d=b.next())c=r(d.value),d=c.next().value,c=c.next().value,this.F.setRequestHeader(d,c);this.Ba&&(this.F.responseType=this.Ba);"withCredentials"in this.F&&this.F.withCredentials!==this.qa&&(this.F.withCredentials=this.qa);try{Yg(this),0<this.s&&(this.oa=Zg(this.F),this.getStatus(),this.oa?(this.F.timeout=this.s,this.F.ontimeout=Xa(this.Qd,
this)):this.L=Uf(this.Qd,this.s,this)),this.getStatus(),this.A=!0,this.F.send(a),this.A=!1}catch(g){this.getStatus(),Xg(this,g)}};
function Zg(a){return Hc&&"number"===typeof a.timeout&&void 0!==a.ontimeout}
l.Qd=function(){"undefined"!=typeof Oa&&this.F&&(this.m="Timed out after "+this.s+"ms, aborting",this.getStatus(),ff(this,"timeout"),this.abort(8))};
function Xg(a,b){a.i=!1;a.F&&(a.j=!0,a.F.abort(),a.j=!1);a.m=b;$g(a);ah(a)}
function $g(a){a.Z||(a.Z=!0,ff(a,"complete"),ff(a,"error"))}
l.abort=function(){this.F&&this.i&&(this.getStatus(),this.i=!1,this.j=!0,this.F.abort(),this.j=!1,ff(this,"complete"),ff(this,"abort"),ah(this))};
l.M=function(){this.F&&(this.i&&(this.i=!1,this.j=!0,this.F.abort(),this.j=!1),ah(this,!0));Sg.va.M.call(this)};
l.Cd=function(){this.h()||(this.aa||this.A||this.j?bh(this):this.Le())};
l.Le=function(){bh(this)};
function bh(a){if(a.i&&"undefined"!=typeof Oa)if(a.R[1]&&4==ch(a)&&2==a.getStatus())a.getStatus();else if(a.A&&4==ch(a))Uf(a.Cd,0,a);else if(ff(a,"readystatechange"),a.isComplete()){a.getStatus();a.i=!1;try{if(dh(a))ff(a,"complete"),ff(a,"success");else{try{var b=2<ch(a)?a.F.statusText:""}catch(c){b=""}a.m=b+" ["+a.getStatus()+"]";$g(a)}}finally{ah(a)}}}
function ah(a,b){if(a.F){Yg(a);var c=a.F,d=a.R[0]?function(){}:null;
a.F=null;a.R=null;b||ff(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function Yg(a){a.F&&a.oa&&(a.F.ontimeout=null);a.L&&(y.clearTimeout(a.L),a.L=null)}
l.isActive=function(){return!!this.F};
l.isComplete=function(){return 4==ch(this)};
function dh(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=0===b)a=oc(1,String(a.ia)),!a&&y.self&&y.self.location&&(a=y.self.location.protocol.slice(0,-1)),b=!Tg.test(a?a.toLowerCase():"");c=b}return c}
function ch(a){return a.F?a.F.readyState:0}
l.getStatus=function(){try{return 2<ch(this)?this.F.status:-1}catch(a){return-1}};
l.getLastError=function(){return"string"===typeof this.m?this.m:String(this.m)};function eh(a){J.call(this,a,-1,fh)}
v(eh,J);var fh=[1];function gh(a){J.call(this,a)}
v(gh,J);var hh=["platform","platformVersion","architecture","model","uaFullVersion"];new eh;function $d(a){J.call(this,a)}
v($d,J);function ih(a){J.call(this,a,31,jh)}
v(ih,J);var jh=[3,20,27];function kh(a){J.call(this,a,17,lh)}
v(kh,J);var lh=[3,5];function mh(a){J.call(this,a,6,nh)}
v(mh,J);var nh=[5];function oh(a){J.call(this,a)}
v(oh,J);var ph;ph=new function(a,b,c){this.i=a;this.fieldName=b;this.h=c;this.isRepeated=0;this.j=Td;this.defaultValue=void 0}(175237375,{Qt:0},oh);function qh(a,b,c,d,e,f,g,h,k,m,n){$e.call(this);var q=this;this.Z="";this.j=[];this.Zc="";this.bd=this.fb=-1;this.Zb=!1;this.R=this.m=null;this.L=0;this.ae=1;this.timeoutMillis=0;this.Ba=!1;$e.call(this);this.ac=b||function(){};
this.A=new rh(a,f);this.Yd=d;this.Yb=n;this.be=Za(kf,0,1);this.ia=e||null;this.V=c||null;this.oa=g||!1;this.pageId=k||null;this.logger=null;this.withCredentials=!h;this.Gb=f||!1;!this.Gb&&(65<=bc("Chromium")||45<=bc("Firefox")||12<=bc("Safari")||(Dc()||C("iPad")||C("iPod"))&&Ec());a=Zd();sh(this.A,a);this.s=new Gg(1E4);this.i=new Sf(this.s.getValue());ve(this,this.i);m=th(this,m);Pe(this.i,"tick",m,!1,this);this.aa=new Sf(6E5);ve(this,this.aa);Pe(this.aa,"tick",m,!1,this);this.oa||this.aa.start();
this.Gb||(Pe(document,"visibilitychange",function(){"hidden"===document.visibilityState&&q.qa()}),Pe(document,"pagehide",this.qa,!1,this))}
v(qh,$e);function th(a,b){return b?function(){b().then(function(){a.flush()})}:function(){a.flush()}}
qh.prototype.M=function(){this.qa();$e.prototype.M.call(this)};
function wh(a){a.ia||(a.ia=.01>a.be()?"https://www.google.com/log?format=json&hasfast=true":"https://play.google.com/log?format=json&hasfast=true");return a.ia}
function xh(a,b){a.s=new Gg(1>b?1:b);Tf(a.i,a.s.getValue())}
qh.prototype.log=function(a){a=a.clone();var b=this.ae++;G(a,21,b);this.Z&&G(a,26,this.Z);if(!Od(a,1)){b=a;var c=Date.now().toString();G(b,1,c)}null==Od(a,15)&&G(a,15,60*(new Date).getTimezoneOffset());this.m&&(b=this.m.clone(),I(a,Eg,16,b));for(;1E3<=this.j.length;)this.j.shift(),++this.L;this.j.push(a);ff(this,new yh(a));this.oa||this.i.enabled||this.i.start()};
qh.prototype.flush=function(a,b){var c=this;if(0===this.j.length)a&&a();else if(this.Ba)zh(this);else{var d=Date.now();if(this.bd>d&&this.fb<d)b&&b("throttled");else{var e=Ah(this.A,this.j,this.L);d={};var f=this.ac();f&&(d.Authorization=f);var g=wh(this);this.V&&(d["X-Goog-AuthUser"]=this.V,g=xc(g,"authuser",this.V));this.pageId&&(d["X-Goog-PageId"]=this.pageId,g=xc(g,"pageId",this.pageId));if(f&&this.Zc===f)b&&b("stale-auth-token");else{this.j=[];this.i.enabled&&this.i.stop();this.L=0;var h=ne(e),
k;this.R&&this.R.isSupported(h.length)&&(k=this.R.compress(h));var m={url:g,body:h,ge:1,Qc:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis},n=function(t){c.s.reset();Tf(c.i,c.s.getValue());if(t){var B=null;try{var D=JSON.parse(t.replace(")]}'\n",""));B=new mh(D)}catch(F){}B&&(t=Number(ae(Od(B,1),"-1")),0<t&&(c.fb=Date.now(),c.bd=c.fb+t),B=ph.h?ph.j(B,ph.h,ph.i,!0):ph.j(B,ph.i,ph.defaultValue,!0))&&(B=ae(Od(B,1),-1),-1!=B&&(c.Zb||xh(c,B)))}a&&a()},q=function(t,
B){var D=E(e.P),F=!!(D&2);
D=Vd(e,ih,3,F,D);var N=Qd(e,3,3,void 0,F);if(!(F||E(N)&8)){for(F=0;F<D.length;F++){var O=D[F],Q=Ud(O);O!==Q&&(D[F]=Q,N[F]=Q.P)}rd(N,8)}N=c.s;N.h=Math.min(3E5,2*N.h);N.i=Math.min(3E5,N.h+Math.round(.2*(Math.random()-.5)*N.h));Tf(c.i,c.s.getValue());401===t&&f&&(c.Zc=f);void 0===B&&(B=500<=t&&600>t||401===t||0===t);B&&(c.j=D.concat(c.j),c.oa||c.i.enabled||c.i.start());b&&b("net-send-failed",t)},u=function(){c.Yb?c.Yb.send(m,n,q):c.Yd(m,n,q)};
k?k.then(function(t){m.Qc["Content-Encoding"]="gzip";m.Qc["Content-Type"]="application/binary";m.body=t;m.ge=2;u()},function(){u()}):u()}}}};
qh.prototype.qa=function(){this.flush()};
function zh(a){Bh(a,function(b,c){b=xc(b,"format","json");var d=!1;try{d=window.navigator.sendBeacon(b,ne(c))}catch(e){}a.Ba&&!d&&(a.Ba=!1);return d})}
function Bh(a,b){if(0!==a.j.length){var c=Bc(wh(a),"format");c=vc(c,"auth",a.ac(),"authuser",a.V||"0");for(var d=0;10>d&&a.j.length;++d){var e=a.j.slice(0,32),f=Ah(a.A,e,a.L);if(!b(c,f))break;a.L=0;a.j=a.j.slice(e.length)}a.i.enabled&&a.i.stop()}}
function yh(){xe.call(this,"event-logged",void 0)}
v(yh,xe);function rh(a,b){this.i=b=void 0===b?!1:b;this.uach=this.locale=null;this.h=new kh;G(this.h,2,a);b||(this.locale=document.documentElement.getAttribute("lang"));sh(this,new $d)}
function sh(a,b){I(a.h,$d,1,b);Od(b,1)||G(b,1,1);a.i||(b=Ch(a),Od(b,5)||G(b,5,a.locale));a.uach&&(b=Ch(a),Td(b,eh,9)||I(b,eh,9,a.uach))}
function Dh(a,b){var c=void 0===c?hh:c;b(window,c).then(function(d){a.uach=d;d=Ch(a);I(d,eh,9,a.uach);return!0}).catch(function(){return!1})}
function Ch(a){a=Td(a.h,$d,1);var b=Td(a,gh,11);b||(b=new gh,I(a,gh,11,b));return b}
function Ah(a,b,c){c=void 0===c?0:c;a=a.h.clone();var d=Date.now().toString();a=G(a,4,d);b=Xd(a,ih,3,b);c&&G(b,14,c);return b}
;function Eh(a,b,c){Wg(a.url,function(d){d=d.target;if(dh(d)){try{var e=d.F?d.F.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.Qc,a.timeoutMillis,a.withCredentials)}
;function Fh(){this.j="https://play.google.com/log?format=json&hasfast=true";this.A=!1;this.m=Eh;this.h=""}
;function Gh(){var a=void 0===a?"":a;var b=void 0===b?"":b;var c=new Fh;c.h="";""!=a&&(c.j=a);b&&(c.i=b);a=new qh(1828,c.R?c.R:Dg,"0",c.m,c.j,c.A,!1,c.aa,void 0,void 0,c.s?c.s:void 0);c.X&&sh(a.A,c.X);if(c.i){b=c.i;var d=Ch(a.A);G(d,7,b)}c.l&&(a.R=c.l);c.h&&(a.Z=c.h);c.H&&((b=c.H)?(a.m||(a.m=new Eg),b=ne(b),G(a.m,4,b)):a.m&&G(a.m,4,void 0,!1));c.V&&(d=c.V,a.m||(a.m=new Eg),b=a.m,d=null==d?Bd:sd(d,1),G(b,2,d));c.L&&(b=c.L,a.Zb=!0,xh(a,b));c.Z&&Dh(a.A,c.Z);this.h=a}
Gh.prototype.flush=function(a){var b=a||[];if(b.length){a=new pg;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=e,g=new ng;var h=G(g,1,f.i);var k=f;g=[];for(var m=0;m<k.h.length;m++)g.push(k.h[m].Lb);if(null==g)g=G(h,3,Bd);else{k=E(g);if(!(k&4)){if(k&2||Object.isFrozen(g))g=Array.prototype.slice.call(g);for(m=0;m<g.length;m++)g[m]=g[m];td(g,k|5)}g=G(h,3,g)}h=[];k=[];m=r(f.rb.keys());for(var n=m.next();!n.done;n=m.next())k.push(n.value.split(","));for(m=0;m<k.length;m++){n=k[m];var q=f.l;for(var u=
f.Ac(n)||[],t=[],B=0;B<u.length;B++){var D=u[B];D=D&&D.hd;var F=new jg;switch(q){case 3:Rd(F,1,kg,Number(D));break;case 2:Rd(F,2,kg,Fd(Number(D)))}t.push(F)}q=t;for(u=0;u<q.length;u++){t=q[u];B=new lg;t=I(B,jg,2,t);B=n;D=[];F=f;for(var N=[],O=0;O<F.h.length;O++)N.push(F.h[O].Mb);F=N;for(N=0;N<F.length;N++){O=F[N];var Q=B[N],ca=new hg;switch(O){case 3:Rd(ca,1,ig,String(Q));break;case 2:Rd(ca,2,ig,Number(Q));break;case 1:Rd(ca,3,ig,"true"==Q)}D.push(ca)}Xd(t,hg,1,D);h.push(t)}}Xd(g,lg,4,h);c.push(g);
e.clear()}Xd(a,ng,1,c);b=this.h;a instanceof ih?b.log(a):(c=new ih,a=ne(a),a=G(c,8,a),b.log(a));this.h.flush()}};function Hh(a){this.H=Ih();this.m=new Gh;this.h=new Vf(this.m);this.s=new ag(this.h);this.j=new bg(this.h);this.l=new cg(this.h);this.i=new Zf(this.h);this.Oa=eg(a)}
function Ih(){var a,b,c;return null!=(c=null==(a=globalThis.performance)?void 0:null==(b=a.now)?void 0:b.call(a))?c:Date.now()}
;function Jh(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function Kh(a){var b=this;this.i=!1;var c=a.program;var d=a.we;if(a.Pe){var e;this.ra=null!=(e=a.ra)?e:new Hh(d)}var f=new Jh;this.j=f.promise;if(y[d])if(y[d].a){var g;null!=(g=this.ra)&&$f(g.i,g.Oa,3)}else{var h;null!=(h=this.ra)&&$f(h.i,h.Oa,2);var k;null!=(k=this.ra)&&k.h.Eb()}else{var m;null!=(m=this.ra)&&$f(m.i,m.Oa,1);var n;null!=(n=this.ra)&&n.h.Eb()}this.l=r((0,y[d].a)(c,function(q,u){Promise.resolve().then(function(){var t;if(null!=(t=b.ra)){var B=Ih()-t.H;t.s.h.xc("/client_streamz/bg/fil",
B,t.Oa)}f.resolve({de:q,ff:u})})},!0)).next().value;
this.ef=f.promise.then(function(){})}
Kh.prototype.snapshot=function(a){var b=this;if(this.i)throw Error("Already disposed");var c=Ih(),d;null!=(d=this.ra)&&d.j.h.wc("/client_streamz/bg/fsc",d.Oa);return this.j.then(function(e){var f=e.de;return new Promise(function(g){f(function(h){var k;if(null!=(k=b.ra)){var m=Ih()-c;k.l.h.xc("/client_streamz/bg/fsl",m,k.Oa)}g(h)},[a.kd,
a.gf])})})};
Kh.prototype.Nd=function(a){if(this.i)throw Error("Already disposed");var b=Ih(),c;null!=(c=this.ra)&&c.j.h.wc("/client_streamz/bg/fsc",c.Oa);a=this.l([a.kd,a.gf]);null!=(c=this.ra)&&(b=Ih()-b,c.l.h.xc("/client_streamz/bg/fsl",b,c.Oa));return a};
Kh.prototype.dispose=function(){var a;null!=(a=this.ra)&&a.h.Eb();this.i=!0;this.j.then(function(b){(b=b.ff)&&b()})};
Kh.prototype.h=function(){return this.i};var Lh=window;Db("csi.gstatic.com");Db("googleads.g.doubleclick.net");Db("partner.googleadservices.com");Db("pubads.g.doubleclick.net");Db("securepubads.g.doubleclick.net");Db("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
var Mh;try{new URL("s://g"),Mh=!0}catch(a){Mh=!1}var Nh=Mh;var Oh={};function Ph(){}
function Qh(a){this.h=a}
v(Qh,Ph);Qh.prototype.toString=function(){return this.h};function Rh(a){var b="true".toString(),c=[new Qh(Sh[0].toLowerCase(),Oh)];if(0===c.length)throw Error("");if(c.map(function(d){if(d instanceof Qh)d=d.h;else throw Error("");return d}).every(function(d){return 0!=="data-loaded".indexOf(d)}))throw Error('Attribute "data-loaded" does not match any of the allowed prefixes.');
a.setAttribute("data-loaded",b)}
;function Th(a){var b,c,d=null==(c=(b=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:c.call(b,"script[nonce]");(b=d?d.nonce||d.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",b)}
function Uh(a,b){a.src=Ib(b);Th(a)}
;function Vh(a){this.De=a}
function Wh(a){return new Vh(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var Xh=[Wh("data"),Wh("http"),Wh("https"),Wh("mailto"),Wh("ftp"),new Vh(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function Yh(a){var b=Zh;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function $h(){var a=[];Yh(function(b){a.push(b)});
return a}
var Zh={Bf:"allow-forms",Cf:"allow-modals",Df:"allow-orientation-lock",Ef:"allow-pointer-lock",Ff:"allow-popups",Gf:"allow-popups-to-escape-sandbox",Hf:"allow-presentation",If:"allow-same-origin",Jf:"allow-scripts",Kf:"allow-top-navigation",Lf:"allow-top-navigation-by-user-activation"},ai=eb(function(){return $h()});
function bi(){var a=ci(),b={};gb(ai(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function ci(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function di(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var ei=(new Date).getTime();var fi="client_dev_domain client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");ia(fi);"undefined"!==typeof TextDecoder&&new TextDecoder;var gi="undefined"!==typeof TextEncoder?new TextEncoder:null,hi=gi?function(a){return gi.encode(a)}:function(a){for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);
128>e?b[c++]=e:(2048>e?b[c++]=e>>6|192:(55296==(e&64512)&&d+1<a.length&&56320==(a.charCodeAt(d+1)&64512)?(e=65536+((e&1023)<<10)+(a.charCodeAt(++d)&1023),b[c++]=e>>18|240,b[c++]=e>>12&63|128):b[c++]=e>>12|224,b[c++]=e>>6&63|128),b[c++]=e&63|128)}a=new Uint8Array(b.length);for(c=0;c<a.length;c++)a[c]=b[c];return a};function ii(a){$e.call(this);var b=this;this.A=this.j=0;this.ya=null!=a?a:{fa:function(e,f){return setTimeout(e,f)},
Da:function(e){clearTimeout(e)}};
var c,d;this.i=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.m=function(){return x(function(e){return w(e,ji(b),0)})};
window.addEventListener("offline",this.m);window.addEventListener("online",this.m);this.A||ki(this)}
v(ii,$e);function li(){var a=mi;ii.h||(ii.h=new ii(a));return ii.h}
ii.prototype.dispose=function(){window.removeEventListener("offline",this.m);window.removeEventListener("online",this.m);this.ya.Da(this.A);delete ii.h};
ii.prototype.ma=function(){return this.i};
function ki(a){a.A=a.ya.fa(function(){var b;return x(function(c){if(1==c.h)return a.i?(null==(b=window.navigator)?0:b.onLine)?c.v(3):w(c,ji(a),3):w(c,ji(a),3);ki(a);c.h=0})},3E4)}
function ji(a,b){return a.s?a.s:a.s=new Promise(function(c){var d,e,f,g;return x(function(h){switch(h.h){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,za(h,2,3),d&&(a.j=a.ya.fa(function(){d.abort()},b||2E4)),w(h,fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:Ca(h);a.s=void 0;a.j&&(a.ya.Da(a.j),a.j=0);g!==a.i&&(a.i=g,a.i?ff(a,"networkstatus-online"):ff(a,"networkstatus-offline"));c(g);Da(h);break;case 2:Ba(h),g=!1,h.v(3)}})})}
;function ni(){this.data_=[];this.h=-1}
ni.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data_[a]!==b&&(this.data_[a]=b,this.h=-1)};
ni.prototype.get=function(a){return!!this.data_[a]};
function oi(a){-1===a.h&&(a.h=jb(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.h}
;function pi(a,b){this.h=a[y.Symbol.iterator]();this.i=b}
pi.prototype[Symbol.iterator]=function(){return this};
pi.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value),done:a.done}};
function qi(a,b){return new pi(a,b)}
;function ri(){this.blockSize=-1}
;function si(){this.blockSize=-1;this.blockSize=64;this.h=[];this.m=[];this.s=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
$a(si,ri);si.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function ti(a,b,c){c||(c=0);var d=a.s;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var m=1518500249}else f=c^g^h,m=1859775393;else 60>e?(f=c&g|h&(c|g),m=2400959708):
(f=c^g^h,m=3395469782);f=(b<<5|b>>>27)+f+k+m+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
si.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.m,f=this.i;d<b;){if(0==f)for(;d<=c;)ti(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){ti(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){ti(this,e);f=0;break}}this.i=f;this.l+=b}};
si.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.m[c]=b&255,b/=256;ti(this,this.m);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function ui(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function vi(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function wi(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:ui(a).match(/\S+/g)||[],b=0<=fb(a,b));return b}
function xi(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):wi(a,"inverted-hdpi")&&vi(a,Array.prototype.filter.call(a.classList?a.classList:ui(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;function yi(){}
yi.prototype.next=function(){return zi};
var zi={done:!0,value:void 0};function Ai(a){return{value:a,done:!1}}
yi.prototype.Ca=function(){return this};function Bi(a){if(a instanceof Ci||a instanceof Di||a instanceof Ei)return a;if("function"==typeof a.next)return new Ci(function(){return a});
if("function"==typeof a[Symbol.iterator])return new Ci(function(){return a[Symbol.iterator]()});
if("function"==typeof a.Ca)return new Ci(function(){return a.Ca()});
throw Error("Not an iterator or iterable.");}
function Ci(a){this.i=a}
Ci.prototype.Ca=function(){return new Di(this.i())};
Ci.prototype[Symbol.iterator]=function(){return new Ei(this.i())};
Ci.prototype.h=function(){return new Ei(this.i())};
function Di(a){this.i=a}
v(Di,yi);Di.prototype.next=function(){return this.i.next()};
Di.prototype[Symbol.iterator]=function(){return new Ei(this.i)};
Di.prototype.h=function(){return new Ei(this.i)};
function Ei(a){Ci.call(this,function(){return a});
this.j=a}
v(Ei,Ci);Ei.prototype.next=function(){return this.j.next()};function Fi(a,b){this.i={};this.h=[];this.Xa=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof Fi)for(c=a.Dc(),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
l=Fi.prototype;l.Dc=function(){Gi(this);return this.h.concat()};
l.has=function(a){return Hi(this.i,a)};
l.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||Ii;Gi(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function Ii(a,b){return a===b}
l.Nb=function(){return 0==this.size};
l.clear=function(){this.i={};this.Xa=this.size=this.h.length=0};
l.remove=function(a){return this.delete(a)};
l.delete=function(a){return Hi(this.i,a)?(delete this.i[a],--this.size,this.Xa++,this.h.length>2*this.size&&Gi(this),!0):!1};
function Gi(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];Hi(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],Hi(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
l.get=function(a,b){return Hi(this.i,a)?this.i[a]:b};
l.set=function(a,b){Hi(this.i,a)||(this.size+=1,this.h.push(a),this.Xa++);this.i[a]=b};
l.forEach=function(a,b){for(var c=this.Dc(),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
l.clone=function(){return new Fi(this)};
l.keys=function(){return Bi(this.Ca(!0)).h()};
l.values=function(){return Bi(this.Ca(!1)).h()};
l.entries=function(){var a=this;return qi(this.keys(),function(b){return[b,a.get(b)]})};
l.Ca=function(a){Gi(this);var b=0,c=this.Xa,d=this,e=new yi;e.next=function(){if(c!=d.Xa)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)return zi;var f=d.h[b++];return Ai(a?f:d.i[f])};
return e};
function Hi(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function Ji(a){K.call(this);this.s=1;this.l=[];this.m=0;this.i=[];this.j={};this.A=!!a}
$a(Ji,K);l=Ji.prototype;l.subscribe=function(a,b,c){var d=this.j[a];d||(d=this.j[a]=[]);var e=this.s;this.i[e]=a;this.i[e+1]=b;this.i[e+2]=c;this.s=e+3;d.push(e);return e};
function Ki(a,b,c,d){if(b=a.j[b]){var e=a.i;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.Fb(b)}}
l.Fb=function(a){var b=this.i[a];if(b){var c=this.j[b];0!=this.m?(this.l.push(a),this.i[a+1]=function(){}):(c&&lb(c,a),delete this.i[a],delete this.i[a+1],delete this.i[a+2])}return!!b};
l.eb=function(a,b){var c=this.j[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.A)for(e=0;e<c.length;e++){var g=c[e];Li(this.i[g+1],this.i[g+2],d)}else{this.m++;try{for(e=0,f=c.length;e<f&&!this.h();e++)g=c[e],this.i[g+1].apply(this.i[g+2],d)}finally{if(this.m--,0<this.l.length&&0==this.m)for(;c=this.l.pop();)this.Fb(c)}}return 0!=e}return!1};
function Li(a,b,c){yf(function(){a.apply(b,c)})}
l.clear=function(a){if(a){var b=this.j[a];b&&(b.forEach(this.Fb,this),delete this.j[a])}else this.i.length=0,this.j={}};
l.M=function(){Ji.va.M.call(this);this.clear();this.l.length=0};function Mi(a){this.h=a}
Mi.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,Hg(b))};
Mi.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Mi.prototype.remove=function(a){this.h.remove(a)};function Ni(a){this.h=a}
$a(Ni,Mi);function Oi(a){this.data=a}
function Pi(a){return void 0===a||a instanceof Oi?a:new Oi(a)}
Ni.prototype.set=function(a,b){Ni.va.set.call(this,a,Pi(b))};
Ni.prototype.i=function(a){a=Ni.va.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Ni.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Qi(a){this.h=a}
$a(Qi,Ni);Qi.prototype.set=function(a,b,c){if(b=Pi(b)){if(c){if(c<Date.now()){Qi.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}Qi.va.set.call(this,a,b)};
Qi.prototype.i=function(a){var b=Qi.va.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())Qi.prototype.remove.call(this,a);else return b}};function Ri(){}
;function Si(){}
$a(Si,Ri);Si.prototype[Symbol.iterator]=function(){return Bi(this.Ca(!0)).h()};
Si.prototype.clear=function(){var a=Array.from(this);a=r(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function Ti(a){this.h=a}
$a(Ti,Si);l=Ti.prototype;l.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
l.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
l.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.h.removeItem(a)};
l.Ca=function(a){var b=0,c=this.h,d=new yi;d.next=function(){if(b>=c.length)return zi;var e=c.key(b++);if(a)return Ai(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Ai(e)};
return d};
l.clear=function(){this.h.clear()};
l.key=function(a){return this.h.key(a)};function Ui(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
$a(Ui,Ti);function Vi(a,b){this.i=a;this.h=null;var c;if(c=Hc)c=!(9<=Number(Xc));if(c){Wi||(Wi=new Fi);this.h=Wi.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),Wi.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
$a(Vi,Si);var Xi={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},Wi=null;function Yi(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return Xi[b]})}
l=Vi.prototype;l.isAvailable=function(){return!!this.h};
l.set=function(a,b){this.h.setAttribute(Yi(a),b);Zi(this)};
l.get=function(a){a=this.h.getAttribute(Yi(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.h.removeAttribute(Yi(a));Zi(this)};
l.Ca=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new yi;d.next=function(){if(b>=c.length)return zi;var e=c[b++];if(a)return Ai(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return Ai(e)};
return d};
l.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);Zi(this)};
function Zi(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function $i(a,b){this.i=a;this.h=b+"::"}
$a($i,Si);$i.prototype.set=function(a,b){this.i.set(this.h+a,b)};
$i.prototype.get=function(a){return this.i.get(this.h+a)};
$i.prototype.remove=function(a){this.i.remove(this.h+a)};
$i.prototype.Ca=function(a){var b=this.i[Symbol.iterator](),c=this,d=new yi;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.h.length)!=c.h;){e=b.next();if(e.done)return e;e=e.value}return Ai(a?e.slice(c.h.length):c.i.get(e))};
return d};/*

 (The MIT License)

 Copyright (C) 2014 by Vitaly Puzrin

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.

 -----------------------------------------------------------------------------
 Ported from zlib, which is under the following license
 https://github.com/madler/zlib/blob/master/zlib.h

 zlib.h -- interface of the 'zlib' general purpose compression library
   version 1.2.8, April 28th, 2013
   Copyright (C) 1995-2013 Jean-loup Gailly and Mark Adler
   This software is provided 'as-is', without any express or implied
   warranty.  In no event will the authors be held liable for any damages
   arising from the use of this software.
   Permission is granted to anyone to use this software for any purpose,
   including commercial applications, and to alter it and redistribute it
   freely, subject to the following restrictions:
   1. The origin of this software must not be misrepresented; you must not
      claim that you wrote the original software. If you use this software
      in a product, an acknowledgment in the product documentation would be
      appreciated but is not required.
   2. Altered source versions must be plainly marked as such, and must not be
      misrepresented as being the original software.
   3. This notice may not be removed or altered from any source distribution.
   Jean-loup Gailly        Mark Adler
   jloup@gzip.org          madler@alumni.caltech.edu
   The data format used by the zlib library is described by RFCs (Request for
   Comments) 1950 to 1952 in the files http://tools.ietf.org/html/rfc1950
   (zlib format), rfc1951 (deflate format) and rfc1952 (gzip format).
*/
var L={},aj="undefined"!==typeof Uint8Array&&"undefined"!==typeof Uint16Array&&"undefined"!==typeof Int32Array;L.assign=function(a){for(var b=Array.prototype.slice.call(arguments,1);b.length;){var c=b.shift();if(c){if("object"!==typeof c)throw new TypeError(c+"must be non-object");for(var d in c)Object.prototype.hasOwnProperty.call(c,d)&&(a[d]=c[d])}}return a};
L.Tc=function(a,b){if(a.length===b)return a;if(a.subarray)return a.subarray(0,b);a.length=b;return a};
var bj={qb:function(a,b,c,d,e){if(b.subarray&&a.subarray)a.set(b.subarray(c,c+d),e);else for(var f=0;f<d;f++)a[e+f]=b[c+f]},
pd:function(a){var b,c;var d=c=0;for(b=a.length;d<b;d++)c+=a[d].length;var e=new Uint8Array(c);d=c=0;for(b=a.length;d<b;d++){var f=a[d];e.set(f,c);c+=f.length}return e}},cj={qb:function(a,b,c,d,e){for(var f=0;f<d;f++)a[e+f]=b[c+f]},
pd:function(a){return[].concat.apply([],a)}};
L.df=function(){aj?(L.cb=Uint8Array,L.Ga=Uint16Array,L.Wd=Int32Array,L.assign(L,bj)):(L.cb=Array,L.Ga=Array,L.Wd=Array,L.assign(L,cj))};
L.df();var dj=!0;try{new Uint8Array(1)}catch(a){dj=!1}for(var ej=new L.cb(256),fj=0;256>fj;fj++)ej[fj]=252<=fj?6:248<=fj?5:240<=fj?4:224<=fj?3:192<=fj?2:1;ej[254]=ej[254]=1;
function gj(a){var b,c,d=a.length,e=0;for(b=0;b<d;b++){var f=a.charCodeAt(b);if(55296===(f&64512)&&b+1<d){var g=a.charCodeAt(b+1);56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)}e+=128>f?1:2048>f?2:65536>f?3:4}var h=new L.cb(e);for(b=c=0;c<e;b++)f=a.charCodeAt(b),55296===(f&64512)&&b+1<d&&(g=a.charCodeAt(b+1),56320===(g&64512)&&(f=65536+(f-55296<<10)+(g-56320),b++)),128>f?h[c++]=f:(2048>f?h[c++]=192|f>>>6:(65536>f?h[c++]=224|f>>>12:(h[c++]=240|f>>>18,h[c++]=128|f>>>12&63),h[c++]=128|f>>>
6&63),h[c++]=128|f&63);return h}
;var hj={};hj=function(a,b,c,d){var e=a&65535|0;a=a>>>16&65535|0;for(var f;0!==c;){f=2E3<c?2E3:c;c-=f;do e=e+b[d++]|0,a=a+e|0;while(--f);e%=65521;a%=65521}return e|a<<16|0};for(var ij={},jj,kj=[],lj=0;256>lj;lj++){jj=lj;for(var mj=0;8>mj;mj++)jj=jj&1?3988292384^jj>>>1:jj>>>1;kj[lj]=jj}ij=function(a,b,c,d){c=d+c;for(a^=-1;d<c;d++)a=a>>>8^kj[(a^b[d])&255];return a^-1};var nj={};nj={2:"need dictionary",1:"stream end",0:"","-1":"file error","-2":"stream error","-3":"data error","-4":"insufficient memory","-5":"buffer error","-6":"incompatible version"};function oj(a){for(var b=a.length;0<=--b;)a[b]=0}
var pj=[0,0,0,0,0,0,0,0,1,1,1,1,2,2,2,2,3,3,3,3,4,4,4,4,5,5,5,5,0],qj=[0,0,0,0,1,1,2,2,3,3,4,4,5,5,6,6,7,7,8,8,9,9,10,10,11,11,12,12,13,13],rj=[0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,2,3,7],sj=[16,17,18,0,8,7,9,6,10,5,11,4,12,3,13,2,14,1,15],tj=Array(576);oj(tj);var uj=Array(60);oj(uj);var vj=Array(512);oj(vj);var wj=Array(256);oj(wj);var xj=Array(29);oj(xj);var yj=Array(30);oj(yj);function zj(a,b,c,d,e){this.Od=a;this.qe=b;this.pe=c;this.le=d;this.He=e;this.td=a&&a.length}
var Aj,Bj,Cj;function Dj(a,b){this.nd=a;this.xb=0;this.Wa=b}
function Ej(a,b){a.S[a.pending++]=b&255;a.S[a.pending++]=b>>>8&255}
function Fj(a,b,c){a.ba>16-c?(a.ha|=b<<a.ba&65535,Ej(a,a.ha),a.ha=b>>16-a.ba,a.ba+=c-16):(a.ha|=b<<a.ba&65535,a.ba+=c)}
function Gj(a,b,c){Fj(a,c[2*b],c[2*b+1])}
function Hj(a,b){var c=0;do c|=a&1,a>>>=1,c<<=1;while(0<--b);return c>>>1}
function Ij(a,b,c){var d=Array(16),e=0,f;for(f=1;15>=f;f++)d[f]=e=e+c[f-1]<<1;for(c=0;c<=b;c++)e=a[2*c+1],0!==e&&(a[2*c]=Hj(d[e]++,e))}
function Jj(a){var b;for(b=0;286>b;b++)a.ja[2*b]=0;for(b=0;30>b;b++)a.hb[2*b]=0;for(b=0;19>b;b++)a.ca[2*b]=0;a.ja[512]=1;a.Na=a.Ab=0;a.sa=a.matches=0}
function Kj(a){8<a.ba?Ej(a,a.ha):0<a.ba&&(a.S[a.pending++]=a.ha);a.ha=0;a.ba=0}
function Lj(a,b,c){Kj(a);Ej(a,c);Ej(a,~c);L.qb(a.S,a.window,b,c,a.pending);a.pending+=c}
function Mj(a,b,c,d){var e=2*b,f=2*c;return a[e]<a[f]||a[e]===a[f]&&d[b]<=d[c]}
function Nj(a,b,c){for(var d=a.U[c],e=c<<1;e<=a.Ka;){e<a.Ka&&Mj(b,a.U[e+1],a.U[e],a.depth)&&e++;if(Mj(b,d,a.U[e],a.depth))break;a.U[c]=a.U[e];c=e;e<<=1}a.U[c]=d}
function Oj(a,b,c){var d=0;if(0!==a.sa){do{var e=a.S[a.Ib+2*d]<<8|a.S[a.Ib+2*d+1];var f=a.S[a.Ic+d];d++;if(0===e)Gj(a,f,b);else{var g=wj[f];Gj(a,g+256+1,b);var h=pj[g];0!==h&&(f-=xj[g],Fj(a,f,h));e--;g=256>e?vj[e]:vj[256+(e>>>7)];Gj(a,g,c);h=qj[g];0!==h&&(e-=yj[g],Fj(a,e,h))}}while(d<a.sa)}Gj(a,256,b)}
function Pj(a,b){var c=b.nd,d=b.Wa.Od,e=b.Wa.td,f=b.Wa.le,g,h=-1;a.Ka=0;a.ub=573;for(g=0;g<f;g++)0!==c[2*g]?(a.U[++a.Ka]=h=g,a.depth[g]=0):c[2*g+1]=0;for(;2>a.Ka;){var k=a.U[++a.Ka]=2>h?++h:0;c[2*k]=1;a.depth[k]=0;a.Na--;e&&(a.Ab-=d[2*k+1])}b.xb=h;for(g=a.Ka>>1;1<=g;g--)Nj(a,c,g);k=f;do g=a.U[1],a.U[1]=a.U[a.Ka--],Nj(a,c,1),d=a.U[1],a.U[--a.ub]=g,a.U[--a.ub]=d,c[2*k]=c[2*g]+c[2*d],a.depth[k]=(a.depth[g]>=a.depth[d]?a.depth[g]:a.depth[d])+1,c[2*g+1]=c[2*d+1]=k,a.U[1]=k++,Nj(a,c,1);while(2<=a.Ka);a.U[--a.ub]=
a.U[1];g=b.nd;k=b.xb;d=b.Wa.Od;e=b.Wa.td;f=b.Wa.qe;var m=b.Wa.pe,n=b.Wa.He,q,u=0;for(q=0;15>=q;q++)a.Ha[q]=0;g[2*a.U[a.ub]+1]=0;for(b=a.ub+1;573>b;b++){var t=a.U[b];q=g[2*g[2*t+1]+1]+1;q>n&&(q=n,u++);g[2*t+1]=q;if(!(t>k)){a.Ha[q]++;var B=0;t>=m&&(B=f[t-m]);var D=g[2*t];a.Na+=D*(q+B);e&&(a.Ab+=D*(d[2*t+1]+B))}}if(0!==u){do{for(q=n-1;0===a.Ha[q];)q--;a.Ha[q]--;a.Ha[q+1]+=2;a.Ha[n]--;u-=2}while(0<u);for(q=n;0!==q;q--)for(t=a.Ha[q];0!==t;)d=a.U[--b],d>k||(g[2*d+1]!==q&&(a.Na+=(q-g[2*d+1])*g[2*d],g[2*
d+1]=q),t--)}Ij(c,h,a.Ha)}
function Qj(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;0===f&&(h=138,k=3);b[2*(c+1)+1]=65535;for(d=0;d<=c;d++){var m=f;f=b[2*(d+1)+1];++g<h&&m===f||(g<k?a.ca[2*m]+=g:0!==m?(m!==e&&a.ca[2*m]++,a.ca[32]++):10>=g?a.ca[34]++:a.ca[36]++,g=0,e=m,0===f?(h=138,k=3):m===f?(h=6,k=3):(h=7,k=4))}}
function Rj(a,b,c){var d,e=-1,f=b[1],g=0,h=7,k=4;0===f&&(h=138,k=3);for(d=0;d<=c;d++){var m=f;f=b[2*(d+1)+1];if(!(++g<h&&m===f)){if(g<k){do Gj(a,m,a.ca);while(0!==--g)}else 0!==m?(m!==e&&(Gj(a,m,a.ca),g--),Gj(a,16,a.ca),Fj(a,g-3,2)):10>=g?(Gj(a,17,a.ca),Fj(a,g-3,3)):(Gj(a,18,a.ca),Fj(a,g-11,7));g=0;e=m;0===f?(h=138,k=3):m===f?(h=6,k=3):(h=7,k=4)}}}
function Sj(a){var b=4093624447,c;for(c=0;31>=c;c++,b>>>=1)if(b&1&&0!==a.ja[2*c])return 0;if(0!==a.ja[18]||0!==a.ja[20]||0!==a.ja[26])return 1;for(c=32;256>c;c++)if(0!==a.ja[2*c])return 1;return 0}
var Tj=!1;function Uj(a,b,c){a.S[a.Ib+2*a.sa]=b>>>8&255;a.S[a.Ib+2*a.sa+1]=b&255;a.S[a.Ic+a.sa]=c&255;a.sa++;0===b?a.ja[2*c]++:(a.matches++,b--,a.ja[2*(wj[c]+256+1)]++,a.hb[2*(256>b?vj[b]:vj[256+(b>>>7)])]++);return a.sa===a.Ob-1}
;function Vj(a,b){a.msg=nj[b];return b}
function Wj(a){for(var b=a.length;0<=--b;)a[b]=0}
function Xj(a){var b=a.state,c=b.pending;c>a.I&&(c=a.I);0!==c&&(L.qb(a.Pb,b.S,b.Qb,c,a.yb),a.yb+=c,b.Qb+=c,a.Uc+=c,a.I-=c,b.pending-=c,0===b.pending&&(b.Qb=0))}
function Yj(a,b){var c=0<=a.la?a.la:-1,d=a.o-a.la,e=0;if(0<a.level){2===a.D.yc&&(a.D.yc=Sj(a));Pj(a,a.mc);Pj(a,a.ic);Qj(a,a.ja,a.mc.xb);Qj(a,a.hb,a.ic.xb);Pj(a,a.ed);for(e=18;3<=e&&0===a.ca[2*sj[e]+1];e--);a.Na+=3*(e+1)+14;var f=a.Na+3+7>>>3;var g=a.Ab+3+7>>>3;g<=f&&(f=g)}else f=g=d+5;if(d+4<=f&&-1!==c)Fj(a,b?1:0,3),Lj(a,c,d);else if(4===a.strategy||g===f)Fj(a,2+(b?1:0),3),Oj(a,tj,uj);else{Fj(a,4+(b?1:0),3);c=a.mc.xb+1;d=a.ic.xb+1;e+=1;Fj(a,c-257,5);Fj(a,d-1,5);Fj(a,e-4,4);for(f=0;f<e;f++)Fj(a,a.ca[2*
sj[f]+1],3);Rj(a,a.ja,c-1);Rj(a,a.hb,d-1);Oj(a,a.ja,a.hb)}Jj(a);b&&Kj(a);a.la=a.o;Xj(a.D)}
function M(a,b){a.S[a.pending++]=b}
function Zj(a,b){a.S[a.pending++]=b>>>8&255;a.S[a.pending++]=b&255}
function ak(a,b){var c=a.zd,d=a.o,e=a.na,f=a.Bd,g=a.o>a.ea-262?a.o-(a.ea-262):0,h=a.window,k=a.Ya,m=a.Fa,n=a.o+258,q=h[d+e-1],u=h[d+e];a.na>=a.sd&&(c>>=2);f>a.u&&(f=a.u);do{var t=b;if(h[t+e]===u&&h[t+e-1]===q&&h[t]===h[d]&&h[++t]===h[d+1]){d+=2;for(t++;h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&h[++d]===h[++t]&&d<n;);t=258-(n-d);d=n-258;if(t>e){a.wb=b;e=t;if(t>=f)break;q=h[d+e-1];u=h[d+e]}}}while((b=m[b&k])>g&&0!==--c);return e<=
a.u?e:a.u}
function bk(a){var b=a.ea,c;do{var d=a.Ud-a.u-a.o;if(a.o>=b+(b-262)){L.qb(a.window,a.window,b,b,0);a.wb-=b;a.o-=b;a.la-=b;var e=c=a.lc;do{var f=a.head[--e];a.head[e]=f>=b?f-b:0}while(--c);e=c=b;do f=a.Fa[--e],a.Fa[e]=f>=b?f-b:0;while(--c);d+=b}if(0===a.D.ga)break;e=a.D;c=a.window;f=a.o+a.u;var g=e.ga;g>d&&(g=d);0===g?c=0:(e.ga-=g,L.qb(c,e.input,e.kb,g,f),1===e.state.wrap?e.C=hj(e.C,c,g,f):2===e.state.wrap&&(e.C=ij(e.C,c,g,f)),e.kb+=g,e.nb+=g,c=g);a.u+=c;if(3<=a.u+a.ka)for(d=a.o-a.ka,a.G=a.window[d],
a.G=(a.G<<a.Ja^a.window[d+1])&a.Ia;a.ka&&!(a.G=(a.G<<a.Ja^a.window[d+3-1])&a.Ia,a.Fa[d&a.Ya]=a.head[a.G],a.head[a.G]=d,d++,a.ka--,3>a.u+a.ka););}while(262>a.u&&0!==a.D.ga)}
function ck(a,b){for(var c;;){if(262>a.u){bk(a);if(262>a.u&&0===b)return 1;if(0===a.u)break}c=0;3<=a.u&&(a.G=(a.G<<a.Ja^a.window[a.o+3-1])&a.Ia,c=a.Fa[a.o&a.Ya]=a.head[a.G],a.head[a.G]=a.o);0!==c&&a.o-c<=a.ea-262&&(a.J=ak(a,c));if(3<=a.J)if(c=Uj(a,a.o-a.wb,a.J-3),a.u-=a.J,a.J<=a.Jc&&3<=a.u){a.J--;do a.o++,a.G=(a.G<<a.Ja^a.window[a.o+3-1])&a.Ia,a.Fa[a.o&a.Ya]=a.head[a.G],a.head[a.G]=a.o;while(0!==--a.J);a.o++}else a.o+=a.J,a.J=0,a.G=a.window[a.o],a.G=(a.G<<a.Ja^a.window[a.o+1])&a.Ia;else c=Uj(a,0,
a.window[a.o]),a.u--,a.o++;if(c&&(Yj(a,!1),0===a.D.I))return 1}a.ka=2>a.o?a.o:2;return 4===b?(Yj(a,!0),0===a.D.I?3:4):a.sa&&(Yj(a,!1),0===a.D.I)?1:2}
function dk(a,b){for(var c,d;;){if(262>a.u){bk(a);if(262>a.u&&0===b)return 1;if(0===a.u)break}c=0;3<=a.u&&(a.G=(a.G<<a.Ja^a.window[a.o+3-1])&a.Ia,c=a.Fa[a.o&a.Ya]=a.head[a.G],a.head[a.G]=a.o);a.na=a.J;a.Ed=a.wb;a.J=2;0!==c&&a.na<a.Jc&&a.o-c<=a.ea-262&&(a.J=ak(a,c),5>=a.J&&(1===a.strategy||3===a.J&&4096<a.o-a.wb)&&(a.J=2));if(3<=a.na&&a.J<=a.na){d=a.o+a.u-3;c=Uj(a,a.o-1-a.Ed,a.na-3);a.u-=a.na-1;a.na-=2;do++a.o<=d&&(a.G=(a.G<<a.Ja^a.window[a.o+3-1])&a.Ia,a.Fa[a.o&a.Ya]=a.head[a.G],a.head[a.G]=a.o);
while(0!==--a.na);a.ib=0;a.J=2;a.o++;if(c&&(Yj(a,!1),0===a.D.I))return 1}else if(a.ib){if((c=Uj(a,0,a.window[a.o-1]))&&Yj(a,!1),a.o++,a.u--,0===a.D.I)return 1}else a.ib=1,a.o++,a.u--}a.ib&&(Uj(a,0,a.window[a.o-1]),a.ib=0);a.ka=2>a.o?a.o:2;return 4===b?(Yj(a,!0),0===a.D.I?3:4):a.sa&&(Yj(a,!1),0===a.D.I)?1:2}
function ek(a,b){for(var c,d,e,f=a.window;;){if(258>=a.u){bk(a);if(258>=a.u&&0===b)return 1;if(0===a.u)break}a.J=0;if(3<=a.u&&0<a.o&&(d=a.o-1,c=f[d],c===f[++d]&&c===f[++d]&&c===f[++d])){for(e=a.o+258;c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&c===f[++d]&&d<e;);a.J=258-(e-d);a.J>a.u&&(a.J=a.u)}3<=a.J?(c=Uj(a,1,a.J-3),a.u-=a.J,a.o+=a.J,a.J=0):(c=Uj(a,0,a.window[a.o]),a.u--,a.o++);if(c&&(Yj(a,!1),0===a.D.I))return 1}a.ka=0;return 4===b?(Yj(a,!0),0===a.D.I?3:4):
a.sa&&(Yj(a,!1),0===a.D.I)?1:2}
function fk(a,b){for(var c;;){if(0===a.u&&(bk(a),0===a.u)){if(0===b)return 1;break}a.J=0;c=Uj(a,0,a.window[a.o]);a.u--;a.o++;if(c&&(Yj(a,!1),0===a.D.I))return 1}a.ka=0;return 4===b?(Yj(a,!0),0===a.D.I?3:4):a.sa&&(Yj(a,!1),0===a.D.I)?1:2}
function gk(a,b,c,d,e){this.xe=a;this.Ge=b;this.Ke=c;this.Fe=d;this.se=e}
var hk;hk=[new gk(0,0,0,0,function(a,b){var c=65535;for(c>a.ta-5&&(c=a.ta-5);;){if(1>=a.u){bk(a);if(0===a.u&&0===b)return 1;if(0===a.u)break}a.o+=a.u;a.u=0;var d=a.la+c;if(0===a.o||a.o>=d)if(a.u=a.o-d,a.o=d,Yj(a,!1),0===a.D.I)return 1;if(a.o-a.la>=a.ea-262&&(Yj(a,!1),0===a.D.I))return 1}a.ka=0;if(4===b)return Yj(a,!0),0===a.D.I?3:4;a.o>a.la&&Yj(a,!1);return 1}),
new gk(4,4,8,4,ck),new gk(4,5,16,8,ck),new gk(4,6,32,32,ck),new gk(4,4,16,16,dk),new gk(8,16,32,32,dk),new gk(8,16,128,128,dk),new gk(8,32,128,256,dk),new gk(32,128,258,1024,dk),new gk(32,258,258,4096,dk)];
function ik(){this.D=null;this.status=0;this.S=null;this.wrap=this.pending=this.Qb=this.ta=0;this.B=null;this.wa=0;this.method=8;this.vb=-1;this.Ya=this.Wc=this.ea=0;this.window=null;this.Ud=0;this.head=this.Fa=null;this.Bd=this.sd=this.strategy=this.level=this.Jc=this.zd=this.na=this.u=this.wb=this.o=this.ib=this.Ed=this.J=this.la=this.Ja=this.Ia=this.Ec=this.lc=this.G=0;this.ja=new L.Ga(1146);this.hb=new L.Ga(122);this.ca=new L.Ga(78);Wj(this.ja);Wj(this.hb);Wj(this.ca);this.ed=this.ic=this.mc=
null;this.Ha=new L.Ga(16);this.U=new L.Ga(573);Wj(this.U);this.ub=this.Ka=0;this.depth=new L.Ga(573);Wj(this.depth);this.ba=this.ha=this.ka=this.matches=this.Ab=this.Na=this.Ib=this.sa=this.Ob=this.Ic=0}
function jk(a,b){if(!a||!a.state||5<b||0>b)return a?Vj(a,-2):-2;var c=a.state;if(!a.Pb||!a.input&&0!==a.ga||666===c.status&&4!==b)return Vj(a,0===a.I?-5:-2);c.D=a;var d=c.vb;c.vb=b;if(42===c.status)if(2===c.wrap)a.C=0,M(c,31),M(c,139),M(c,8),c.B?(M(c,(c.B.text?1:0)+(c.B.Ta?2:0)+(c.B.Sa?4:0)+(c.B.name?8:0)+(c.B.comment?16:0)),M(c,c.B.time&255),M(c,c.B.time>>8&255),M(c,c.B.time>>16&255),M(c,c.B.time>>24&255),M(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),M(c,c.B.os&255),c.B.Sa&&c.B.Sa.length&&(M(c,
c.B.Sa.length&255),M(c,c.B.Sa.length>>8&255)),c.B.Ta&&(a.C=ij(a.C,c.S,c.pending,0)),c.wa=0,c.status=69):(M(c,0),M(c,0),M(c,0),M(c,0),M(c,0),M(c,9===c.level?2:2<=c.strategy||2>c.level?4:0),M(c,3),c.status=113);else{var e=8+(c.Wc-8<<4)<<8;e|=(2<=c.strategy||2>c.level?0:6>c.level?1:6===c.level?2:3)<<6;0!==c.o&&(e|=32);c.status=113;Zj(c,e+(31-e%31));0!==c.o&&(Zj(c,a.C>>>16),Zj(c,a.C&65535));a.C=1}if(69===c.status)if(c.B.Sa){for(e=c.pending;c.wa<(c.B.Sa.length&65535)&&(c.pending!==c.ta||(c.B.Ta&&c.pending>
e&&(a.C=ij(a.C,c.S,c.pending-e,e)),Xj(a),e=c.pending,c.pending!==c.ta));)M(c,c.B.Sa[c.wa]&255),c.wa++;c.B.Ta&&c.pending>e&&(a.C=ij(a.C,c.S,c.pending-e,e));c.wa===c.B.Sa.length&&(c.wa=0,c.status=73)}else c.status=73;if(73===c.status)if(c.B.name){e=c.pending;do{if(c.pending===c.ta&&(c.B.Ta&&c.pending>e&&(a.C=ij(a.C,c.S,c.pending-e,e)),Xj(a),e=c.pending,c.pending===c.ta)){var f=1;break}f=c.wa<c.B.name.length?c.B.name.charCodeAt(c.wa++)&255:0;M(c,f)}while(0!==f);c.B.Ta&&c.pending>e&&(a.C=ij(a.C,c.S,c.pending-
e,e));0===f&&(c.wa=0,c.status=91)}else c.status=91;if(91===c.status)if(c.B.comment){e=c.pending;do{if(c.pending===c.ta&&(c.B.Ta&&c.pending>e&&(a.C=ij(a.C,c.S,c.pending-e,e)),Xj(a),e=c.pending,c.pending===c.ta)){f=1;break}f=c.wa<c.B.comment.length?c.B.comment.charCodeAt(c.wa++)&255:0;M(c,f)}while(0!==f);c.B.Ta&&c.pending>e&&(a.C=ij(a.C,c.S,c.pending-e,e));0===f&&(c.status=103)}else c.status=103;103===c.status&&(c.B.Ta?(c.pending+2>c.ta&&Xj(a),c.pending+2<=c.ta&&(M(c,a.C&255),M(c,a.C>>8&255),a.C=0,
c.status=113)):c.status=113);if(0!==c.pending){if(Xj(a),0===a.I)return c.vb=-1,0}else if(0===a.ga&&(b<<1)-(4<b?9:0)<=(d<<1)-(4<d?9:0)&&4!==b)return Vj(a,-5);if(666===c.status&&0!==a.ga)return Vj(a,-5);if(0!==a.ga||0!==c.u||0!==b&&666!==c.status){d=2===c.strategy?fk(c,b):3===c.strategy?ek(c,b):hk[c.level].se(c,b);if(3===d||4===d)c.status=666;if(1===d||3===d)return 0===a.I&&(c.vb=-1),0;if(2===d&&(1===b?(Fj(c,2,3),Gj(c,256,tj),16===c.ba?(Ej(c,c.ha),c.ha=0,c.ba=0):8<=c.ba&&(c.S[c.pending++]=c.ha&255,
c.ha>>=8,c.ba-=8)):5!==b&&(Fj(c,0,3),Lj(c,0,0),3===b&&(Wj(c.head),0===c.u&&(c.o=0,c.la=0,c.ka=0))),Xj(a),0===a.I))return c.vb=-1,0}if(4!==b)return 0;if(0>=c.wrap)return 1;2===c.wrap?(M(c,a.C&255),M(c,a.C>>8&255),M(c,a.C>>16&255),M(c,a.C>>24&255),M(c,a.nb&255),M(c,a.nb>>8&255),M(c,a.nb>>16&255),M(c,a.nb>>24&255)):(Zj(c,a.C>>>16),Zj(c,a.C&65535));Xj(a);0<c.wrap&&(c.wrap=-c.wrap);return 0!==c.pending?0:1}
;var kk={};kk=function(){this.input=null;this.nb=this.ga=this.kb=0;this.Pb=null;this.Uc=this.I=this.yb=0;this.msg="";this.state=null;this.yc=2;this.C=0};var lk=Object.prototype.toString;
function mk(a){if(!(this instanceof mk))return new mk(a);a=this.options=L.assign({level:-1,method:8,chunkSize:16384,Za:15,Ie:8,strategy:0,K:""},a||{});a.raw&&0<a.Za?a.Za=-a.Za:a.ye&&0<a.Za&&16>a.Za&&(a.Za+=16);this.err=0;this.msg="";this.ended=!1;this.chunks=[];this.D=new kk;this.D.I=0;var b=this.D;var c=a.level,d=a.method,e=a.Za,f=a.Ie,g=a.strategy;if(b){var h=1;-1===c&&(c=6);0>e?(h=0,e=-e):15<e&&(h=2,e-=16);if(1>f||9<f||8!==d||8>e||15<e||0>c||9<c||0>g||4<g)b=Vj(b,-2);else{8===e&&(e=9);var k=new ik;
b.state=k;k.D=b;k.wrap=h;k.B=null;k.Wc=e;k.ea=1<<k.Wc;k.Ya=k.ea-1;k.Ec=f+7;k.lc=1<<k.Ec;k.Ia=k.lc-1;k.Ja=~~((k.Ec+3-1)/3);k.window=new L.cb(2*k.ea);k.head=new L.Ga(k.lc);k.Fa=new L.Ga(k.ea);k.Ob=1<<f+6;k.ta=4*k.Ob;k.S=new L.cb(k.ta);k.Ib=1*k.Ob;k.Ic=3*k.Ob;k.level=c;k.strategy=g;k.method=d;if(b&&b.state){b.nb=b.Uc=0;b.yc=2;c=b.state;c.pending=0;c.Qb=0;0>c.wrap&&(c.wrap=-c.wrap);c.status=c.wrap?42:113;b.C=2===c.wrap?0:1;c.vb=0;if(!Tj){d=Array(16);for(f=g=0;28>f;f++)for(xj[f]=g,e=0;e<1<<pj[f];e++)wj[g++]=
f;wj[g-1]=f;for(f=g=0;16>f;f++)for(yj[f]=g,e=0;e<1<<qj[f];e++)vj[g++]=f;for(g>>=7;30>f;f++)for(yj[f]=g<<7,e=0;e<1<<qj[f]-7;e++)vj[256+g++]=f;for(e=0;15>=e;e++)d[e]=0;for(e=0;143>=e;)tj[2*e+1]=8,e++,d[8]++;for(;255>=e;)tj[2*e+1]=9,e++,d[9]++;for(;279>=e;)tj[2*e+1]=7,e++,d[7]++;for(;287>=e;)tj[2*e+1]=8,e++,d[8]++;Ij(tj,287,d);for(e=0;30>e;e++)uj[2*e+1]=5,uj[2*e]=Hj(e,5);Aj=new zj(tj,pj,257,286,15);Bj=new zj(uj,qj,0,30,15);Cj=new zj([],rj,0,19,7);Tj=!0}c.mc=new Dj(c.ja,Aj);c.ic=new Dj(c.hb,Bj);c.ed=
new Dj(c.ca,Cj);c.ha=0;c.ba=0;Jj(c);c=0}else c=Vj(b,-2);0===c&&(b=b.state,b.Ud=2*b.ea,Wj(b.head),b.Jc=hk[b.level].Ge,b.sd=hk[b.level].xe,b.Bd=hk[b.level].Ke,b.zd=hk[b.level].Fe,b.o=0,b.la=0,b.u=0,b.ka=0,b.J=b.na=2,b.ib=0,b.G=0);b=c}}else b=-2;if(0!==b)throw Error(nj[b]);a.header&&(b=this.D)&&b.state&&2===b.state.wrap&&(b.state.B=a.header);if(a.Jb){var m;"string"===typeof a.Jb?m=gj(a.Jb):"[object ArrayBuffer]"===lk.call(a.Jb)?m=new Uint8Array(a.Jb):m=a.Jb;a=this.D;f=m;g=f.length;if(a&&a.state)if(m=
a.state,b=m.wrap,2===b||1===b&&42!==m.status||m.u)b=-2;else{1===b&&(a.C=hj(a.C,f,g,0));m.wrap=0;g>=m.ea&&(0===b&&(Wj(m.head),m.o=0,m.la=0,m.ka=0),c=new L.cb(m.ea),L.qb(c,f,g-m.ea,m.ea,0),f=c,g=m.ea);c=a.ga;d=a.kb;e=a.input;a.ga=g;a.kb=0;a.input=f;for(bk(m);3<=m.u;){f=m.o;g=m.u-2;do m.G=(m.G<<m.Ja^m.window[f+3-1])&m.Ia,m.Fa[f&m.Ya]=m.head[m.G],m.head[m.G]=f,f++;while(--g);m.o=f;m.u=2;bk(m)}m.o+=m.u;m.la=m.o;m.ka=m.u;m.u=0;m.J=m.na=2;m.ib=0;a.kb=d;a.input=e;a.ga=c;m.wrap=b;b=0}else b=-2;if(0!==b)throw Error(nj[b]);
this.Ft=!0}}
mk.prototype.push=function(a,b){var c=this.D,d=this.options.chunkSize;if(this.ended)return!1;var e=b===~~b?b:!0===b?4:0;"string"===typeof a?c.input=gj(a):"[object ArrayBuffer]"===lk.call(a)?c.input=new Uint8Array(a):c.input=a;c.kb=0;c.ga=c.input.length;do{0===c.I&&(c.Pb=new L.cb(d),c.yb=0,c.I=d);a=jk(c,e);if(1!==a&&0!==a)return nk(this,a),this.ended=!0,!1;if(0===c.I||0===c.ga&&(4===e||2===e))if("string"===this.options.K){var f=L.Tc(c.Pb,c.yb);b=f;f=f.length;if(65537>f&&(b.subarray&&dj||!b.subarray))b=
String.fromCharCode.apply(null,L.Tc(b,f));else{for(var g="",h=0;h<f;h++)g+=String.fromCharCode(b[h]);b=g}this.chunks.push(b)}else b=L.Tc(c.Pb,c.yb),this.chunks.push(b)}while((0<c.ga||0===c.I)&&1!==a);if(4===e)return(c=this.D)&&c.state?(d=c.state.status,42!==d&&69!==d&&73!==d&&91!==d&&103!==d&&113!==d&&666!==d?a=Vj(c,-2):(c.state=null,a=113===d?Vj(c,-3):0)):a=-2,nk(this,a),this.ended=!0,0===a;2===e&&(nk(this,0),c.I=0);return!0};
function nk(a,b){0===b&&(a.result="string"===a.options.K?a.chunks.join(""):L.pd(a.chunks));a.chunks=[];a.err=b;a.msg=a.D.msg}
function ok(a){var b=b||{};b.ye=!0;b=new mk(b);b.push(a,!0);if(b.err)throw b.msg||nj[b.err];return b.result}
;function pk(a){return Jb(null===a?"null":void 0===a?"undefined":a)}
;function qk(a){this.name=a}
;var rk=new qk("rawColdConfigGroup");var sk=new qk("rawHotConfigGroup");function tk(a){J.call(this,a)}
v(tk,J);function uk(a,b){return G(a,1,b)}
;function vk(a){J.call(this,a,-1,wk)}
v(vk,J);var wk=[1];function xk(a){J.call(this,a)}
v(xk,J);function yk(a){J.call(this,a)}
v(yk,J);function zk(a){J.call(this,a)}
v(zk,J);function Ak(a){J.call(this,a,-1,Bk)}
v(Ak,J);var Bk=[2];function Ck(a){J.call(this,a,-1,Dk)}
v(Ck,J);Ck.prototype.getPlayerType=function(){return Od(this,36)};
Ck.prototype.setHomeGroupInfo=function(a){return I(this,Ak,81,a)};
Ck.prototype.clearLocationPlayabilityToken=function(){return G(this,89,void 0,!1)};
var Dk=[9,66,24,32,86,100,101];function Ek(a){J.call(this,a)}
v(Ek,J);Ek.prototype.getKey=function(){return be(this,1)};
Ek.prototype.getValue=function(){return be(this,2===Sd(this,Fk)?2:-1)};
var Fk=[2,3,4,5,6];function Gk(a){J.call(this,a,-1,Hk)}
v(Gk,J);var Hk=[15,26,28];function Ik(a){J.call(this,a,-1,Jk)}
v(Ik,J);var Jk=[5];function Kk(a){J.call(this,a)}
v(Kk,J);function Lk(a){J.call(this,a,-1,Mk)}
v(Lk,J);Lk.prototype.setSafetyMode=function(a){return G(this,5,a)};
var Mk=[12];function Nk(a){J.call(this,a,-1,Ok)}
v(Nk,J);Nk.prototype.l=function(a){return I(this,Ck,1,a)};
var Ok=[12];var Pk=new qk("continuationCommand");var Qk=new qk("webCommandMetadata");var Rk=new qk("signalServiceEndpoint");var Sk={tk:"EMBEDDED_PLAYER_MODE_UNKNOWN",qk:"EMBEDDED_PLAYER_MODE_DEFAULT",sk:"EMBEDDED_PLAYER_MODE_PFP",rk:"EMBEDDED_PLAYER_MODE_PFL"};var Tk=new qk("feedbackEndpoint");var Uk={ct:"WEB_DISPLAY_MODE_UNKNOWN",Xs:"WEB_DISPLAY_MODE_BROWSER",Zs:"WEB_DISPLAY_MODE_MINIMAL_UI",bt:"WEB_DISPLAY_MODE_STANDALONE",Ys:"WEB_DISPLAY_MODE_FULLSCREEN"};function Vk(a){J.call(this,a)}
v(Vk,J);Vk.prototype.getKey=function(){return be(this,1)};
Vk.prototype.getValue=function(){return be(this,2)};function Wk(a){J.call(this,a,-1,Xk)}
v(Wk,J);var Xk=[4,5];function rl(a){J.call(this,a)}
v(rl,J);function sl(a){J.call(this,a)}
v(sl,J);var tl=[2,3,4];function ul(a){J.call(this,a)}
v(ul,J);ul.prototype.getMessage=function(){return be(this,1)};function vl(a){J.call(this,a)}
v(vl,J);function wl(a){J.call(this,a)}
v(wl,J);function xl(a){J.call(this,a,-1,yl)}
v(xl,J);var yl=[10,17];function zl(a){J.call(this,a)}
v(zl,J);function Al(a){J.call(this,a)}
v(Al,J);function Bl(a){J.call(this,a)}
v(Bl,J);function Cl(a){J.call(this,a)}
v(Cl,J);function Dl(a){J.call(this,a)}
v(Dl,J);function El(a){J.call(this,a,-1,Fl)}
v(El,J);El.prototype.getVideoData=function(){return Td(this,Dl,15)};
var Fl=[4];function Gl(a){J.call(this,a)}
v(Gl,J);function Hl(a,b){I(a,Bl,1,b)}
;function Il(a){J.call(this,a)}
v(Il,J);function Jl(a,b){return I(a,Bl,1,b)}
Il.prototype.h=function(a){return G(this,2,a)};function Kl(a){J.call(this,a,-1,Ll)}
v(Kl,J);Kl.prototype.h=function(a){return G(this,1,a)};
function Ml(a,b){return I(a,Bl,2,b)}
var Ll=[3];function Nl(a){J.call(this,a)}
v(Nl,J);Nl.prototype.h=function(a){return G(this,1,a)};function Ol(a){J.call(this,a)}
v(Ol,J);Ol.prototype.h=function(a){return G(this,1,a)};function Pl(a){J.call(this,a)}
v(Pl,J);Pl.prototype.h=function(a){return G(this,1,a)};function Ql(a){J.call(this,a)}
v(Ql,J);Ql.prototype.h=function(a){return G(this,1,a)};function Rl(a){J.call(this,a)}
v(Rl,J);function Sl(a){J.call(this,a)}
v(Sl,J);function Tl(a){var b=new Sl;return G(b,1,a)}
Sl.prototype.getId=function(){return be(this,2)};
function Ul(a,b){return G(a,2,b)}
;function Vl(a){J.call(this,a)}
v(Vl,J);function Wl(a){J.call(this,a,-1,Xl)}
v(Wl,J);Wl.prototype.getPlayerType=function(){return ae(Od(this,7),0)};
Wl.prototype.setVideoId=function(a){return G(this,19,a)};
function Yl(a,b){Yd(a,68,Sl,b)}
var Xl=[83,68];function Zl(a){J.call(this,a)}
v(Zl,J);function $l(a){J.call(this,a)}
v($l,J);function am(a){J.call(this,a)}
v(am,J);function bm(a){J.call(this,a,459)}
v(bm,J);
var cm=[2,3,5,6,7,11,13,20,21,22,23,24,28,32,37,45,59,72,73,74,76,78,79,80,85,91,97,100,102,105,111,117,119,126,127,136,146,148,151,156,157,158,159,163,164,168,176,177,178,179,184,188,189,190,191,193,194,195,196,197,198,199,200,201,202,203,204,205,206,208,209,215,219,222,225,226,227,229,232,233,234,240,241,244,247,248,249,251,254,255,256,257,258,259,260,261,266,270,272,278,288,291,293,300,304,308,309,310,311,313,314,319,320,321,323,324,327,328,330,331,332,334,337,338,340,344,348,350,351,352,353,354,
355,356,357,358,361,363,364,368,369,370,373,374,375,378,380,381,383,388,389,402,403,410,411,412,413,414,415,416,417,418,423,424,425,426,427,429,430,431,439,441,444,448,458];var dm={zl:0,fl:1,nl:2,ol:4,vl:8,pl:16,ql:32,yl:64,xl:128,jl:256,ll:512,sl:1024,kl:2048,ml:4096,il:8192,rl:16384,wl:32768,ul:65536};function em(a){J.call(this,a)}
v(em,J);function fm(a){J.call(this,a)}
v(fm,J);fm.prototype.setVideoId=function(a){return Rd(this,1,gm,a)};
fm.prototype.getPlaylistId=function(){var a=2===Sd(this,gm)?2:-1;return Od(this,a)};
var gm=[1,2];function hm(a){J.call(this,a,-1,im)}
v(hm,J);var im=[3];var jm=new qk("webPlayerShareEntityServiceEndpoint");var km=new qk("playlistEditEndpoint");var lm=new qk("modifyChannelNotificationPreferenceEndpoint");var mm=new qk("unsubscribeEndpoint");var nm=new qk("subscribeEndpoint");function om(){var a=pm;A("yt.ads.biscotti.getId_")||z("yt.ads.biscotti.getId_",a)}
function qm(a){z("yt.ads.biscotti.lastId_",a)}
;function rm(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var sm=y.window,tm,um,vm=(null==sm?void 0:null==(tm=sm.yt)?void 0:tm.config_)||(null==sm?void 0:null==(um=sm.ytcfg)?void 0:um.data_)||{};z("yt.config_",vm);function wm(){rm(vm,arguments)}
function P(a,b){return a in vm?vm[a]:b}
function xm(){var a=vm.EXPERIMENT_FLAGS;return a?a.web_disable_gel_stp_ecatcher_killswitch:void 0}
;var ym=[];function zm(a){ym.forEach(function(b){return b(a)})}
function Am(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Bm(b)}}:a}
function Bm(a,b,c,d){var e=A("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=P("ERRORS",[]),e.push([a,"ERROR",b,c,d]),wm("ERRORS",e));zm(a)}
function Cm(a,b,c,d){var e=A("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=P("ERRORS",[]),e.push([a,"WARNING",b,c,d]),wm("ERRORS",e))}
;var Dm=/^[\w.]*$/,Em={q:!0,search_query:!0};function Fm(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=Gm(f[0]||""),h=Gm(f[1]||"");g in c?Array.isArray(c[g])?mb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(q){var k=q,m=f[0],n=String(Fm);k.args=[{key:m,value:f[1],query:a,method:Hm==n?"unchanged":n}];Em.hasOwnProperty(m)||Cm(k)}}return c}
var Hm=String(Fm);function Im(a){var b=[];nb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];gb(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function Jm(a){"?"==a.charAt(0)&&(a=a.substr(1));return Fm(a,"&")}
function Km(a){return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),Jm(1<a.length?a[1]:a[0])):{}}
function Lm(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=Jm(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return wc(a,e)+d}
function Mm(a){if(!b)var b=window.location.href;var c=oc(1,a),d=pc(a);c&&d?(a=a.match(kc),b=b.match(kc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?pc(b)==d&&(Number(oc(4,b))||null)==(Number(oc(4,a))||null):!0;return a}
function Gm(a){return a&&a.match(Dm)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function Nm(a){var b=Om;a=void 0===a?A("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=ei;e.flash="0";a:{try{var f=b.h.top.location.href}catch(ja){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?Lh:g;try{var h=g.history.length}catch(ja){h=0}e.u_his=h;var k;e.u_h=null==(k=Lh.screen)?void 0:k.height;var m;e.u_w=null==(m=Lh.screen)?void 0:m.width;var n;e.u_ah=null==(n=Lh.screen)?void 0:n.availHeight;var q;e.u_aw=
null==(q=Lh.screen)?void 0:q.availWidth;var u;e.u_cd=null==(u=Lh.screen)?void 0:u.colorDepth}catch(ja){}h=b.h;try{var t=h.screenX;var B=h.screenY}catch(ja){}try{var D=h.outerWidth;var F=h.outerHeight}catch(ja){}try{var N=h.innerWidth;var O=h.innerHeight}catch(ja){}try{var Q=h.screenLeft;var ca=h.screenTop}catch(ja){}try{N=h.innerWidth,O=h.innerHeight}catch(ja){}try{var X=h.screen.availWidth;var vb=h.screen.availTop}catch(ja){}t=[Q,ca,t,B,X,vb,D,F,N,O];try{var Ya=(b.h.top||window).document,sa="CSS1Compat"==
Ya.compatMode?Ya.documentElement:Ya.body;var H=(new mf(sa.clientWidth,sa.clientHeight)).round()}catch(ja){H=new mf(-12245933,-12245933)}Ya=H;H={};var oa=void 0===oa?y:oa;sa=new ni;oa.SVGElement&&oa.document.createElementNS&&sa.set(0);B=bi();B["allow-top-navigation-by-user-activation"]&&sa.set(1);B["allow-popups-to-escape-sandbox"]&&sa.set(2);oa.crypto&&oa.crypto.subtle&&sa.set(3);oa.TextDecoder&&oa.TextEncoder&&sa.set(4);oa=oi(sa);H.bc=oa;H.bih=Ya.height;H.biw=Ya.width;H.brdim=t.join();b=b.i;b=(H.vis=
b.prerendering?3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,H.wgl=!!Lh.WebGLRenderingContext,H);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var Om=new function(){var a=window.document;this.h=window;this.i=a};
z("yt.ads_.signals_.getAdSignalsString",function(a){return Im(Nm(a))});Date.now();function R(a){a=Pm(a);return"string"===typeof a&&"false"===a?!1:!!a}
function Qm(a,b){a=Pm(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function Rm(){return P("EXPERIMENTS_TOKEN","")}
function Pm(a){var b=P("EXPERIMENTS_FORCED_FLAGS",{})||{};return void 0!==b[a]?b[a]:P("EXPERIMENT_FLAGS",{})[a]}
function Sm(){for(var a=[],b=P("EXPERIMENTS_FORCED_FLAGS",{}),c=r(Object.keys(b)),d=c.next();!d.done;d=c.next())d=d.value,a.push({key:d,value:String(b[d])});c=P("EXPERIMENT_FLAGS",{});var e=r(Object.keys(c));for(d=e.next();!d.done;d=e.next())d=d.value,d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var Tm="XMLHttpRequest"in y?function(){return new XMLHttpRequest}:null;
function Um(){if(!Tm)return null;var a=Tm();return"open"in a?a:null}
function Vm(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function Wm(a,b){"function"===typeof a&&(a=Am(a));return window.setTimeout(a,b)}
;var Xm={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM","X-Goog-AuthUser":"SESSION_INDEX","X-Goog-PageId":"DELEGATED_SESSION_ID"},Ym="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ia(fi)),Zm=!1;
function $m(a,b){b=void 0===b?{}:b;var c=Mm(a),d=R("web_ajax_ignore_global_headers_if_set"),e;for(e in Xm){var f=P(Xm[e]);"X-Goog-Visitor-Id"!==e||f||(f=P("VISITOR_DATA"));!f||!c&&pc(a)||d&&void 0!==b[e]||!(R("move_vss_away_from_login_info_cookie")||"X-Goog-AuthUser"!==e&&"X-Goog-PageId"!==e)||(b[e]=f)}R("move_vss_away_from_login_info_cookie")&&(b["X-Yt-Auth-Test"]="test");"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!pc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());
if(c||!pc(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}document.location.hostname.endsWith("youtubeeducation.com")||!c&&pc(a)||(b["X-YouTube-Ad-Signals"]=Im(Nm()));return b}
function an(a){var b=window.location.search,c=pc(a);R("debug_handle_relative_url_for_query_forward_killswitch")||!c&&Mm(a)&&(c=document.location.hostname);var d=nc(oc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=Jm(b),f={};gb(Ym,function(g){e[g]&&(f[g]=e[g])});
return Lm(a,f||{},!1)}
function bn(a,b){var c=b.format||"JSON";a=cn(a,b);var d=dn(a,b),e=!1,f=en(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);var m=Vm(k),n=null,q=400<=k.status&&500>k.status,u=500<=k.status&&600>k.status;if(m||q||u)n=fn(a,c,k,b.convertToSafeHtml);if(m)a:if(k&&204==k.status)m=!0;else{switch(c){case "XML":m=0==parseInt(n&&n.return_code,10);break a;case "RAW":m=!0;break a}m=!!n}n=n||{};q=b.context||y;m?b.onSuccess&&b.onSuccess.call(q,k,n):b.onError&&b.onError.call(q,k,n);b.onFinish&&b.onFinish.call(q,
k,n)}},b.method,d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=Wm(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||y,f))},d)}return f}
function cn(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=P("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=Lm(a,b||{},!0);return a}
function dn(a,b){var c=P("XSRF_FIELD_NAME"),d=P("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=P("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||pc(a)&&!b.withCredentials&&pc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);(R("ajax_parse_query_data_only_when_filled")&&f&&0<Object.keys(f).length||f)&&"string"===typeof e&&(e=Jm(e),yb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?
JSON.stringify(e):uc(e));f=e||f&&!qb(f);!Zm&&f&&"POST"!=b.method&&(Zm=!0,Bm(Error("AJAX request with postData should use POST")));return e}
function fn(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Cm(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?gn(a):null)e={},gb(a.getElementsByTagName("*"),function(g){e[g.tagName]=hn(g)})}d&&jn(e);
return e}
function jn(a){if(Ra(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b],e=Ab();d=e?e.createHTML(d):d;a[c]=new dc(d)}else jn(a[b])}}
function gn(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function hn(a){var b="";gb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function kn(a,b){b.method="POST";b.postParams||(b.postParams={});return bn(a,b)}
function en(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&Am(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=Um();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;R("debug_forward_web_query_parameters")&&(a=an(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=$m(a,e))for(var m in e)k.setRequestHeader(m,e[m]),"content-type"==m.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;var ln=Yc||Zc;function mn(a){var b=Ub();return b?0<=b.toLowerCase().indexOf(a):!1}
;var nn=[{Kc:function(a){return"Cannot read property '"+a.key+"'"},
oc:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Kc:function(a){return"Cannot call '"+a.key+"'"},
oc:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Kc:function(a){return a.key+" is not defined"},
oc:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var pn={Va:[],Ra:[{callback:on,weight:500}]};function on(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function qn(){this.Ra=[];this.Va=[]}
var rn;function sn(){if(!rn){var a=rn=new qn;a.Va.length=0;a.Ra.length=0;pn.Va&&a.Va.push.apply(a.Va,pn.Va);pn.Ra&&a.Ra.push.apply(a.Ra,pn.Ra)}return rn}
;var tn=new Ji;function un(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=vn(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=vn(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=vn(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function vn(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function wn(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=xn(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=un(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?xn(e+".ve",f,g,h):0;d+=g;d+=xn(e,a[e],b,c);if(500<d)break}}else c[b]=yn(a),d+=c[b].length;else c[b]=yn(a),d+=c[b].length;return d}
function xn(a,b,c,d){c+="."+a;a=yn(b);d[c]=a;return c.length+a.length}
function yn(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;function zn(){this.hf=!0}
function An(){zn.h||(zn.h=new zn);return zn.h}
function Bn(a,b){a={};var c=Dg([]);c&&(a.Authorization=c,c=b=null==b?void 0:b.sessionIndex,void 0===c&&(c=Number(P("SESSION_INDEX",0)),c=isNaN(c)?0:c),R("voice_search_auth_header_removal")||(a["X-Goog-AuthUser"]=c.toString()),"INNERTUBE_HOST_OVERRIDE"in vm||(a["X-Origin"]=window.location.origin),void 0===b&&"DELEGATED_SESSION_ID"in vm&&(a["X-Goog-PageId"]=P("DELEGATED_SESSION_ID")));return a}
;var Cn={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};function Dn(a){var b=this;this.i=void 0;this.h=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.i=c});
a.addEventListener("appinstalled",function(){b.h=!0},{once:!0})}
function En(){if(!y.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return y.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":y.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":y.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":y.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function Fn(a,b,c,d,e){zg.set(""+a,b,{nc:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
function Gn(a,b,c){zg.remove(""+a,void 0===b?"/":b,void 0===c?"youtube.com":c)}
function Hn(){if(!zg.isEnabled())return!1;if(!zg.Nb())return!0;zg.set("TESTCOOKIESENABLED","1",{nc:60});if("1"!==zg.get("TESTCOOKIESENABLED"))return!1;zg.remove("TESTCOOKIESENABLED");return!0}
;var In=A("ytglobal.prefsUserPrefsPrefs_")||{};z("ytglobal.prefsUserPrefsPrefs_",In);function Jn(){this.h=P("ALT_PREF_COOKIE_NAME","PREF");this.i=P("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=zg.get(""+this.h,void 0);a&&this.parse(a)}
var Kn;function Ln(){Kn||(Kn=new Jn);return Kn}
l=Jn.prototype;l.get=function(a,b){Mn(a);Nn(a);a=void 0!==In[a]?In[a].toString():null;return null!=a?a:b?b:""};
l.set=function(a,b){Mn(a);Nn(a);if(null==b)throw Error("ExpectedNotNull");In[a]=b.toString()};
function On(a){return!!((Pn("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
l.remove=function(a){Mn(a);Nn(a);delete In[a]};
l.clear=function(){for(var a in In)delete In[a]};
function Nn(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function Mn(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function Pn(a){a=void 0!==In[a]?In[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
l.parse=function(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(In[d]=c.toString())}};var Qn={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},Rn={CONN_DEFAULT:0,CONN_UNKNOWN:1,CONN_NONE:2,CONN_WIFI:3,CONN_CELLULAR_2G:4,CONN_CELLULAR_3G:5,CONN_CELLULAR_4G:6,CONN_CELLULAR_UNKNOWN:7,CONN_DISCO:8,CONN_CELLULAR_5G:9,CONN_WIFI_METERED:10,CONN_CELLULAR_5G_SA:11,
CONN_CELLULAR_5G_NSA:12,CONN_INVALID:31},Sn={EFFECTIVE_CONNECTION_TYPE_UNKNOWN:0,EFFECTIVE_CONNECTION_TYPE_OFFLINE:1,EFFECTIVE_CONNECTION_TYPE_SLOW_2G:2,EFFECTIVE_CONNECTION_TYPE_2G:3,EFFECTIVE_CONNECTION_TYPE_3G:4,EFFECTIVE_CONNECTION_TYPE_4G:5},Tn={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};function Un(){var a=y.navigator;return a?a.connection:void 0}
function Vn(){var a=Un();if(a){var b=Qn[a.type||"unknown"]||"CONN_UNKNOWN";a=Qn[a.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===b&&"CONN_UNKNOWN"!==a&&(b=a);if("CONN_UNKNOWN"!==b)return b;if("CONN_UNKNOWN"!==a)return a}}
function Wn(){var a=Un();if(null!=a&&a.effectiveType)return Tn.hasOwnProperty(a.effectiveType)?Tn[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function S(a){var b=Ka.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ia(b))}
v(S,Error);function Xn(){try{return Yn(),!0}catch(a){return!1}}
function Yn(a){if(void 0!==P("DATASYNC_ID"))return P("DATASYNC_ID");throw new S("Datasync ID not set",void 0===a?"unknown":a);}
;function Zn(){}
function $n(a,b){return ao(a,0,b)}
Zn.prototype.fa=function(a,b){return ao(a,1,b)};
function bo(a){var b=A("yt.scheduler.instance.addImmediateJob");b?b(a):a()}
;function co(){Zn.apply(this,arguments)}
v(co,Zn);function eo(){co.h||(co.h=new co);return co.h}
function ao(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=A("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):Wm(a,c||0)}
co.prototype.Da=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=A("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
co.prototype.start=function(){var a=A("yt.scheduler.instance.start");a&&a()};
co.prototype.pause=function(){var a=A("yt.scheduler.instance.pause");a&&a()};
var mi=eo();function fo(a){var b=new Ui;(b=b.isAvailable()?a?new $i(b,a):b:null)||(a=new Vi(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new Qi(a):null;this.i=document.domain||window.location.hostname}
fo.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(Hg(b))}catch(f){return}else e=escape(b);Fn(a,e,c,this.i)};
fo.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=zg.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
fo.prototype.remove=function(a){this.h&&this.h.remove(a);Gn(a,"/",this.i)};var go=function(){var a;return function(){a||(a=new fo("ytidb"));return a}}();
function ho(){var a;return null==(a=go())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var io=[],jo,ko=!1;function lo(){var a={};for(jo=new mo(void 0===a.handleError?no:a.handleError,void 0===a.logEvent?oo:a.logEvent);0<io.length;)switch(a=io.shift(),a.type){case "ERROR":jo.handleError(a.payload);break;case "EVENT":jo.logEvent(a.eventType,a.payload)}}
function po(a){ko||(jo?jo.handleError(a):(io.push({type:"ERROR",payload:a}),10<io.length&&io.shift()))}
function qo(a,b){ko||(jo?jo.logEvent(a,b):(io.push({type:"EVENT",eventType:a,payload:b}),10<io.length&&io.shift()))}
;function ro(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function so(a){return a.substr(0,a.indexOf(":"))||a}
;var to={},uo=(to.AUTH_INVALID="No user identifier specified.",to.EXPLICIT_ABORT="Transaction was explicitly aborted.",to.IDB_NOT_SUPPORTED="IndexedDB is not supported.",to.MISSING_INDEX="Index not created.",to.MISSING_OBJECT_STORES="Object stores not created.",to.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",to.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",to.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
to.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",to.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",to.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",to.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",to),vo={},wo=(vo.AUTH_INVALID="ERROR",vo.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",vo.EXPLICIT_ABORT="IGNORED",vo.IDB_NOT_SUPPORTED="ERROR",vo.MISSING_INDEX=
"WARNING",vo.MISSING_OBJECT_STORES="ERROR",vo.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",vo.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",vo.QUOTA_EXCEEDED="WARNING",vo.QUOTA_MAYBE_EXCEEDED="WARNING",vo.UNKNOWN_ABORT="WARNING",vo.INCOMPATIBLE_DB_VERSION="WARNING",vo),xo={},yo=(xo.AUTH_INVALID=!1,xo.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,xo.EXPLICIT_ABORT=!1,xo.IDB_NOT_SUPPORTED=!1,xo.MISSING_INDEX=!1,xo.MISSING_OBJECT_STORES=!1,xo.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,xo.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,xo.QUOTA_EXCEEDED=!1,xo.QUOTA_MAYBE_EXCEEDED=!0,xo.UNKNOWN_ABORT=!0,xo.INCOMPATIBLE_DB_VERSION=!1,xo);function zo(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?uo[a]:c;d=void 0===d?wo[a]:d;e=void 0===e?yo[a]:e;S.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,zo.prototype)}
v(zo,S);function Ao(a,b){zo.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},uo.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,Ao.prototype)}
v(Ao,zo);function Bo(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,Bo.prototype)}
v(Bo,Error);var Co=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function Do(a,b,c,d){b=so(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof zo)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new zo("QUOTA_EXCEEDED",a);if($c&&"UnknownError"===e.name)return new zo("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof Bo)return new zo("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&Co.some(function(f){return e.message.includes(f)}))return new zo("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new zo("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",Dd:e.name})];e.level="WARNING";return e}
function Eo(a,b,c){var d=ho();return new zo("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function Fo(a){if(!a)throw Error();throw a;}
function Go(a){return a}
function Ho(a){this.h=a}
function Io(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=r(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=r(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.i=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
Io.all=function(a){return new Io(new Ho(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={ob:0};f.ob<a.length;f={ob:f.ob},++f.ob)Io.resolve(a[f.ob]).then(function(g){return function(h){d[g.ob]=h;e--;0===e&&b(d)}}(f)).catch(function(g){c(g)})}))};
Io.resolve=function(a){return new Io(new Ho(function(b,c){a instanceof Io?a.then(b,c):b(a)}))};
Io.reject=function(a){return new Io(new Ho(function(b,c){c(a)}))};
Io.prototype.then=function(a,b){var c=this,d=null!=a?a:Go,e=null!=b?b:Fo;return new Io(new Ho(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){Jo(c,c,d,f,g)}),c.i.push(function(){Ko(c,c,e,f,g)})):"FULFILLED"===c.state.status?Jo(c,c,d,f,g):"REJECTED"===c.state.status&&Ko(c,c,e,f,g)}))};
Io.prototype.catch=function(a){return this.then(void 0,a)};
function Jo(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof Io?Lo(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Ko(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof Io?Lo(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Lo(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof Io?Lo(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Mo(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function No(a){return new Promise(function(b,c){Mo(a,b,c)})}
function Oo(a){return new Io(new Ho(function(b,c){Mo(a,b,c)}))}
;function Po(a,b){return new Io(new Ho(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;var Qo=window,T=Qo.ytcsi&&Qo.ytcsi.now?Qo.ytcsi.now:Qo.performance&&Qo.performance.timing&&Qo.performance.now&&Qo.performance.timing.navigationStart?function(){return Qo.performance.timing.navigationStart+Qo.performance.now()}:function(){return(new Date).getTime()};function Ro(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(T());this.i=!1}
l=Ro.prototype;l.add=function(a,b,c){return So(this,[a],{mode:"readwrite",da:!0},function(d){return d.objectStore(a).add(b,c)})};
l.clear=function(a){return So(this,[a],{mode:"readwrite",da:!0},function(b){return b.objectStore(a).clear()})};
l.close=function(){this.h.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
l.count=function(a,b){return So(this,[a],{mode:"readonly",da:!0},function(c){return c.objectStore(a).count(b)})};
function To(a,b,c){a=a.h.createObjectStore(b,c);return new Uo(a)}
l.delete=function(a,b){return So(this,[a],{mode:"readwrite",da:!0},function(c){return c.objectStore(a).delete(b)})};
l.get=function(a,b){return So(this,[a],{mode:"readonly",da:!0},function(c){return c.objectStore(a).get(b)})};
function Vo(a,b,c){return So(a,[b],{mode:"readwrite",da:!0},function(d){d=d.objectStore(b);return Oo(d.h.put(c,void 0))})}
l.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function So(a,b,c,d){var e,f,g,h,k,m,n,q,u,t,B,D;return x(function(F){switch(F.h){case 1:var N={mode:"readonly",da:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?N.mode=c:Object.assign(N,c);e=N;a.transactionCount++;f=e.da?3:1;g=0;case 2:if(h){F.v(3);break}g++;k=Math.round(T());za(F,4);m=a.h.transaction(b,e.mode);N=new Wo(m);N=Xo(N,d);return w(F,N,6);case 6:return n=F.i,q=Math.round(T()),Yo(a,k,q,g,void 0,b.join(),e),F.return(n);case 4:u=Ba(F);t=Math.round(T());B=Do(u,a.h.name,b.join(),
a.h.version);if((D=B instanceof zo&&!B.h)||g>=f)Yo(a,k,t,g,B,b.join(),e),h=B;F.v(2);break;case 3:return F.return(Promise.reject(h))}})}
function Yo(a,b,c,d,e,f,g){b=c-b;e?(e instanceof zo&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&qo("QUOTA_EXCEEDED",{dbName:so(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof zo&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),qo("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),Zo(a,!1,d,f,b,g.tag),po(e)):Zo(a,!0,d,f,b,g.tag)}
function Zo(a,b,c,d,e,f){qo("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
l.getName=function(){return this.h.name};
function Uo(a){this.h=a}
l=Uo.prototype;l.add=function(a,b){return Oo(this.h.add(a,b))};
l.autoIncrement=function(){return this.h.autoIncrement};
l.clear=function(){return Oo(this.h.clear()).then(function(){})};
function $o(a,b,c){a.h.createIndex(b,c,{unique:!1})}
l.count=function(a){return Oo(this.h.count(a))};
function ap(a,b){return bp(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
l.delete=function(a){return a instanceof IDBKeyRange?ap(this,a):Oo(this.h.delete(a))};
l.get=function(a){return Oo(this.h.get(a))};
l.index=function(a){try{return new cp(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new Bo(a,this.h.name);throw b;}};
l.getName=function(){return this.h.name};
l.keyPath=function(){return this.h.keyPath};
function bp(a,b,c){a=a.h.openCursor(b.query,b.direction);return dp(a).then(function(d){return Po(d,c)})}
function Wo(a){var b=this;this.h=a;this.j=new Map;this.i=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.i){e=zo;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function Xo(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return r(d).next().value})}
Wo.prototype.abort=function(){this.h.abort();this.i=!0;throw new zo("EXPLICIT_ABORT");};
Wo.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.j.get(a);b||(b=new Uo(a),this.j.set(a,b));return b};
function cp(a){this.h=a}
l=cp.prototype;l.count=function(a){return Oo(this.h.count(a))};
l.delete=function(a){return ep(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
l.get=function(a){return Oo(this.h.get(a))};
l.getKey=function(a){return Oo(this.h.getKey(a))};
l.keyPath=function(){return this.h.keyPath};
l.unique=function(){return this.h.unique};
function ep(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return dp(a).then(function(d){return Po(d,c)})}
function fp(a,b){this.request=a;this.cursor=b}
function dp(a){return Oo(a).then(function(b){return b?new fp(a,b):null})}
l=fp.prototype;l.advance=function(a){this.cursor.advance(a);return dp(this.request)};
l.continue=function(a){this.cursor.continue(a);return dp(this.request)};
l.delete=function(){return Oo(this.cursor.delete()).then(function(){})};
l.getKey=function(){return this.cursor.key};
l.getValue=function(){return this.cursor.value};
l.update=function(a){return Oo(this.cursor.update(a))};function gp(a,b,c){return new Promise(function(d,e){function f(){u||(u=new Ro(g.result,{closed:q}));return u}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.ee,k=c.blocking,m=c.jf,n=c.upgrade,q=c.closed,u;g.addEventListener("upgradeneeded",function(t){try{if(null===t.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");t.dataLoss&&"none"!==t.dataLoss&&qo("IDB_DATA_CORRUPTED",{reason:t.dataLossMessage||"unknown reason",dbName:so(a)});var B=f(),D=new Wo(g.transaction);
n&&n(B,function(F){return t.oldVersion<F&&t.newVersion>=F},D);
D.done.catch(function(F){e(F)})}catch(F){e(F)}});
g.addEventListener("success",function(){var t=g.result;k&&t.addEventListener("versionchange",function(){k(f())});
t.addEventListener("close",function(){qo("IDB_UNEXPECTEDLY_CLOSED",{dbName:so(a),dbVersion:t.version});m&&m()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function hp(a,b,c){c=void 0===c?{}:c;return gp(a,b,c)}
function ip(a,b){b=void 0===b?{}:b;var c,d,e,f;return x(function(g){if(1==g.h)return za(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.ee)&&c.addEventListener("blocked",function(){e()}),w(g,No(c),4);
if(2!=g.h)return Aa(g,0);f=Ba(g);throw Do(f,a,"",-1);})}
;function jp(a,b){this.name=a;this.options=b;this.j=!0;this.m=this.l=0}
jp.prototype.i=function(a,b,c){c=void 0===c?{}:c;return hp(a,b,c)};
jp.prototype.delete=function(a){a=void 0===a?{}:a;return ip(this.name,a)};
function kp(a,b){return new zo("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function lp(a,b){if(!b)throw Eo("openWithToken",so(a.name));return mp(a)}
function mp(a){function b(){var f,g,h,k,m,n,q,u,t,B;return x(function(D){switch(D.h){case 1:return g=null!=(f=Error().stack)?f:"",za(D,2),w(D,a.i(a.name,a.options.version,d),4);case 4:h=D.i;for(var F=a.options,N=[],O=r(Object.keys(F.zb)),Q=O.next();!Q.done;Q=O.next()){Q=Q.value;var ca=F.zb[Q],X=void 0===ca.Qe?Number.MAX_VALUE:ca.Qe;!(h.h.version>=ca.Hb)||h.h.version>=X||h.h.objectStoreNames.contains(Q)||N.push(Q)}k=N;if(0===k.length){D.v(5);break}m=Object.keys(a.options.zb);n=h.objectStoreNames();
if(a.m<Qm("ytidb_reopen_db_retries",0))return a.m++,h.close(),po(new zo("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:n})),D.return(b());if(!(a.l<Qm("ytidb_remake_db_retries",1))){D.v(6);break}a.l++;return w(D,a.delete(),7);case 7:return po(new zo("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:n})),D.return(b());case 6:throw new Ao(n,m);case 5:return D.return(h);case 2:q=Ba(D);if(q instanceof DOMException?
"VersionError"!==q.name:"DOMError"in self&&q instanceof DOMError?"VersionError"!==q.name:!(q instanceof Object&&"message"in q)||"An attempt was made to open a database using a lower version than the existing version."!==q.message){D.v(8);break}return w(D,a.i(a.name,void 0,Object.assign({},d,{upgrade:void 0})),9);case 9:u=D.i;t=u.h.version;if(void 0!==a.options.version&&t>a.options.version+1)throw u.close(),a.j=!1,kp(a,t);return D.return(u);case 8:throw c(),q instanceof Error&&!R("ytidb_async_stack_killswitch")&&
(q.stack=q.stack+"\n"+g.substring(g.indexOf("\n")+1)),Do(q,a.name,"",null!=(B=a.options.version)?B:-1);}})}
function c(){a.h===e&&(a.h=void 0)}
if(!a.j)throw kp(a);if(a.h)return a.h;var d={blocking:function(f){f.close()},
closed:c,jf:c,upgrade:a.options.upgrade};var e=b();a.h=e;return a.h}
;var np=new jp("YtIdbMeta",{zb:{databases:{Hb:1}},upgrade:function(a,b){b(1)&&To(a,"databases",{keyPath:"actualName"})}});
function op(a,b){var c;return x(function(d){if(1==d.h)return w(d,lp(np,b),2);c=d.i;return d.return(So(c,["databases"],{da:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Oo(f.h.put(a,void 0)).then(function(){})})}))})}
function pp(a,b){var c;return x(function(d){if(1==d.h)return a?w(d,lp(np,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function qp(a,b){var c,d;return x(function(e){return 1==e.h?(c=[],w(e,lp(np,b),2)):3!=e.h?(d=e.i,w(e,So(d,["databases"],{da:!0,mode:"readonly"},function(f){c.length=0;return bp(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function rp(a){return qp(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
function sp(a,b,c){return qp(function(d){return c?void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)},b)}
function tp(a){var b,c;return x(function(d){if(1==d.h)return b=Yn("YtIdbMeta hasAnyMeta other"),w(d,qp(function(e){return void 0!==e.userIdentifier&&e.userIdentifier!==b},a),2);
c=d.i;return d.return(0<c.length)})}
;var up,vp=new function(){}(new function(){});
function wp(){var a,b,c,d;return x(function(e){switch(e.h){case 1:a=ho();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=ln)f=/WebKit\/([0-9]+)/.exec(Ub()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Ub()),f=!(f&&602<=parseInt(f[1],10)));if(f||Ic)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
za(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return w(e,op(d,vp),4);case 4:return w(e,pp("yt-idb-test-do-not-use",vp),5);case 5:return e.return(!0);case 2:return Ba(e),e.return(!1)}})}
function xp(){if(void 0!==up)return up;ko=!0;return up=wp().then(function(a){ko=!1;var b;if(null!=(b=go())&&b.h){var c;b={hasSucceededOnce:(null==(c=ho())?void 0:c.hasSucceededOnce)||a};var d;null==(d=go())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function yp(){return A("ytglobal.idbToken_")||void 0}
function zp(){var a=yp();return a?Promise.resolve(a):xp().then(function(b){(b=b?vp:void 0)&&z("ytglobal.idbToken_",b);return b})}
;var Ap=0;function Bp(a,b){Ap||(Ap=mi.fa(function(){var c,d,e,f,g;return x(function(h){switch(h.h){case 1:return w(h,zp(),2);case 2:c=h.i;if(!c)return h.return();d=!0;za(h,3);return w(h,sp(a,c,b),5);case 5:e=h.i;if(!e.length){d=!1;h.v(6);break}f=e[0];return w(h,ip(f.actualName),7);case 7:return w(h,pp(f.actualName,c),6);case 6:Aa(h,4);break;case 3:g=Ba(h),po(g),d=!1;case 4:mi.Da(Ap),Ap=0,d&&Bp(a,b),h.h=0}})}))}
function Cp(){var a;return x(function(b){return 1==b.h?w(b,zp(),2):(a=b.i)?b.return(tp(a)):b.return(!1)})}
new Jh;function Dp(a){if(!Xn())throw a=new zo("AUTH_INVALID",{dbName:a}),po(a),a;var b=Yn();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function Ep(a,b,c,d){var e,f,g,h,k,m;return x(function(n){switch(n.h){case 1:return f=null!=(e=Error().stack)?e:"",w(n,zp(),2);case 2:g=n.i;if(!g)throw h=Eo("openDbImpl",a,b),R("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),po(h),h;ro(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:Dp(a);za(n,3);return w(n,op(k,g),5);case 5:return w(n,hp(k.actualName,b,d),6);case 6:return n.return(n.i);case 3:return m=Ba(n),za(n,7),w(n,pp(k.actualName,g),9);case 9:Aa(n,
8);break;case 7:Ba(n);case 8:throw m;}})}
function Fp(a,b,c){c=void 0===c?{}:c;return Ep(a,b,!1,c)}
function Gp(a,b,c){c=void 0===c?{}:c;return Ep(a,b,!0,c)}
function Hp(a,b){b=void 0===b?{}:b;var c,d;return x(function(e){if(1==e.h)return w(e,zp(),2);if(3!=e.h){c=e.i;if(!c)return e.return();ro(a);d=Dp(a);return w(e,ip(d.actualName,b),3)}return w(e,pp(d.actualName,c),0)})}
function Ip(a,b,c){a=a.map(function(d){return x(function(e){return 1==e.h?w(e,ip(d.actualName,b),2):w(e,pp(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function Jp(){var a=void 0===a?{}:a;var b,c;return x(function(d){if(1==d.h)return w(d,zp(),2);if(3!=d.h){b=d.i;if(!b)return d.return();ro("LogsDatabaseV2");return w(d,rp(b),3)}c=d.i;return w(d,Ip(c,a,b),0)})}
function Kp(a,b){b=void 0===b?{}:b;var c;return x(function(d){if(1==d.h)return w(d,zp(),2);if(3!=d.h){c=d.i;if(!c)return d.return();ro(a);return w(d,ip(a,b),3)}return w(d,pp(a,c),0)})}
;function Lp(a,b){jp.call(this,a,b);this.options=b;ro(a)}
v(Lp,jp);function Mp(a,b){var c;return function(){c||(c=new Lp(a,b));return c}}
Lp.prototype.i=function(a,b,c){c=void 0===c?{}:c;return(this.options.uc?Gp:Fp)(a,b,Object.assign({},c))};
Lp.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.uc?Kp:Hp)(this.name,a)};
function Np(a,b){return Mp(a,b)}
;var Op={},Pp=Np("ytGcfConfig",{zb:(Op.coldConfigStore={Hb:1},Op.hotConfigStore={Hb:1},Op),uc:!1,upgrade:function(a,b){b(1)&&($o(To(a,"hotConfigStore",{keyPath:"key",autoIncrement:!0}),"hotTimestampIndex","timestamp"),$o(To(a,"coldConfigStore",{keyPath:"key",autoIncrement:!0}),"coldTimestampIndex","timestamp"))},
version:1});function Qp(a){return lp(Pp(),a)}
function Rp(a,b,c){var d,e,f;return x(function(g){switch(g.h){case 1:return d={config:a,hashData:b,timestamp:T()},w(g,Qp(c),2);case 2:return e=g.i,w(g,e.clear("hotConfigStore"),3);case 3:return w(g,Vo(e,"hotConfigStore",d),4);case 4:return f=g.i,g.return(f)}})}
function Sp(a,b,c,d){var e,f,g;return x(function(h){switch(h.h){case 1:return e={config:a,hashData:b,configData:c,timestamp:T()},w(h,Qp(d),2);case 2:return f=h.i,w(h,f.clear("coldConfigStore"),3);case 3:return w(h,Vo(f,"coldConfigStore",e),4);case 4:return g=h.i,h.return(g)}})}
function Tp(a){var b,c;return x(function(d){return 1==d.h?w(d,Qp(a),2):3!=d.h?(b=d.i,c=void 0,w(d,So(b,["coldConfigStore"],{mode:"readwrite",da:!0},function(e){return ep(e.objectStore("coldConfigStore").index("coldTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
function Up(a){var b,c;return x(function(d){return 1==d.h?w(d,Qp(a),2):3!=d.h?(b=d.i,c=void 0,w(d,So(b,["hotConfigStore"],{mode:"readwrite",da:!0},function(e){return ep(e.objectStore("hotConfigStore").index("hotTimestampIndex"),{direction:"prev"},function(f){c=f.getValue()})}),3)):d.return(c)})}
;function Vp(){this.h=0}
function Wp(a,b,c){var d,e,f;return x(function(g){if(1==g.h){if(!R("update_log_event_config"))return g.v(0);c&&(a.i=c,z("yt.gcf.config.hotConfigGroup",a.i));a.hotHashData=b;z("yt.gcf.config.hotHashData",a.hotHashData);return(d=yp())?c?g.v(4):w(g,Up(d),5):g.v(0)}4!=g.h&&(e=g.i,c=null==(f=e)?void 0:f.config);return w(g,Rp(c,b,d),0)})}
function Xp(a,b,c){var d,e,f,g;return x(function(h){if(1==h.h){if(!R("update_log_event_config"))return h.v(0);a.coldHashData=b;z("yt.gcf.config.coldHashData",a.coldHashData);return(d=yp())?c?h.v(4):w(h,Tp(d),5):h.v(0)}4!=h.h&&(e=h.i,c=null==(f=e)?void 0:f.config);if(!c)return h.v(0);g=c.configData;return w(h,Sp(c,b,g,d),0)})}
;function Yp(){return"INNERTUBE_API_KEY"in vm&&"INNERTUBE_API_VERSION"in vm}
function Zp(){return{innertubeApiKey:P("INNERTUBE_API_KEY"),innertubeApiVersion:P("INNERTUBE_API_VERSION"),Fc:P("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),ud:P("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),ze:P("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:P("INNERTUBE_CONTEXT_CLIENT_VERSION"),wd:P("INNERTUBE_CONTEXT_HL"),vd:P("INNERTUBE_CONTEXT_GL"),Ae:P("INNERTUBE_HOST_OVERRIDE")||"",Ce:!!P("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Be:!!P("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:P("SERIALIZED_CLIENT_CONFIG_DATA")}}
function $p(a){var b={client:{hl:a.wd,gl:a.vd,clientName:a.ud,clientVersion:a.innertubeContextClientVersion,configInfo:a.Fc}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=y.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=Rm();""!==c&&(b.client.experimentsToken=c);c=Sm();0<c.length&&(b.request={internalExperimentFlags:c});aq(a,void 0,b);bq(void 0,b);cq(void 0,b);dq(a,void 0,b);eq(void 0,b);R("start_sending_config_hash")&&fq(void 0,b);P("DELEGATED_SESSION_ID")&&
!R("pageid_as_header_web")&&(b.user={onBehalfOfUser:P("DELEGATED_SESSION_ID")});a=Object;c=a.assign;for(var d=b.client,e={},f=r(Object.entries(Jm(P("DEVICE","")))),g=f.next();!g.done;g=f.next()){var h=r(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?e.deviceMake=h:"cmodel"===g?e.deviceModel=h:"cbr"===g?e.browserName=h:"cbrver"===g?e.browserVersion=h:"cos"===g?e.osName=h:"cosver"===g?e.osVersion=h:"cplatform"===g&&(e.platform=h)}b.client=c.call(a,d,e);return b}
function gq(a){var b=new Nk,c=new Ck;G(c,1,a.wd);G(c,2,a.vd);G(c,16,a.ze);G(c,17,a.innertubeContextClientVersion);if(a.Fc){var d=a.Fc,e=new yk;d.coldConfigData&&G(e,1,d.coldConfigData);d.appInstallData&&G(e,6,d.appInstallData);d.coldHashData&&G(e,3,d.coldHashData);d.hotHashData&&G(e,5,d.hotHashData);I(c,yk,62,e)}(d=y.devicePixelRatio)&&1!=d&&G(c,65,Fd(d));d=Rm();""!==d&&G(c,54,d);d=Sm();if(0<d.length){e=new Gk;for(var f=0;f<d.length;f++){var g=new Ek;G(g,1,d[f].key);Rd(g,2,Fk,d[f].value);Yd(e,15,
Ek,g)}I(b,Gk,5,e)}aq(a,c);bq(b);cq(c);dq(a,c);eq(c);R("start_sending_config_hash")&&fq(c);P("DELEGATED_SESSION_ID")&&!R("pageid_as_header_web")&&(a=new Lk,G(a,3,P("DELEGATED_SESSION_ID")));a=r(Object.entries(Jm(P("DEVICE",""))));for(d=a.next();!d.done;d=a.next())e=r(d.value),d=e.next().value,e=e.next().value,"cbrand"===d?G(c,12,e):"cmodel"===d?G(c,13,e):"cbr"===d?G(c,87,e):"cbrver"===d?G(c,88,e):"cos"===d?G(c,18,e):"cosver"===d?G(c,19,e):"cplatform"===d&&G(c,42,e);b.l(c);return b}
function aq(a,b,c){a=a.ud;if("WEB"===a||"MWEB"===a||1===a||2===a)if(b){c=Td(b,zk,96)||new zk;var d=En();d=Object.keys(Uk).indexOf(d);d=-1===d?null:d;null!==d&&G(c,3,d);I(b,zk,96,c)}else c&&(c.client.mainAppWebInfo=null!=(d=c.client.mainAppWebInfo)?d:{},c.client.mainAppWebInfo.webDisplayMode=En())}
function bq(a,b){var c=A("yt.embedded_player.embed_url");c&&(a?(b=Td(a,Ik,7)||new Ik,G(b,4,c),I(a,Ik,7,b)):b&&(b.thirdParty={embedUrl:c}))}
function cq(a,b){var c;if(R("web_log_memory_total_kbytes")&&(null==(c=y.navigator)?0:c.deviceMemory)){var d;c=null==(d=y.navigator)?void 0:d.deviceMemory;a?G(a,95,1E6*c):b&&(b.client.memoryTotalKbytes=""+1E6*c)}}
function dq(a,b,c){if(a.appInstallData)if(b){var d;c=null!=(d=Td(b,yk,62))?d:new yk;G(c,6,a.appInstallData);I(b,yk,62,c)}else c&&(c.client.configInfo=c.client.configInfo||{},c.client.configInfo.appInstallData=a.appInstallData)}
function eq(a,b){var c=Vn();c&&(a?G(a,61,Rn[c]):b&&(b.client.connectionType=c));R("web_log_effective_connection_type")&&(c=Wn())&&(a?G(a,94,Sn[c]):b&&(b.client.effectiveConnectionType=c))}
function hq(a,b,c){c=void 0===c?{}:c;var d={};P("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":P("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||P("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;b=c.Ht||P("AUTHORIZATION");b||(a?b="Bearer "+A("gapi.auth.getToken")().Gt:(a=Bn(An()),R("pageid_as_header_web")||delete a["X-Goog-PageId"],d=Object.assign({},d,a)));b&&(d.Authorization=b);return d}
function fq(a,b){Vp.h||(Vp.h=new Vp);var c=Vp.h;var d=T()-c.h;if(0!==c.h&&d<Qm("send_config_hash_timer"))c=void 0;else{d=A("yt.gcf.config.coldConfigData");var e=A("yt.gcf.config.hotHashData"),f=A("yt.gcf.config.coldHashData");d&&e&&f&&(c.h=T());c={coldConfigData:d,hotHashData:e,coldHashData:f}}if(e=c)if(c=e.coldConfigData,d=e.coldHashData,e=e.hotHashData,c&&d&&e)if(a){var g;b=null!=(g=Td(a,yk,62))?g:new yk;G(b,1,c);G(b,3,d);G(b,5,e);I(a,yk,62,b)}else b&&(b.client.configInfo=b.client.configInfo||{},
b.client.configInfo.coldConfigData=c,b.client.configInfo.coldHashData=d,b.client.configInfo.hotHashData=e)}
;function iq(a,b){this.version=a;this.args=b}
;function jq(a,b){this.topic=a;this.h=b}
jq.prototype.toString=function(){return this.topic};var kq=A("ytPubsub2Pubsub2Instance")||new Ji;Ji.prototype.subscribe=Ji.prototype.subscribe;Ji.prototype.unsubscribeByKey=Ji.prototype.Fb;Ji.prototype.publish=Ji.prototype.eb;Ji.prototype.clear=Ji.prototype.clear;z("ytPubsub2Pubsub2Instance",kq);var lq=A("ytPubsub2Pubsub2SubscribedKeys")||{};z("ytPubsub2Pubsub2SubscribedKeys",lq);var mq=A("ytPubsub2Pubsub2TopicToKeys")||{};z("ytPubsub2Pubsub2TopicToKeys",mq);var nq=A("ytPubsub2Pubsub2IsAsync")||{};z("ytPubsub2Pubsub2IsAsync",nq);
z("ytPubsub2Pubsub2SkipSubKey",null);function oq(a,b){var c=pq();c&&c.publish.call(c,a.toString(),a,b)}
function qq(a){var b=rq,c=pq();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=A("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(lq[d])try{if(f&&b instanceof jq&&b!=e)try{var h=b.h,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.Xa){var m=new h;h.Xa=m.version}var n=h.Xa}catch(F){}if(!n||k.version!=n)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{n=Reflect;var q=n.construct;
var u=k.args,t=u.length;if(0<t){var B=Array(t);for(k=0;k<t;k++)B[k]=u[k];var D=B}else D=[];f=q.call(n,h,D)}catch(F){throw F.message="yt.pubsub2.Data.deserialize(): "+F.message,F;}}catch(F){throw F.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+F.message,F;}a.call(window,f)}catch(F){Bm(F)}},nq[b.toString()]?A("yt.scheduler.instance")?mi.fa(g):Wm(g,0):g())});
lq[d]=!0;mq[b.toString()]||(mq[b.toString()]=[]);mq[b.toString()].push(d);return d}
function sq(){var a=tq,b=qq(function(c){a.apply(void 0,arguments);uq(b)});
return b}
function uq(a){var b=pq();b&&("number"===typeof a&&(a=[a]),gb(a,function(c){b.unsubscribeByKey(c);delete lq[c]}))}
function pq(){return A("ytPubsub2Pubsub2Instance")}
;var vq=!0,wq=Qm("compression_performance_threshold",250);
function xq(a,b,c,d){var e={startTime:T()};if(vq)try{var f=ok(hi(b));e.endTime=T();R("disable_compression_due_to_performance_degredation")&&e.endTime-e.startTime>=wq&&(vq=!1);!R("gel_compression_csi_killswitch")&&R("log_gel_compression_latency")&&.01>=Math.random()&&oq("gel_compression_latency_payload",e);if(!R("only_compress_gel_if_smaller")||(window.Blob?f.length<(new Blob(b.split(""))).size:1))c.headers||(c.headers={}),c.headers["Content-Encoding"]="gzip",c.postBody=f,c.postParams=void 0;d(a,c)}catch(g){Cm(g),
d(a,c)}else d(a,c)}
function yq(a){if(!a.body)return a;try{var b="string"===typeof a.body?a.body:JSON.stringify(a.body),c=ok(hi(b));if(R("only_compress_gel_if_smaller")&&!(window.Blob?c.length<(new Blob(b.split(""))).size:1))return a;a.headers=Object.assign({},{"Content-Encoding":"gzip"},a.headers||{});a.body=c;return a}catch(d){return Cm(d),a}}
;function zq(a){a=Object.assign({},a);delete a.Authorization;var b=Dg();if(b){var c=new si;c.update(P("INNERTUBE_API_KEY"));c.update(b);a.hash=cd(c.digest(),3)}return a}
;var Aq;function Bq(){Aq||(Aq=new fo("yt.innertube"));return Aq}
function Cq(a,b,c,d){if(d)return null;d=Bq().get("nextId",!0)||1;var e=Bq().get("requests",!0)||{};e[d]={method:a,request:b,authState:zq(c),requestTime:Math.round(T())};Bq().set("nextId",d+1,86400,!0);Bq().set("requests",e,86400,!0);return d}
function Dq(a){var b=Bq().get("requests",!0)||{};delete b[a];Bq().set("requests",b,86400,!0)}
function Eq(a){var b=Bq().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(T())-d.requestTime)){var e=d.authState,f=zq(hq(!1));tb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(T())),Fq(a,d.method,e,{}));delete b[c]}}Bq().set("requests",b,86400,!0)}}
;function Gq(a){this.dc=this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.tb=function(){};
this.now=Date.now;this.Kb=!1;var b;this.Pd=null!=(b=a.Pd)?b:100;var c;this.Jd=null!=(c=a.Jd)?c:1;var d;this.Hd=null!=(d=a.Hd)?d:2592E6;var e;this.Fd=null!=(e=a.Fd)?e:12E4;var f;this.Id=null!=(f=a.Id)?f:5E3;var g;this.O=null!=(g=a.O)?g:void 0;this.jc=!!a.jc;var h;this.hc=null!=(h=a.hc)?h:.1;var k;this.pc=null!=(k=a.pc)?k:10;a.handleError&&(this.handleError=a.handleError);a.tb&&(this.tb=a.tb);a.Kb&&(this.Kb=a.Kb);a.dc&&(this.dc=a.dc);this.T=a.T;this.ya=a.ya;this.Y=a.Y;this.W=a.W;this.Pa=a.Pa;this.Nc=
a.Nc;this.Mc=a.Mc;Hq(this)&&(!this.T||this.T("networkless_logging"))&&Iq(this)}
function Iq(a){Hq(a)&&!a.Kb&&(a.h=!0,a.jc&&Math.random()<=a.hc&&a.Y.he(a.O),Jq(a),a.W.ma()&&a.Tb(),a.W.Ma(a.Nc,a.Tb.bind(a)),a.W.Ma(a.Mc,a.fd.bind(a)))}
l=Gq.prototype;l.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(Hq(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.Y.set(d,this.O).then(function(e){d.id=e;c.W.ma()&&Kq(c,d)}).catch(function(e){Kq(c,d);
Lq(c,e)})}else this.Pa(a,b)};
l.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(Hq(this)&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.T&&this.T("nwl_skip_retry")&&(e.skipRetry=c);if(this.W.ma()||this.T&&this.T("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return x(function(k){if(1==k.h)return w(k,d.Y.set(e,d.O).catch(function(m){Lq(d,m)}),2);
f(g,h);k.h=0})}}this.Pa(a,b,e.skipRetry)}else this.Y.set(e,this.O).catch(function(g){d.Pa(a,b,e.skipRetry);
Lq(d,g)})}else this.Pa(a,b,this.T&&this.T("nwl_skip_retry")&&c)};
l.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(Hq(this)&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.Y.sb(d.id,c.O):e=!0;c.W.jb&&c.T&&c.T("vss_network_hint")&&c.W.jb(!0);f(g,h)};
this.Pa(d.url,d.options);this.Y.set(d,this.O).then(function(g){d.id=g;e&&c.Y.sb(d.id,c.O)}).catch(function(g){Lq(c,g)})}else this.Pa(a,b)};
l.Tb=function(){var a=this;if(!Hq(this))throw Eo("throttleSend");this.i||(this.i=this.ya.fa(function(){var b;return x(function(c){if(1==c.h)return w(c,a.Y.rd("NEW",a.O),2);if(3!=c.h)return b=c.i,b?w(c,Kq(a,b),3):(a.fd(),c.return());a.i&&(a.i=0,a.Tb());c.h=0})},this.Pd))};
l.fd=function(){this.ya.Da(this.i);this.i=0};
function Kq(a,b){var c,d;return x(function(e){switch(e.h){case 1:if(!Hq(a))throw c=Eo("immediateSend"),c;if(void 0===b.id){e.v(2);break}return w(e,a.Y.Ee(b.id,a.O),3);case 3:(d=e.i)||a.tb(Error("The request cannot be found in the database."));case 2:if(Mq(a,b,a.Hd)){e.v(4);break}a.tb(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.v(5);break}return w(e,a.Y.sb(b.id,a.O),5);case 5:return e.return();case 4:b.skipRetry||(b=Nq(a,b));if(!b){e.v(0);break}if(!b.skipRetry||
void 0===b.id){e.v(8);break}return w(e,a.Y.sb(b.id,a.O),8);case 8:a.Pa(b.url,b.options,!!b.skipRetry),e.h=0}})}
function Nq(a,b){if(!Hq(a))throw Eo("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k,m;return x(function(n){switch(n.h){case 1:g=Oq(f);h=Pq(f);if(!(a.T&&a.T("nwl_consider_error_code")&&g||a.T&&!a.T("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.pc)){n.v(2);break}if(!a.W.tc){n.v(3);break}return w(n,a.W.tc(),3);case 3:if(a.W.ma()){n.v(2);break}c(e,f);if(!a.T||!a.T("nwl_consider_error_code")||void 0===(null==(k=b)?void 0:k.id)){n.v(6);break}return w(n,a.Y.Rc(b.id,a.O,!1),6);case 6:return n.return();case 2:if(a.T&&a.T("nwl_consider_error_code")&&
!g&&a.potentialEsfErrorCounter>a.pc)return n.return();a.potentialEsfErrorCounter++;if(void 0===(null==(m=b)?void 0:m.id)){n.v(8);break}return b.sendCount<a.Jd?w(n,a.Y.Rc(b.id,a.O,!0,h?!1:void 0),12):w(n,a.Y.sb(b.id,a.O),8);case 12:a.ya.fa(function(){a.W.ma()&&a.Tb()},a.Id);
case 8:c(e,f),n.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return x(function(h){if(1==h.h)return void 0===(null==(g=b)?void 0:g.id)?h.v(2):w(h,a.Y.sb(b.id,a.O),2);a.W.jb&&a.T&&a.T("vss_network_hint")&&a.W.jb(!0);d(e,f);h.h=0})};
return b}
function Mq(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function Jq(a){if(!Hq(a))throw Eo("retryQueuedRequests");a.Y.rd("QUEUED",a.O).then(function(b){b&&!Mq(a,b,a.Fd)?a.ya.fa(function(){return x(function(c){if(1==c.h)return void 0===b.id?c.v(2):w(c,a.Y.Rc(b.id,a.O),2);Jq(a);c.h=0})}):a.W.ma()&&a.Tb()})}
function Lq(a,b){a.Vd&&!a.W.ma()?a.Vd(b):a.handleError(b)}
function Hq(a){return!!a.O||a.dc}
function Oq(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
function Pq(a){var b;a=null==a?void 0:null==(b=a.error)?void 0:b.code;return!(400!==a&&415!==a)}
;var Qq;
function Rq(){if(Qq)return Qq();var a={};Qq=Np("LogsDatabaseV2",{zb:(a.LogsRequestsStore={Hb:2},a),uc:!1,upgrade:function(b,c,d){c(2)&&To(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),$o(d,"newRequestV2",["status","interface","timestamp"]));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return Qq()}
;function Sq(a){return lp(Rq(),a)}
function Tq(a,b){var c,d,e,f;return x(function(g){if(1==g.h)return c={startTime:T(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},w(g,Sq(b),2);if(3!=g.h)return d=g.i,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:P("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),w(g,Vo(d,"LogsRequestsStore",e),3);f=g.i;c.lf=T();Uq(c);return g.return(f)})}
function Vq(a,b){var c,d,e,f,g,h,k;return x(function(m){if(1==m.h)return c={startTime:T(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},w(m,Sq(b),2);if(3!=m.h)return d=m.i,e=P("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,T()],h=IDBKeyRange.bound(f,g),k=void 0,w(m,So(d,["LogsRequestsStore"],{mode:"readwrite",da:!0},function(n){return ep(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(q){q.getValue()&&(k=q.getValue(),"NEW"===a&&(k.status="QUEUED",
q.update(k)))})}),3);
c.lf=T();Uq(c);return m.return(k)})}
function ir(a,b){var c;return x(function(d){if(1==d.h)return w(d,Sq(b),2);c=d.i;return d.return(So(c,["LogsRequestsStore"],{mode:"readwrite",da:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Oo(f.h.put(g,void 0)).then(function(){return g})})}))})}
function Hr(a,b,c,d){c=void 0===c?!0:c;var e;return x(function(f){if(1==f.h)return w(f,Sq(b),2);e=f.i;return f.return(So(e,["LogsRequestsStore"],{mode:"readwrite",da:!0},function(g){var h=g.objectStore("LogsRequestsStore");return h.get(a).then(function(k){return k?(k.status="NEW",c&&(k.sendCount+=1),void 0!==d&&(k.options.compress=d),Oo(h.h.put(k,void 0)).then(function(){return k})):Io.resolve(void 0)})}))})}
function Ir(a,b){var c;return x(function(d){if(1==d.h)return w(d,Sq(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function Jr(a){var b,c;return x(function(d){if(1==d.h)return w(d,Sq(a),2);b=d.i;c=T()-2592E6;return w(d,So(b,["LogsRequestsStore"],{mode:"readwrite",da:!0},function(e){return bp(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Kr(){x(function(a){return w(a,Jp(),0)})}
function Uq(a){R("nwl_csi_killswitch")||.01>=Math.random()&&oq("nwl_transaction_latency_payload",a)}
;var Lr={},Mr=Np("ServiceWorkerLogsDatabase",{zb:(Lr.SWHealthLog={Hb:1},Lr),uc:!0,upgrade:function(a,b){b(1)&&$o(To(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}),"swHealthNewRequest",["interface","timestamp"])},
version:1});function Nr(a){return lp(Mr(),a)}
function Or(a){var b,c;x(function(d){if(1==d.h)return w(d,Nr(a),2);b=d.i;c=T()-2592E6;return w(d,So(b,["SWHealthLog"],{mode:"readwrite",da:!0},function(e){return bp(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Pr(a){var b;return x(function(c){if(1==c.h)return w(c,Nr(a),2);b=c.i;return w(c,b.clear("SWHealthLog"),0)})}
;var Qr={},Rr=0;function Sr(a){var b=new Image,c=""+Rr++;Qr[c]=b;b.onload=b.onerror=function(){delete Qr[c]};
b.src=a}
;function Tr(){this.h=new Map;this.i=!1}
function Ur(){if(!Tr.h){var a=A("yt.networkRequestMonitor.instance")||new Tr;z("yt.networkRequestMonitor.instance",a);Tr.h=a}return Tr.h}
Tr.prototype.requestComplete=function(a,b){b&&(this.i=!0);a=this.removeParams(a);this.h.get(a)||this.h.set(a,b)};
Tr.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.h.get(a))?!1:!1===a&&this.i?!0:null};
Tr.prototype.removeParams=function(a){return a.split("?")[0]};
Tr.prototype.removeParams=Tr.prototype.removeParams;Tr.prototype.isEndpointCFR=Tr.prototype.isEndpointCFR;Tr.prototype.requestComplete=Tr.prototype.requestComplete;Tr.getInstance=Ur;var Vr;function Wr(){Vr||(Vr=new fo("yt.offline"));return Vr}
function Xr(a){if(R("offline_error_handling")){var b=Wr().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Wr().set("errors",b,2592E3,!0)}}
;function Yr(){$e.call(this);var a=this;this.j=!1;this.i=li();this.i.Ma("networkstatus-online",function(){if(a.j&&R("offline_error_handling")){var b=Wr().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new S(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;Bm(d)}Wr().set("errors",{},2592E3,!0)}}})}
v(Yr,$e);function Zr(){if(!Yr.h){var a=A("yt.networkStatusManager.instance")||new Yr;z("yt.networkStatusManager.instance",a);Yr.h=a}return Yr.h}
l=Yr.prototype;l.ma=function(){return this.i.ma()};
l.jb=function(a){this.i.i=a};
l.ue=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
l.me=function(){this.j=!0};
l.Ma=function(a,b){return this.i.Ma(a,b)};
l.tc=function(a){a=ji(this.i,a);a.then(function(b){R("use_cfr_monitor")&&Ur().requestComplete("generate_204",b)});
return a};
Yr.prototype.sendNetworkCheckRequest=Yr.prototype.tc;Yr.prototype.listen=Yr.prototype.Ma;Yr.prototype.enableErrorFlushing=Yr.prototype.me;Yr.prototype.getWindowStatus=Yr.prototype.ue;Yr.prototype.networkStatusHint=Yr.prototype.jb;Yr.prototype.isNetworkAvailable=Yr.prototype.ma;Yr.getInstance=Zr;function $r(a){a=void 0===a?{}:a;$e.call(this);var b=this;this.i=this.s=0;this.j=Zr();var c=A("yt.networkStatusManager.instance.listen").bind(this.j);c&&(a.sc?(this.sc=a.sc,c("networkstatus-online",function(){as(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){as(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){ff(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){ff(b,"publicytnetworkstatus-offline")})))}
v($r,$e);$r.prototype.ma=function(){var a=A("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.j)():!0};
$r.prototype.jb=function(a){var b=A("yt.networkStatusManager.instance.networkStatusHint").bind(this.j);b&&b(a)};
$r.prototype.tc=function(a){var b=this,c;return x(function(d){c=A("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.j);return R("skip_network_check_if_cfr")&&Ur().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.jb((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.ma())})):c?d.return(c(a)):d.return(!0)})};
function as(a,b){a.sc?a.i?(mi.Da(a.s),a.s=mi.fa(function(){a.m!==b&&(ff(a,b),a.m=b,a.i=T())},a.sc-(T()-a.i))):(ff(a,b),a.m=b,a.i=T()):ff(a,b)}
;var bs;function cs(){var a=Gq.call;bs||(bs=new $r({Tt:!0,Nt:!0}));a.call(Gq,this,{Y:{he:Jr,sb:Ir,rd:Vq,Ee:ir,Rc:Hr,set:Tq},W:bs,handleError:Bm,tb:Cm,Pa:ds,now:T,Vd:Xr,ya:eo(),Nc:"publicytnetworkstatus-online",Mc:"publicytnetworkstatus-offline",jc:!0,hc:.1,pc:Qm("potential_esf_error_limit",10),T:R,Kb:!(Xn()&&es())});this.j=new Jh;R("networkless_immediately_drop_all_requests")&&Kr();Kp("LogsDatabaseV2")}
v(cs,Gq);function fs(){var a=A("yt.networklessRequestController.instance");a||(a=new cs,z("yt.networklessRequestController.instance",a),R("networkless_logging")&&zp().then(function(b){a.O=b;Iq(a);a.j.resolve();a.jc&&Math.random()<=a.hc&&a.O&&Or(a.O);R("networkless_immediately_drop_sw_health_store")&&gs(a)}));
return a}
cs.prototype.writeThenSend=function(a,b){b||(b={});Xn()||(this.h=!1);Gq.prototype.writeThenSend.call(this,a,b)};
cs.prototype.sendThenWrite=function(a,b,c){b||(b={});Xn()||(this.h=!1);Gq.prototype.sendThenWrite.call(this,a,b,c)};
cs.prototype.sendAndWrite=function(a,b){b||(b={});Xn()||(this.h=!1);Gq.prototype.sendAndWrite.call(this,a,b)};
cs.prototype.awaitInitialization=function(){return this.j.promise};
function gs(a){var b;x(function(c){if(!a.O)throw b=Eo("clearSWHealthLogsDb"),b;return c.return(Pr(a.O).catch(function(d){a.handleError(d)}))})}
function ds(a,b,c){R("use_cfr_monitor")&&hs(a,b);if(R("use_request_time_ms_header"))b.headers&&(b.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(T())));else{var d;if(null==(d=b.postParams)?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(T())}if(c&&0===Object.keys(b).length){var e=void 0===e?"":e;var f=void 0===f?!1:f;if(a)if(e)en(a,void 0,"POST",e);else if(P("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))en(a,void 0,"GET","",void 0,void 0,f);else{b:{try{var g=new cb({url:a});if(g.j&&g.i||
g.l){var h=nc(oc(5,a)),k;if(!(k=!h||!h.endsWith("/aclk"))){var m=a.search(zc),n=yc(a,0,"ri",m);if(0>n)var q=null;else{var u=a.indexOf("&",n);if(0>u||u>m)u=m;q=decodeURIComponent(a.slice(n+3,-1!==u?u:0).replace(/\+/g," "))}k="1"!==q}var t=!k;break b}}catch(D){}t=!1}if(t){b:{try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var B=!0;break b}}catch(D){}B=!1}c=B?!0:!1}else c=!1;c||Sr(a)}}else b.compress?b.postBody?("string"!==typeof b.postBody&&(b.postBody=JSON.stringify(b.postBody)),
xq(a,b.postBody,b,bn)):xq(a,JSON.stringify(b.postParams),b,kn):bn(a,b)}
function hs(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){Ur().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){Ur().requestComplete(a,!0);d(e,f)}}
function es(){return"www.youtube-nocookie.com"!==pc(document.location.toString())}
;var is=!1,js=y.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:is};z("ytNetworklessLoggingInitializationOptions",js);function ks(){var a;x(function(b){if(1==b.h)return w(b,zp(),2);a=b.i;if(!a||!Xn()&&!R("nwl_init_require_datasync_id_killswitch")||!es())return b.v(0);is=!0;js.isNwlInitialized=is;return w(b,fs().awaitInitialization(),0)})}
;function ls(a){var b=this;this.config_=null;a?this.config_=a:Yp()&&(this.config_=Zp());$n(function(){Eq(b)},5E3)}
ls.prototype.isReady=function(){!this.config_&&Yp()&&(this.config_=Zp());return!!this.config_};
function Fq(a,b,c,d){function e(B){B=void 0===B?!1:B;var D;if(d.retry&&"www.youtube-nocookie.com"!=h&&(B||R("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(D=Cq(b,c,m,k)),D)){var F=g.onSuccess,N=g.onFetchSuccess;g.onSuccess=function(Q,ca){Dq(D);F(Q,ca)};
c.onFetchSuccess=function(Q,ca){Dq(D);N(Q,ca)}}try{if(B&&d.retry&&!d.Ad.bypassNetworkless)g.method="POST",d.Ad.writeThenSend?fs().writeThenSend(t,g):fs().sendAndWrite(t,g);
else if(d.compress)if(g.postBody){var O=g.postBody;"string"!==typeof O&&(O=JSON.stringify(g.postBody));xq(t,O,g,bn)}else xq(t,JSON.stringify(g.postParams),g,kn);else R("web_all_payloads_via_jspb")?bn(t,g):kn(t,g)}catch(Q){if("InvalidAccessError"==Q.name)D&&(Dq(D),D=0),Cm(Error("An extension is blocking network request."));else throw Q;}D&&$n(function(){Eq(a)},5E3)}
!P("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Cm(new S("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new S("innertube xhrclient not ready",b,c,d);Bm(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(B,D){if(d.onSuccess)d.onSuccess(D)},
onFetchSuccess:function(B){if(d.onSuccess)d.onSuccess(B)},
onError:function(B,D){if(d.onError)d.onError(D)},
onFetchError:function(B){if(d.onError)d.onError(B)},
timeout:d.timeout,withCredentials:!0,compress:d.compress};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.Ae)&&(h=f);var k=a.config_.Ce||!1,m=hq(k,h,d);Object.assign(g.headers,m);(f=g.headers.Authorization)&&!h&&k&&(g.headers["x-origin"]=window.location.origin);var n="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,q={alt:"json"},u=a.config_.Be&&f;u=u&&f.startsWith("Bearer");u||(q.key=a.config_.innertubeApiKey);var t=Lm(""+h+n,q||{},!0);(A("ytNetworklessLoggingInitializationOptions")?
js.isNwlInitialized:is)?xp().then(function(B){e(B)}):e(!1)}
;var ms=0,ns=Kc?"webkit":Jc?"moz":Hc?"ms":Gc?"o":"";z("ytDomDomGetNextId",A("ytDomDomGetNextId")||function(){return++ms});var os={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function ps(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in os||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.h=a.pageX;this.i=a.pageY}}catch(e){}}
function qs(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.h=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.i=a.clientY+b}}
ps.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
ps.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
ps.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var pb=y.ytEventsEventsListeners||{};z("ytEventsEventsListeners",pb);var rs=y.ytEventsEventsCounter||{count:0};z("ytEventsEventsCounter",rs);
function ss(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return ob(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Ra(e[4])&&Ra(d)&&tb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var ts=eb(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function us(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=ss(a,b,c,d);if(e)return e;e=++rs.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new ps(h);if(!pf(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new ps(h);
h.currentTarget=a;return c.call(a,h)};
g=Am(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),ts()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);pb[e]=[a,b,c,g,d];return e}
function vs(a){a&&("string"==typeof a&&(a=[a]),gb(a,function(b){if(b in pb){var c=pb[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?ts()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete pb[b]}}))}
;function ws(a){this.L=a;this.i=null;this.m=0;this.A=null;this.s=0;this.j=[];for(a=0;4>a;a++)this.j.push(0);this.l=0;this.V=us(window,"mousemove",Xa(this.Z,this));a=Xa(this.R,this);"function"===typeof a&&(a=Am(a));this.aa=window.setInterval(a,25)}
$a(ws,K);ws.prototype.Z=function(a){void 0===a.h&&qs(a);var b=a.h;void 0===a.i&&qs(a);this.i=new lf(b,a.i)};
ws.prototype.R=function(){if(this.i){var a=T();if(0!=this.m){var b=this.A,c=this.i,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.m);this.j[this.l]=.5<Math.abs((d-this.s)/this.s)?1:0;for(c=b=0;4>c;c++)b+=this.j[c]||0;3<=b&&this.L();this.s=d}this.m=a;this.A=this.i;this.l=(this.l+1)%4}};
ws.prototype.M=function(){window.clearInterval(this.aa);vs(this.V)};var xs={};
function ys(a){var b=void 0===a?{}:a;a=void 0===b.Ne?!1:b.Ne;b=void 0===b.ne?!0:b.ne;if(null==A("_lact",window)){var c=parseInt(P("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;z("_lact",c,window);z("_fact",c,window);-1==c&&zs();us(document,"keydown",zs);us(document,"keyup",zs);us(document,"mousedown",zs);us(document,"mouseup",zs);a?us(window,"touchmove",function(){As("touchmove",200)},{passive:!0}):(us(window,"resize",function(){As("resize",200)}),b&&us(window,"scroll",function(){As("scroll",200)}));
new ws(function(){As("mouse",100)});
us(document,"touchstart",zs,{passive:!0});us(document,"touchend",zs,{passive:!0})}}
function As(a,b){xs[a]||(xs[a]=!0,mi.fa(function(){zs();xs[a]=!1},b))}
function zs(){null==A("_lact",window)&&ys();var a=Date.now();z("_lact",a,window);-1==A("_fact",window)&&z("_fact",a,window);(a=A("ytglobal.ytUtilActivityCallback_"))&&a()}
function Bs(){var a=A("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var Cs=y.ytPubsubPubsubInstance||new Ji,Ds=y.ytPubsubPubsubSubscribedKeys||{},Es=y.ytPubsubPubsubTopicToKeys||{},Fs=y.ytPubsubPubsubIsSynchronous||{};function Gs(a,b){var c=Hs();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){Ds[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{Fs[a]?f():Wm(f,0)}catch(g){Bm(g)}},void 0);
Ds[d]=!0;Es[a]||(Es[a]=[]);Es[a].push(d);return d}return 0}
function Is(a){var b=Hs();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),gb(a,function(c){b.unsubscribeByKey(c);delete Ds[c]}))}
function Js(a,b){var c=Hs();c&&c.publish.apply(c,arguments)}
function Ks(a){var b=Hs();if(b)if(b.clear(a),a)Ls(a);else for(var c in Es)Ls(c)}
function Hs(){return y.ytPubsubPubsubInstance}
function Ls(a){Es[a]&&(a=Es[a],gb(a,function(b){Ds[b]&&delete Ds[b]}),a.length=0)}
Ji.prototype.subscribe=Ji.prototype.subscribe;Ji.prototype.unsubscribeByKey=Ji.prototype.Fb;Ji.prototype.publish=Ji.prototype.eb;Ji.prototype.clear=Ji.prototype.clear;z("ytPubsubPubsubInstance",Cs);z("ytPubsubPubsubTopicToKeys",Es);z("ytPubsubPubsubIsSynchronous",Fs);z("ytPubsubPubsubSubscribedKeys",Ds);var Ms=Symbol("injectionDeps");function Ns(a){this.name=a}
Ns.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function Os(a){this.key=a}
function Ps(){this.h=new Map;this.i=new Map}
Ps.prototype.resolve=function(a){return a instanceof Os?Qs(this,a.key,[],!0):Qs(this,a,[])};
function Qs(a,b,c,d){d=void 0===d?!1:d;if(-1<c.indexOf(b))throw Error("Deps cycle for: "+b);if(a.i.has(b))return a.i.get(b);if(!a.h.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.h.get(b);c.push(b);if(d.Sd)var e=d.Sd;else if(d.pf)e=d[Ms]?Rs(a,d[Ms],c):[],e=d.pf.apply(d,ia(e));else if(d.Rd){e=d.Rd;var f=e[Ms]?Rs(a,e[Ms],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(ia(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.eu||a.i.set(b,e);return e}
function Rs(a,b,c){return b?b.map(function(d){return d instanceof Os?Qs(a,d.key,c,!0):Qs(a,d,c)}):[]}
;var Ss;function Ts(){Ss||(Ss=new Ps);return Ss}
;function Us(){this.store={};this.h={}}
Us.prototype.storePayload=function(a,b){a=Vs(a);this.store[a]?this.store[a].push(b):(this.h={},this.store[a]=[b]);return a};
Us.prototype.extractMatchingEntries=function(a){a=Ws(this,a);for(var b=[],c=0;c<a.length;c++)this.store[a[c]]&&(b.push.apply(b,ia(this.store[a[c]])),delete this.store[a[c]]);return b};
Us.prototype.getSequenceCount=function(a){a=Ws(this,a);for(var b=0,c=0;c<a.length;c++)b+=this.store[a[c]].length||0;return b};
function Ws(a,b){var c=Vs(b);if(a.h[c])return a.h[c];var d=Object.keys(a.store)||[];if(1>=d.length&&Vs(b)===d[0])return d;for(var e=[],f=0;f<d.length;f++){var g=d[f].split("/");if(Xs(b.auth,g[0])){var h=b.isJspb;Xs(void 0===h?"undefined":h?"true":"false",g[1])&&Xs(b.cttAuthInfo,g[2])&&e.push(d[f])}}return a.h[c]=e}
function Xs(a,b){return void 0===a||"undefined"===a?!0:a===b}
Us.prototype.getSequenceCount=Us.prototype.getSequenceCount;Us.prototype.extractMatchingEntries=Us.prototype.extractMatchingEntries;Us.prototype.storePayload=Us.prototype.storePayload;function Vs(a){return[void 0===a.auth?"undefined":a.auth,void 0===a.isJspb?"undefined":a.isJspb,void 0===a.cttAuthInfo?"undefined":a.cttAuthInfo].join("/")}
;function Ys(a,b){if(a)return a[b.name]}
;var Zs=Qm("initial_gel_batch_timeout",2E3),$s=Qm("gel_queue_timeout_max_ms",6E4),at=Math.pow(2,16)-1,bt=void 0;function ct(){this.j=this.h=this.i=0}
var dt=new ct,et=new ct,ft,gt=!0,ht=y.ytLoggingTransportTokensToCttTargetIds_||{};z("ytLoggingTransportTokensToCttTargetIds_",ht);var jt=y.ytLoggingTransportTokensToJspbCttTargetIds_||{};z("ytLoggingTransportTokensToJspbCttTargetIds_",jt);var kt={};function lt(){var a=A("yt.logging.ims");a||(a=new Us,z("yt.logging.ims",a));return a}
function mt(a,b){R("web_all_payloads_via_jspb")&&Cm(new S("transport.log called for JSON in JSPB only experiment"));if("log_event"===a.endpoint){nt(a);var c=ot(a);kt[c]=!0;var d={cttAuthInfo:c,isJspb:!1};lt().storePayload(d,a.payload);pt(b,c,!1,d)}}
function qt(a,b){if("log_event"===a.endpoint){nt(void 0,a);var c=ot(a,!0);kt[c]=!0;var d={cttAuthInfo:c,isJspb:!0};lt().storePayload(d,a.payload.toJSON());pt(b,c,!0,d)}}
function pt(a,b,c,d){c=void 0===c?!1:c;a&&(bt=new a);a=Qm("tvhtml5_logging_max_batch_ads_fork")||Qm("tvhtml5_logging_max_batch")||Qm("web_logging_max_batch")||100;var e=T(),f=c?et.j:dt.j,g=0;d&&(g=lt().getSequenceCount(d));g>=a?ft||(ft=rt(function(){st({writeThenSend:!0},R("flush_only_full_queue")?b:void 0,c);ft=void 0},0)):10<=e-f&&(tt(c),c?et.j=e:dt.j=e)}
function ut(a,b){R("web_all_payloads_via_jspb")&&Cm(new S("transport.logIsolatedGelPayload called in JSPB only experiment"));if("log_event"===a.endpoint){nt(a);var c=ot(a),d=new Map;d.set(c,[a.payload]);b&&(bt=new b);return new Bf(function(e,f){bt&&bt.isReady()?vt(d,bt,e,f,{bypassNetworkless:!0},!0):e()})}}
function wt(a,b){if("log_event"===a.endpoint){nt(void 0,a);var c=ot(a,!0),d=new Map;d.set(c,[a.payload.toJSON()]);b&&(bt=new b);return new Bf(function(e){bt&&bt.isReady()?xt(d,bt,e,{bypassNetworkless:!0},!0):e()})}}
function ot(a,b){var c="";if(a.dangerousLogToVisitorSession)c="visitorOnlyApprovedKey";else if(a.cttAuthInfo){if(void 0===b?0:b){b=a.cttAuthInfo.token;c=a.cttAuthInfo;var d=new fm;c.videoId?d.setVideoId(c.videoId):c.playlistId&&Rd(d,2,gm,c.playlistId);jt[b]=d}else b=a.cttAuthInfo,c={},b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId),ht[a.cttAuthInfo.token]=c;c=a.cttAuthInfo.token}return c}
function st(a,b,c){a=void 0===a?{}:a;c=void 0===c?!1:c;!c&&R("web_all_payloads_via_jspb")&&Cm(new S("transport.flushLogs called for JSON in JSPB only experiment"));new Bf(function(d,e){c?(zt(et.i),zt(et.h),et.h=0):(zt(dt.i),zt(dt.h),dt.h=0);if(bt&&bt.isReady()){var f=a,g=c,h=bt;f=void 0===f?{}:f;g=void 0===g?!1:g;var k=new Map,m=new Map;if(void 0!==b)g?(e=lt().extractMatchingEntries({isJspb:g,cttAuthInfo:b}),k.set(b,e),xt(k,h,d,f)):(k=lt().extractMatchingEntries({isJspb:g,cttAuthInfo:b}),m.set(b,
k),vt(m,h,d,e,f));else if(g){e=r(Object.keys(kt));for(g=e.next();!g.done;g=e.next())m=g.value,g=lt().extractMatchingEntries({isJspb:!0,cttAuthInfo:m}),0<g.length&&k.set(m,g),delete kt[m];xt(k,h,d,f)}else{k=r(Object.keys(kt));for(g=k.next();!g.done;g=k.next()){g=g.value;var n=lt().extractMatchingEntries({isJspb:!1,cttAuthInfo:g});0<n.length&&m.set(g,n);delete kt[g]}vt(m,h,d,e,f)}}else tt(c),d()})}
function tt(a){a=void 0===a?!1:a;if(R("web_gel_timeout_cap")&&(!a&&!dt.h||a&&!et.h)){var b=rt(function(){st({writeThenSend:!0},void 0,a)},$s);
a?et.h=b:dt.h=b}zt(a?et.i:dt.i);b=P("LOGGING_BATCH_TIMEOUT",Qm("web_gel_debounce_ms",1E4));R("shorten_initial_gel_batch_timeout")&&gt&&(b=Zs);b=rt(function(){st({writeThenSend:!0},void 0,a)},b);
a?et.i=b:dt.i=b}
function vt(a,b,c,d,e,f){e=void 0===e?{}:e;var g=Math.round(T()),h=a.size,k={};a=r(a);for(var m=a.next();!m.done;k={Vb:k.Vb,ab:k.ab,Cb:k.Cb,Xb:k.Xb,Wb:k.Wb},m=a.next()){var n=r(m.value);m=n.next().value;n=n.next().value;k.ab=wb({context:$p(b.config_||Zp())});if(!Qa(n)&&!R("throw_err_when_logevent_malformed_killswitch")){d();break}k.ab.events=n;(n=ht[m])&&At(k.ab,m,n);delete ht[m];k.Cb="visitorOnlyApprovedKey"===m;Bt(k.ab,g,k.Cb);Ct(e);k.Xb=function(q){R("update_log_event_config")&&mi.fa(function(){return x(function(u){return w(u,
Dt(q),0)})});
h--;h||c()};
k.Vb=0;k.Wb=function(q){return function(){q.Vb++;if(e.bypassNetworkless&&1===q.Vb)try{Fq(b,"log_event",q.ab,Et({writeThenSend:!0},q.Cb,q.Xb,q.Wb,f)),gt=!1}catch(u){Bm(u),d()}h--;h||c()}}(k);
try{Fq(b,"log_event",k.ab,Et(e,k.Cb,k.Xb,k.Wb,f)),gt=!1}catch(q){Bm(q),d()}}}
function xt(a,b,c,d,e){d=void 0===d?{}:d;var f=Math.round(T()),g=a.size,h=new Map([].concat(ia(a)));h=r(h);for(var k=h.next();!k.done;k=h.next()){var m=r(k.value).next().value,n=a.get(m);k=new hm;var q=gq(b.config_||Zp());I(k,Nk,1,q);n=n?Ft(n):[];n=r(n);for(q=n.next();!q.done;q=n.next())Yd(k,3,bm,q.value);(n=jt[m])&&Gt(k,m,n);delete jt[m];m="visitorOnlyApprovedKey"===m;Ht(k,f,m);Ct(d);k=ne(k);m=Et(d,m,function(u){R("update_log_event_config")&&mi.fa(function(){return x(function(t){return w(t,Dt(u),
0)})});
g--;g||c()},function(){g--;
g||c()},e);
m.headers["Content-Type"]="application/json+protobuf";m.postBodyFormat="JSPB";m.postBody=k;Fq(b,"log_event","",m);gt=!1}}
function Ct(a){R("always_send_and_write")&&(a.writeThenSend=!1)}
function Et(a,b,c,d,e){a={retry:!0,onSuccess:c,onError:d,Ad:a,dangerousLogToVisitorSession:b,Jt:!!e,headers:{},postBodyFormat:"",postBody:"",compress:R("compress_gel")};It()&&(a.headers["X-Goog-Request-Time"]=JSON.stringify(Math.round(T())));return a}
function Bt(a,b,c){It()||(a.requestTimeMs=String(b));R("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=P("EVENT_ID"))&&(c=Jt(),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Ht(a,b,c){It()||G(a,2,b);if(!c&&(b=P("EVENT_ID"))){c=Jt();var d=new em;G(d,1,b);G(d,2,c);I(a,em,5,d)}}
function Jt(){var a=P("BATCH_CLIENT_COUNTER")||0;a||(a=Math.floor(Math.random()*at/2));a++;a>at&&(a=1);wm("BATCH_CLIENT_COUNTER",a);return a}
function At(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Gt(a,b,c){var d=1===Sd(c,gm)?1:-1;if(Od(c,d))d=1;else if(c.getPlaylistId())d=2;else return;I(a,fm,4,c);a=Td(a,Nk,1)||new Nk;c=Td(a,Lk,3)||new Lk;var e=new Kk;G(e,2,b);G(e,1,d);Yd(c,12,Kk,e);I(a,Lk,3,c)}
function Ft(a){for(var b=[],c=0;c<a.length;c++)try{b.push(new bm(a[c]))}catch(d){Bm(new S("Transport failed to deserialize "+String(a[c])))}return b}
function nt(a,b){if(A("yt.logging.transport.enableScrapingForTest")){var c=A("yt.logging.transport.scrapedPayloadsForTesting"),d=A("yt.logging.transport.payloadToScrape","");b&&(b=A("yt.logging.transport.getScrapedPayloadFromClientEventsFunction").bind(b.payload)())&&c.push(b);a&&a.payload[d]&&c.push((null==a?void 0:a.payload)[d]);z("yt.logging.transport.scrapedPayloadsForTesting",c)}}
function It(){return R("use_request_time_ms_header")||R("lr_use_request_time_ms_header")}
function rt(a,b){return R("transport_use_scheduler")?$n(a,b):Wm(a,b)}
function zt(a){R("transport_use_scheduler")?mi.Da(a):window.clearTimeout(a)}
function Dt(a){var b,c,d,e,f,g,h,k,m,n;return x(function(q){return 1==q.h?(d=null==(b=a)?void 0:null==(c=b.responseContext)?void 0:c.globalConfigGroup,e=Ys(d,sk),g=null==(f=d)?void 0:f.hotHashData,h=Ys(d,rk),m=null==(k=d)?void 0:k.coldHashData,(n=Ts().resolve(new Os(Vp)))?g?e?w(q,Wp(n,g,e),2):w(q,Wp(n,g),2):q.v(2):q.return()):m?h?w(q,Xp(n,m,h),0):w(q,Xp(n,m),0):q.v(0)})}
;var Kt=y.ytLoggingGelSequenceIdObj_||{};z("ytLoggingGelSequenceIdObj_",Kt);
function Lt(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||T());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;R("enable_unknown_lact_fix_on_html5")&&ys();a=Bs();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};R("log_sequence_info_on_gel_web")&&d.sequenceGroup&&(a=e.context,b=d.sequenceGroup,b={index:Mt(b),groupKey:b},a.sequence=b,d.endOfSequence&&delete Kt[d.sequenceGroup]);(d.sendIsolatedPayload?ut:mt)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,
dangerousLogToVisitorSession:d.dangerousLogToVisitorSession},c)}
function Nt(a){st(void 0,void 0,void 0===a?!1:a)}
function Mt(a){Kt[a]=a in Kt?Kt[a]+1:0;return Kt[a]}
;var Ot=[];function oo(a,b,c){c=void 0===c?{}:c;var d=ls;P("ytLoggingEventsDefaultDisabled",!1)&&ls===ls&&(d=null);R("web_all_payloads_via_jspb")?Ot.push({Oc:a,payload:b,options:c}):Lt(a,b,d,c)}
;var Pt=y.ytLoggingGelSequenceIdObj_||{};z("ytLoggingGelSequenceIdObj_",Pt);
function Qt(a,b,c){c=void 0===c?{}:c;var d=Math.round(c.timestamp||T());G(a,1,d<Number.MAX_SAFE_INTEGER?d:0);var e=Bs();d=new am;G(d,1,c.timestamp||!isFinite(e)?-1:e);if(R("log_sequence_info_on_gel_web")&&c.sequenceGroup){e=c.sequenceGroup;var f=Mt(e),g=new $l;G(g,2,f);G(g,1,e);I(d,$l,3,g);c.endOfSequence&&delete Pt[c.sequenceGroup]}I(a,am,33,d);(c.sendIsolatedPayload?wt:qt)({endpoint:"log_event",payload:a,cttAuthInfo:c.cttAuthInfo,dangerousLogToVisitorSession:c.dangerousLogToVisitorSession},b)}
;function Rt(a,b){b=void 0===b?{}:b;var c=!1;P("ytLoggingEventsDefaultDisabled",!1)&&(c=!0);Qt(a,c?null:ls,b)}
;function St(a,b,c){var d=new bm;Wd(d,Pl,72,cm,a);c?Qt(d,c,b):Rt(d,b)}
function Tt(a,b,c){var d=new bm;Wd(d,Ol,73,cm,a);c?Qt(d,c,b):Rt(d,b)}
function Ut(a,b,c){var d=new bm;Wd(d,Nl,78,cm,a);c?Qt(d,c,b):Rt(d,b)}
function Vt(a,b,c){var d=new bm;Wd(d,Ql,208,cm,a);c?Qt(d,c,b):Rt(d,b)}
function Wt(a,b,c){var d=new bm;Wd(d,Il,156,cm,a);c?Qt(d,c,b):Rt(d,b)}
function Xt(a,b,c){var d=new bm;Wd(d,Kl,215,cm,a);c?Qt(d,c,b):Rt(d,b)}
;var Yt=new Set,Zt=0,$t=0,au=0,bu=[],cu=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function no(a){du(a)}
function eu(a){du(a,"WARNING")}
function du(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||P("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||P("INNERTUBE_CONTEXT_CLIENT_VERSION");var g=f||{},h=void 0===b?"ERROR":b;h=void 0===h?"ERROR":h;if(a){a.hasOwnProperty("level")&&a.level&&(h=a.level);if(R("console_log_js_exceptions")){var k=[];k.push("Name: "+a.name);k.push("Message: "+a.message);a.hasOwnProperty("params")&&k.push("Error Params: "+JSON.stringify(a.params));a.hasOwnProperty("args")&&k.push("Error args: "+JSON.stringify(a.args));
k.push("File name: "+a.fileName);k.push("Stacktrace: "+a.stack);window.console.log(k.join("\n"),a)}if(!(5<=Zt)){var m=bu,n=ye(a),q=n.message||"Unknown Error",u=n.name||"UnknownError",t=n.stack||a.i||"Not available";if(t.startsWith(u+": "+q)){var B=t.split("\n");B.shift();t=B.join("\n")}var D=n.lineNumber||"Not available",F=n.fileName||"Not available",N=t,O=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var Q=0;Q<a.args.length&&!(O=wn(a.args[Q],"params."+Q,g,O),500<=O);Q++);else if(a.hasOwnProperty("params")&&
a.params){var ca=a.params;if("object"===typeof a.params)for(var X in ca){if(ca[X]){var vb="params."+X,Ya=yn(ca[X]);g[vb]=Ya;O+=vb.length+Ya.length;if(500<O)break}}else g.params=yn(ca)}if(m.length)for(var sa=0;sa<m.length&&!(O=wn(m[sa],"params.context."+sa,g,O),500<=O);sa++);navigator.vendor&&!g.hasOwnProperty("vendor")&&(g["device.vendor"]=navigator.vendor);var H={message:q,name:u,lineNumber:D,fileName:F,stack:N,params:g,sampleWeight:1},oa=Number(a.columnNumber);isNaN(oa)||(H.lineNumber=H.lineNumber+
":"+oa);if("IGNORED"===a.level)var ja=0;else a:{for(var af=sn(),bf=r(af.Va),Jd=bf.next();!Jd.done;Jd=bf.next()){var va=Jd.value;if(H.message&&H.message.match(va.Ut)){ja=va.weight;break a}}for(var Wq=r(af.Ra),Yk=Wq.next();!Yk.done;Yk=Wq.next()){var Xq=Yk.value;if(Xq.callback(H)){ja=Xq.weight;break a}}ja=1}H.sampleWeight=ja;for(var Yq=r(nn),Zk=Yq.next();!Zk.done;Zk=Yq.next()){var $k=Zk.value;if($k.oc[H.name])for(var Zq=r($k.oc[H.name]),al=Zq.next();!al.done;al=Zq.next()){var $q=al.value,uh=H.message.match($q.regexp);
if(uh){H.params["params.error.original"]=uh[0];for(var bl=$q.groups,ar={},Kd=0;Kd<bl.length;Kd++)ar[bl[Kd]]=uh[Kd+1],H.params["params.error."+bl[Kd]]=uh[Kd+1];H.message=$k.Kc(ar);break}}}H.params||(H.params={});var br=sn();H.params["params.errorServiceSignature"]="msg="+br.Va.length+"&cb="+br.Ra.length;H.params["params.serviceWorker"]="false";y.document&&y.document.querySelectorAll&&(H.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));Db("sample").constructor!==
Bb&&(H.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(H);if(0!==H.sampleWeight&&!Yt.has(H.message)){if("ERROR"===h){tn.eb("handleError",H);if(R("record_app_crashed_web")&&0===au&&1===H.sampleWeight)if(au++,R("errors_via_jspb")){var cl=new zl;G(cl,1,1);if(!R("report_client_error_with_app_crash_ks")){var cr=new ul;G(cr,1,H.message);var dr=new vl;I(dr,ul,3,cr);var er=new wl;I(er,vl,5,dr);var fr=new xl;I(fr,wl,9,er);I(cl,xl,4,fr)}var gr=new bm;Wd(gr,zl,20,
cm,cl);Rt(gr)}else{var hr={appCrashType:"APP_CRASH_TYPE_BREAKPAD"};R("report_client_error_with_app_crash_ks")||(hr.systemHealth={crashData:{clientError:{logMessage:{message:H.message}}}});oo("appCrashed",hr)}$t++}else"WARNING"===h&&tn.eb("handleWarning",H);if(R("kevlar_gel_error_routing"))a:{var cf=h;if(R("errors_via_jspb")){if(fu())var jr=void 0;else{var Ld=new rl;G(Ld,1,H.stack);H.fileName&&G(Ld,4,H.fileName);var Ob=H.lineNumber&&H.lineNumber.split?H.lineNumber.split(":"):[];0!==Ob.length&&(1!==
Ob.length||isNaN(Number(Ob[0]))?2!==Ob.length||isNaN(Number(Ob[0]))||isNaN(Number(Ob[1]))||(G(Ld,2,Number(Ob[0])),G(Ld,3,Number(Ob[1]))):G(Ld,2,Number(Ob[0])));var Mc=new ul;G(Mc,1,H.message);G(Mc,3,H.name);G(Mc,6,H.sampleWeight);"ERROR"===cf?G(Mc,2,2):"WARNING"===cf?G(Mc,2,1):G(Mc,2,0);var dl=new sl;G(dl,1,!0);Wd(dl,rl,3,tl,Ld);var lc=new Wk;G(lc,3,window.location.href);for(var kr=P("FEXP_EXPERIMENTS",[]),el=0;el<kr.length;el++){var by=kr[el];Dd(lc);Qd(lc,5,2,!1,!1).push(by)}var fl=P("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");
if(!xm()&&fl)for(var lr=r(Object.keys(fl)),Nc=lr.next();!Nc.done;Nc=lr.next()){var mr=Nc.value,gl=new Vk;G(gl,1,mr);G(gl,2,String(fl[mr]));Yd(lc,4,Vk,gl)}var hl=H.params;if(hl){var nr=r(Object.keys(hl));for(Nc=nr.next();!Nc.done;Nc=nr.next()){var or=Nc.value,il=new Vk;G(il,1,"client."+or);G(il,2,String(hl[or]));Yd(lc,4,Vk,il)}}var pr=P("SERVER_NAME"),qr=P("SERVER_VERSION");if(pr&&qr){var jl=new Vk;G(jl,1,"server.name");G(jl,2,pr);Yd(lc,4,Vk,jl);var kl=new Vk;G(kl,1,"server.version");G(kl,2,qr);Yd(lc,
4,Vk,kl)}var vh=new vl;I(vh,Wk,1,lc);I(vh,sl,2,dl);I(vh,ul,3,Mc);jr=vh}var rr=jr;if(!rr)break a;var sr=new bm;Wd(sr,vl,163,cm,rr);Rt(sr)}else{if(fu())var tr=void 0;else{var df={stackTrace:H.stack};H.fileName&&(df.filename=H.fileName);var Pb=H.lineNumber&&H.lineNumber.split?H.lineNumber.split(":"):[];0!==Pb.length&&(1!==Pb.length||isNaN(Number(Pb[0]))?2!==Pb.length||isNaN(Number(Pb[0]))||isNaN(Number(Pb[1]))||(df.lineNumber=Number(Pb[0]),df.columnNumber=Number(Pb[1])):df.lineNumber=Number(Pb[0]));
var ll={level:"ERROR_LEVEL_UNKNOWN",message:H.message,errorClassName:H.name,sampleWeight:H.sampleWeight};"ERROR"===cf?ll.level="ERROR_LEVEL_ERROR":"WARNING"===cf&&(ll.level="ERROR_LEVEL_WARNNING");var cy={isObfuscated:!0,browserStackInfo:df},Md={pageUrl:window.location.href,kvPairs:[]};P("FEXP_EXPERIMENTS")&&(Md.experimentIds=P("FEXP_EXPERIMENTS"));var ml=P("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!xm()&&ml)for(var ur=r(Object.keys(ml)),Oc=ur.next();!Oc.done;Oc=ur.next()){var vr=Oc.value;Md.kvPairs.push({key:vr,
value:String(ml[vr])})}var nl=H.params;if(nl){var wr=r(Object.keys(nl));for(Oc=wr.next();!Oc.done;Oc=wr.next()){var xr=Oc.value;Md.kvPairs.push({key:"client."+xr,value:String(nl[xr])})}}var yr=P("SERVER_NAME"),zr=P("SERVER_VERSION");yr&&zr&&(Md.kvPairs.push({key:"server.name",value:yr}),Md.kvPairs.push({key:"server.version",value:zr}));tr={errorMetadata:Md,stackTrace:cy,logMessage:ll}}var Ar=tr;if(!Ar)break a;oo("clientError",Ar)}if("ERROR"===cf||R("errors_flush_gel_always_killswitch"))b:{if(R("web_fp_via_jspb")&&
(Nt(!0),!R("web_fp_via_jspb_and_json")))break b;Nt()}}if(!R("suppress_error_204_logging")){var ef=H.params||{},mc={urlParams:{a:"logerror",t:"jserror",type:H.name,msg:H.message.substr(0,250),line:H.lineNumber,level:h,"client.name":ef.name},postParams:{url:P("PAGE_NAME",window.location.href),file:H.fileName},method:"POST"};ef.version&&(mc["client.version"]=ef.version);if(mc.postParams){H.stack&&(mc.postParams.stack=H.stack);for(var Br=r(Object.keys(ef)),ol=Br.next();!ol.done;ol=Br.next()){var Cr=ol.value;
mc.postParams["client."+Cr]=ef[Cr]}var pl=P("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(pl)for(var Dr=r(Object.keys(pl)),ql=Dr.next();!ql.done;ql=Dr.next()){var Er=ql.value;mc.postParams[Er]=pl[Er]}var Fr=P("SERVER_NAME"),Gr=P("SERVER_VERSION");Fr&&Gr&&(mc.postParams["server.name"]=Fr,mc.postParams["server.version"]=Gr)}bn(P("ECATCHER_REPORT_HOST","")+"/error_204",mc)}try{Yt.add(H.message)}catch(Pz){}Zt++}}}}
function fu(){for(var a=r(cu),b=a.next();!b.done;b=a.next())if(mn(b.value.toLowerCase()))return!0;return!1}
function gu(a){var b=Ka.apply(1,arguments);a.args||(a.args=[]);a.args.push.apply(a.args,ia(b))}
;function hu(){this.register=new Map}
function iu(a){a=r(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.Yt("ABORTED")}
hu.prototype.clear=function(){iu(this);this.register.clear()};
var ju=new hu;var ku=Date.now().toString();function lu(){for(var a=Array(16),b=0;16>b;b++){for(var c=Date.now(),d=0;d<c%23;d++)a[b]=Math.random();a[b]=Math.floor(256*Math.random())}if(ku)for(b=1,c=0;c<ku.length;c++)a[b%16]=a[b%16]^a[(b-1)%16]/4^ku.charCodeAt(c),b++;return a}
function mu(){if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];return a}catch(d){}return lu()}
function nu(){for(var a=mu(),b=[],c=0;c<a.length;c++)b.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(a[c]&63));return b.join("")}
;var ou=y.ytLoggingDocDocumentNonce_;ou||(ou=nu(),z("ytLoggingDocDocumentNonce_",ou));var pu=ou;var qu={ek:0,lg:1,vg:2,Qn:3,gk:4,Os:5,Qo:6,Iq:7,Xp:8,wq:9,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE",8:"PUSH_NOTIFICATIONS",9:"RICH_GRID_WATCH"};function ru(a){this.N=a}
function su(a){return new ru({trackingParams:a})}
ru.prototype.getAsJson=function(){var a={};void 0!==this.N.trackingParams?a.trackingParams=this.N.trackingParams:(a.veType=this.N.veType,void 0!==this.N.veCounter&&(a.veCounter=this.N.veCounter),void 0!==this.N.elementIndex&&(a.elementIndex=this.N.elementIndex));void 0!==this.N.dataElement&&(a.dataElement=this.N.dataElement.getAsJson());void 0!==this.N.youtubeData&&(a.youtubeData=this.N.youtubeData);return a};
ru.prototype.getAsJspb=function(){var a=new Bl;if(void 0!==this.N.trackingParams){var b=this.N.trackingParams;if(null!=b)if("string"===typeof b)b=b?new pd(b,md):nd||(nd=new pd(null,md));else if(b.constructor!==pd)if(ld(b))b=b.length?new pd(new Uint8Array(b),md):nd||(nd=new pd(null,md));else throw Error();G(a,1,b)}else void 0!==this.N.veType&&G(a,2,this.N.veType),void 0!==this.N.veCounter&&G(a,6,this.N.veCounter),void 0!==this.N.elementIndex&&G(a,3,this.N.elementIndex);void 0!==this.N.dataElement&&
(b=this.N.dataElement.getAsJspb(),I(a,Bl,7,b));void 0!==this.N.youtubeData&&I(a,xk,8,this.N.jspbYoutubeData);return a};
ru.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
ru.prototype.isClientVe=function(){return!this.N.trackingParams&&!!this.N.veType};function tu(a){a=void 0===a?0:a;return 0===a?"client-screen-nonce":"client-screen-nonce."+a}
function uu(a){a=void 0===a?0:a;return 0===a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function vu(a){return P(uu(void 0===a?0:a))}
z("yt_logging_screen.getRootVeType",vu);function wu(a){return(a=vu(void 0===a?0:a))?new ru({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null}
function xu(){var a=P("csn-to-ctt-auth-info");a||(a={},wm("csn-to-ctt-auth-info",a));return a}
function yu(a){a=P(tu(void 0===a?0:a));if(!a&&!P("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
z("yt_logging_screen.getCurrentCsn",yu);function zu(a){for(var b=r(Object.values(qu)),c=b.next();!c.done;c=b.next())if(yu(c.value)===a)return!0;return!1}
function Au(a,b,c){var d=xu();(c=yu(c))&&delete d[c];b&&(d[a]=b)}
function Bu(a){return xu()[a]}
z("yt_logging_screen.getCttAuthInfo",Bu);function Cu(a,b,c,d){c=void 0===c?0:c;if(a!==P(tu(c))||b!==P(uu(c)))if(Au(a,d,c),wm(tu(c),a),wm(uu(c),b),b=function(){setTimeout(function(){if(a)if(R("web_time_via_jspb")){var e=new Cl;G(e,1,pu);G(e,2,a);var f=new bm;Wd(f,Cl,111,cm,e);Rt(f)}else oo("foregroundHeartbeatScreenAssociated",{clientDocumentNonce:pu,clientScreenNonce:a})},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()}
z("yt_logging_screen.setCurrentScreen",Cu);var Du=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};z("yt.msgs_",Du);function Eu(a){rm(Du,arguments)}
;var Fu={kg:3611,qf:27686,rf:85013,sf:23462,tf:157557,uf:42016,vf:62407,wf:26926,xf:51236,yf:79148,zf:50160,Af:77504,Mf:153587,Nf:87907,Of:18630,Pf:54445,Qf:80935,Rf:152172,Sf:105675,Tf:150723,Uf:37521,Vf:147285,Wf:47786,Xf:98349,Yf:168271,Zf:168954,ag:168277,cg:168273,dg:168270,eg:123695,fg:6827,gg:29434,hg:171388,ig:7282,jg:124448,ng:32276,mg:76278,og:147868,pg:147869,qg:93911,rg:106531,sg:27259,tg:27262,ug:27263,wg:21759,xg:27107,yg:62936,zg:160866,Ag:49568,Bg:171243,Cg:160789,Dg:171244,Eg:171241,
Fg:171245,Gg:171242,Hg:38408,Ig:80637,Jg:68727,Kg:68728,Lg:80353,Mg:80356,Ng:74610,Og:45707,Pg:83962,Qg:83970,Rg:46713,Sg:166591,Tg:89711,Ug:74612,Vg:155792,Wg:93265,Xg:74611,Yg:131380,ah:128979,bh:139311,dh:128978,Zg:131391,eh:105350,gh:139312,hh:134800,fh:131392,jh:113533,kh:93252,lh:99357,nh:94521,oh:114252,ph:113532,qh:94522,mh:94583,rh:88E3,sh:139580,th:93253,uh:93254,vh:94387,wh:94388,xh:93255,yh:97424,ih:72502,zh:110111,Ah:76019,Ch:117092,Dh:117093,Bh:89431,Eh:110466,Fh:77240,Gh:60508,Hh:148123,
Ih:148124,Jh:137401,Kh:137402,Lh:137046,Mh:73393,Nh:113534,Oh:92098,Ph:131381,Qh:84517,Rh:83759,Sh:162711,Th:162712,Uh:80357,Vh:86113,Wh:72598,Xh:168413,Yh:72733,Zh:107349,ai:124275,bi:118203,ci:133275,di:160157,fi:152569,gi:156651,hi:133274,ii:160159,ji:160158,ki:133272,li:133273,mi:133276,ni:144507,oi:143247,ri:156652,si:143248,ti:143249,vi:143250,wi:143251,xi:156653,yi:144401,Ai:117431,zi:133797,Bi:153964,Ci:128572,Di:133405,Ei:117429,Fi:117430,Gi:117432,Hi:173996,Ii:173995,Ji:173994,Ki:173997,
Li:120080,Mi:117259,Ni:156655,Oi:156654,Pi:121692,Qi:145656,Ri:156656,Si:145655,Ti:145653,Ui:145654,Vi:145657,Wi:132972,Xi:133051,Yi:133658,Zi:132971,aj:97615,cj:143359,bj:143356,ej:143361,dj:143358,gj:143360,fj:143357,hj:142303,ij:143353,jj:172859,kj:143354,lj:144479,mj:143355,nj:31402,pj:133624,qj:146477,rj:133623,sj:133622,oj:133621,tj:84774,vj:160801,uj:95117,wj:172721,xj:150497,yj:98930,zj:98931,Aj:98932,Bj:153320,Cj:153321,Dj:43347,Ej:129889,Fj:149123,Gj:45474,Hj:100352,Ij:84758,Jj:98443,Kj:117985,
Lj:74613,Mj:155911,Nj:74614,Oj:64502,Pj:136032,Qj:74615,Rj:74616,Sj:122224,Tj:74617,Uj:77820,Vj:74618,Wj:93278,Xj:93274,Yj:93275,Zj:93276,ak:22110,bk:29433,ck:133798,dk:132295,fk:120541,hk:82047,ik:113550,jk:75836,kk:75837,lk:42352,mk:84512,nk:76065,pk:75989,uk:51879,vk:16623,wk:32594,xk:27240,yk:32633,zk:74858,Ak:156999,Ck:3945,Bk:16989,Dk:45520,Ek:25488,Fk:25492,Gk:25494,Hk:55760,Ik:14057,Jk:18451,Kk:57204,Lk:57203,Mk:17897,Nk:57205,Ok:18198,Pk:17898,Qk:17909,Rk:43980,Sk:46220,Tk:11721,Uk:147994,
Vk:49954,Wk:96369,Xk:3854,Yk:151633,Zk:56251,al:159108,bl:25624,dl:152036,Al:16906,Bl:99999,Cl:68172,Dl:27068,El:47973,Fl:72773,Gl:26970,Hl:26971,Il:96805,Jl:17752,Kl:73233,Ll:109512,Ml:22256,Nl:14115,Ol:22696,Pl:89278,Ql:89277,Rl:109513,Sl:43278,Tl:43459,Ul:43464,Vl:89279,Wl:43717,Xl:55764,Yl:22255,Zl:147912,am:89281,bm:40963,cm:43277,dm:43442,em:91824,fm:120137,gm:96367,hm:36850,im:72694,jm:37414,km:36851,mm:124863,lm:121343,nm:73491,om:54473,pm:166861,qm:43375,rm:46674,sm:143815,tm:139095,um:144402,
vm:149968,wm:149969,xm:32473,ym:72901,zm:72906,Am:50612,Bm:50613,Cm:50942,Dm:84938,Em:84943,Fm:84939,Gm:84941,Hm:84944,Im:84940,Jm:84942,Km:35585,Lm:51926,Mm:79983,Nm:18921,Om:57893,Pm:41182,Qm:135732,Rm:33424,Sm:22207,Tm:36229,Um:22206,Vm:22205,Wm:44763,Xm:33427,Ym:67793,Zm:22182,an:37091,bn:34650,cn:50617,dn:22287,en:25144,fn:97917,gn:62397,hn:150871,jn:150874,kn:125598,ln:137935,mn:36961,nn:108035,pn:27426,qn:27857,rn:27846,sn:27854,tn:69692,un:61411,vn:39299,wn:38696,xn:62520,yn:36382,zn:108701,
An:50663,Bn:36387,Cn:14908,Dn:37533,En:105443,Fn:61635,Gn:62274,Hn:161670,In:133818,Jn:65702,Kn:65703,Ln:65701,Mn:76256,Nn:166382,On:37671,Pn:49953,Rn:36216,Sn:28237,Tn:173718,Un:39553,Vn:29222,Wn:26107,Xn:38050,Yn:26108,ao:120745,Zn:26109,bo:26110,co:66881,eo:28236,fo:14586,ho:160598,jo:57929,ko:74723,lo:44098,mo:173689,no:44099,qo:23528,ro:61699,oo:134104,po:134103,so:59149,to:173191,uo:173192,vo:173193,xo:101951,wo:171502,yo:97346,zo:118051,Ao:95102,Bo:64882,Co:119505,Do:63595,Eo:63349,Fo:95101,
Go:75240,Ho:27039,Io:68823,Jo:21537,Ko:83464,Lo:75707,Mo:170215,No:83113,Oo:101952,Po:101953,Ro:79610,So:125755,To:24402,Uo:24400,Vo:32925,Xo:57173,Wo:156421,Yo:122502,Zo:145268,ap:138480,bp:64423,cp:64424,ep:33986,fp:100828,gp:129089,hp:21409,lp:135155,mp:135156,np:135157,qp:135158,rp:158225,sp:135159,tp:135160,up:167651,vp:135161,xp:135162,yp:135163,wp:158226,zp:158227,Ap:135164,Bp:135165,Cp:135166,ip:11070,jp:11074,kp:17880,Ep:30709,Fp:30707,Gp:30711,Hp:30710,Ip:30708,Dp:26984,Jp:146143,Kp:63648,
Lp:63649,Mp:111059,Np:5754,Op:20445,Pp:151308,Qp:151152,Tp:130975,Sp:130976,Rp:167637,Up:110386,Vp:113746,Wp:66557,Yp:17310,Zp:28631,aq:21589,bq:164817,cq:168011,fq:154946,gq:68012,hq:162617,iq:60480,jq:138664,kq:141121,lq:164502,mq:31571,nq:141978,oq:150105,pq:150106,qq:150107,rq:150108,sq:76980,tq:41577,uq:45469,xq:38669,yq:13768,zq:13777,Aq:141842,Bq:62985,Cq:4724,Dq:59369,Eq:43927,Fq:43928,Gq:12924,Hq:100355,Kq:56219,Lq:27669,Mq:10337,Jq:47896,Nq:122629,Pq:139723,Oq:139722,Qq:121258,Rq:107598,
Sq:127991,Tq:96639,Uq:107536,Vq:130169,Wq:96661,Xq:145188,Yq:96658,Zq:116646,br:159428,er:168611,fr:168612,dr:121122,gr:96660,hr:127738,ir:127083,jr:155281,kr:162959,lr:163566,mr:147842,pr:104443,qr:96659,rr:147595,sr:106442,tr:162776,ur:134840,vr:63667,wr:63668,xr:63669,yr:130686,zr:147036,Ar:78314,Br:147799,Cr:174049,Dr:148649,Er:55761,Fr:127098,Gr:134841,Hr:96368,Ir:67374,Jr:48992,Kr:146176,Lr:49956,Mr:31961,Nr:26388,Or:23811,Pr:5E4,Qr:126250,Rr:96370,Sr:47355,Tr:47356,Ur:37935,Vr:45521,Wr:21760,
Xr:83769,Yr:49977,Zr:49974,bs:93497,ds:93498,es:34325,gs:140759,hs:115803,ks:123707,ls:100081,ms:35309,ns:68314,qs:25602,rs:100339,ts:170873,us:143516,vs:59018,ws:18248,xs:50625,ys:9729,zs:37168,As:37169,Bs:21667,Cs:16749,Ds:18635,Es:39305,Fs:18046,Gs:53969,Hs:8213,Is:93926,Js:102852,Ks:110099,Ls:22678,Ms:69076,Ns:137575,Ps:139224,Qs:100856,Rs:154430,Ss:17736,Ts:3832,Us:147111,Vs:55759,Ws:64031,et:93044,ft:93045,gt:170701,ht:170702,lt:34388,jt:167841,kt:170419,mt:17657,nt:17655,ot:39579,pt:39578,
qt:170412,rt:77448,tt:8196,ut:11357,vt:69877,wt:8197,xt:168501,zt:156512,At:161613,Bt:156509,Ct:161612,Dt:161614,Et:82039};function Gu(){var a=ub(Hu),b;return(new Bf(function(c,d){a.onSuccess=function(e){Vm(e)?c(new Iu(e)):d(new Ju("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new Ju("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new Ju("Request timed out","net.timeout",e))};
b=bn("//googleads.g.doubleclick.net/pagead/id",a)})).vc(function(c){c instanceof If&&b.abort();
return Gf(c)})}
function Ju(a,b,c){bb.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
v(Ju,bb);function Iu(a){this.xhr=a}
;function Ku(){this.h=0;this.Aa=null}
Ku.prototype.then=function(a,b,c){return 1===this.h&&a?(a=a.call(c,this.Aa))&&"function"===typeof a.then?a:Lu(a):2===this.h&&b?(a=b.call(c,this.Aa))&&"function"===typeof a.then?a:Mu(a):this};
Ku.prototype.getValue=function(){return this.Aa};
Ku.prototype.$goog_Thenable=!0;function Mu(a){var b=new Ku;a=void 0===a?null:a;b.h=2;b.Aa=void 0===a?null:a;return b}
function Lu(a){var b=new Ku;a=void 0===a?null:a;b.h=1;b.Aa=void 0===a?null:a;return b}
;function Nu(a,b){var c=void 0===c?{}:c;a={method:void 0===b?"POST":b,mode:Mm(a)?"same-origin":"cors",credentials:Mm(a)?"same-origin":"include"};b={};for(var d=r(Object.keys(c)),e=d.next();!e.done;e=d.next())e=e.value,c[e]&&(b[e]=c[e]);0<Object.keys(b).length&&(a.headers=b);return a}
;function Ou(){return Bg()||ln&&mn("applewebkit")&&!mn("version")&&(!mn("safari")||mn("gsa/"))||Lc&&mn("version/")?!0:P("EOM_VISITOR_DATA")?!1:!0}
;function Pu(a){a:{var b=a.raw_embedded_player_response;if(!b&&(a=a.embedded_player_response))try{b=JSON.parse(a)}catch(d){b="EMBEDDED_PLAYER_MODE_UNKNOWN";break a}if(b)b:{for(var c in Sk)if(Sk[c]==b.embeddedPlayerMode){b=Sk[c];break b}b="EMBEDDED_PLAYER_MODE_UNKNOWN"}else b="EMBEDDED_PLAYER_MODE_UNKNOWN"}return"EMBEDDED_PLAYER_MODE_PFL"===b}
;function Qu(a){bb.call(this,a.message||a.description||a.name);this.isMissing=a instanceof Ru;this.isTimeout=a instanceof Ju&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof If}
v(Qu,bb);Qu.prototype.name="BiscottiError";function Ru(){bb.call(this,"Biscotti ID is missing from server")}
v(Ru,bb);Ru.prototype.name="BiscottiMissingError";var Hu={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},Su=null;function Tu(){if(R("disable_biscotti_fetch_entirely_for_all_web_clients"))return Error("Biscotti id fetching has been disabled entirely.");if(!Ou())return Error("User has not consented - not fetching biscotti id.");var a=P("PLAYER_VARS",{});if("1"==sb(a))return Error("Biscotti ID is not available in private embed mode");if(Pu(a))return Error("Biscotti id fetching has been disabled for pfl.")}
function pm(){var a=Tu();if(void 0!==a)return Gf(a);Su||(Su=Gu().then(Uu).vc(function(b){return Vu(2,b)}));
return Su}
function Uu(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new Ru;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new Ru;a=a.id;qm(a);Su=Lu(a);Wu(18E5,2);return a}
function Vu(a,b){b=new Qu(b);qm("");Su=Mu(b);0<a&&Wu(12E4,a-1);throw b;}
function Wu(a,b){Wm(function(){Gu().then(Uu,function(c){return Vu(b,c)}).vc(db)},a)}
function Xu(){try{var a=A("yt.ads.biscotti.getId_");return a?a():pm()}catch(b){return Gf(b)}}
;function Yu(a){if("1"!=sb(P("PLAYER_VARS",{}))){a&&om();try{Xu().then(function(){},function(){}),Wm(Yu,18E5)}catch(b){Bm(b)}}}
;function Zu(){var a=Ln(),b=On(119),c=1<window.devicePixelRatio;if(document.body&&wi(document.body,"exp-invert-logo"))if(c&&!wi(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!wi(d,"inverted-hdpi")){var e=ui(d);vi(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&wi(document.body,"inverted-hdpi")&&xi();if(b!=c){b="f"+(Math.floor(119/31)+1);d=Pn(b)||0;d=c?d|67108864:d&-67108865;0===d?delete In[b]:(c=d.toString(16),In[b]=c.toString());
c=!0;R("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.h;d=[];for(var f in In)In.hasOwnProperty(f)&&d.push(f+"="+encodeURIComponent(String(In[f])));Fn(b,d.join("&"),63072E3,a.i,c)}}
;var $u=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function av(){var a=void 0===a?window.location.href:a;if(R("kevlar_disable_theme_param"))return null;nc(oc(5,a));try{var b=Km(a).theme;return $u.get(b)||null}catch(c){}return null}
;function bv(){this.h={};if(this.i=Hn()){var a=zg.get("CONSISTENCY",void 0);a&&cv(this,{encryptedTokenJarContents:a})}}
bv.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=(null==(c=b.La.context)?void 0:null==(d=c.request)?void 0:d.consistencyTokenJars)||[];var e;if(a=null==(e=a.responseContext)?void 0:e.consistencyTokenJar){e=r(b);for(c=e.next();!c.done;c=e.next())delete this.h[c.value.encryptedTokenJarContents];cv(this,a)}};
function cv(a,b){if(b.encryptedTokenJarContents&&(a.h[b.encryptedTokenJarContents]=b,"string"===typeof b.expirationSeconds)){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.h[b.encryptedTokenJarContents]},1E3*c);
a.i&&Fn("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var dv=window.location.hostname.split(".").slice(-2).join(".");function ev(){var a=P("LOCATION_PLAYABILITY_TOKEN");"TVHTML5"===P("INNERTUBE_CLIENT_NAME")&&(this.h=fv(this))&&(a=this.h.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.i=void 0)}
var gv;function hv(){gv=A("yt.clientLocationService.instance");gv||(gv=new ev,z("yt.clientLocationService.instance",gv));return gv}
l=ev.prototype;l.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});this.i?(a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(1E7*this.i.coords.latitude),a.client.locationInfo.longitudeE7=Math.floor(1E7*this.i.coords.longitude),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.i.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0):this.locationPlayabilityToken&&(a.client.locationPlayabilityToken=this.locationPlayabilityToken)};
l.handleResponse=function(a){var b;a=null==(b=a.responseContext)?void 0:b.locationPlayabilityToken;void 0!==a&&(this.locationPlayabilityToken=a,this.i=void 0,"TVHTML5"===P("INNERTUBE_CLIENT_NAME")?(this.h=fv(this))&&this.h.set("yt-location-playability-token",a,15552E3):Fn("YT_CL",JSON.stringify({loctok:a}),15552E3,dv,!0))};
function fv(a){return void 0===a.h?new fo("yt-client-location"):a.h}
l.clearLocationPlayabilityToken=function(a){"TVHTML5"===a?(this.h=fv(this))&&this.h.remove("yt-location-playability-token"):Gn("YT_CL")};
l.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;"MWEB"===P("INNERTUBE_CLIENT_NAME")&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.i=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
l.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);if(null==a?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};function iv(a,b){var c,d=null==(c=Ys(a,Rk))?void 0:c.signal;if(d&&b.Sb&&(c=b.Sb[d]))return c();var e;if((c=null==(e=Ys(a,Pk))?void 0:e.request)&&b.je&&(e=b.je[c]))return e();for(var f in a)if(b.jd[f]&&(a=b.jd[f]))return a()}
;function jv(a){return function(){return new a}}
;var kv={},lv=(kv.WEB_UNPLUGGED="^unplugged/",kv.WEB_UNPLUGGED_ONBOARDING="^unplugged/",kv.WEB_UNPLUGGED_OPS="^unplugged/",kv.WEB_UNPLUGGED_PUBLIC="^unplugged/",kv.WEB_CREATOR="^creator/",kv.WEB_KIDS="^kids/",kv.WEB_EXPERIMENTS="^experiments/",kv.WEB_MUSIC="^music/",kv.WEB_REMIX="^music/",kv.WEB_MUSIC_EMBEDDED_PLAYER="^music/",kv.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",kv);
function mv(a){var b=void 0===b?"UNKNOWN_INTERFACE":b;if(1===a.length)return a[0];var c=lv[b];if(c){var d=new RegExp(c),e=r(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,d.exec(c))return c}var f=[];Object.entries(lv).forEach(function(g){var h=r(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
d=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
e=r(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,!d.exec(c))return c;return a[0]}
;function nv(){}
nv.prototype.m=function(a,b,c){b=void 0===b?{}:b;c=void 0===c?Cn:c;var d=a.clickTrackingParams,e=this.l,f=!1;f=void 0===f?!1:f;e=void 0===e?!1:e;var g=P("INNERTUBE_CONTEXT");if(g){g=wb(g);R("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;"MWEB"===h.clientName&&(h.clientFormFactor=P("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||
1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=void 0===k?!1:k;Ln();var m="USER_INTERFACE_THEME_LIGHT";On(165)?m="USER_INTERFACE_THEME_DARK":On(174)?m="USER_INTERFACE_THEME_LIGHT":!R("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(m="USER_INTERFACE_THEME_DARK");k=k?m:av()||m;h.userInterfaceTheme=k;if(!f){if(k=Vn())h.connectionType=
k;R("web_log_effective_connection_type")&&(k=Wn())&&(g.client.effectiveConnectionType=k)}var n;if(R("web_log_memory_total_kbytes")&&(null==(n=y.navigator)?0:n.deviceMemory)){var q;n=null==(q=y.navigator)?void 0:q.deviceMemory;g.client.memoryTotalKbytes=""+1E6*n}q=Km(y.location.href);!R("web_populate_internal_geo_killswitch")&&q.internalcountrycode&&(h.internalGeo=q.internalcountrycode);"MWEB"===h.clientName||"WEB"===h.clientName?(h.mainAppWebInfo={graftUrl:y.location.href},R("kevlar_woffle")&&Dn.h&&
(q=Dn.h,h.mainAppWebInfo.pwaInstallabilityStatus=!q.h&&q.i?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=En(),h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&void 0!==navigator.share):"TVHTML5"===h.clientName&&(!R("web_lr_app_quality_killswitch")&&(q=P("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:q})),q=P("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{certificationScope:q}));
if(!R("web_populate_time_zone_itc_killswitch")){b:{if("undefined"!==typeof Intl)try{var u=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(vb){}u=void 0}u&&(h.timeZone=u)}(u=Rm())?h.experimentsToken=u:delete h.experimentsToken;u=Sm();bv.h||(bv.h=new bv);h=bv.h.h;q=[];n=0;for(var t in h)q[n++]=h[t];g.request=Object.assign({},g.request,{internalExperimentFlags:u,consistencyTokenJars:q});!R("web_prequest_context_killswitch")&&(t=P("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&(g.request.externalPrequestContext=
t);u=Ln();t=On(58);u=u.get("gsml","");g.user=Object.assign({},g.user);t&&(g.user.enableSafetyMode=t);u&&(g.user.lockedSafetyMode=!0);R("warm_op_csn_cleanup")?e&&(f=yu())&&(g.clientScreenNonce=f):!f&&(f=yu())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=A("yt.mdx.remote.remoteClient_"))g.remoteClient=d;hv().setLocationOnInnerTubeContext(g);try{var B=Nm(),D=B.bid;delete B.bid;g.adSignalsInfo={params:[],bid:D};var F=r(Object.entries(B));for(var N=F.next();!N.done;N=F.next()){var O=
r(N.value),Q=O.next().value,ca=O.next().value;B=Q;D=ca;d=void 0;null==(d=g.adSignalsInfo.params)||d.push({key:B,value:""+D})}}catch(vb){du(vb)}F=g}else du(Error("Error: No InnerTubeContext shell provided in ytconfig.")),F={};F={context:F};if(N=this.h(a)){this.i(F,N,b);var X;b="/youtubei/v1/"+mv(this.j());(N=null==(X=Ys(a.commandMetadata,Qk))?void 0:X.apiUrl)&&(b=N);X=b;(b=P("INNERTUBE_HOST_OVERRIDE"))&&(X=String(b)+String(qc(X)));b={};b.key=P("INNERTUBE_API_KEY");R("json_condensed_response")&&(b.prettyPrint=
"false");X=Lm(X,b||{},!1);a=Object.assign({},{command:a},void 0);a={input:X,lb:Nu(X),La:F,config:a};a.config.cc?a.config.cc.identity=c:a.config.cc={identity:c};return a}du(new S("Error: Failed to create Request from Command.",a))};
ea.Object.defineProperties(nv.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!1}}});function ov(){}
v(ov,nv);ov.prototype.m=function(){return{input:"/getDatasyncIdsEndpoint",lb:Nu("/getDatasyncIdsEndpoint","GET"),La:{}}};
ov.prototype.j=function(){return[]};
ov.prototype.h=function(){};
ov.prototype.i=function(){};var pv={},qv=(pv.GET_DATASYNC_IDS=jv(ov),pv);function rv(a){var b=Ka.apply(1,arguments);if(!sv(a)||b.some(function(d){return!sv(d)}))throw Error("Only objects may be merged.");
b=r(b);for(var c=b.next();!c.done;c=b.next())tv(a,c.value);return a}
function tv(a,b){for(var c in b)if(sv(b[c])){if(c in a&&!sv(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});tv(a[c],b[c])}else if(uv(b[c])){if(c in a&&!uv(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);vv(a[c],b[c])}else a[c]=b[c];return a}
function vv(a,b){b=r(b);for(var c=b.next();!c.done;c=b.next())c=c.value,sv(c)?a.push(tv({},c)):uv(c)?a.push(vv([],c)):a.push(c);return a}
function sv(a){return"object"===typeof a&&!Array.isArray(a)}
function uv(a){return"object"===typeof a&&Array.isArray(a)}
;function wv(a){var b;(b=A("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},z("ytcsi."+(a||"")+"data_",b));return b}
function xv(){var a=wv();a.info||(a.info={});return a.info}
function yv(a){a=wv(a);a.metadata||(a.metadata={});return a.metadata}
function zv(a){a=wv(a);a.tick||(a.tick={});return a.tick}
function Av(a){a=wv(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function Bv(a){a=Av(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function Cv(a){var b=wv(a).nonce;b||(b=nu(),wv(a).nonce=b);return b}
;function Dv(){var a=A("ytcsi.debug");a||(a=[],z("ytcsi.debug",a),z("ytcsi.reference",{}));return a}
function Ev(a){a=a||"";var b=A("ytcsi.reference");b||(Dv(),b=A("ytcsi.reference"));if(b[a])return b[a];var c=Dv(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var U={},Fv=(U.auto_search="LATENCY_ACTION_AUTO_SEARCH",U.ad_to_ad="LATENCY_ACTION_AD_TO_AD",U.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",U["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",U.app_startup="LATENCY_ACTION_APP_STARTUP",U["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",U["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",U["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",U["asset.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS",
U["asset.composition"]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION",U["asset.embeds"]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS",U["asset.issues"]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES",U["asset.licenses"]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES",U["asset.metadata"]="LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA",U["asset.ownership"]="LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP",U["asset.policy"]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY",U["asset.references"]="LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES",
U["asset.sound_recordings"]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS",U["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",U.browse="LATENCY_ACTION_BROWSE",U.cast_splash="LATENCY_ACTION_CAST_SPLASH",U.channels="LATENCY_ACTION_CHANNELS",U.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",U["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",U["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",U["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",
U["channel.content.promotions"]="LATENCY_ACTION_CREATOR_PROMOTION_LIST",U["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",U["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",U["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",U["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",U["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",U["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",U["channel.translations"]=
"LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",U["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",U["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",U.chips="LATENCY_ACTION_CHIPS",U["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",U["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",U["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",U.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",U.embed="LATENCY_ACTION_EMBED",
U.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",U.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",U.explore="LATENCY_ACTION_EXPLORE",U.home="LATENCY_ACTION_HOME",U.library="LATENCY_ACTION_LIBRARY",U.live="LATENCY_ACTION_LIVE",U.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",U.onboarding="LATENCY_ACTION_ONBOARDING",U.owner="LATENCY_ACTION_CREATOR_CMS_DASHBOARD",U["owner.allowlist"]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST",U["owner.analytics"]=
"LATENCY_ACTION_CREATOR_CMS_ANALYTICS",U["owner.art_tracks"]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS",U["owner.assets"]="LATENCY_ACTION_CREATOR_CMS_ASSETS",U["owner.asset_groups"]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS",U["owner.campaigns"]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS",U["owner.channels"]="LATENCY_ACTION_CREATOR_CMS_CHANNELS",U["owner.claimed_videos"]="LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS",U["owner.claims"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",U["owner.claims.manual"]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING",
U["owner.delivery"]="LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY",U["owner.issues"]="LATENCY_ACTION_CREATOR_CMS_ISSUES",U["owner.licenses"]="LATENCY_ACTION_CREATOR_CMS_LICENSES",U["owner.pitch_music"]="LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC",U["owner.policies"]="LATENCY_ACTION_CREATOR_CMS_POLICIES",U["owner.releases"]="LATENCY_ACTION_CREATOR_CMS_RELEASES",U["owner.reports"]="LATENCY_ACTION_CREATOR_CMS_REPORTS",U["owner.videos"]="LATENCY_ACTION_CREATOR_CMS_VIDEOS",U.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",
U.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",U.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",U.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",U["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",U["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",U.prebuffer="LATENCY_ACTION_PREBUFFER",U.prefetch="LATENCY_ACTION_PREFETCH",U.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",U.profile_switcher="LATENCY_ACTION_LOGIN",U.reel_watch="LATENCY_ACTION_REEL_WATCH",
U.results="LATENCY_ACTION_RESULTS",U["promotion.edit"]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT",U.search_ui="LATENCY_ACTION_SEARCH_UI",U.search_suggest="LATENCY_ACTION_SUGGEST",U.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",U.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",U.seek="LATENCY_ACTION_PLAYER_SEEK",U.settings="LATENCY_ACTION_SETTINGS",U.store="LATENCY_ACTION_STORE",U.tenx="LATENCY_ACTION_TENX",U.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",U.watch="LATENCY_ACTION_WATCH",U.watch_it_again=
"LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",U["watch,watch7"]="LATENCY_ACTION_WATCH",U["watch,watch7_html5"]="LATENCY_ACTION_WATCH",U["watch,watch7ad"]="LATENCY_ACTION_WATCH",U["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",U.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",U.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",U["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",U["video.claims"]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS",U["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",U["video.copyright"]=
"LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT",U["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",U["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",U["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",U["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",U["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",U["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",U["video.policy"]="LATENCY_ACTION_CREATOR_VIDEO_POLICY",U["video.rights_management"]=
"LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT",U["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",U.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",U.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",U.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",U.gel_compression="LATENCY_ACTION_GEL_COMPRESSION",U),V={},Gv=(V.ad_allowed="adTypesAllowed",V.yt_abt="adBreakType",V.ad_cpn="adClientPlaybackNonce",V.ad_docid="adVideoId",V.yt_ad_an="adNetworks",
V.ad_at="adType",V.aida="appInstallDataAgeMs",V.browse_id="browseId",V.p="httpProtocol",V.t="transportProtocol",V.cs="commandSource",V.cpn="clientPlaybackNonce",V.ccs="creatorInfo.creatorCanaryState",V.ctop="creatorInfo.topEntityType",V.csn="clientScreenNonce",V.docid="videoId",V.GetHome_rid="requestIds",V.GetSearch_rid="requestIds",V.GetPlayer_rid="requestIds",V.GetWatchNext_rid="requestIds",V.GetBrowse_rid="requestIds",V.GetLibrary_rid="requestIds",V.is_continuation="isContinuation",V.is_nav="isNavigation",
V.b_p="kabukiInfo.browseParams",V.is_prefetch="kabukiInfo.isPrefetch",V.is_secondary_nav="kabukiInfo.isSecondaryNav",V.nav_type="kabukiInfo.navigationType",V.prev_browse_id="kabukiInfo.prevBrowseId",V.query_source="kabukiInfo.querySource",V.voz_type="kabukiInfo.vozType",V.yt_lt="loadType",V.mver="creatorInfo.measurementVersion",V.yt_ad="isMonetized",V.nr="webInfo.navigationReason",V.nrsu="navigationRequestedSameUrl",V.pnt="performanceNavigationTiming",V.prt="playbackRequiresTap",V.plt="playerInfo.playbackType",
V.pis="playerInfo.playerInitializedState",V.paused="playerInfo.isPausedOnLoad",V.yt_pt="playerType",V.fmt="playerInfo.itag",V.yt_pl="watchInfo.isPlaylist",V.yt_pre="playerInfo.preloadType",V.yt_ad_pr="prerollAllowed",V.pa="previousAction",V.yt_red="isRedSubscriber",V.rce="mwebInfo.responseContentEncoding",V.rc="resourceInfo.resourceCache",V.scrh="screenHeight",V.scrw="screenWidth",V.st="serverTimeMs",V.ssdm="shellStartupDurationMs",V.br_trs="tvInfo.bedrockTriggerState",V.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",
V.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",V.label="tvInfo.label",V.is_mdx="tvInfo.isMdx",V.preloaded="tvInfo.isPreloaded",V.aac_type="tvInfo.authAccessCredentialType",V.upg_player_vis="playerInfo.visibilityState",V.query="unpluggedInfo.query",V.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",V.yt_vst="videoStreamType",V.vph="viewportHeight",V.vpw="viewportWidth",V.yt_vis="isVisible",V.rcl="mwebInfo.responseContentLength",V.GetSettings_rid="requestIds",V.GetTrending_rid="requestIds",
V.GetMusicSearchSuggestions_rid="requestIds",V.REQUEST_ID="requestIds",V),Hv="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),Iv={},Jv=(Iv.ccs="CANARY_STATE_",Iv.mver="MEASUREMENT_VERSION_",Iv.pis="PLAYER_INITIALIZED_STATE_",
Iv.yt_pt="LATENCY_PLAYER_",Iv.pa="LATENCY_ACTION_",Iv.ctop="TOP_ENTITY_TYPE_",Iv.yt_vst="VIDEO_STREAM_TYPE_",Iv),Kv="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function Lv(a){return Fv[a]||"LATENCY_ACTION_UNKNOWN"}
function Mv(a,b,c){c=Av(c);if(c.gelInfos)c.gelInfos[a]=!0;else{var d={};c.gelInfos=(d[a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in Gv){c=Gv[a];0<=fb(Hv,c)&&(b=!!b);a in Jv&&"string"===typeof b&&(b=Jv[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return rv({},d)}0<=fb(Kv,a)||eu(new S("Unknown label logged with GEL CSI",a))}
;var W={LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING:179,LATENCY_ACTION_KIDS_PROFILE_SWITCHER:90,LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER:100,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC:46,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR:37,LATENCY_ACTION_SPINNER_DISPLAYED:14,LATENCY_ACTION_PLAYABILITY_CHECK:10,LATENCY_ACTION_PROCESS:9,LATENCY_ACTION_APP_STARTUP:5,LATENCY_ACTION_GEL_COMPRESSION:215,LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE:204,LATENCY_ACTION_COMMERCE_ACTION_COMMAND_RPC:203,LATENCY_ACTION_COMMERCE_TRANSACTION:184,
LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC:173,LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC:172,LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC:171,LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC:170,LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC:169,LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC:168,LATENCY_ACTION_GET_OFFERS_RPC:167,LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC:166,LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC:165,LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC:164,LATENCY_ACTION_GET_OFFER_DETAILS_RPC:163,
LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC:162,LATENCY_ACTION_GET_TIP_MODULE_RPC:161,LATENCY_ACTION_HANDLE_TRANSACTION_RPC:160,LATENCY_ACTION_COMPLETE_TRANSACTION_RPC:159,LATENCY_ACTION_GET_CART_RPC:158,LATENCY_ACTION_THUMBNAIL_FETCH:156,LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK:154,LATENCY_ACTION_SHARE_VIDEO:153,LATENCY_ACTION_AD_TO_VIDEO_INT:152,LATENCY_ACTION_ABANDONED_BROWSE:151,LATENCY_ACTION_PLAYER_ROTATION:150,LATENCY_ACTION_GENERIC_WEB_VIEW:183,LATENCY_ACTION_SHOPPING_IN_APP:124,LATENCY_ACTION_PLAYER_ATTESTATION:121,
LATENCY_ACTION_PLAYER_SEEK:119,LATENCY_ACTION_SUPER_STICKER_BUY_FLOW:114,LATENCY_ACTION_DOWNLOADS_DATA_ACCESS:180,LATENCY_ACTION_BLOCKS_PERFORMANCE:148,LATENCY_ACTION_ASSISTANT_QUERY:138,LATENCY_ACTION_ASSISTANT_SETTINGS:137,LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF:129,LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF:128,LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE:127,LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION:123,LATENCY_ACTION_NETWORKLESS_PERFORMANCE:122,LATENCY_ACTION_DOWNLOADS_EXPANSION:133,LATENCY_ACTION_ENTITY_TRANSFORM:131,
LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER:96,LATENCY_ACTION_EMBEDS_SET_VIDEO:95,LATENCY_ACTION_SETTINGS:93,LATENCY_ACTION_ABANDONED_STARTUP:81,LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY:80,LATENCY_ACTION_MEDIA_BROWSER_SEARCH:79,LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE:78,LATENCY_ACTION_WHO_IS_WATCHING:77,LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH:76,LATENCY_ACTION_LITE_SWITCH_ACCOUNT:73,LATENCY_ACTION_ELEMENTS_PERFORMANCE:70,LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION:69,LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION:65,
LATENCY_ACTION_OFFLINE_STORE_START:61,LATENCY_ACTION_REEL_EDITOR:58,LATENCY_ACTION_CHANNEL_SUBSCRIBE:56,LATENCY_ACTION_CHANNEL_PREVIEW:55,LATENCY_ACTION_PREFETCH:52,LATENCY_ACTION_ABANDONED_WATCH:45,LATENCY_ACTION_LOAD_COMMENT_REPLIES:26,LATENCY_ACTION_LOAD_COMMENTS:25,LATENCY_ACTION_EDIT_COMMENT:24,LATENCY_ACTION_NEW_COMMENT:23,LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING:19,LATENCY_ACTION_EMBED:18,LATENCY_ACTION_MDX_LAUNCH:15,LATENCY_ACTION_RESOLVE_URL:13,LATENCY_ACTION_CAST_SPLASH:149,LATENCY_ACTION_MDX_CONNECT_TO_SESSION:190,
LATENCY_ACTION_MDX_STREAM_TRANSFER:178,LATENCY_ACTION_MDX_CAST:120,LATENCY_ACTION_MDX_COMMAND:12,LATENCY_ACTION_MOBILE_LIVE_NAV_MDE:231,LATENCY_ACTION_REEL_SELECT_SEGMENT:136,LATENCY_ACTION_ACCELERATED_EFFECTS:145,LATENCY_ACTION_SHORTS_TRIM_TO_EDITOR_TRANSCODING:229,LATENCY_ACTION_EDIT_AUDIO_GEN:182,LATENCY_ACTION_UPLOAD_AUDIO_MIXER:147,LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING:157,LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING:146,LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK:130,LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD:125,
LATENCY_ACTION_SHORTS_VIDEO_INGESTION:155,LATENCY_ACTION_SHORTS_GALLERY:107,LATENCY_ACTION_SHORTS_TRIM:105,LATENCY_ACTION_SHORTS_EDIT:104,LATENCY_ACTION_SHORTS_CAMERA:103,LATENCY_ACTION_PRODUCER_IMPORT_LOCAL_MEDIA:233,LATENCY_ACTION_PRODUCER_EXPORT_PROJECT:193,LATENCY_ACTION_PRODUCER_EDITOR:192,LATENCY_ACTION_PARENT_TOOLS_DASHBOARD:102,LATENCY_ACTION_PARENT_TOOLS_COLLECTION:101,LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS:116,LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS:115,LATENCY_ACTION_MUSIC_ALBUM_DETAIL:72,
LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL:71,LATENCY_ACTION_STORE:175,LATENCY_ACTION_CHIPS:68,LATENCY_ACTION_SEARCH_ZERO_STATE:67,LATENCY_ACTION_LIVE_PAGINATION:117,LATENCY_ACTION_LIVE:20,LATENCY_ACTION_PREBUFFER:40,LATENCY_ACTION_TENX:39,LATENCY_ACTION_KIDS_PROFILE_SETTINGS:94,LATENCY_ACTION_KIDS_WATCH_IT_AGAIN:92,LATENCY_ACTION_KIDS_SECRET_CODE:91,LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS:89,LATENCY_ACTION_KIDS_ONBOARDING:88,LATENCY_ACTION_KIDS_VOICE_SEARCH:82,LATENCY_ACTION_KIDS_CURATED_COLLECTION:62,
LATENCY_ACTION_KIDS_LIBRARY:53,LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS:38,LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT:219,LATENCY_ACTION_CREATOR_VIDEO_POLICY:217,LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION:74,LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING:141,LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS:142,LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC:51,LATENCY_ACTION_CREATOR_VIDEO_EDITOR:50,LATENCY_ACTION_CREATOR_VIDEO_EDIT:36,LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT:218,LATENCY_ACTION_CREATOR_VIDEO_COMMENTS:34,
LATENCY_ACTION_CREATOR_VIDEO_CLAIMS:216,LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS:33,LATENCY_ACTION_CREATOR_SONG_ANALYTICS:176,LATENCY_ACTION_CREATOR_PROMOTION_LIST:186,LATENCY_ACTION_CREATOR_PROMOTION_EDIT:185,LATENCY_ACTION_CREATOR_POST_LIST:112,LATENCY_ACTION_CREATOR_POST_EDIT:110,LATENCY_ACTION_CREATOR_POST_COMMENTS:111,LATENCY_ACTION_CREATOR_LIVE_STREAMING:108,LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT:174,LATENCY_ACTION_CREATOR_DIALOG_UPLOADS:86,LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES:87,
LATENCY_ACTION_CREATOR_CMS_VIDEOS:202,LATENCY_ACTION_CREATOR_CMS_REPORTS:201,LATENCY_ACTION_CREATOR_CMS_RELEASES:226,LATENCY_ACTION_CREATOR_CMS_POLICIES:225,LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC:224,LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING:200,LATENCY_ACTION_CREATOR_CMS_LICENSES:223,LATENCY_ACTION_CREATOR_CMS_ISSUES:191,LATENCY_ACTION_CREATOR_CMS_DASHBOARD:199,LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY:198,LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS:197,LATENCY_ACTION_CREATOR_CMS_CHANNELS:196,LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS:222,
LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS:214,LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES:209,LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY:208,LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP:207,LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA:205,LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES:212,LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES:206,LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS:221,LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS:210,LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION:213,LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS:211,
LATENCY_ACTION_CREATOR_CMS_ASSETS:195,LATENCY_ACTION_CREATOR_CMS_ART_TRACKS:220,LATENCY_ACTION_CREATOR_CMS_ANALYTICS:194,LATENCY_ACTION_CREATOR_CMS_ALLOWLIST:227,LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS:32,LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS:48,LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS:139,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT:177,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC:99,LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION:43,LATENCY_ACTION_CREATOR_CHANNEL_EDITING:113,LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD:49,
LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT:44,LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS:66,LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS:31,LATENCY_ACTION_CREATOR_ARTIST_PROFILE:85,LATENCY_ACTION_CREATOR_ARTIST_CONCERTS:84,LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS:83,LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE:140,LATENCY_ACTION_EXPERIMENTAL_WATCH_UI:181,LATENCY_ACTION_FINE_SCRUBBING_THUMBNAILS:228,LATENCY_ACTION_STORYBOARD_THUMBNAILS:118,LATENCY_ACTION_SEARCH_THUMBNAILS:59,LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD:54,
LATENCY_ACTION_VOICE_ASSISTANT:47,LATENCY_ACTION_SEARCH_UI:35,LATENCY_ACTION_SUGGEST:30,LATENCY_ACTION_AUTO_SEARCH:126,LATENCY_ACTION_DOWNLOADS:98,LATENCY_ACTION_EXPLORE:75,LATENCY_ACTION_VIDEO_LIST:63,LATENCY_ACTION_HOME_RESUME:60,LATENCY_ACTION_SUBSCRIPTIONS_LIST:57,LATENCY_ACTION_THUMBNAIL_LOAD:42,LATENCY_ACTION_FIRST_THUMBNAIL_LOAD:29,LATENCY_ACTION_SUBSCRIPTIONS_FEED:109,LATENCY_ACTION_SUBSCRIPTIONS:28,LATENCY_ACTION_TRENDING:27,LATENCY_ACTION_LIBRARY:21,LATENCY_ACTION_VIDEO_THUMBNAIL:8,LATENCY_ACTION_SHOW_MORE:7,
LATENCY_ACTION_VIDEO_PREVIEW:6,LATENCY_ACTION_AD_TO_AD:22,LATENCY_ACTION_VIDEO_TO_AD:17,LATENCY_ACTION_AD_TO_VIDEO:16,LATENCY_ACTION_DIRECT_PLAYBACK:132,LATENCY_ACTION_PREBUFFER_VIDEO:144,LATENCY_ACTION_PREFETCH_VIDEO:143,LATENCY_ACTION_STARTUP:106,LATENCY_ACTION_INLINE_TO_WATCH:232,LATENCY_ACTION_MUSIC_IMMERSIVE_WATCH:230,LATENCY_ACTION_ONBOARDING:135,LATENCY_ACTION_LOGIN:97,LATENCY_ACTION_REEL_WATCH:41,LATENCY_ACTION_WATCH:3,LATENCY_ACTION_RESULTS:2,LATENCY_ACTION_CHANNELS:4,LATENCY_ACTION_HOME:1,
LATENCY_ACTION_BROWSE:11,LATENCY_ACTION_USER_ACTION:189,LATENCY_ACTION_INFRASTRUCTURE:188,LATENCY_ACTION_PAGE_NAVIGATION:187,LATENCY_ACTION_UNKNOWN:0};W[W.LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING";W[W.LATENCY_ACTION_KIDS_PROFILE_SWITCHER]="LATENCY_ACTION_KIDS_PROFILE_SWITCHER";W[W.LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER]="LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER";W[W.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC";
W[W.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR";W[W.LATENCY_ACTION_SPINNER_DISPLAYED]="LATENCY_ACTION_SPINNER_DISPLAYED";W[W.LATENCY_ACTION_PLAYABILITY_CHECK]="LATENCY_ACTION_PLAYABILITY_CHECK";W[W.LATENCY_ACTION_PROCESS]="LATENCY_ACTION_PROCESS";W[W.LATENCY_ACTION_APP_STARTUP]="LATENCY_ACTION_APP_STARTUP";W[W.LATENCY_ACTION_GEL_COMPRESSION]="LATENCY_ACTION_GEL_COMPRESSION";W[W.LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE]="LATENCY_ACTION_PREMIUM_PAGE_GET_BROWSE";
W[W.LATENCY_ACTION_COMMERCE_ACTION_COMMAND_RPC]="LATENCY_ACTION_COMMERCE_ACTION_COMMAND_RPC";W[W.LATENCY_ACTION_COMMERCE_TRANSACTION]="LATENCY_ACTION_COMMERCE_TRANSACTION";W[W.LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC]="LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC";W[W.LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC]="LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC";W[W.LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC]="LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC";
W[W.LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC]="LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC";W[W.LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC]="LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC";W[W.LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC]="LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC";W[W.LATENCY_ACTION_GET_OFFERS_RPC]="LATENCY_ACTION_GET_OFFERS_RPC";W[W.LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC";W[W.LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC";
W[W.LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC]="LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC";W[W.LATENCY_ACTION_GET_OFFER_DETAILS_RPC]="LATENCY_ACTION_GET_OFFER_DETAILS_RPC";W[W.LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC]="LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC";W[W.LATENCY_ACTION_GET_TIP_MODULE_RPC]="LATENCY_ACTION_GET_TIP_MODULE_RPC";W[W.LATENCY_ACTION_HANDLE_TRANSACTION_RPC]="LATENCY_ACTION_HANDLE_TRANSACTION_RPC";
W[W.LATENCY_ACTION_COMPLETE_TRANSACTION_RPC]="LATENCY_ACTION_COMPLETE_TRANSACTION_RPC";W[W.LATENCY_ACTION_GET_CART_RPC]="LATENCY_ACTION_GET_CART_RPC";W[W.LATENCY_ACTION_THUMBNAIL_FETCH]="LATENCY_ACTION_THUMBNAIL_FETCH";W[W.LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK]="LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK";W[W.LATENCY_ACTION_SHARE_VIDEO]="LATENCY_ACTION_SHARE_VIDEO";W[W.LATENCY_ACTION_AD_TO_VIDEO_INT]="LATENCY_ACTION_AD_TO_VIDEO_INT";W[W.LATENCY_ACTION_ABANDONED_BROWSE]="LATENCY_ACTION_ABANDONED_BROWSE";
W[W.LATENCY_ACTION_PLAYER_ROTATION]="LATENCY_ACTION_PLAYER_ROTATION";W[W.LATENCY_ACTION_GENERIC_WEB_VIEW]="LATENCY_ACTION_GENERIC_WEB_VIEW";W[W.LATENCY_ACTION_SHOPPING_IN_APP]="LATENCY_ACTION_SHOPPING_IN_APP";W[W.LATENCY_ACTION_PLAYER_ATTESTATION]="LATENCY_ACTION_PLAYER_ATTESTATION";W[W.LATENCY_ACTION_PLAYER_SEEK]="LATENCY_ACTION_PLAYER_SEEK";W[W.LATENCY_ACTION_SUPER_STICKER_BUY_FLOW]="LATENCY_ACTION_SUPER_STICKER_BUY_FLOW";W[W.LATENCY_ACTION_DOWNLOADS_DATA_ACCESS]="LATENCY_ACTION_DOWNLOADS_DATA_ACCESS";
W[W.LATENCY_ACTION_BLOCKS_PERFORMANCE]="LATENCY_ACTION_BLOCKS_PERFORMANCE";W[W.LATENCY_ACTION_ASSISTANT_QUERY]="LATENCY_ACTION_ASSISTANT_QUERY";W[W.LATENCY_ACTION_ASSISTANT_SETTINGS]="LATENCY_ACTION_ASSISTANT_SETTINGS";W[W.LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF";W[W.LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF";W[W.LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE]="LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE";
W[W.LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION]="LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION";W[W.LATENCY_ACTION_NETWORKLESS_PERFORMANCE]="LATENCY_ACTION_NETWORKLESS_PERFORMANCE";W[W.LATENCY_ACTION_DOWNLOADS_EXPANSION]="LATENCY_ACTION_DOWNLOADS_EXPANSION";W[W.LATENCY_ACTION_ENTITY_TRANSFORM]="LATENCY_ACTION_ENTITY_TRANSFORM";W[W.LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER]="LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER";W[W.LATENCY_ACTION_EMBEDS_SET_VIDEO]="LATENCY_ACTION_EMBEDS_SET_VIDEO";
W[W.LATENCY_ACTION_SETTINGS]="LATENCY_ACTION_SETTINGS";W[W.LATENCY_ACTION_ABANDONED_STARTUP]="LATENCY_ACTION_ABANDONED_STARTUP";W[W.LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY]="LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY";W[W.LATENCY_ACTION_MEDIA_BROWSER_SEARCH]="LATENCY_ACTION_MEDIA_BROWSER_SEARCH";W[W.LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE]="LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE";W[W.LATENCY_ACTION_WHO_IS_WATCHING]="LATENCY_ACTION_WHO_IS_WATCHING";W[W.LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH]="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH";
W[W.LATENCY_ACTION_LITE_SWITCH_ACCOUNT]="LATENCY_ACTION_LITE_SWITCH_ACCOUNT";W[W.LATENCY_ACTION_ELEMENTS_PERFORMANCE]="LATENCY_ACTION_ELEMENTS_PERFORMANCE";W[W.LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION]="LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION";W[W.LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION]="LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION";W[W.LATENCY_ACTION_OFFLINE_STORE_START]="LATENCY_ACTION_OFFLINE_STORE_START";W[W.LATENCY_ACTION_REEL_EDITOR]="LATENCY_ACTION_REEL_EDITOR";
W[W.LATENCY_ACTION_CHANNEL_SUBSCRIBE]="LATENCY_ACTION_CHANNEL_SUBSCRIBE";W[W.LATENCY_ACTION_CHANNEL_PREVIEW]="LATENCY_ACTION_CHANNEL_PREVIEW";W[W.LATENCY_ACTION_PREFETCH]="LATENCY_ACTION_PREFETCH";W[W.LATENCY_ACTION_ABANDONED_WATCH]="LATENCY_ACTION_ABANDONED_WATCH";W[W.LATENCY_ACTION_LOAD_COMMENT_REPLIES]="LATENCY_ACTION_LOAD_COMMENT_REPLIES";W[W.LATENCY_ACTION_LOAD_COMMENTS]="LATENCY_ACTION_LOAD_COMMENTS";W[W.LATENCY_ACTION_EDIT_COMMENT]="LATENCY_ACTION_EDIT_COMMENT";
W[W.LATENCY_ACTION_NEW_COMMENT]="LATENCY_ACTION_NEW_COMMENT";W[W.LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING]="LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING";W[W.LATENCY_ACTION_EMBED]="LATENCY_ACTION_EMBED";W[W.LATENCY_ACTION_MDX_LAUNCH]="LATENCY_ACTION_MDX_LAUNCH";W[W.LATENCY_ACTION_RESOLVE_URL]="LATENCY_ACTION_RESOLVE_URL";W[W.LATENCY_ACTION_CAST_SPLASH]="LATENCY_ACTION_CAST_SPLASH";W[W.LATENCY_ACTION_MDX_CONNECT_TO_SESSION]="LATENCY_ACTION_MDX_CONNECT_TO_SESSION";
W[W.LATENCY_ACTION_MDX_STREAM_TRANSFER]="LATENCY_ACTION_MDX_STREAM_TRANSFER";W[W.LATENCY_ACTION_MDX_CAST]="LATENCY_ACTION_MDX_CAST";W[W.LATENCY_ACTION_MDX_COMMAND]="LATENCY_ACTION_MDX_COMMAND";W[W.LATENCY_ACTION_MOBILE_LIVE_NAV_MDE]="LATENCY_ACTION_MOBILE_LIVE_NAV_MDE";W[W.LATENCY_ACTION_REEL_SELECT_SEGMENT]="LATENCY_ACTION_REEL_SELECT_SEGMENT";W[W.LATENCY_ACTION_ACCELERATED_EFFECTS]="LATENCY_ACTION_ACCELERATED_EFFECTS";W[W.LATENCY_ACTION_SHORTS_TRIM_TO_EDITOR_TRANSCODING]="LATENCY_ACTION_SHORTS_TRIM_TO_EDITOR_TRANSCODING";
W[W.LATENCY_ACTION_EDIT_AUDIO_GEN]="LATENCY_ACTION_EDIT_AUDIO_GEN";W[W.LATENCY_ACTION_UPLOAD_AUDIO_MIXER]="LATENCY_ACTION_UPLOAD_AUDIO_MIXER";W[W.LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING]="LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING";W[W.LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING]="LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING";W[W.LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK]="LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK";W[W.LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD]="LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD";
W[W.LATENCY_ACTION_SHORTS_VIDEO_INGESTION]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION";W[W.LATENCY_ACTION_SHORTS_GALLERY]="LATENCY_ACTION_SHORTS_GALLERY";W[W.LATENCY_ACTION_SHORTS_TRIM]="LATENCY_ACTION_SHORTS_TRIM";W[W.LATENCY_ACTION_SHORTS_EDIT]="LATENCY_ACTION_SHORTS_EDIT";W[W.LATENCY_ACTION_SHORTS_CAMERA]="LATENCY_ACTION_SHORTS_CAMERA";W[W.LATENCY_ACTION_PRODUCER_IMPORT_LOCAL_MEDIA]="LATENCY_ACTION_PRODUCER_IMPORT_LOCAL_MEDIA";W[W.LATENCY_ACTION_PRODUCER_EXPORT_PROJECT]="LATENCY_ACTION_PRODUCER_EXPORT_PROJECT";
W[W.LATENCY_ACTION_PRODUCER_EDITOR]="LATENCY_ACTION_PRODUCER_EDITOR";W[W.LATENCY_ACTION_PARENT_TOOLS_DASHBOARD]="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD";W[W.LATENCY_ACTION_PARENT_TOOLS_COLLECTION]="LATENCY_ACTION_PARENT_TOOLS_COLLECTION";W[W.LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS";W[W.LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS";W[W.LATENCY_ACTION_MUSIC_ALBUM_DETAIL]="LATENCY_ACTION_MUSIC_ALBUM_DETAIL";
W[W.LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL]="LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL";W[W.LATENCY_ACTION_STORE]="LATENCY_ACTION_STORE";W[W.LATENCY_ACTION_CHIPS]="LATENCY_ACTION_CHIPS";W[W.LATENCY_ACTION_SEARCH_ZERO_STATE]="LATENCY_ACTION_SEARCH_ZERO_STATE";W[W.LATENCY_ACTION_LIVE_PAGINATION]="LATENCY_ACTION_LIVE_PAGINATION";W[W.LATENCY_ACTION_LIVE]="LATENCY_ACTION_LIVE";W[W.LATENCY_ACTION_PREBUFFER]="LATENCY_ACTION_PREBUFFER";W[W.LATENCY_ACTION_TENX]="LATENCY_ACTION_TENX";
W[W.LATENCY_ACTION_KIDS_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PROFILE_SETTINGS";W[W.LATENCY_ACTION_KIDS_WATCH_IT_AGAIN]="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN";W[W.LATENCY_ACTION_KIDS_SECRET_CODE]="LATENCY_ACTION_KIDS_SECRET_CODE";W[W.LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS";W[W.LATENCY_ACTION_KIDS_ONBOARDING]="LATENCY_ACTION_KIDS_ONBOARDING";W[W.LATENCY_ACTION_KIDS_VOICE_SEARCH]="LATENCY_ACTION_KIDS_VOICE_SEARCH";
W[W.LATENCY_ACTION_KIDS_CURATED_COLLECTION]="LATENCY_ACTION_KIDS_CURATED_COLLECTION";W[W.LATENCY_ACTION_KIDS_LIBRARY]="LATENCY_ACTION_KIDS_LIBRARY";W[W.LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS";W[W.LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT]="LATENCY_ACTION_CREATOR_VIDEO_RIGHTS_MANAGEMENT";W[W.LATENCY_ACTION_CREATOR_VIDEO_POLICY]="LATENCY_ACTION_CREATOR_VIDEO_POLICY";W[W.LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION";
W[W.LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING";W[W.LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR";W[W.LATENCY_ACTION_CREATOR_VIDEO_EDIT]="LATENCY_ACTION_CREATOR_VIDEO_EDIT";W[W.LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT]="LATENCY_ACTION_CREATOR_VIDEO_COPYRIGHT";
W[W.LATENCY_ACTION_CREATOR_VIDEO_COMMENTS]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS";W[W.LATENCY_ACTION_CREATOR_VIDEO_CLAIMS]="LATENCY_ACTION_CREATOR_VIDEO_CLAIMS";W[W.LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_SONG_ANALYTICS]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_PROMOTION_LIST]="LATENCY_ACTION_CREATOR_PROMOTION_LIST";W[W.LATENCY_ACTION_CREATOR_PROMOTION_EDIT]="LATENCY_ACTION_CREATOR_PROMOTION_EDIT";
W[W.LATENCY_ACTION_CREATOR_POST_LIST]="LATENCY_ACTION_CREATOR_POST_LIST";W[W.LATENCY_ACTION_CREATOR_POST_EDIT]="LATENCY_ACTION_CREATOR_POST_EDIT";W[W.LATENCY_ACTION_CREATOR_POST_COMMENTS]="LATENCY_ACTION_CREATOR_POST_COMMENTS";W[W.LATENCY_ACTION_CREATOR_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_LIVE_STREAMING";W[W.LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT";W[W.LATENCY_ACTION_CREATOR_DIALOG_UPLOADS]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS";
W[W.LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES";W[W.LATENCY_ACTION_CREATOR_CMS_VIDEOS]="LATENCY_ACTION_CREATOR_CMS_VIDEOS";W[W.LATENCY_ACTION_CREATOR_CMS_REPORTS]="LATENCY_ACTION_CREATOR_CMS_REPORTS";W[W.LATENCY_ACTION_CREATOR_CMS_RELEASES]="LATENCY_ACTION_CREATOR_CMS_RELEASES";W[W.LATENCY_ACTION_CREATOR_CMS_POLICIES]="LATENCY_ACTION_CREATOR_CMS_POLICIES";W[W.LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC]="LATENCY_ACTION_CREATOR_CMS_PITCH_MUSIC";
W[W.LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING]="LATENCY_ACTION_CREATOR_CMS_MANUAL_CLAIMING";W[W.LATENCY_ACTION_CREATOR_CMS_LICENSES]="LATENCY_ACTION_CREATOR_CMS_LICENSES";W[W.LATENCY_ACTION_CREATOR_CMS_ISSUES]="LATENCY_ACTION_CREATOR_CMS_ISSUES";W[W.LATENCY_ACTION_CREATOR_CMS_DASHBOARD]="LATENCY_ACTION_CREATOR_CMS_DASHBOARD";W[W.LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY]="LATENCY_ACTION_CREATOR_CMS_CONTENT_DELIVERY";W[W.LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS]="LATENCY_ACTION_CREATOR_CMS_CLAIMED_VIDEOS";
W[W.LATENCY_ACTION_CREATOR_CMS_CHANNELS]="LATENCY_ACTION_CREATOR_CMS_CHANNELS";W[W.LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS]="LATENCY_ACTION_CREATOR_CMS_CAMPAIGNS";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS]="LATENCY_ACTION_CREATOR_CMS_ASSET_SOUND_RECORDINGS";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES]="LATENCY_ACTION_CREATOR_CMS_ASSET_REFERENCES";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY]="LATENCY_ACTION_CREATOR_CMS_ASSET_POLICY";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP]="LATENCY_ACTION_CREATOR_CMS_ASSET_OWNERSHIP";
W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA]="LATENCY_ACTION_CREATOR_CMS_ASSET_METADATA";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES]="LATENCY_ACTION_CREATOR_CMS_ASSET_LICENSES";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES]="LATENCY_ACTION_CREATOR_CMS_ASSET_ISSUES";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS]="LATENCY_ACTION_CREATOR_CMS_ASSET_GROUPS";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS]="LATENCY_ACTION_CREATOR_CMS_ASSET_EMBEDS";W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION]="LATENCY_ACTION_CREATOR_CMS_ASSET_COMPOSITION";
W[W.LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS]="LATENCY_ACTION_CREATOR_CMS_ASSET_CLAIMED_VIDEOS";W[W.LATENCY_ACTION_CREATOR_CMS_ASSETS]="LATENCY_ACTION_CREATOR_CMS_ASSETS";W[W.LATENCY_ACTION_CREATOR_CMS_ART_TRACKS]="LATENCY_ACTION_CREATOR_CMS_ART_TRACKS";W[W.LATENCY_ACTION_CREATOR_CMS_ANALYTICS]="LATENCY_ACTION_CREATOR_CMS_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_CMS_ALLOWLIST]="LATENCY_ACTION_CREATOR_CMS_ALLOWLIST";W[W.LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS";
W[W.LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC";W[W.LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION";
W[W.LATENCY_ACTION_CREATOR_CHANNEL_EDITING]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING";W[W.LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD]="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD";W[W.LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT";W[W.LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS";W[W.LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_ARTIST_PROFILE]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE";
W[W.LATENCY_ACTION_CREATOR_ARTIST_CONCERTS]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS";W[W.LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS";W[W.LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE";W[W.LATENCY_ACTION_EXPERIMENTAL_WATCH_UI]="LATENCY_ACTION_EXPERIMENTAL_WATCH_UI";W[W.LATENCY_ACTION_FINE_SCRUBBING_THUMBNAILS]="LATENCY_ACTION_FINE_SCRUBBING_THUMBNAILS";W[W.LATENCY_ACTION_STORYBOARD_THUMBNAILS]="LATENCY_ACTION_STORYBOARD_THUMBNAILS";
W[W.LATENCY_ACTION_SEARCH_THUMBNAILS]="LATENCY_ACTION_SEARCH_THUMBNAILS";W[W.LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD]="LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD";W[W.LATENCY_ACTION_VOICE_ASSISTANT]="LATENCY_ACTION_VOICE_ASSISTANT";W[W.LATENCY_ACTION_SEARCH_UI]="LATENCY_ACTION_SEARCH_UI";W[W.LATENCY_ACTION_SUGGEST]="LATENCY_ACTION_SUGGEST";W[W.LATENCY_ACTION_AUTO_SEARCH]="LATENCY_ACTION_AUTO_SEARCH";W[W.LATENCY_ACTION_DOWNLOADS]="LATENCY_ACTION_DOWNLOADS";W[W.LATENCY_ACTION_EXPLORE]="LATENCY_ACTION_EXPLORE";
W[W.LATENCY_ACTION_VIDEO_LIST]="LATENCY_ACTION_VIDEO_LIST";W[W.LATENCY_ACTION_HOME_RESUME]="LATENCY_ACTION_HOME_RESUME";W[W.LATENCY_ACTION_SUBSCRIPTIONS_LIST]="LATENCY_ACTION_SUBSCRIPTIONS_LIST";W[W.LATENCY_ACTION_THUMBNAIL_LOAD]="LATENCY_ACTION_THUMBNAIL_LOAD";W[W.LATENCY_ACTION_FIRST_THUMBNAIL_LOAD]="LATENCY_ACTION_FIRST_THUMBNAIL_LOAD";W[W.LATENCY_ACTION_SUBSCRIPTIONS_FEED]="LATENCY_ACTION_SUBSCRIPTIONS_FEED";W[W.LATENCY_ACTION_SUBSCRIPTIONS]="LATENCY_ACTION_SUBSCRIPTIONS";
W[W.LATENCY_ACTION_TRENDING]="LATENCY_ACTION_TRENDING";W[W.LATENCY_ACTION_LIBRARY]="LATENCY_ACTION_LIBRARY";W[W.LATENCY_ACTION_VIDEO_THUMBNAIL]="LATENCY_ACTION_VIDEO_THUMBNAIL";W[W.LATENCY_ACTION_SHOW_MORE]="LATENCY_ACTION_SHOW_MORE";W[W.LATENCY_ACTION_VIDEO_PREVIEW]="LATENCY_ACTION_VIDEO_PREVIEW";W[W.LATENCY_ACTION_AD_TO_AD]="LATENCY_ACTION_AD_TO_AD";W[W.LATENCY_ACTION_VIDEO_TO_AD]="LATENCY_ACTION_VIDEO_TO_AD";W[W.LATENCY_ACTION_AD_TO_VIDEO]="LATENCY_ACTION_AD_TO_VIDEO";
W[W.LATENCY_ACTION_DIRECT_PLAYBACK]="LATENCY_ACTION_DIRECT_PLAYBACK";W[W.LATENCY_ACTION_PREBUFFER_VIDEO]="LATENCY_ACTION_PREBUFFER_VIDEO";W[W.LATENCY_ACTION_PREFETCH_VIDEO]="LATENCY_ACTION_PREFETCH_VIDEO";W[W.LATENCY_ACTION_STARTUP]="LATENCY_ACTION_STARTUP";W[W.LATENCY_ACTION_INLINE_TO_WATCH]="LATENCY_ACTION_INLINE_TO_WATCH";W[W.LATENCY_ACTION_MUSIC_IMMERSIVE_WATCH]="LATENCY_ACTION_MUSIC_IMMERSIVE_WATCH";W[W.LATENCY_ACTION_ONBOARDING]="LATENCY_ACTION_ONBOARDING";W[W.LATENCY_ACTION_LOGIN]="LATENCY_ACTION_LOGIN";
W[W.LATENCY_ACTION_REEL_WATCH]="LATENCY_ACTION_REEL_WATCH";W[W.LATENCY_ACTION_WATCH]="LATENCY_ACTION_WATCH";W[W.LATENCY_ACTION_RESULTS]="LATENCY_ACTION_RESULTS";W[W.LATENCY_ACTION_CHANNELS]="LATENCY_ACTION_CHANNELS";W[W.LATENCY_ACTION_HOME]="LATENCY_ACTION_HOME";W[W.LATENCY_ACTION_BROWSE]="LATENCY_ACTION_BROWSE";W[W.LATENCY_ACTION_USER_ACTION]="LATENCY_ACTION_USER_ACTION";W[W.LATENCY_ACTION_INFRASTRUCTURE]="LATENCY_ACTION_INFRASTRUCTURE";W[W.LATENCY_ACTION_PAGE_NAVIGATION]="LATENCY_ACTION_PAGE_NAVIGATION";
W[W.LATENCY_ACTION_UNKNOWN]="LATENCY_ACTION_UNKNOWN";var Nv={LATENCY_NETWORK_MOBILE:2,LATENCY_NETWORK_WIFI:1,LATENCY_NETWORK_UNKNOWN:0};Nv[Nv.LATENCY_NETWORK_MOBILE]="LATENCY_NETWORK_MOBILE";Nv[Nv.LATENCY_NETWORK_WIFI]="LATENCY_NETWORK_WIFI";Nv[Nv.LATENCY_NETWORK_UNKNOWN]="LATENCY_NETWORK_UNKNOWN";
var Y={CONN_INVALID:31,CONN_CELLULAR_5G_NSA:12,CONN_CELLULAR_5G_SA:11,CONN_WIFI_METERED:10,CONN_CELLULAR_5G:9,CONN_DISCO:8,CONN_CELLULAR_UNKNOWN:7,CONN_CELLULAR_4G:6,CONN_CELLULAR_3G:5,CONN_CELLULAR_2G:4,CONN_WIFI:3,CONN_NONE:2,CONN_UNKNOWN:1,CONN_DEFAULT:0};Y[Y.CONN_INVALID]="CONN_INVALID";Y[Y.CONN_CELLULAR_5G_NSA]="CONN_CELLULAR_5G_NSA";Y[Y.CONN_CELLULAR_5G_SA]="CONN_CELLULAR_5G_SA";Y[Y.CONN_WIFI_METERED]="CONN_WIFI_METERED";Y[Y.CONN_CELLULAR_5G]="CONN_CELLULAR_5G";Y[Y.CONN_DISCO]="CONN_DISCO";
Y[Y.CONN_CELLULAR_UNKNOWN]="CONN_CELLULAR_UNKNOWN";Y[Y.CONN_CELLULAR_4G]="CONN_CELLULAR_4G";Y[Y.CONN_CELLULAR_3G]="CONN_CELLULAR_3G";Y[Y.CONN_CELLULAR_2G]="CONN_CELLULAR_2G";Y[Y.CONN_WIFI]="CONN_WIFI";Y[Y.CONN_NONE]="CONN_NONE";Y[Y.CONN_UNKNOWN]="CONN_UNKNOWN";Y[Y.CONN_DEFAULT]="CONN_DEFAULT";
var Z={DETAILED_NETWORK_TYPE_NR_NSA:126,DETAILED_NETWORK_TYPE_NR_SA:125,DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED:124,DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT:123,DETAILED_NETWORK_TYPE_DISCONNECTED:122,DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN:121,DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN:120,DETAILED_NETWORK_TYPE_WIMAX:119,DETAILED_NETWORK_TYPE_ETHERNET:118,DETAILED_NETWORK_TYPE_BLUETOOTH:117,DETAILED_NETWORK_TYPE_WIFI:116,DETAILED_NETWORK_TYPE_LTE:115,DETAILED_NETWORK_TYPE_HSPAP:114,DETAILED_NETWORK_TYPE_EHRPD:113,
DETAILED_NETWORK_TYPE_EVDO_B:112,DETAILED_NETWORK_TYPE_UMTS:111,DETAILED_NETWORK_TYPE_IDEN:110,DETAILED_NETWORK_TYPE_HSUPA:109,DETAILED_NETWORK_TYPE_HSPA:108,DETAILED_NETWORK_TYPE_HSDPA:107,DETAILED_NETWORK_TYPE_EVDO_A:106,DETAILED_NETWORK_TYPE_EVDO_0:105,DETAILED_NETWORK_TYPE_CDMA:104,DETAILED_NETWORK_TYPE_1_X_RTT:103,DETAILED_NETWORK_TYPE_GPRS:102,DETAILED_NETWORK_TYPE_EDGE:101,DETAILED_NETWORK_TYPE_UNKNOWN:0};Z[Z.DETAILED_NETWORK_TYPE_NR_NSA]="DETAILED_NETWORK_TYPE_NR_NSA";
Z[Z.DETAILED_NETWORK_TYPE_NR_SA]="DETAILED_NETWORK_TYPE_NR_SA";Z[Z.DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED]="DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED";Z[Z.DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT]="DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT";Z[Z.DETAILED_NETWORK_TYPE_DISCONNECTED]="DETAILED_NETWORK_TYPE_DISCONNECTED";Z[Z.DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN";Z[Z.DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN";
Z[Z.DETAILED_NETWORK_TYPE_WIMAX]="DETAILED_NETWORK_TYPE_WIMAX";Z[Z.DETAILED_NETWORK_TYPE_ETHERNET]="DETAILED_NETWORK_TYPE_ETHERNET";Z[Z.DETAILED_NETWORK_TYPE_BLUETOOTH]="DETAILED_NETWORK_TYPE_BLUETOOTH";Z[Z.DETAILED_NETWORK_TYPE_WIFI]="DETAILED_NETWORK_TYPE_WIFI";Z[Z.DETAILED_NETWORK_TYPE_LTE]="DETAILED_NETWORK_TYPE_LTE";Z[Z.DETAILED_NETWORK_TYPE_HSPAP]="DETAILED_NETWORK_TYPE_HSPAP";Z[Z.DETAILED_NETWORK_TYPE_EHRPD]="DETAILED_NETWORK_TYPE_EHRPD";Z[Z.DETAILED_NETWORK_TYPE_EVDO_B]="DETAILED_NETWORK_TYPE_EVDO_B";
Z[Z.DETAILED_NETWORK_TYPE_UMTS]="DETAILED_NETWORK_TYPE_UMTS";Z[Z.DETAILED_NETWORK_TYPE_IDEN]="DETAILED_NETWORK_TYPE_IDEN";Z[Z.DETAILED_NETWORK_TYPE_HSUPA]="DETAILED_NETWORK_TYPE_HSUPA";Z[Z.DETAILED_NETWORK_TYPE_HSPA]="DETAILED_NETWORK_TYPE_HSPA";Z[Z.DETAILED_NETWORK_TYPE_HSDPA]="DETAILED_NETWORK_TYPE_HSDPA";Z[Z.DETAILED_NETWORK_TYPE_EVDO_A]="DETAILED_NETWORK_TYPE_EVDO_A";Z[Z.DETAILED_NETWORK_TYPE_EVDO_0]="DETAILED_NETWORK_TYPE_EVDO_0";Z[Z.DETAILED_NETWORK_TYPE_CDMA]="DETAILED_NETWORK_TYPE_CDMA";
Z[Z.DETAILED_NETWORK_TYPE_1_X_RTT]="DETAILED_NETWORK_TYPE_1_X_RTT";Z[Z.DETAILED_NETWORK_TYPE_GPRS]="DETAILED_NETWORK_TYPE_GPRS";Z[Z.DETAILED_NETWORK_TYPE_EDGE]="DETAILED_NETWORK_TYPE_EDGE";Z[Z.DETAILED_NETWORK_TYPE_UNKNOWN]="DETAILED_NETWORK_TYPE_UNKNOWN";var Ov={LATENCY_PLAYER_RTSP:7,LATENCY_PLAYER_HTML5_INLINE:6,LATENCY_PLAYER_HTML5_FULLSCREEN:5,LATENCY_PLAYER_HTML5:4,LATENCY_PLAYER_FRAMEWORK:3,LATENCY_PLAYER_FLASH:2,LATENCY_PLAYER_EXO:1,LATENCY_PLAYER_UNKNOWN:0};Ov[Ov.LATENCY_PLAYER_RTSP]="LATENCY_PLAYER_RTSP";
Ov[Ov.LATENCY_PLAYER_HTML5_INLINE]="LATENCY_PLAYER_HTML5_INLINE";Ov[Ov.LATENCY_PLAYER_HTML5_FULLSCREEN]="LATENCY_PLAYER_HTML5_FULLSCREEN";Ov[Ov.LATENCY_PLAYER_HTML5]="LATENCY_PLAYER_HTML5";Ov[Ov.LATENCY_PLAYER_FRAMEWORK]="LATENCY_PLAYER_FRAMEWORK";Ov[Ov.LATENCY_PLAYER_FLASH]="LATENCY_PLAYER_FLASH";Ov[Ov.LATENCY_PLAYER_EXO]="LATENCY_PLAYER_EXO";Ov[Ov.LATENCY_PLAYER_UNKNOWN]="LATENCY_PLAYER_UNKNOWN";
var Pv={LATENCY_AD_BREAK_TYPE_POSTROLL:3,LATENCY_AD_BREAK_TYPE_MIDROLL:2,LATENCY_AD_BREAK_TYPE_PREROLL:1,LATENCY_AD_BREAK_TYPE_UNKNOWN:0};Pv[Pv.LATENCY_AD_BREAK_TYPE_POSTROLL]="LATENCY_AD_BREAK_TYPE_POSTROLL";Pv[Pv.LATENCY_AD_BREAK_TYPE_MIDROLL]="LATENCY_AD_BREAK_TYPE_MIDROLL";Pv[Pv.LATENCY_AD_BREAK_TYPE_PREROLL]="LATENCY_AD_BREAK_TYPE_PREROLL";Pv[Pv.LATENCY_AD_BREAK_TYPE_UNKNOWN]="LATENCY_AD_BREAK_TYPE_UNKNOWN";var Qv={LATENCY_ACTION_ERROR_STARTUP_TIMEOUT:1,LATENCY_ACTION_ERROR_UNSPECIFIED:0};
Qv[Qv.LATENCY_ACTION_ERROR_STARTUP_TIMEOUT]="LATENCY_ACTION_ERROR_STARTUP_TIMEOUT";Qv[Qv.LATENCY_ACTION_ERROR_UNSPECIFIED]="LATENCY_ACTION_ERROR_UNSPECIFIED";var Rv={LIVE_STREAM_MODE_WINDOW:5,LIVE_STREAM_MODE_POST:4,LIVE_STREAM_MODE_LP:3,LIVE_STREAM_MODE_LIVE:2,LIVE_STREAM_MODE_DVR:1,LIVE_STREAM_MODE_UNKNOWN:0};Rv[Rv.LIVE_STREAM_MODE_WINDOW]="LIVE_STREAM_MODE_WINDOW";Rv[Rv.LIVE_STREAM_MODE_POST]="LIVE_STREAM_MODE_POST";Rv[Rv.LIVE_STREAM_MODE_LP]="LIVE_STREAM_MODE_LP";
Rv[Rv.LIVE_STREAM_MODE_LIVE]="LIVE_STREAM_MODE_LIVE";Rv[Rv.LIVE_STREAM_MODE_DVR]="LIVE_STREAM_MODE_DVR";Rv[Rv.LIVE_STREAM_MODE_UNKNOWN]="LIVE_STREAM_MODE_UNKNOWN";var Sv={VIDEO_STREAM_TYPE_VOD:3,VIDEO_STREAM_TYPE_DVR:2,VIDEO_STREAM_TYPE_LIVE:1,VIDEO_STREAM_TYPE_UNSPECIFIED:0};Sv[Sv.VIDEO_STREAM_TYPE_VOD]="VIDEO_STREAM_TYPE_VOD";Sv[Sv.VIDEO_STREAM_TYPE_DVR]="VIDEO_STREAM_TYPE_DVR";Sv[Sv.VIDEO_STREAM_TYPE_LIVE]="VIDEO_STREAM_TYPE_LIVE";Sv[Sv.VIDEO_STREAM_TYPE_UNSPECIFIED]="VIDEO_STREAM_TYPE_UNSPECIFIED";
var Tv={YT_IDB_TRANSACTION_TYPE_READ:2,YT_IDB_TRANSACTION_TYPE_WRITE:1,YT_IDB_TRANSACTION_TYPE_UNKNOWN:0};Tv[Tv.YT_IDB_TRANSACTION_TYPE_READ]="YT_IDB_TRANSACTION_TYPE_READ";Tv[Tv.YT_IDB_TRANSACTION_TYPE_WRITE]="YT_IDB_TRANSACTION_TYPE_WRITE";Tv[Tv.YT_IDB_TRANSACTION_TYPE_UNKNOWN]="YT_IDB_TRANSACTION_TYPE_UNKNOWN";var Uv={PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN:2,PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT:1,PLAYER_ROTATION_TYPE_UNKNOWN:0};Uv[Uv.PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN]="PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN";
Uv[Uv.PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT]="PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT";Uv[Uv.PLAYER_ROTATION_TYPE_UNKNOWN]="PLAYER_ROTATION_TYPE_UNKNOWN";var Vv="actionVisualElement spinnerInfo resourceInfo playerInfo commentInfo mdxInfo watchInfo thumbnailLoadInfo creatorInfo unpluggedInfo reelInfo subscriptionsFeedInfo requestIds mediaBrowserActionInfo musicLoadActionInfo shoppingInfo webViewInfo prefetchInfo accelerationSession commerceInfo inlineToWatchInfo webInfo tvInfo kabukiInfo mwebInfo musicInfo transcodingContext".split(" ");function Wv(a,b){iq.call(this,1,arguments);this.timer=b}
v(Wv,iq);var Xv=new jq("aft-recorded",Wv);var Yv=y.ytLoggingLatencyUsageStats_||{};z("ytLoggingLatencyUsageStats_",Yv);function Zv(){this.h=0}
function $v(){Zv.h||(Zv.h=new Zv);return Zv.h}
Zv.prototype.tick=function(a,b,c,d){aw(this,"tick_"+a+"_"+b)||(c={timestamp:c,cttAuthInfo:d},R("web_csi_via_jspb")?(d=new Zl,G(d,1,a),G(d,2,b),a=new bm,Wd(a,Zl,5,cm,d),Rt(a,c)):oo("latencyActionTicked",{tickName:a,clientActionNonce:b},c))};
Zv.prototype.info=function(a,b,c){var d=Object.keys(a).join("");aw(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,oo("latencyActionInfo",a,{cttAuthInfo:c}))};
Zv.prototype.jspbInfo=function(a,b,c){for(var d="",e=0;e<a.toJSON().length;e++)void 0!==a.toJSON()[e]&&(d=0===e?d.concat(""+e):d.concat("_"+e));aw(this,"info_"+d+"_"+b)||(G(a,2,b),b={cttAuthInfo:c},c=new bm,Wd(c,Wl,7,cm,a),Rt(c,b))};
Zv.prototype.span=function(a,b,c){var d=Object.keys(a).join("");aw(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,oo("latencyActionSpan",a,{cttAuthInfo:c}))};
function aw(a,b){Yv[b]=Yv[b]||{count:0};var c=Yv[b];c.count++;c.time=T();a.h||(a.h=$n(function(){var d=T(),e;for(e in Yv)Yv[e]&&6E4<d-Yv[e].time&&delete Yv[e];a&&(a.h=0)},5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new S("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||eu(c)),!0):!1}
;var bw=window;function cw(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
function dw(){var a;if(R("csi_use_performance_navigation_timing")||R("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=null==ew?void 0:null==(a=ew.getEntriesByType)?void 0:null==(b=a.call(ew,"navigation"))?void 0:null==(c=b[0])?void 0:null==(d=c.toJSON)?void 0:d.call(c);e?(e.requestStart=fw(e.requestStart),e.responseEnd=fw(e.responseEnd),e.redirectStart=fw(e.redirectStart),e.redirectEnd=fw(e.redirectEnd),e.domainLookupEnd=fw(e.domainLookupEnd),e.connectStart=fw(e.connectStart),e.connectEnd=
fw(e.connectEnd),e.responseStart=fw(e.responseStart),e.secureConnectionStart=fw(e.secureConnectionStart),e.domainLookupStart=fw(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=ew.timing}else a=ew.timing;return a}
function fw(a){return Math.round(gw()+a)}
function gw(){return(R("csi_use_time_origin")||R("csi_use_time_origin_tvhtml5"))&&ew.timeOrigin?Math.floor(ew.timeOrigin):ew.timing.navigationStart}
var ew=bw.performance||bw.mozPerformance||bw.msPerformance||bw.webkitPerformance||new cw;var hw=!1,iw={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"};
Xa(ew.clearResourceTimings||ew.webkitClearResourceTimings||ew.mozClearResourceTimings||ew.msClearResourceTimings||ew.oClearResourceTimings||db,ew);function jw(a,b,c,d){if(null!==b){if("yt_lt"===a){var e="string"===typeof b?b:""+b;yv(c).loadType=e}(a=Mv(a,b,c))&&kw(a,c,d)}}
function kw(a,b,c){if(!R("web_csi_via_jspb")||(void 0===c?0:c))c=Ev(b||""),rv(c.info,a),a.loadType&&(c=a.loadType,yv(b).loadType=c),rv(Bv(b),a),c=Cv(b),b=wv(b).cttAuthInfo,$v().info(a,c,b);else{c=new Wl;var d=Object.keys(a);a=Object.values(a);for(var e=0;e<d.length;e++){var f=d[e];try{switch(f){case "actionType":G(c,1,W[a[e]]);break;case "clientActionNonce":G(c,2,a[e]);break;case "clientScreenNonce":G(c,4,a[e]);break;case "loadType":G(c,3,a[e]);break;case "isPrewarmedLaunch":G(c,92,a[e]);break;case "isFirstInstall":G(c,
55,a[e]);break;case "networkType":G(c,5,Nv[a[e]]);break;case "connectionType":G(c,26,Y[a[e]]);break;case "detailedConnectionType":G(c,27,Z[a[e]]);break;case "isVisible":G(c,6,a[e]);break;case "playerType":G(c,7,Ov[a[e]]);break;case "clientPlaybackNonce":G(c,8,a[e]);break;case "adClientPlaybackNonce":G(c,28,a[e]);break;case "previousCpn":G(c,77,a[e]);break;case "targetCpn":G(c,76,a[e]);break;case "isMonetized":G(c,9,a[e]);break;case "isPrerollAllowed":G(c,16,a[e]);break;case "isPrerollShown":G(c,17,
a[e]);break;case "adType":G(c,12,a[e]);break;case "adTypesAllowed":G(c,36,a[e]);break;case "adNetworks":G(c,37,a[e]);break;case "previousAction":G(c,13,W[a[e]]);break;case "isRedSubscriber":G(c,14,a[e]);break;case "serverTimeMs":G(c,15,a[e]);break;case "videoId":c.setVideoId(a[e]);break;case "adVideoId":G(c,20,a[e]);break;case "targetVideoId":G(c,78,a[e]);break;case "adBreakType":G(c,21,Pv[a[e]]);break;case "isNavigation":G(c,25,a[e]);break;case "viewportHeight":G(c,29,a[e]);break;case "viewportWidth":G(c,
30,a[e]);break;case "screenHeight":G(c,84,a[e]);break;case "screenWidth":G(c,85,a[e]);break;case "browseId":G(c,31,a[e]);break;case "isCacheHit":G(c,32,a[e]);break;case "httpProtocol":G(c,33,a[e]);break;case "transportProtocol":G(c,34,a[e]);break;case "searchQuery":G(c,41,a[e]);break;case "isContinuation":G(c,42,a[e]);break;case "availableProcessors":G(c,43,a[e]);break;case "sdk":G(c,44,a[e]);break;case "isLocalStream":G(c,45,a[e]);break;case "navigationRequestedSameUrl":G(c,64,a[e]);break;case "shellStartupDurationMs":G(c,
70,a[e]);break;case "appInstallDataAgeMs":G(c,73,a[e]);break;case "latencyActionError":G(c,71,Qv[a[e]]);break;case "actionStep":G(c,79,a[e]);break;case "jsHeapSizeLimit":G(c,80,a[e]);break;case "totalJsHeapSize":G(c,81,a[e]);break;case "usedJsHeapSize":G(c,82,a[e]);break;case "sourceVideoDurationMs":G(c,90,a[e]);break;case "videoOutputFrames":G(c,93,a[e]);break;case "isResume":G(c,104,a[e]);break;case "debugTicksExcluded":G(c,105,a[e]);break;case "adPrebufferedTimeSecs":G(c,39,a[e]);break;case "isLivestream":G(c,
47,a[e]);break;case "liveStreamMode":G(c,91,Rv[a[e]]);break;case "adCpn2":G(c,48,a[e]);break;case "adDaiDriftMillis":G(c,49,a[e]);break;case "videoStreamType":G(c,53,Sv[a[e]]);break;case "playbackRequiresTap":G(c,56,a[e]);break;case "performanceNavigationTiming":G(c,67,a[e]);break;case "transactionType":G(c,74,Tv[a[e]]);break;case "playerRotationType":G(c,101,Uv[a[e]]);break;case "allowedPreroll":G(c,10,a[e]);break;case "shownPreroll":G(c,11,a[e]);break;case "getHomeRequestId":G(c,57,a[e]);break;
case "getSearchRequestId":G(c,60,a[e]);break;case "getPlayerRequestId":G(c,61,a[e]);break;case "getWatchNextRequestId":G(c,62,a[e]);break;case "getBrowseRequestId":G(c,63,a[e]);break;case "getLibraryRequestId":G(c,66,a[e]);break;case "isTransformerEnabledForFeature":G(c,106,a[e]);break;default:Vv.includes(f)&&Bm(new S("Codegen laipb translator asked to translate message field",""+f))}}catch(g){Bm(Error("Codegen laipb translator failed to set "+f))}}lw(c,b)}}
function lw(a,b){var c=be(a,3);c&&(yv(b).loadType=c);Ev(b||"").jspbInfo.push(a);c=Cv(b);b=wv(b).cttAuthInfo;$v().jspbInfo(a,c,b)}
function mw(a,b,c){if(!b&&"_"!==a[0]){var d=a;ew.mark&&(0==d.lastIndexOf("mark_",0)||(d="mark_"+d),c&&(d+=" ("+c+")"),ew.mark(d))}d=Ev(c||"");d.tick[a]=b||T();if(d.callback&&d.callback[a]){d=r(d.callback[a]);for(var e=d.next();!e.done;e=d.next())e=e.value,e()}d=Av(c);d.gelTicks&&(d.gelTicks[a]=!0);e=zv(c);d=b||T();R("log_repeated_ytcsi_ticks")?a in e||(e[a]=d):e[a]=d;e=Cv(c);var f=wv(c).cttAuthInfo;"_start"===a?(a=$v(),aw(a,"baseline_"+e)||(b={timestamp:b,cttAuthInfo:f},R("web_csi_via_jspb")?(a=new Rl,
G(a,1,e),e=new bm,Wd(e,Rl,6,cm,a),Rt(e,b)):oo("latencyActionBaselined",{clientActionNonce:e},b))):$v().tick(a,e,b,f);nw(c);return d}
function ow(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=ns+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function pw(a){var b=dw(),c=gw(),d=P("CSI_START_TIMESTAMP_MILLIS",0);0<d&&!R("embeds_web_enable_csi_start_override_killswitch")&&(c=d);c&&(mw("srt",b.responseStart),1!==a.prerender&&mw("_start",c,void 0));a=qw();0<a&&mw("fpt",a);a=dw();a.isPerformanceNavigationTiming&&kw({performanceNavigationTiming:!0},void 0);mw("nreqs",a.requestStart,void 0);mw("nress",a.responseStart,void 0);mw("nrese",a.responseEnd,void 0);0<a.redirectEnd-a.redirectStart&&(mw("nrs",a.redirectStart,void 0),mw("nre",a.redirectEnd,
void 0));0<a.domainLookupEnd-a.domainLookupStart&&(mw("ndnss",a.domainLookupStart,void 0),mw("ndnse",a.domainLookupEnd,void 0));0<a.connectEnd-a.connectStart&&(mw("ntcps",a.connectStart,void 0),mw("ntcpe",a.connectEnd,void 0));a.secureConnectionStart>=gw()&&0<a.connectEnd-a.secureConnectionStart&&(mw("nstcps",a.secureConnectionStart,void 0),mw("ntcpe",a.connectEnd,void 0));ew&&"getEntriesByType"in ew&&rw()}
function sw(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);hc()&&a.setAttribute("nonce",hc());return c?(a=ew.getEntriesByName(c))&&a[0]&&(a=a[0],c=gw(),mw("rsf_"+b,c+Math.round(a.fetchStart)),mw("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function tw(){var a=[];if(document.querySelector&&ew&&ew.getEntriesByName)for(var b in iw)if(iw.hasOwnProperty(b)){var c=iw[b];sw(b,c)&&a.push(c)}return a}
function rw(){var a=window.location.protocol,b=ew.getEntriesByType("resource");b=hb(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=jb(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(mw("wffs",fw(b.startTime)),mw("wffe",fw(b.responseEnd)))}
function uw(a){var b=vw("aft",a);if(b)return b;b=P((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=b.length,d=0;d<c;d++){var e=vw(b[d],a);if(e)return e}return NaN}
function vw(a,b){if(a=zv(b)[a])return"number"===typeof a?a:a[a.length-1]}
function nw(a){var b=vw("_start",a),c=uw(a);b&&c&&!hw&&(oq(Xv,new Wv(Math.round(c-b),a)),hw=!0)}
function ww(a,b){for(var c=r(Object.keys(b)),d=c.next();!d.done;d=c.next())if(d=d.value,!Object.keys(a).includes(d)||"object"===typeof b[d]&&!ww(a[d],b[d]))return!1;return!0}
function qw(){if(ew.getEntriesByType){var a=ew.getEntriesByType("paint");if(a=kb(a,function(b){return"first-paint"===b.name}))return fw(a.startTime)}a=ew.timing;
return a.Je?Math.max(0,a.Je):0}
;function xw(a,b){Am(function(){Ev("").info.actionType=a;b&&wm("TIMING_AFT_KEYS",b);wm("TIMING_ACTION",a);if(R("web_csi_via_jspb")){var c=P("TIMING_INFO",{}),d=new Wl;c=r(Object.entries(c));for(var e=c.next();!e.done;e=c.next()){var f=r(e.value);e=f.next().value;f=f.next().value;switch(e){case "GetBrowse_rid":Yl(d,Ul(Tl(e),String(f)));break;case "GetGuide_rid":Yl(d,Ul(Tl(e),String(f)));break;case "GetHome_rid":Yl(d,Ul(Tl(e),String(f)));break;case "GetPlayer_rid":Yl(d,Ul(Tl(e),String(f)));break;case "GetSearch_rid":Yl(d,
Ul(Tl(e),String(f)));break;case "GetSettings_rid":Yl(d,Ul(Tl(e),String(f)));break;case "GetTrending_rid":Yl(d,Ul(Tl(e),String(f)));break;case "GetWatchNext_rid":Yl(d,Ul(Tl(e),String(f)));break;case "yt_red":G(d,14,!!f);break;case "yt_ad":G(d,9,!!f)}}lw(d);d=new Wl;d=G(d,25,!0);d=G(d,1,W[Lv(P("TIMING_ACTION"))]);(c=P("PREVIOUS_ACTION"))&&G(d,13,W[Lv(c)]);(c=P("CLIENT_PROTOCOL"))&&G(d,33,c);(c=P("CLIENT_TRANSPORT"))&&G(d,34,c);(c=yu())&&"UNDEFINED_CSN"!==c&&G(d,4,c);c=ow();1!==c&&-1!==c||G(d,6,!0);
c=xv();yv();G(d,3,"cold");pw(c);c=tw();if(0<c.length)for(c=r(c),e=c.next();!e.done;e=c.next())e=e.value,f=new Vl,G(f,1,e),Yd(d,83,Vl,f);lw(d)}else{d=P("TIMING_INFO",{});for(c in d)d.hasOwnProperty(c)&&jw(c,d[c]);d={isNavigation:!0,actionType:Lv(P("TIMING_ACTION"))};if(c=P("PREVIOUS_ACTION"))d.previousAction=Lv(c);if(c=P("CLIENT_PROTOCOL"))d.httpProtocol=c;if(c=P("CLIENT_TRANSPORT"))d.transportProtocol=c;(c=yu())&&"UNDEFINED_CSN"!==c&&(d.clientScreenNonce=c);c=ow();if(1===c||-1===c)d.isVisible=!0;
yv();xv();d.loadType="cold";pw(xv());c=tw();if(0<c.length)for(d.resourceInfo=[],c=r(c),e=c.next();!e.done;e=c.next())d.resourceInfo.push({resourceCache:e.value});kw(d)}d=xv();c=Bv();if("cold"===yv().loadType&&("cold"===d.yt_lt||"cold"===c.loadType)){e=zv();f=Av();f=f.gelTicks?f.gelTicks:f.gelTicks={};for(var g in e)if(!(g in f))if("number"===typeof e[g])mw(g,vw(g));else if(R("log_repeated_ytcsi_ticks"))for(var h=r(e[g]),k=h.next();!k.done;k=h.next())mw(g.slice(1),k.value);g={};e=!1;f=r(Object.keys(d));
for(h=f.next();!h.done;h=f.next())h=h.value,(h=Mv(h,d[h]))&&!ww(Bv(),h)&&(rv(c,h),rv(g,h),e=!0);e&&kw(g)}z("ytglobal.timingready_",!0);g=P("TIMING_ACTION");A("ytglobal.timingready_")&&g&&yw()&&uw()&&nw()})()}
function zw(a,b,c,d){Am(jw)(a,b,c,d)}
function Aw(a,b,c){return Am(mw)(a,b,c)}
function yw(){return Am(function(){return"_start"in zv()})()}
function Bw(){Am(function(){var a=Cv();requestAnimationFrame(function(){setTimeout(function(){a===Cv()&&Aw("ol",void 0,void 0)},0)})})()}
var Cw=window;Cw.ytcsi&&(Cw.ytcsi.info=zw,Cw.ytcsi.tick=Aw);var Dw="tokens consistency mss client_location entities response_received_commands store PLAYER_PRELOAD".split(" "),Ew=["type.googleapis.com/youtube.api.pfiinnertube.YoutubeApiInnertube.BrowseResponse"];function Fw(a,b,c,d){this.m=a;this.W=b;this.l=c;this.j=d;this.i=void 0;this.h=new Map;a.Sb||(a.Sb={});a.Sb=Object.assign({},qv,a.Sb)}
function Gw(a,b,c,d){if(void 0!==Fw.h){if(d=Fw.h,a=[a!==d.m,b!==d.W,c!==d.l,!1,!1,void 0!==d.i],a.some(function(e){return e}))throw new S("InnerTubeTransportService is already initialized",a);
}else Fw.h=new Fw(a,b,c,d)}
function Hw(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=void 0===c?Cn:c;var d=iv(b,a.m);if(!d)return Gf(new S("Error: No request builder found for command.",b));var e=d.m(b,void 0,c);return e?new Bf(function(f){var g,h,k;return x(function(m){if(1==m.h){h="cors"===(null==(g=e.lb)?void 0:g.mode)?"cors":void 0;if(a.l.hf){var n=e.config,q;n=null==n?void 0:null==(q=n.cc)?void 0:q.sessionIndex;q=Bn(0,{sessionIndex:n});k=Object.assign({},Iw(h),q);return m.v(2)}return w(m,Jw(e.config,
h),3)}2!=m.h&&(k=m.i);f(Kw(a,e,k));m.h=0})}):Gf(new S("Error: Failed to build request for command.",b))}
function Lw(a,b,c){var d;if(b&&!(null==b?0:null==(d=b.bu)?0:d.fu)&&a.j){d=r(Dw);for(var e=d.next();!e.done;e=d.next())e=e.value,a.j[e]&&a.j[e].handleResponse(b,c)}}
function Kw(a,b,c){var d,e,f,g,h,k,m,n,q,u,t,B,D,F,N,O,Q,ca,X,vb,Ya,sa,H,oa,ja,af,bf,Jd;return x(function(va){switch(va.h){case 1:va.v(2);break;case 3:if((d=va.i)&&!d.isExpired())return va.return(Promise.resolve(d.h()));case 2:if(null==(e=b)?0:null==(f=e.La)?0:f.context)for(g=r([]),h=g.next();!h.done;h=g.next())k=h.value,k.Xt(b.La.context);if(null==(m=a.i)||!m.cu(b.input,b.La)){va.v(4);break}return w(va,a.i.St(b.input,b.La),5);case 5:return n=va.i,R("kevlar_process_local_innertube_responses_killswitch")||
Lw(a,n,b),va.return(n);case 4:return(t=null==(u=b.config)?void 0:u.Oa)&&a.h.has(t)&&R("web_memoize_inflight_requests")?q=a.h.get(t):(B=JSON.stringify(b.La),N=null!=(F=null==(D=b.lb)?void 0:D.headers)?F:{},b.lb=Object.assign({},b.lb,{headers:Object.assign({},N,c)}),O=Object.assign({},b.lb),"POST"===b.lb.method&&(O=Object.assign({},O,{body:B})),(null==(Q=b.config)?0:Q.Re)&&Aw(b.config.Re),ca=function(){return a.W.fetch(b.input,O,b.config)},q=ca(),t&&a.h.set(t,q)),w(va,q,6);
case 6:if((X=va.i)&&"error"in X&&(null==(vb=X)?0:null==(Ya=vb.error)?0:Ya.details))for(sa=X.error.details,H=r(sa),oa=H.next();!oa.done;oa=H.next())ja=oa.value,(af=ja["@type"])&&-1<Ew.indexOf(af)&&(delete ja["@type"],X=ja);t&&a.h.has(t)&&a.h.delete(t);(null==(bf=b.config)?0:bf.Se)&&Aw(b.config.Se);if(X||null==(Jd=a.i)||!Jd.Kt(b.input,b.La)){va.v(7);break}return w(va,a.i.Rt(b.input,b.La),8);case 8:X=va.i;case 7:return Lw(a,X,b),va.return(X||void 0)}})}
function Jw(a,b){var c,d,e,f;return x(function(g){if(1==g.h){e=null==(c=a)?void 0:null==(d=c.cc)?void 0:d.sessionIndex;var h=Bn(0,{sessionIndex:e});if(!(h instanceof Bf)){var k=new Bf(db);Cf(k,2,h);h=k}return w(g,h,2)}f=g.i;return g.return(Promise.resolve(Object.assign({},Iw(b),f)))})}
function Iw(a){var b={"Content-Type":"application/json"};P("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=P("EOM_VISITOR_DATA"):P("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=P("VISITOR_DATA"));b["X-Youtube-Bootstrap-Logged-In"]=P("LOGGED_IN",!1);"cors"!==a&&((a=P("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=P("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=P("CHROME_CONNECTED_HEADER"))&&(b["X-Youtube-Chrome-Connected"]=a),(a=P("DOMAIN_ADMIN_STATE"))&&
(b["X-Youtube-Domain-Admin-State"]=a));return b}
;var Mw=new Ns("INNERTUBE_TRANSPORT_TOKEN");var Nw=["share/get_web_player_share_panel"],Ow=["feedback"],Pw=["notification/modify_channel_preference"],Qw=["browse/edit_playlist"],Rw=["subscription/subscribe"],Sw=["subscription/unsubscribe"];function Tw(){}
v(Tw,nv);Tw.prototype.j=function(){return Rw};
Tw.prototype.h=function(a){return Ys(a,nm)||void 0};
Tw.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
ea.Object.defineProperties(Tw.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Uw(){}
v(Uw,nv);Uw.prototype.j=function(){return Sw};
Uw.prototype.h=function(a){return Ys(a,mm)||void 0};
Uw.prototype.i=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
ea.Object.defineProperties(Uw.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Vw(){}
v(Vw,nv);Vw.prototype.j=function(){return Ow};
Vw.prototype.h=function(a){return Ys(a,Tk)||void 0};
Vw.prototype.i=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
ea.Object.defineProperties(Vw.prototype,{l:{configurable:!0,enumerable:!0,get:function(){return!0}}});function Ww(){}
v(Ww,nv);Ww.prototype.j=function(){return Pw};
Ww.prototype.h=function(a){return Ys(a,lm)||void 0};
Ww.prototype.i=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function Xw(){}
v(Xw,nv);Xw.prototype.j=function(){return Qw};
Xw.prototype.h=function(a){return Ys(a,km)||void 0};
Xw.prototype.i=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function Yw(){}
v(Yw,nv);Yw.prototype.j=function(){return Nw};
Yw.prototype.h=function(a){return Ys(a,jm)};
Yw.prototype.i=function(a,b,c){c=void 0===c?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var Zw=new Ns("NETWORK_SLI_TOKEN");function $w(a){this.h=a}
$w.prototype.fetch=function(a,b){var c=this,d,e,f;return x(function(g){c.h&&(d=nc(oc(5,Bc(a,"key")))||"/UNKNOWN_PATH",c.h.start(d));e=b;R("wug_networking_gzip_request")&&(e=yq(b));f=new window.Request(a,e);return R("web_fetch_promise_cleanup_killswitch")?g.return(Promise.resolve(fetch(f).then(function(h){return c.handleResponse(h)}).catch(function(h){eu(h)}))):g.return(fetch(f).then(function(h){return c.handleResponse(h)}).catch(function(h){eu(h)}))})};
$w.prototype.handleResponse=function(a){var b=a.text().then(function(c){return JSON.parse(c.replace(")]}'",""))});
a.redirected||a.ok?this.h&&this.h.success():(this.h&&this.h.Ot(),b=b.then(function(c){eu(new S("Error: API fetch failed",a.status,a.url,c));return Object.assign({},c,{errorMetadata:{status:a.status}})}));
return b};
$w[Ms]=[new Os(Zw)];var ax=new Ns("NETWORK_MANAGER_TOKEN");var bx;function cx(a){a=void 0===a||a?mu():lu();for(var b=[],c=0;c<a.length;c++)b.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(a[c]&63));return b.join("")}
;function dx(a){iq.call(this,1,arguments);this.csn=a}
v(dx,iq);var rq=new jq("screen-created",dx),ex=[],gx=fx,hx=0;function ix(a,b,c,d,e,f,g,h){function k(){eu(new S("newScreen() parent element does not have a VE - rootVe",b))}
var m=gx(),n=new ru({veType:b,youtubeData:f,jspbYoutubeData:void 0});f={sequenceGroup:m};e&&(f.cttAuthInfo=e);if(R("il_via_jspb")){e=Jl((new Il).h(m),n.getAsJspb());c&&c.visualElement?(n=new Gl,c.clientScreenNonce&&G(n,2,c.clientScreenNonce),Hl(n,c.visualElement.getAsJspb()),g&&G(n,4,dm[g]),I(e,Gl,5,n)):c&&k();d&&G(e,3,d);if(R("expectation_logging")&&h&&h.screenCreatedLoggingExpectations){c=new vk;h=r(h.screenCreatedLoggingExpectations.expectedParentScreens||[]);for(d=h.next();!d.done;d=h.next())d=
d.value,d.screenVeType&&(d=uk(new tk,d.screenVeType),Yd(c,1,tk,d));I(e,vk,7,c)}Wt(e,f,a)}else e={csn:m,pageVe:n.getAsJson()},R("expectation_logging")&&h&&h.screenCreatedLoggingExpectations&&(e.screenCreatedLoggingExpectations=h.screenCreatedLoggingExpectations),c&&c.visualElement?(e.implicitGesture={parentCsn:c.clientScreenNonce,gesturedVe:c.visualElement.getAsJson()},g&&(e.implicitGesture.gestureType=g)):c&&k(),d&&(e.cloneCsn=d),a?Lt("screenCreated",e,a,f):oo("screenCreated",e,f);oq(rq,new dx(m));
return m}
function jx(a,b,c,d){var e=d.filter(function(k){k.csn!==b?(k.csn=b,k=!0):k=!1;return k}),f={cttAuthInfo:Bu(b)||void 0,
sequenceGroup:b};d=r(d);for(var g=d.next();!g.done;g=d.next())g=g.value.getAsJson(),(qb(g)||!g.trackingParams&&!g.veType)&&eu(Error("Child VE logged with no data"));if(R("il_via_jspb")){var h=Ml((new Kl).h(b),c.getAsJspb());ib(e,function(k){k=k.getAsJspb();Yd(h,3,Bl,k)});
"UNDEFINED_CSN"===b?kx("visualElementAttached",f,void 0,h):Xt(h,f,a)}else c={csn:b,parentVe:c.getAsJson(),childVes:ib(e,function(k){return k.getAsJson()})},"UNDEFINED_CSN"===b?kx("visualElementAttached",f,c):a?Lt("visualElementAttached",c,a,f):oo("visualElementAttached",c,f)}
function lx(a,b,c,d,e,f){d={cttAuthInfo:Bu(b)||void 0,sequenceGroup:b};R("il_via_jspb")?(e=(new Pl).h(b),c=c.getAsJspb(),c=I(e,Bl,2,c),c=G(c,4,1),f&&I(c,El,3,f),"UNDEFINED_CSN"===b?kx("visualElementShown",d,void 0,c):St(c,d,a)):(f={csn:b,ve:c.getAsJson(),eventType:1},e&&(f.clientData=e),"UNDEFINED_CSN"===b?kx("visualElementShown",d,f):a?Lt("visualElementShown",f,a,d):oo("visualElementShown",f,d))}
function mx(a,b,c){var d=!0,e=(d=void 0===d?!1:d)?16:8,f={cttAuthInfo:Bu(b)||void 0,sequenceGroup:b,endOfSequence:d};R("il_via_jspb")?(e=(new Ol).h(b),c=c.getAsJspb(),c=I(e,Bl,2,c),G(c,4,d?16:8),"UNDEFINED_CSN"===b?kx("visualElementHidden",f,void 0,c):Tt(c,f,a)):(d={csn:b,ve:c.getAsJson(),eventType:e},"UNDEFINED_CSN"===b?kx("visualElementHidden",f,d):a?Lt("visualElementHidden",d,a,f):oo("visualElementHidden",d,f))}
function fx(){if(R("enable_web_96_bit_csn"))var a=cx();else if(R("enable_web_96_bit_csn_no_crypto"))a=cx(!1);else{a=Math.random()+"";for(var b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}a=cd(b,3)}return a}
function kx(a,b,c,d){ex.push({Oc:a,payload:c,Ua:d,options:b});hx||(hx=sq())}
function tq(a){if(ex){for(var b=r(ex),c=b.next();!c.done;c=b.next())if(c=c.value,R("il_via_jspb")&&c.Ua)switch(c.Ua.h(a.csn),c.Oc){case "screenCreated":Wt(c.Ua,c.options);break;case "visualElementAttached":Xt(c.Ua,c.options);break;case "visualElementShown":St(c.Ua,c.options);break;case "visualElementHidden":Tt(c.Ua,c.options);break;case "visualElementGestured":Ut(c.Ua,c.options);break;case "visualElementStateChanged":Vt(c.Ua,c.options);break;default:eu(new S("flushQueue unable to map payloadName to JSPB setter"))}else c.payload&&
(c.payload.csn=a.csn,oo(c.Oc,c.payload,c.options));ex.length=0}hx=0}
;function nx(){this.j=new Set;this.i=new Set;this.m=new Map;this.client=void 0;this.csn=null}
function ox(){nx.h||(nx.h=new nx);return nx.h}
nx.prototype.l=function(a){this.client=a};
nx.prototype.h=function(){this.clear();this.csn=yu()};
nx.prototype.clear=function(){this.j.clear();this.i.clear();this.m.clear();this.csn=null};function px(){}
px.prototype.l=function(a){Am(ox().l).bind(ox())(a)};
px.prototype.clear=function(){Am(ox().clear).bind(ox())()};function qx(){this.s=[];this.H=[];this.h=[];this.A=[];this.m=[];this.X=[];this.i=new Set;this.L=new Map}
qx.prototype.l=function(a){this.client=a};
function rx(){qx.h||(qx.h=new qx);var a=qx.h;var b=16623;var c=void 0===c?{}:c;Am(function(){Object.values(Fu).includes(b)||(eu(new S("createClientScreen() called with a non-page VE",b)),b=83769);c.isHistoryNavigation||(a.A=[],a.h.push({rootVe:b,key:c.key||""}));a.s=[];a.H=[];c.md?sx(a,b,c):tx(a,b,c)})()}
function ux(a,b,c){c=void 0===c?0:c;Am(function(){b.then(function(d){a.i.has(c)&&a.j&&a.j();var e=yu(c),f=wu(c);if(e&&f){var g;(null==d?0:null==(g=d.response)?0:g.trackingParams)&&jx(a.client,e,f,[su(d.response.trackingParams)]);var h;(null==d?0:null==(h=d.playerResponse)?0:h.trackingParams)&&jx(a.client,e,f,[su(d.playerResponse.trackingParams)])}})})()}
function vx(a,b,c,d){d=void 0===d?0:d;Am(function(){if(a.i.has(d))return a.s.push([b,c]),!0;var e=yu(d),f=c||wu(d);return e&&f?(jx(a.client,e,f,[b]),!0):!1})()}
qx.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=void 0===c?0:c;if(d)if(c=yu(void 0===c?0:c)){a=this.client;var e=su(d);d={cttAuthInfo:Bu(c)||void 0,sequenceGroup:c};R("il_via_jspb")?(b=(new Nl).h(c),e=e.getAsJspb(),b=I(b,Bl,2,e),G(b,4,dm.INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK),"UNDEFINED_CSN"===c?kx("visualElementGestured",d,void 0,b):Ut(b,d,a)):(e={csn:c,ve:e.getAsJson(),gestureType:"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK"},b&&(e.clientData=b),"UNDEFINED_CSN"===
c?kx("visualElementGestured",d,e):a?Lt("visualElementGestured",e,a,d):oo("visualElementGestured",e,d));b=!0}else b=!1;else b=!1;return b};
qx.prototype.visualElementStateChanged=function(a,b,c){c=void 0===c?0:c;0===c&&this.i.has(c)?this.H.push([a,b]):wx(this,a,b,c)};
function wx(a,b,c,d){d=void 0===d?0:d;var e=yu(d);d=b||wu(d);e&&d&&(a=a.client,b={cttAuthInfo:Bu(e)||void 0,sequenceGroup:e},R("il_via_jspb")?(c=new Ql,c.h(e),d=d.getAsJspb(),I(c,Bl,2,d),"UNDEFINED_CSN"===e?kx("visualElementStateChanged",b,void 0,c):Vt(c,b,a)):(c={csn:e,ve:d.getAsJson(),clientData:c},"UNDEFINED_CSN"===e?kx("visualElementStateChanged",b,c):a?Lt("visualElementStateChanged",c,a,b):oo("visualElementStateChanged",c,b)))}
function sx(a,b,c){c=void 0===c?{}:c;a.i.add(c.layer||0);a.j=function(){tx(a,b,c);var f=wu(c.layer);if(f){for(var g=r(a.s),h=g.next();!h.done;h=g.next())h=h.value,vx(a,h[0],h[1]||f,c.layer);f=r(a.H);for(g=f.next();!g.done;g=f.next())g=g.value,wx(a,g[0],g[1])}};
yu(c.layer)||a.j();if(c.md)for(var d=r(c.md),e=d.next();!e.done;e=d.next())ux(a,e.value,c.layer);else du(Error("Delayed screen needs a data promise."))}
function tx(a,b,c){c=void 0===c?{}:c;var d=void 0;c.layer||(c.layer=0);d=void 0!==c.Me?c.Me:c.layer;var e=yu(d);d=wu(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));var g,h=P("EVENT_ID");"UNDEFINED_CSN"===e&&h&&(g={servletData:{serializedServletEventId:h}});try{var k=ix(a.client,b,f,c.ld,c.cttAuthInfo,g,c.Pt,c.loggingExpectations)}catch(q){gu(q,{Zt:b,rootVe:d,Wt:void 0,Lt:e,Vt:f,ld:c.ld});du(q);
return}Cu(k,b,c.layer,c.cttAuthInfo);e&&"UNDEFINED_CSN"!==e&&d&&!zu(e)&&mx(a.client,e,d);a.h[a.h.length-1]&&!a.h[a.h.length-1].csn&&(a.h[a.h.length-1].csn=k||"");Am(kw)({clientScreenNonce:k},void 0,!1);px.h||(px.h=new px);Am(ox().h).bind(ox())();var m=wu(c.layer);e&&"UNDEFINED_CSN"!==e&&m&&(R("web_mark_root_visible")||R("music_web_mark_root_visible"))&&Am(lx)(void 0,k,m,void 0,void 0,void 0);a.i.delete(c.layer||0);a.j=void 0;var n;null==(n=a.L.get(c.layer))||n.forEach(function(q,u){q?vx(a,u,q,c.layer):
m&&vx(a,u,m,c.layer)});
xx(a)}
function xx(a){for(var b=0;b<a.m.length;b++){var c=a.m[b];try{c()}catch(d){du(d)}}for(b=a.m.length=0;b<a.X.length;b++){c=a.X[b];try{c()}catch(d){du(d)}}}
;function yx(){var a,b,c;return x(function(d){if(1==d.h)return a=Ts().resolve(Mw),a?w(d,Hw(a),2):(eu(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),d.return(void 0));if(b=d.i){if(b.errorMetadata)return eu(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),d.return(void 0);c=b.Mt;return d.return(c)}eu(Error("Network request to get Datasync IDs failed."));return d.return(void 0)})}
;var zx=y.caches,Ax;function Bx(a){var b=a.indexOf(":");return-1===b?{Dd:a}:{Dd:a.substring(0,b),datasyncId:a.substring(b+1)}}
function Cx(){return x(function(a){if(void 0!==Ax)return a.return(Ax);Ax=new Promise(function(b){var c;return x(function(d){switch(d.h){case 1:return za(d,2),w(d,zx.open("test-only"),4);case 4:return w(d,zx.delete("test-only"),5);case 5:Aa(d,3);break;case 2:if(c=Ba(d),c instanceof Error&&"SecurityError"===c.name)return b(!1),d.return();case 3:b("caches"in window),d.h=0}})});
return a.return(Ax)})}
function Dx(a){var b,c,d,e,f,g,h;x(function(k){if(1==k.h)return w(k,Cx(),2);if(3!=k.h){if(!k.i)return k.return(!1);b=[];return w(k,zx.keys(),3)}c=k.i;d=r(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=Bx(f),h=g.datasyncId,!h||a.includes(h)||b.push(zx.delete(f));return k.return(Promise.all(b).then(function(m){return m.some(function(n){return n})}))})}
function Ex(){var a,b,c,d,e,f,g;return x(function(h){if(1==h.h)return w(h,Cx(),2);if(3!=h.h){if(!h.i)return h.return(!1);a=Yn("cache contains other");return w(h,zx.keys(),3)}b=h.i;c=r(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=Bx(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function Fx(){try{return!!self.localStorage}catch(a){return!1}}
;function Gx(a){a=a.match(/(.*)::.*::.*/);if(null!==a)return a[1]}
function Hx(a){if(Fx()){var b=Object.keys(window.localStorage);b=r(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Gx(c);void 0===d||a.includes(d)||self.localStorage.removeItem(c)}}}
function Ix(){if(!Fx())return!1;var a=Yn(),b=Object.keys(window.localStorage);b=r(b);for(var c=b.next();!c.done;c=b.next())if(c=Gx(c.value),void 0!==c&&c!==a)return!0;return!1}
;function Jx(){yx().then(function(a){a&&(Bp(a),Dx(a),Hx(a))})}
function Kx(){var a=new $r;mi.fa(function(){var b,c,d,e;return x(function(f){switch(f.h){case 1:if(R("ytidb_clear_optimizations_killswitch")){f.v(2);break}b=Yn("clear");if(b.startsWith("V")){var g=[b];Bp(g);Dx(g);Hx(g);return f.return()}c=Ix();return w(f,Ex(),3);case 3:return d=f.i,w(f,Cp(),4);case 4:if(e=f.i,!c&&!d&&!e)return f.return();case 2:a.ma()?Jx():a.l.add("publicytnetworkstatus-online",Jx,!0,void 0,void 0),f.h=0}})})}
;var Sh=ha(["data-"]);function Lx(a){a&&(a.dataset?a.dataset[Mx("loaded")]="true":Rh(a))}
function Nx(a,b){return a?a.dataset?a.dataset[Mx(b)]:a.getAttribute("data-"+b):null}
var Ox={};function Mx(a){return Ox[a]||(Ox[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Px=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,Qx=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function Rx(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(Px,""),c=c.replace(Qx,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else Sx(a,b,c)}
function Sx(a,b,c){c=void 0===c?null:c;var d=Tx(a),e=document.getElementById(d),f=e&&Nx(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=Gs(d,b),b=""+Sa(b),Ux[b]=f),g||(e=Vx(a,d,function(){Nx(e,"loaded")||(Lx(e),Js(d),Wm(Za(Ks,d),0))},c)))}
function Vx(a,b,c,d){d=void 0===d?null:d;var e=of("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);Uh(e,pk(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function Wx(a){a=Tx(a);var b=document.getElementById(a);b&&(Ks(a),b.parentNode.removeChild(b))}
function Xx(a,b){a&&b&&(a=""+Sa(b),(a=Ux[a])&&Is(a))}
function Tx(a){var b=document.createElement("a");ec(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+jc(a)}
var Ux={};var Yx=[],Zx=!1;function $x(){if(!R("disable_biscotti_fetch_for_ad_blocker_detection")&&!R("disable_biscotti_fetch_entirely_for_all_web_clients")&&Ou()){var a=P("PLAYER_VARS",{});if("1"!=sb(a)&&!Pu(a)){var b=function(){Zx=!0;"google_ad_status"in window?wm("DCLKSTAT",1):wm("DCLKSTAT",2)};
try{Rx("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Yx.push(mi.fa(function(){if(!(Zx||"google_ad_status"in window)){try{Xx("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}Zx=!0;wm("DCLKSTAT",3)}},5E3))}}}
function ay(){var a=Number(P("DCLKSTAT",0));return isNaN(a)?0:a}
;var dy=window,ey,fy=R("web_enable_lifecycle_monitoring")&&(null==(ey=dy.performance)?void 0:ey.measure);function gy(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?eo():d;this.l=c;this.j=d;this.i=new Jh;this.h=a;a={};c=r(this.h.entries());for(d=c.next();!d.done;a={Db:a.Db,Ub:a.Ub},d=c.next()){var e=r(d.value);d=e.next().value;e=e.next().value;a.Ub=d;a.Db=e;d=function(f){return function(){f.Db.Hc();b.h[f.Ub].qc=!0;b.h.every(function(g){return!0===g.qc})&&b.i.resolve()}}(a);
e=ao(d,hy(this,a.Db));this.h[a.Ub]=Object.assign({},a.Db,{Hc:d,jobId:e})}}
function iy(a){var b=Array.from(a.h.keys()).sort(function(d,e){return hy(a,a.h[e])-hy(a,a.h[d])});
b=r(b);for(var c=b.next();!c.done;c=b.next())c=a.h[c.value],void 0===c.jobId||c.qc||(a.j.Da(c.jobId),ao(c.Hc,10))}
gy.prototype.cancel=function(){for(var a=r(this.h),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.jobId||b.qc||this.j.Da(b.jobId),b.qc=!0;this.i.resolve()};
function hy(a,b){var c;return null!=(c=b.priority)?c:a.l}
;function jy(a){this.state=a;this.plugins=[];this.s=void 0;this.H={};fy&&window.performance.mark(this.state+"-start")}
l=jy.prototype;l.install=function(a){this.plugins.push(a);return this};
l.uninstall=function(){var a=this;Ka.apply(0,arguments).forEach(function(b){b=a.plugins.indexOf(b);-1<b&&a.plugins.splice(b,1)})};
l.transition=function(a,b){var c=this;ky(this);var d=this.transitions.find(function(f){return Array.isArray(f.from)?f.from.find(function(g){return g===c.state&&f.K===a}):f.from===c.state&&f.K===a});
if(d){this.j&&(iy(this.j),this.j=void 0);ly(this,a,b);this.state=a;fy&&window.performance.mark(this.state+"-start");d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(my(this,e),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function my(a,b){var c=b.filter(function(e){return 10===ny(a,e)}),d=b.filter(function(e){return 10!==ny(a,e)});
return a.H.du?function(){var e=Ka.apply(0,arguments);return x(function(f){if(1==f.h)return w(f,a.Te.apply(a,[c].concat(ia(e))),2);a.Md.apply(a,[d].concat(ia(e)));f.h=0})}:function(){var e=Ka.apply(0,arguments);
a.Ue.apply(a,[c].concat(ia(e)));a.Md.apply(a,[d].concat(ia(e)))}}
l.Ue=function(a){var b=Ka.apply(1,arguments);eo();for(var c={},d=r(a),e=d.next();!e.done;c={pb:c.pb},e=d.next())c.pb=e.value,bo(function(f){return function(){oy(f.pb.name);f.pb.callback.apply(f.pb,ia(b));py(f.pb.name)}}(c))};
l.Te=function(a){var b=Ka.apply(1,arguments),c,d,e,f;return x(function(g){1==g.h&&(eo(),c={},d=r(a),e=d.next());if(3!=g.h){if(e.done)return g.v(0);c.bb=e.value;c.Bb=void 0;f=function(h){return function(){oy(h.bb.name);var k=h.bb.callback.apply(h.bb,ia(b));k&&(k instanceof Bf||k instanceof Promise)?h.Bb=k.then(function(){py(h.bb.name)}):py(h.bb.name)}}(c);
bo(f);return c.Bb?w(g,c.Bb,3):g.v(3)}c={bb:c.bb,Bb:c.Bb};e=d.next();return g.v(2)})};
l.Md=function(a){var b=Ka.apply(1,arguments),c=this,d=a.map(function(e){return{Hc:function(){oy(e.name);e.callback.apply(e,ia(b));py(e.name)},
priority:ny(c,e)}});
d.length&&(this.j=new gy(d))};
function ny(a,b){var c,d;return null!=(d=null!=(c=a.s)?c:b.priority)?d:0}
function ky(a){if(fy){var b=a.state+"-start",c=a.state+"-end";window.performance.mark(c);window.performance.measure(a.state,b,c)}}
function oy(a){fy&&a&&window.performance.mark(a+"-start")}
function py(a){if(fy&&a){var b=a+"-start",c=a+"-end";window.performance.mark(c);window.performance.measure(a,b,c)}}
function ly(a,b,c){fy&&(console.groupCollapsed("["+a.constructor.name+"] '"+a.state+"' to '"+b+"'"),console.log("with message: ",c),console.groupEnd())}
ea.Object.defineProperties(jy.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function qy(a){jy.call(this,void 0===a?"document_active":a);var b=this;this.s=10;this.h=new Map;this.transitions=[{from:"document_active",K:"document_disposed_preventable",action:this.X},{from:"document_active",K:"document_disposed",action:this.l},{from:"document_disposed_preventable",K:"document_disposed",action:this.l},{from:"document_disposed_preventable",K:"flush_logs",action:this.m},{from:"document_disposed_preventable",K:"document_active",action:this.i},{from:"document_disposed",K:"flush_logs",
action:this.m},{from:"document_disposed",K:"document_active",action:this.i},{from:"document_disposed",K:"document_disposed",action:function(){}},
{from:"flush_logs",K:"document_active",action:this.i}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
v(qy,jy);qy.prototype.X=function(a,b){if(!this.h.get("document_disposed_preventable")){a(null==b?void 0:b.event);var c,d;if((null==b?0:null==(c=b.event)?0:c.defaultPrevented)||(null==b?0:null==(d=b.event)?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.h=new Map;this.transition("document_active");return}}this.h.set("document_disposed_preventable",!0);this.h.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
qy.prototype.l=function(a,b){this.h.get("document_disposed")?this.transition("document_active"):(a(null==b?void 0:b.event),this.h.set("document_disposed",!0),this.transition("flush_logs"))};
qy.prototype.m=function(a,b){a(null==b?void 0:b.event);this.transition("document_active")};
qy.prototype.i=function(){this.h=new Map};function ry(a){jy.call(this,void 0===a?"document_visibility_unknown":a);var b=this;this.transitions=[{from:"document_visibility_unknown",K:"document_visible",action:this.i},{from:"document_visibility_unknown",K:"document_hidden",action:this.h},{from:"document_visibility_unknown",K:"document_foregrounded",action:this.m},{from:"document_visibility_unknown",K:"document_backgrounded",action:this.l},{from:"document_visible",K:"document_hidden",action:this.h},{from:"document_visible",K:"document_foregrounded",
action:this.m},{from:"document_visible",K:"document_visible",action:this.i},{from:"document_foregrounded",K:"document_visible",action:this.i},{from:"document_foregrounded",K:"document_hidden",action:this.h},{from:"document_foregrounded",K:"document_foregrounded",action:this.m},{from:"document_hidden",K:"document_visible",action:this.i},{from:"document_hidden",K:"document_backgrounded",action:this.l},{from:"document_hidden",K:"document_hidden",action:this.h},{from:"document_backgrounded",K:"document_hidden",
action:this.h},{from:"document_backgrounded",K:"document_backgrounded",action:this.l},{from:"document_backgrounded",K:"document_visible",action:this.i}];document.addEventListener("visibilitychange",function(c){"visible"===document.visibilityState?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
R("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
v(ry,jy);ry.prototype.i=function(a,b){a(null==b?void 0:b.event);R("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
ry.prototype.h=function(a,b){a(null==b?void 0:b.event);R("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
ry.prototype.l=function(a,b){a(null==b?void 0:b.event)};
ry.prototype.m=function(a,b){a(null==b?void 0:b.event)};function sy(){this.j=new qy;this.l=new ry}
sy.prototype.install=function(){var a=Ka.apply(0,arguments),b=this;a.forEach(function(c){b.j.install(c)});
a.forEach(function(c){b.l.install(c)})};function ty(){sy.call(this);var a={};this.install((a.document_disposed={callback:this.h},a));a={};this.install((a.flush_logs={callback:this.i},a))}
v(ty,sy);ty.prototype.i=function(){if(R("web_fp_via_jspb")){var a=new Al,b=yu();b&&G(a,1,b);b=new bm;Wd(b,Al,380,cm,a);Rt(b);R("web_fp_via_jspb_and_json")&&oo("finalPayload",{csn:yu()})}else oo("finalPayload",{csn:yu()})};
ty.prototype.h=function(){iu(ju)};function uy(){}
function vy(){var a=A("ytglobal.storage_");a||(a=new uy,z("ytglobal.storage_",a));return a}
uy.prototype.estimate=function(){var a,b,c;return x(function(d){a=navigator;return(null==(b=a.storage)?0:b.estimate)?d.return(a.storage.estimate()):(null==(c=a.webkitTemporaryStorage)?0:c.queryUsageAndQuota)?d.return(wy()):d.return()})};
function wy(){var a=navigator;return new Promise(function(b,c){var d;null!=(d=a.webkitTemporaryStorage)&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
z("ytglobal.storageClass_",uy);function mo(a,b){var c=this;this.handleError=a;this.h=b;this.i=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.i=!0});
this.j=Math.random()<=Qm("ytidb_transaction_ended_event_rate_limit_session",.2)}
mo.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":R("idb_data_corrupted_killswitch")||this.h("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.h("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":R("idb_is_supported_completed_killswitch")||this.h("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":xy(this,b);break;case "TRANSACTION_ENDED":this.j&&Math.random()<=Qm("ytidb_transaction_ended_event_rate_limit_transaction",.1)&&this.h("idbTransactionEnded",
b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign({},b,{hasWindowUnloaded:this.i}),this.h("idbTransactionAborted",a)}};
function xy(a,b){vy().estimate().then(function(c){c=Object.assign({},b,{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:yy(null==c?void 0:c.usage),deviceStorageQuotaMbytes:yy(null==c?void 0:c.quota)});a.h("idbQuotaExceeded",c)})}
function yy(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;function zy(a,b,c){K.call(this);var d=this;c=c||P("POST_MESSAGE_ORIGIN")||window.document.location.protocol+"//"+window.document.location.hostname;this.l=b||null;this.targetOrigin="*";this.m=c;this.sessionId=null;this.i="widget";this.R=!!a;this.L=function(e){a:if(!("*"!=d.m&&e.origin!=d.m||d.l&&e.source!=d.l||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.R&&(d.sessionId&&d.sessionId!=f.id||d.i&&d.i!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.m=d.targetOrigin=e.origin);d.l=e.source;d.sessionId=f.id;d.j&&(d.j(),d.j=null);break;case "command":d.s&&(!d.A||0<=fb(d.A,f.func))&&d.s(f.func,f.args,e.origin)}}};
this.A=this.j=this.s=null;window.addEventListener("message",this.L)}
v(zy,K);zy.prototype.sendMessage=function(a,b){if(b=b||this.l){this.sessionId&&(a.id=this.sessionId);this.i&&(a.channel=this.i);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){Cm(d)}}};
zy.prototype.M=function(){window.removeEventListener("message",this.L);K.prototype.M.call(this)};function Ay(){this.i=[];this.isReady=!1;this.j={};var a=this.h=new zy(!!P("WIDGET_ID_ENFORCE")),b=this.Oe.bind(this);a.s=b;a.A=null;this.h.i="widget";if(a=P("WIDGET_ID"))this.h.sessionId=a}
l=Ay.prototype;l.Oe=function(a,b,c){"addEventListener"===a&&b?this.Gc(b[0],c):this.Xc(a,b,c)};
l.Xc=function(){};
l.zc=function(a){var b=this;return function(c){return b.sendMessage(a,c)}};
l.Gc=function(a,b){this.j[a]||"onReady"===a||(this.addEventListener(a,this.zc(a,b)),this.j[a]=!0)};
l.addEventListener=function(){};
l.re=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.Cc());this.sendMessage("onReady");gb(this.i,this.Kd,this);this.i=[]};
l.Cc=function(){return null};
function By(a,b){a.sendMessage("infoDelivery",b)}
l.Kd=function(a){this.isReady?this.h.sendMessage(a):this.i.push(a)};
l.sendMessage=function(a,b){this.Kd({event:a,info:void 0===b?null:b})};
l.dispose=function(){this.h=null};var Cy={},Dy=(Cy["api.invalidparam"]=2,Cy.auth=150,Cy["drm.auth"]=150,Cy["heartbeat.net"]=150,Cy["heartbeat.servererror"]=150,Cy["heartbeat.stop"]=150,Cy["html5.unsupportedads"]=5,Cy["fmt.noneavailable"]=5,Cy["fmt.decode"]=5,Cy["fmt.unplayable"]=5,Cy["html5.missingapi"]=5,Cy["html5.unsupportedlive"]=5,Cy["drm.unavailable"]=5,Cy["mrm.blocked"]=151,Cy);var Ey=new Set("endSeconds startSeconds mediaContentUrl suggestedQuality videoId rct rctn".split(" "));function Fy(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function Gy(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b={};c=r(Ey);for(var d=c.next();!d.done;d=c.next())d=d.value,a[d]&&(b[d]=a[d]);return b}
function Hy(a,b,c,d){if(Ra(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function Iy(a){Ay.call(this);this.listeners=[];this.l=!1;this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.af.bind(this));this.addEventListener("onVolumeChange",this.bf.bind(this));this.addEventListener("onApiChange",this.Ve.bind(this));this.addEventListener("onPlaybackQualityChange",this.Xe.bind(this));this.addEventListener("onPlaybackRateChange",this.Ye.bind(this));this.addEventListener("onStateChange",this.Ze.bind(this));this.addEventListener("onWebglSettingsChanged",
this.cf.bind(this))}
v(Iy,Ay);l=Iy.prototype;
l.Xc=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&Fy(a)){var d=b;if(Ra(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=Gy(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=Gy(e);break;case "loadPlaylist":case "cuePlaylist":e=Hy(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);Fy(a)&&By(this,this.Cc())}};
l.Gc=function(a,b){("onReady"===a||"onError"===a&&this.l)&&this.api.logApiCall(a+" invocation",b);this.api.logApiCall(a+" registration",b);Ay.prototype.Gc.call(this,a,b)};
l.zc=function(a,b){var c=this,d=Ay.prototype.zc.call(this,a,b);return function(e){c.api.logApiCall(a+" invocation",b);d(e)}};
l.onReady=function(){var a=this.re.bind(this);this.h.j=a;a=this.api.getVideoData();if(!a.isPlayable){this.l=!0;a=a.errorCode;var b=void 0===b?5:b;this.sendMessage("onError",(a?Dy[a]||b:b).toString())}};
l.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
l.Cc=function(){if(!this.api)return null;var a=this.api.getApiInterface();lb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
l.Ze=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());By(this,a)};
l.Xe=function(a){By(this,{playbackQuality:a})};
l.Ye=function(a){By(this,{playbackRate:a})};
l.Ve=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],m=this.api.getOption(e,k);b[e][k]=m}}this.sendMessage("apiInfoDelivery",b)};
l.bf=function(){By(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
l.af=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());By(this,a)};
l.cf=function(){var a={sphericalProperties:this.api.getSphericalProperties()};By(this,a)};
l.dispose=function(){Ay.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function Jy(a){K.call(this);this.i={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.Gd,this)}
v(Jy,K);l=Jy.prototype;l.start=function(){this.started||this.h()||(this.started=!0,this.connection.mb("RECEIVING"))};
l.mb=function(a,b){this.started&&!this.h()&&this.connection.mb(a,b)};
l.Gd=function(a,b,c){if(this.started&&!this.h()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=Ky(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=Ly(a,c))&&this.mb(a,c))}}};
l.addListener=function(a){if(!(a in this.i)){var b=this.We.bind(this,a);this.i[a]=b;this.addEventListener(a,b)}};
l.We=function(a,b){this.started&&!this.h()&&this.connection.mb(a,this.Bc(a,b))};
l.Bc=function(a,b){if(null!=b)return{value:b}};
l.removeListener=function(a){a in this.i&&(this.removeEventListener(a,this.i[a]),delete this.i[a])};
l.M=function(){var a=this.connection;a.h()||Ki(a.i,"command",this.Gd,this);this.connection=null;for(var b in this.i)this.i.hasOwnProperty(b)&&this.removeListener(b);K.prototype.M.call(this)};function My(a,b){Jy.call(this,b);this.api=a;this.start()}
v(My,Jy);My.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
My.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function Ky(a,b){switch(a){case "loadVideoById":return a=Gy(b),[a];case "cueVideoById":return a=Gy(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=Hy(b),[a];case "cuePlaylist":return a=Hy(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Ly(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
My.prototype.Bc=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return Jy.prototype.Bc.call(this,a,b)};
My.prototype.M=function(){Jy.prototype.M.call(this);delete this.api};function Ny(a){a=void 0===a?!1:a;K.call(this);this.i=new Ji(a);ve(this,this.i)}
$a(Ny,K);Ny.prototype.subscribe=function(a,b,c){return this.h()?0:this.i.subscribe(a,b,c)};
Ny.prototype.m=function(a,b){this.h()||this.i.eb.apply(this.i,arguments)};function Oy(a,b,c){Ny.call(this);this.l=a;this.j=b;this.id=c}
v(Oy,Ny);Oy.prototype.mb=function(a,b){this.h()||this.l.mb(this.j,this.id,a,b)};
Oy.prototype.M=function(){this.j=this.l=null;Ny.prototype.M.call(this)};function Py(a,b,c){K.call(this);this.i=a;this.origin=c;this.j=us(window,"message",this.l.bind(this));this.connection=new Oy(this,a,b);ve(this,this.connection)}
v(Py,K);Py.prototype.mb=function(a,b,c,d){this.h()||a!==this.i||(a={id:b,command:c},d&&(a.data=d),this.i.postMessage(JSON.stringify(a),this.origin))};
Py.prototype.l=function(a){if(!this.h()&&a.origin===this.origin){var b=a.data;if("string"===typeof b){try{b=JSON.parse(b)}catch(d){return}if(b.command){var c=this.connection;c.h()||c.m("command",b.command,b.data,a.origin)}}}};
Py.prototype.M=function(){vs(this.j);this.i=null;K.prototype.M.call(this)};function Qy(){this.state=1;this.h=null}
l=Qy.prototype;
l.initialize=function(a,b,c){if(a.program){var d,e=null!=(d=a.interpreterUrl)?d:null;if(a.interpreterSafeScript){d=a.interpreterSafeScript;Db("From proto message. b/166824318");d=d.privateDoNotAccessOrElseSafeScriptWrappedValue||"";var f=Ab();d=f?f.createScript(d):d;d=new Fb(d,Eb)}else d=null!=(f=a.interpreterScript)?f:null;a.interpreterSafeUrl&&(e=a.interpreterSafeUrl,Db("From proto message. b/166824318"),e=Jb(e.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||"").toString());Ry(this,d,e,
a.program,b,c)}else eu(Error("Cannot initialize botguard without program"))};
function Ry(a,b,c,d,e,f){var g=void 0===g?"trayride":g;c?(a.state=2,Rx(c,function(){window[g]?Sy(a,d,g,e):(a.state=3,Wx(c),eu(new S("Unable to load Botguard","from "+c)))},f)):b?(f=of("SCRIPT"),b instanceof Fb?(b instanceof Fb&&b.constructor===Fb?b=b.j:(Pa(b),b="type_error:SafeScript"),f.textContent=b,Th(f)):f.textContent=b,f.nonce=hc(),document.head.appendChild(f),document.head.removeChild(f),window[g]?Sy(a,d,g,e):(a.state=4,eu(new S("Unable to load Botguard from JS")))):eu(new S("Unable to load VM; no url or JS provided"))}
function Sy(a,b,c,d){a.state=5;try{var e=new Kh({program:b,we:c,Pe:R("att_web_record_metrics")});e.ef.then(function(){a.state=6;d&&d(b)});
a.Sc(e)}catch(f){a.state=7,f instanceof Error&&eu(f)}}
l.invoke=function(a){a=void 0===a?{}:a;return this.Vc()?this.Td({kd:a}):null};
l.dispose=function(){this.Yc()};
l.Yc=function(){this.Sc(null);this.state=8};
l.Vc=function(){return!!this.h};
l.Td=function(a){return this.h.Nd(a)};
l.Sc=function(a){te(this.h);this.h=a};function Ty(){var a=A("yt.abuse.playerAttLoader");return a&&["bgvma","bgvmb","bgvmc"].every(function(b){return b in a})?a:null}
;function Uy(){Qy.apply(this,arguments)}
v(Uy,Qy);Uy.prototype.Yc=function(){this.state=8};
Uy.prototype.Sc=function(a){var b;null==(b=Ty())||b.bgvma();a?(b={bgvma:a.dispose.bind(a),bgvmb:a.snapshot.bind(a),bgvmc:a.Nd.bind(a)},z("yt.abuse.playerAttLoader",b),z("yt.abuse.playerAttLoaderRun",function(c){return a.snapshot(c)})):(z("yt.abuse.playerAttLoader",null),z("yt.abuse.playerAttLoaderRun",null))};
Uy.prototype.Vc=function(){return!!Ty()};
Uy.prototype.Td=function(a){return Ty().bgvmc(a)};var Vy=new Uy;function Wy(){return Vy.Vc()}
function Xy(a){a=void 0===a?{}:a;return Vy.invoke(a)}
;function Yy(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||ub(b);this.assets=a.assets||{};this.attrs=a.attrs||ub(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
Yy.prototype.clone=function(){var a=new Yy,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Pa(c)?a[b]=ub(c):a[b]=c}return a};var Zy=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function $y(a){a=a||"";if(window.spf){var b=a.match(Zy);spf.style.load(a,b?b[1]:"",void 0)}else az(a)}
function az(a){var b=bz(a),c=document.getElementById(b),d=c&&Nx(c,"loaded");d||c&&!d||(c=cz(a,b,function(){Nx(c,"loaded")||(Lx(c),Js(b),Wm(Za(Ks,b),0))}))}
function cz(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=pk(a);fc(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function bz(a){var b=of("A");ec(b,new Mb(a,Nb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+jc(a)}
;function dz(){K.call(this);this.i=[]}
v(dz,K);dz.prototype.M=function(){for(;this.i.length;){var a=this.i.pop();a.target.removeEventListener(a.name,a.callback,void 0)}K.prototype.M.call(this)};function ez(){dz.apply(this,arguments)}
v(ez,dz);function fz(a,b,c,d,e){K.call(this);var f=this;this.A=b;this.webPlayerContextConfig=d;this.Yb=e;this.Ba=!1;this.api={};this.oa=this.s=null;this.V=new Ji;this.i={};this.aa=this.qa=this.elementId=this.fb=this.config=null;this.Z=!1;this.l=this.L=null;this.Qa={};this.Zb=["onReady"];this.lastError=null;this.Gb=NaN;this.R={};this.ac=new ez(this);this.ia=0;this.j=this.m=a;ve(this,this.V);gz(this);hz(this);ve(this,this.ac);c?this.ia=Wm(function(){f.loadNewVideoConfig(c)},0):d&&(iz(this),jz(this))}
v(fz,K);l=fz.prototype;l.getId=function(){return this.A};
l.loadNewVideoConfig=function(a){if(!this.h()){this.ia&&(window.clearTimeout(this.ia),this.ia=0);var b=a||{};b instanceof Yy||(b=new Yy(b));this.config=b;this.setConfig(a);jz(this);this.isReady()&&kz(this)}};
function iz(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;"video-player"===a.elementId&&(a.elementId=a.A,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.A:a.config.attrs.id=a.A);var c;(null==(c=a.j)?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
l.setConfig=function(a){this.fb=a;this.config=lz(a);iz(this);if(!this.qa){var b;this.qa=mz(this,(null==(b=this.config.args)?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null==(c=this.config)?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.j&&(this.j.style.width=di(Number(b)||b)),(a=a.height)&&this.j&&(this.j.style.height=di(Number(a)||a))};
function kz(a){if(a.config&&!0!==a.config.loaded)if(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay){var b;a.api.loadVideoByPlayerVars(null!=(b=a.config.args)?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function nz(a){var b=!0,c=oz(a);c&&a.config&&(a=pz(a),b=Nx(c,"version")===a);return b&&!!A("yt.player.Application.create")}
function jz(a){if(!a.h()&&!a.Z){var b=nz(a);if(b&&"html5"===(oz(a)?"html5":null))a.aa="html5",a.isReady()||qz(a);else if(rz(a),a.aa="html5",b&&a.l&&a.m)a.m.appendChild(a.l),qz(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.L=function(){c=!0;var d=sz(a,"player_bootstrap_method")?A("yt.player.Application.createAlternate")||A("yt.player.Application.create"):A("yt.player.Application.create");var e=a.config?lz(a.config):void 0;d&&d(a.m,e,a.webPlayerContextConfig,a.Yb);qz(a)};
a.Z=!0;b?a.L():(Rx(pz(a),a.L),(b=tz(a))&&$y(b),uz(a)&&!c&&z("yt.player.Application.create",null))}}}
function oz(a){var b=nf(a.elementId);!b&&a.j&&a.j.querySelector&&(b=a.j.querySelector("#"+a.elementId));return b}
function qz(a){if(!a.h()){var b=oz(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.Z=!1;if(!sz(a,"html5_remove_not_servable_check_killswitch")){var d;if((null==b?0:b.isNotServable)&&a.config&&(null==b?0:b.isNotServable(null==(d=a.config.args)?void 0:d.video_id)))return}vz(a)}else a.Gb=Wm(function(){qz(a)},50)}}
function vz(a){gz(a);a.Ba=!0;var b=oz(a);if(b){a.s=wz(a,b,"addEventListener");a.oa=wz(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=wz(a,b,f))}}for(var g in a.i)a.i.hasOwnProperty(g)&&a.s&&a.s(g,a.i[g]);kz(a);a.qa&&a.qa(a.api);a.V.eb("onReady",a.api)}
function wz(a,b,c){var d=b[c];return function(){var e=Ka.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,eu(f))}}}
function gz(a){a.Ba=!1;if(a.oa)for(var b in a.i)a.i.hasOwnProperty(b)&&a.oa(b,a.i[b]);for(var c in a.R)a.R.hasOwnProperty(c)&&window.clearTimeout(Number(c));a.R={};a.s=null;a.oa=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.fb};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
l.isReady=function(){return this.Ba};
function hz(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){Js("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){Js("WATCH_LATER_VIDEO_REMOVED",b)})}
l.addEventListener=function(a,b){var c=this,d=mz(this,b);d&&(0<=fb(this.Zb,a)||this.i[a]||(b=xz(this,a),this.s&&this.s(a,b)),this.V.subscribe(a,d),"onReady"===a&&this.isReady()&&Wm(function(){d(c.api)},0))};
l.removeEventListener=function(a,b){this.h()||(b=mz(this,b))&&Ki(this.V,a,b)};
function mz(a,b){var c=b;if("string"===typeof b){if(a.Qa[b])return a.Qa[b];c=function(){var d=Ka.apply(0,arguments),e=A(b);if(e)try{e.apply(y,d)}catch(f){du(f)}};
a.Qa[b]=c}return c?c:null}
function xz(a,b){var c="ytPlayer"+b+a.A;a.i[b]=c;y[c]=function(d){var e=Wm(function(){if(!a.h()){try{a.V.eb(b,null!=d?d:void 0)}catch(h){eu(new S("PlayerProxy error when creating global callback",{error:h,event:b,playerId:a.A,data:d}))}var f=a.R,g=String(e);g in f&&delete f[g]}},0);
rb(a.R,String(e))};
return c}
l.getPlayerType=function(){return this.aa||(oz(this)?"html5":null)};
l.getLastError=function(){return this.lastError};
function rz(a){a.cancel();gz(a);a.aa=null;a.config&&(a.config.loaded=!1);var b=oz(a);b&&(nz(a)||!uz(a)?a.l=b:(b&&b.destroy&&b.destroy(),a.l=null));if(a.m)for(a=a.m;b=a.firstChild;)a.removeChild(b)}
l.cancel=function(){this.L&&Xx(pz(this),this.L);window.clearTimeout(this.Gb);this.Z=!1};
l.M=function(){rz(this);if(this.l&&this.config&&this.l.destroy)try{this.l.destroy()}catch(b){du(b)}this.Qa=null;for(var a in this.i)this.i.hasOwnProperty(a)&&(y[this.i[a]]=null);this.fb=this.config=this.api=null;delete this.m;delete this.j;K.prototype.M.call(this)};
function uz(a){var b,c;a=null==(b=a.config)?void 0:null==(c=b.args)?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function pz(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function tz(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function sz(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if(null==(d=a.config)?0:d.args)c=a.config.args.fflags}return"true"===Fm(c||"","&")[b]}
function lz(a){for(var b={},c=r(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?ub(e):e}return b}
;var yz={},zz="player_uid_"+(1E9*Math.random()>>>0);function Az(a,b){var c="player",d=!1;d=void 0===d?!0:d;c="string"===typeof c?nf(c):c;var e=zz+"_"+Sa(c),f=yz[e];if(f&&d)return Bz(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new fz(c,e,a,b,void 0);yz[e]=f;Js("player-added",f.api);we(f,function(){delete yz[f.getId()]});
return f.api}
function Bz(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var Cz=null,Dz=null,Ez=null;function Fz(){Gz()}
function Hz(){Gz()}
function Gz(){var a=Cz.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
function Iz(){Cz&&Cz.sendAbandonmentPing&&Cz.sendAbandonmentPing();P("PL_ATT")&&Vy.dispose();for(var a=mi,b=0,c=Yx.length;b<c;b++)a.Da(Yx[b]);Yx.length=0;Wx("//static.doubleclick.net/instream/ad_status.js");Zx=!1;wm("DCLKSTAT",0);ue(Ez,Dz);Cz&&(Cz.removeEventListener("onVideoDataChange",Fz),Cz.destroy())}
;function Jz(a,b,c){a="ST-"+jc(a).toString(36);b=b?uc(b):"";c=c||5;Ou()&&Fn(a,b,c)}
;function Kz(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=P("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=P("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=pc(window.location.href);g&&f.push(g);g=pc(d);if(0<=fb(f,g)||!g&&0==d.lastIndexOf("/",0))if(R("autoescape_tempdata_url")&&(f=document.createElement("a"),ec(f,d),d=f.href),d&&(d=qc(d),f=d.indexOf("#"),d=0>f?d:d.slice(0,f)))if(e&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:yu()},b)),h){var h=parseInt(h,10);isFinite(h)&&0<h&&
Jz(d,b,h)}else Jz(d,b)}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var k=void 0===k?{}:k;var m=void 0===m?"":m;var n=void 0===n?window:n;c=n.location;a=wc(a,k)+m;var q=void 0===q?Xh:q;a:{q=void 0===q?Xh:q;for(k=0;k<q.length;++k)if(m=q[k],m instanceof Vh&&m.De(a)){q=new Mb(a,Nb);break a}q=void 0}q=q||Tb;if(q instanceof Mb)var u=Qb(q);else{b:if(Nh){try{u=new URL(q)}catch(t){u="https:";break b}u=u.protocol}else c:{u=document.createElement("a");try{u.href=q}catch(t){u=void 0;break c}u=
u.protocol;u=":"===u||""===u?"https:":u}u="javascript:"!==u?q:void 0}void 0!==u&&(c.href=u)}return!0}
;z("yt.setConfig",wm);z("yt.config.set",wm);z("yt.setMsg",Eu);z("yt.msgs.set",Eu);z("yt.logging.errors.log",du);
z("writeEmbed",function(){var a=P("PLAYER_CONFIG");if(!a){var b=P("PLAYER_VARS");b&&(a={args:b})}Yu(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=P("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);xw("embed",["ol"]);c=P("WEB_PLAYER_CONTEXT_CONFIGS").WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;if(!c.serializedForcedExperimentIds){var d=Km(window.location.href);
d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}var e;R("embeds_web_enable_watch_on_autoplay")&&(null==(e=a.args)?0:e.autoplay)&&xw("watch",["pbs","pbu","pbp"]);Cz=Az(a,c);Cz.addEventListener("onVideoDataChange",Fz);Cz.addEventListener("onReady",Hz);a=P("POST_MESSAGE_ID","player");P("ENABLE_JS_API")?Ez=new Iy(Cz):P("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(Dz=new Py(window.parent,a,b),Ez=new My(Cz,Dz.connection));$x();R("ytidb_create_logger_embed_killswitch")||
lo();a={};ty.h||(ty.h=new ty);ty.h.install((a.flush_logs={callback:function(){st()}},a));
ks();R("ytidb_clear_embedded_player")&&mi.fa(function(){var f,g;if(!bx){var h=Ts(),k={Pc:ax,Rd:$w};h.h.set(k.Pc,k);k={jd:{feedbackEndpoint:jv(Vw),modifyChannelNotificationPreferenceEndpoint:jv(Ww),playlistEditEndpoint:jv(Xw),subscribeEndpoint:jv(Tw),unsubscribeEndpoint:jv(Uw),webPlayerShareEntityServiceEndpoint:jv(Yw)}};var m=hv(),n={};m&&(n.client_location=m);void 0===f&&(f=An());void 0===g&&(g=h.resolve(ax));Gw(k,g,f,n);f={Pc:Mw,Sd:Fw.h};h.h.set(f.Pc,f);bx=h.resolve(Mw)}Kx()})});
var Lz=Am(function(){Bw();Zu();R("embeds_web_enable_ve_logging_unification")||rx()}),Mz=Am(function(a){a.persisted||(Bw(),Zu())}),Nz=Am(function(a){R("embeds_web_enable_dispose_player_if_page_not_cached_killswitch")?Iz():a.persisted||Iz()}),Oz=Am(Iz);
window.addEventListener?(window.addEventListener("load",Lz),window.addEventListener("pageshow",Mz),window.addEventListener("pagehide",Nz)):window.attachEvent&&(window.attachEvent("onload",Lz),window.attachEvent("onunload",Oz));z("yt.abuse.player.botguardInitialized",A("yt.abuse.player.botguardInitialized")||Wy);z("yt.abuse.player.invokeBotguard",A("yt.abuse.player.invokeBotguard")||Xy);z("yt.abuse.dclkstatus.checkDclkStatus",A("yt.abuse.dclkstatus.checkDclkStatus")||ay);
z("yt.player.exports.navigate",A("yt.player.exports.navigate")||Kz);z("yt.util.activity.init",A("yt.util.activity.init")||ys);z("yt.util.activity.getTimeSinceActive",A("yt.util.activity.getTimeSinceActive")||Bs);z("yt.util.activity.setTimestamp",A("yt.util.activity.setTimestamp")||zs);}).call(this);
