# bashttpd
Simple Bash based web server, fork of https://github.com/avleen/bashttpd by Avleen.  The only difference in this fork is for navigating multi-level directory structures where tree is used.  Usefulness is limited to when entry is made by the browser's first page rendering into the root-most directory where navigation will be desired, because the browser's "back" button is used for traversing root-ward.

To run it just fire up 
```shell
$> bashttpd -s -m 
```
Then visit http://your.ip.addr:8080/ in your favorite web browser! 

You can browse the filesystem and with this version you can also view pictures and stream multimedia content from the remote host. 
