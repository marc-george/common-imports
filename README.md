common-import-elements
===============

Webcomponent for importing common libraries, if more than one component uses it.
This would eliminate importing javascript file for that particular library everytime, in different
components under same project.

-----------

How to use
===========

```
bower install --save https://github.build.ge.com/DET-Software/common-imports.git#0.0.3
```

For lodash
```
<link rel="import" href="/bower_components/common-imports/lodash.html">
```
-----------

For moment
```
<link rel="import" href="/bower_components/common-imports/moment.html">
```
-----------

For stomp
```
<link rel="import" href="/bower_components/common-imports/stomp.html">
```
-----------

For sockjs
```
<link rel="import" href="/bower_components/common-imports/sockjs.html">
```
-----------

For fuse.js [fuzzy search](https://github.com/krisk/Fuse)
```
<link rel="import" href="../../bower_components/common-imports/fuse.html">
```

How to add more libraries
===========

Currently only lodash and moment libraries has been added to this particular repo,
but if your project needs any other libraries which are used across different components
create a PR on the repo to add that particular dependency.