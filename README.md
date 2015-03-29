# Mintr

Mintr is a simple unix monitoring tool.  It intentially avoids authentication, and thus does not monitor or display any private information, nor does it allow any actions to be taken from the web interface.

It, quite simply, shows a few graphs that should help indicate the current status of your server, as well as over the past hour.

Currently it shows

* Memory usage
* CPU Usage
* Network activity
* Process memory usage & CPU usage

# Installation

```
npm install -g mintr
```

You can run `mintr` in a screen/tmux, add it to your system's startup, or anything else you please.