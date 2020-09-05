# FTPiHole.com

A growing, frequently updated, tested and researched set of Pi Hole blocklists, both generic and aimed at various products and services so as to be as flexible as possible - for example we have [a generic mobile list](https://raw.githubusercontent.com/ftpmorph/ftpihole/master/blocklists/smartphone-ads-tracking.txt) but also [one dedicated to Windows 10 "telemetry."](https://raw.githubusercontent.com/ftpmorph/ftpihole/master/blocklists/windows10-spying-erm-i-mean-telemetry-lol.txt)

We also optionally have three separate lists for blocking one or all of: [Facebook](https://raw.githubusercontent.com/ftpmorph/ftpihole/master/blocklists/facebook-full-block.txt), [Instagram](https://raw.githubusercontent.com/ftpmorph/ftpihole/master/blocklists/instagram-full-block.txt), or [WhatsApp](https://raw.githubusercontent.com/ftpmorph/ftpihole/master/blocklists/whatsapp-full-block.txt) entirely on your network or device. For Spotify users without premium we offer [a list to block (most) ads within the Spotify app.](https://raw.githubusercontent.com/ftpmorph/ftpihole/master/blocklists/spotify-ads-tracking.txt) All the Spotify domains are also on the mobile list, which also includes extras such as SMS phishing links to protect users from being scammed. We give the power back to you to decide what to allow on your own network!

Of course we also have the common Facebook tracking scripts added in the general lists. But these are balanced to ensure the services still work. If you don't use FB and don't care if it's simply inaccessible, you can use the block all Facebook list and have it gone from your entire network for good. As well as protecting your privacy this may even encourage guests to speak to each other :) 

With a [strong code of ethics in favour of personal privacy](https://www.ftpihole.com/ethos/) we also like going after bad piracy invadors. For example Xiaomi phones are gaining popularity but they send out crazy amounts of traffic and have ads built into the official MIUI. Yes there are ads built into the OS. If you install an app, a window comes up "checking for viruses" and there is a banner ad at the bottom. This is insane so I have [a list specifically for blocking all MIUI services.](https://raw.githubusercontent.com/ftpmorph/ftpihole/master/blocklists/xiaomi-ads-tracking.txt)

If you have suggestions for appropriate additions to any of the lists or you have spotted any false positives please let us know here through GitHub. We recommend using pull requests for both, but raising an issue works too. We also strongly suggest giving a reason for your request. For example simply giving a domain and saying "this shouldn't be there" without an explanation or further detail is likely to be ignored.

Lists are hosted here on GitHub and in our S3 bucket. When adding the lists to your Pi Hole, either source will work. The two should be always synced perfectly, so the choice is yours.

Finally, if you get the reference in the name you are my kind of human.

Fuck ads, fuck tracking, fuck privacy invasion...

## https://www.ftpihole.com/

**P.S. You can also keep up with [the FTPiHole project on Telegram.](https://telegram.me/FTPiHole) We are [also on Twitter.](https://twitter.com/FTPiHole)**
