# WordPress Checklist

Simple todo list for new WordPress websites.


## WordPress installation

- [ ] Install Wordpess
	- [ ] Change admin username
	- [ ] Store password
	- [ ] Set mail: hostmaster@example.com
- [ ] Add template and delete unused templates
- [ ] Disable pingbacks and trackbacks (uncheck Allow link notifications from other blogs)
- [ ] Update Perma Link Structure to day and anme: /%year%/%monthnum%/%day%/%postname%/
- [ ] Update site info
	- [ ] title
	- [ ] description
- [ ] Update administrator
	- [ ] First and lastname
	- [ ] Disable visual editor 
- [ ] Add customer user
	- [ ] username: firstnamelastname
	- [ ] login@example.com
- [ ] Delete default content
	- [ ] page
	- [ ] post
	- [ ] comments
	- [ ] default plugins
- [ ] Add example content (see below)

## Plugins

- [ ] Install and configure plugins
	- [ ] [SyntaxHighlighter Evolved](http://wordpress.org/plugins/syntaxhighlighter/ )
	- [ ] [Disqus Comment System](http://wordpress.org/plugins/disqus-comment-system/ )
	 	- [ ] Enable disqus comments
	 	- [ ] Register the website
	 	- [ ] Enable guest commenting on disqus admin page
	- [ ] [BackUpWordPress](http://wordpress.org/plugins/backupwordpress/ )
	 	- [ ] Daily 7 times at 9 o'clock
	 	- [ ] Weekly 2 times at 10 o'clock
	- [ ] [WP-Piwik](http://wordpress.org/plugins/wp-piwik/ )
	 	- [ ] Add Piwik url
	 	- [ ] Add tracking code
	- [ ] [Jetpack by WordPress.com](http://wordpress.org/plugins/jetpack/ )
	 	- [ ] Login with Wordpress.com Account
	 	- [ ] Add Markdown support
	 	- [ ] Enable Website-Symbol and add favicon
	 	- [ ] Enable Monitor
	 	- [ ] Enable Manage
	- [ ] [Image Captcha](https://wordpress.org/plugins/image-captcha/screenshots/ )
	 	- [ ] Enable for add comments
	- [ ] [oEmbed Gist](http://wordpress.org/plugins/oembed-gist/ )
	- [ ] [Sugar Events Calendar Lite](http://wordpress.org/plugins/sugar-calendar-lite/ )
	- [ ] [oEmbed Instagram](http://wordpress.org/plugins/oembed-instagram/ )
	- [ ] [Enable Media Replace](https://wordpress.org/plugins/enable-media-replace/ )
	- [ ] [Broken Link Checker](https://wordpress.org/plugins/broken-link-checker/)
- [ ] Install and configure optional plugins
	- [ ] [Widgets on Pages](https://wordpress.org/plugins/widgets-on-pages/)
	- [ ] [qTranslate Plus](https://wordpress.org/plugins/qtranslate-xp/)

## Example content

```
# This is sample content 
 
Lorem ipsum dolor sit amet, mel no prima tation adolescens, at has numquam elaboraret, duo ex detraxit sensibus. Audire albucius corrumpit et per, ea mel nonumy audiam verterem. Nam ad illud movet causae, mel an nostrud efficiantur. No vis tota adolescens adipiscing. Sint eloquentiam reprehendunt quo ut, cu quo feugiat fierent gloriatur. 
 
## Instagram Post 
 
http://instagram.com/p/vNalF-BKk6/ 
 
http://instagram.com/p/yohLKDRAxi/ 
 
## GitHub Gist code 
https://gist.github.com/janikvonrotz/11531335 
 
## Syntax Highlighter 
[code lang="js"] 
/** 
 * IEMobile responsive fix 
 */ 
 
if (navigator.userAgent.match(/IEMobile\/10\.0/)) { 
    var msViewportStyle = document.createElement("style"); 
    msViewportStyle.appendChild( 
        document.createTextNode( 
            "@-ms-viewport{width:auto!important}" 
        ) 
    ); 
    document.getElementsByTagName("head")[0]. 
        appendChild(msViewportStyle); 
} 
[/code] 
```
