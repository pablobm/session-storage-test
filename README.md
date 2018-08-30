# Session storage test

A simple demonstration of use of `sessionStorage`. You can host it locally
with a simple web server (eg: `python -mSimpleHTTPServer`) or visit it
at https://session-storage-test.herokuapp.com.

The purpose is to show how the counter will stay independent across tabs.
You can refresh each tab, or click on the link, and each tab will keep
its own counter, without affecting the others.

As I write these lines, `sessionStorage` appears to be well supported
across different browsers: https://caniuse.com/#search=sessionstorage
