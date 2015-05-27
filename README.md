Widget Sandbox
==============

This is a simple repo for experimenting with Shopbeam widget, lightbox, cart, 
and checkout apps.

How To Use This Repo
--------------------

###OSX/Linux:
_NOTE: These instructions assume `git` and `python` are installed. 
You can verify with `which git` and `which python` respectively._

In your teminal, change directory to where you would like to download and 
work with the repository.

######Example
```bash
cd ~/projects
```

Clone and `cd` into this repo:

```bash
git clone git@github.com:shopbeam/widget-sandbox.git
cd ./widget-sandbox
```

Serve the sandbox files:
```bash
python -m SimpleHTTPServer
```

This process will block your terminal, so if you need to do other  things 
in the terminal, you'll need to open a new tab. To shut the server down 
press `ctrl+c`. You do not need to restart the server after making changes 
to files; you only have to refresh the browser.

By default this server binds to port `8000`. You can optionally specify  a 
different port as follows `python -m SimpleHTTPServer -p <port>`, replacing 
`<port>` with the desired/available port.

Now you can point your browser to [http://localhost:8000](http://localhost:8000) 
(again, optionally substituting `8000` for an alternate port).
