# agario-client
Old agario web-client, can be used for something like offline agar.io, school agar.io etc.

Agar.io webclient, was originally made by https://github.com/Eureka22/ but is no longer avaliable.
This contains a edited version for a friend, removed ads & some other useless features and added some features too.

# How to setup

Extract files to a webhost.
Edit index.html and find:

```html
<title>Sharp.io</title>
```

Change sharp.io to the name you like (optional).
Find:

```html
<script>
function connectToServer() {
	connect("ws://changetoogarip");
}
</script>
```

Change "changetoogarip" to the ipaddress of your Ogar server.

Find:

```html
<div class="form-group">
    <div style="float: left; margin-left: 20px;"><h2>Sharp.io</h2></div>
```

Change Sharp.io to a name you like (optional)

#Contact
Reddit: /u/dataloss
Site: dataloss.me
Email: contact@dataloss.me
