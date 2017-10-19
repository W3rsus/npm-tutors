<style>
body{
font-family:open-sans;
}
code pre{
color:black;
background-color:lightgrey;
font-family:open-sans;
font-size:14px;
border: 1px solid black;
padding: 5px;
}
</style>
<h3>Permissions</h3>
<code><pre>ivan@ivan-master:~/Documents/npm-tutor$ ls -l
total 8
-rw-rw-r-- 1 ivan ivan  41 Oct 20 00:10 hello.js
-rw-rw-r-- 1 ivan ivan 205 Oct 20 00:09 package.json
ivan@ivan-master:~/Documents/npm-tutor$ whoami
ivan
ivan@ivan-master:~/Documents/npm-tutor$ sudo chown ivan hello.js //changes user
ivan@ivan-master:~/Documents/npm-tutor$ npm config get prefix //rootdirectory
/usr/local
</pre></code>
<h3>Install packages</h3>
<code><pre>
ivan@ivan-master:~/Documents/npm-tutor$ npm install lodash
npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN npm-tutor@1.0.0 No description
npm WARN npm-tutor@1.0.0 No repository field.
+ lodash@4.17.4
added 1 package in 1.053s //local package installation
$>npm install //installing packages locally from package.json
</pre></code>
