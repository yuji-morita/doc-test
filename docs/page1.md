# codetabs


```java tab=
AdView adView = new AdView(this);
adView.setAdSize(AdSize.BANNER);
adView.setAdUnitId("ca-app-pub-3940256099942544/6300978111");
// TODO: Add adView to your view hierarchy.
```

```kotlin tab=
val adView = AdView(this)
adView.adSize = AdSize.BANNER
adView.adUnitId = "ca-app-pub-3940256099942544/6300978111"
// TODO: Add adView to your view hierarchy.
```


aaa


```diff tab= 
Index: grunt.js
===================================================================
--- grunt.js    (revision 31200)
+++ grunt.js    (working copy)
@@ -12,6 +12,7 @@

 module.exports = function (grunt) {

+  console.log('hello world');
   // Project configuration.
   grunt.initConfig({
     lint: {
@@ -19,10 +20,6 @@
         'packages/services.web/{!(test)/**/,}*.js',
         'packages/error/**/*.js'
       ],
-      scripts: [
-        'grunt.js',
-        'db/**/*.js'
-      ],
       browser: [
         'packages/web/server.js',
         'packages/web/server/**/*.js',
```

```Kotlin tab=
val adView = AdView(this)
adView.adSize = AdSize.BANNER
adView.adUnitId = "ca-app-pub-3940256099942544/6300978111"
// TODO: Add adView to your view hierarchy.
```
## codetab1

## codetab2
