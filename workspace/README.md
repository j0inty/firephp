
The [PINF JavaScript Loader](https://github.com/pinf/loader-js) is used to provide a development environment and package releases for this project.

**NOTE:** It is assumed you have the _PINF JavaScript Loader_ mapped to the `commonjs` command and are using the `node` platform by default as explained [here](https://github.com/pinf/loader-js/blob/master/docs/Setup.md).

Documentation
=============

    commonjs -v https://github.com/pinf/server-js -v --port 8080 https://github.com/pinf/docs-js ../docs/
    
    open http://localhost:8080/


Tests
=====

**NOTE: At this time these tests will only work on OSX!**

    commonjs -v --script setup ./packages/test

    commonjs -v ../tests/toolchain/firefox_5-firebug_1_7-firephpextension_0_5-zendframework_1_11/
    open http://zendframework.firefox_5-firebug_1_7-firephpextension_0_5-zendframework_1_11.macbook.home.cadorn.net:10089/?test=1

    commonjs -v ../tests/toolchain/firefox_5-firebug_1_7-firephpextension_0_5-firephpcore_0_3/
    open http://firephpcore.firefox_5-firebug_1_7-firephpextension_0_5-firephpcore_0_3.macbook.home.cadorn.net:10089/?test=1

    commonjs -v --script teardown ./packages/test