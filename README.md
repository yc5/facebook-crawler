# facebook-crawler
Simple Facebook crawler.

## Profile Posts Backup
```js
//push each post text to array
output = [];
document.querySelectorAll("[dir=auto][class='']").forEach(e => {
	output.push(e.textContent);

})
console.log(output)

//click all more buttons
document.querySelectorAll('.oajrlxb2.g5ia77u1.qu0x051f.esr5mh6w.e9989ue4.r7d6kgcz.rq0escxv.nhd2j8a9.nc684nl6.p7hjln8o.kvgmc6g5.cxmmr5t8.oygrvhab.hcukyx3x.jb3vyjys.rz4wbd8a.qt6c0cv9.a8nywdso.i1ao9s8h.esuyzwwr.f1sip0of.lzcic4wl.oo9gr5id.gpro0wi8.lrazzd5p[role=button]')

//scroll to bottom
window.scrollTo(0,document.body.scrollHeight);


```
