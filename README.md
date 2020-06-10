# The Master .htaccess

Security-enhancing .htaccess (Apache), web.config (IIS) and NginX configuration files for Joomla!

## Customization required

The files in this repository are designed as a template for you to create the .htaccess, web.config or NginX configuration file for your Joomla 3.x and 4.x sites. Their goal is to increase the security and performance of your site.

You cannot simply drop a file into your site and call it a day. Each site and server configuration is a unique environment. These files need customization. You need to go through the entire file and understand what it's doing - there are comments. At the very least you need to replace `example.com`, `www.example.com`, `example\.com` and `www\.example\.com` with your real domain name.

Some sections may cause problems with legitimate requests. You are ultimately responsible for disabling them or writing exception rules for your requests. Most notably, the advanced server protection section may cause issues with core features and third party software. You must add exceptions for them manually.

On the same note, some sections - depending on your server configuration - may cause your site to throw 500 Internal Server Error. The only way to figure out which one is causing it is trial and error.

## No support

Please bear in mind that I do not offer any kind of support for these files. If it breaks you get to keep both pieces.

## Do you want an easier way to customize these files?

Customizing the server configuration files can be done with a few clicks using [Admin Tools Professional](http://www.akeebabackup.com/software/admin-tools.html). You also get a lot more security enhancing features for your Joomla site. Moreover, it comes with support.

Purchasing a subscription to any of our software helps me and the other three people working with me to make a living. This allows us to work on Free and Open Source Software, do research and come up with things like this repository here.

## Why is this repository called Master .htaccess?

When I started working on it back in 2009 it was only a .htaccess file I was using on all of my sites. It was my "master" .htaccess file. So I created a repository for it.

In the following years I adapted it for NginX and IIS 7+.