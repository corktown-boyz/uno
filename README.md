# Our Server
+ dns: ec2-54-84-59-247.compute-1.amazonaws.com
+ ip: 54.84.59.247
+ web: https://54.84.59.247
+ web server root folder: `/usr/share/nginx/www/`
+ html file for our website: `/usr/share/nginx/www/index.html`
+ editor we use to edit our web page: `nano`

## Things We Should Know Pt 1

1. If I am logged on to our server, what command or commands do I use to edit our web page?
2. If I edit the `index.html` file in nano, why do I have to `^O` (WriteOut) the changes before the web page shows my edits?
3. Look at the output from the following command:
```
ubuntu@ip-172-31-40-200:~$ ls -lA /usr/share/nginx/www/
total 160
-rw-r--r-- 1 root   root      383 Jul  7  2006 50x.html
-rwxrw-r-- 1 ubuntu doans     236 Mar 26 05:54 index.html
```

   + What user owns the `index.html` file?
   + What group owns the `index.html` file?
   + Explain why you have the necessary permission to edit `index.html`
   




