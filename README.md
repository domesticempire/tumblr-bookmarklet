# tumblr-bookmarklet
Speed up slow browsing on tumblr.

Some tumblr pages take forever to load thanks to yahoo's over zealous scripting. Frustratingly, some sites won't load for me at all. The easy way around this is to browse the author's Archive. Unfortunately some themes don't include a link to the Archive.

So I created this bookmarklet, which works for all tumblr sites. 

javascript:%20window.location%20=%20window.location.protocol%20+%20'//'%20+%20window.location.hostname%20+%20'/archive';
