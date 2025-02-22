## Personal blog

### Building

Last login: Sat Feb 22 16:54:04 on ttys001
chruby: unknown Ruby: ruby-3.4.1
jereminchan@Mac ~ % ls   
Applications
Desktop
Documents
Downloads
HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Wondershare\Wondershare Filmora
Library
MediaInfo
MediaLibrary
Movies
Music
Pictures
Public
openfx_plugin_cache.xml

jereminchan@Mac ~ % cd Documents

jereminchan@Mac Documents % ls
21			Photos			Thangs
Books			Receipts and Forms	Travel
Budget			Scanned family photos	Uni
EWB			School			Videos
Frands			Sheet Music		Work
Misc			TLG			jeremin-chan.blog
jereminchan@Mac Documents % cd jeremin-chan.blog
jereminchan@Mac jeremin-chan.blog % 

To experiment and test your new blog locally run the following:

```
bundle exec jekyll serve
```

And visit http://127.0.0.1:4000

### Publishing

Add all of the files that you have changed, and then commit and push the changes to GitHub

```
git status
git add .
git commit -m <Insert message>
git push

```