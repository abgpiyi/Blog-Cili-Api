Blog-Cili-Api
=============

Blogger Script #1
(function() { var b=window,e="jstiming",g="tick";(function(){function d(a){this.t={};this.tick=function(a,d,c){c=void 0!=c?c:(new Date).getTime();this.t[a]=[c,d]};this[g]("start",null,a)}var a=new d;b.jstiming={Timer:d,load:a};if(b.performance&&b.performance.timing){var a=b.performance.timing,c=b[e].load,f=a.navigationStart,a=a.responseStart;0<f&&a>=f&&(c[g]("_wtsrt",void 0,f),c[g]("wtsrt_","_wtsrt",a),c[g]("tbsd_","wtsrt_"))}try{a=null,b.chrome&&b.chrome.csi&&(a=Math.floor(b.chrome.csi().pageT),c&&0<f&&(c[g]("_tbnd",void 0,b.chrome.csi().startE),
c[g]("tbnd_","_tbnd",f))),null==a&&b.gtbExternal&&(a=b.gtbExternal.pageT()),null==a&&b.external&&(a=b.external.pageT,c&&0<f&&(c[g]("_tbnd",void 0,b.external.startE),c[g]("tbnd_","_tbnd",f))),a&&(b[e].pt=a)}catch(l){}})();b.tickAboveFold=function(d){var a=0;if(d.offsetParent){do a+=d.offsetTop;while(d=d.offsetParent)}d=a;750>=d&&b[e].load[g]("aft")};var h=!1;function k(){h||(h=!0,b[e].load[g]("firstScrollTime"))}b.addEventListener?b.addEventListener("scroll",k,!1):b.attachEvent("onscroll",k);
 })();
