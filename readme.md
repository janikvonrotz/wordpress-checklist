# WordPress Checklist

Simple todo list for new WordPress websites.


## WordPress installation

- [ ] Install Wordpess
	- [ ] Change admin username
	- [ ] Save password
	- [ ] Mail: hostmaster@example.com
- [ ] Add template and delete unused templates
- [ ] Disable pingbacks and trackbacks (uncheck Allow link notifications from other blogs)
- [ ] Update Perma Link Structure to day and anme: /%year%/%monthnum%/%day%/%postname%/
- [ ] Update site info
	- [ ] title
	- [ ] description
- [ ] Update Administrator
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
	- [ ] SyntaxHighlighter Evolved
	- [ ] Disqus Comment System
	 	- [ ] Enable disqus comments
	 	- [ ] Register the website
	 	- [ ] Enable guest commenting on disqus admin page
	- [ ] BackUpWordPress
	 	- [ ] Daily 7 times at 9 o'clock
	 	- [ ] Weekly 2 times at 10 o'clock
	- [ ] WP-Piwik
	 	- [ ] Add Piwik url
	 	- [ ] Add Tracking code
	- [ ] Jetpack by WordPress.com
	 	- [ ] Login with Wordpress.com Account
	 	- [ ] Add Markdown support
	 	- [ ] Enable Website-Symbol and add favicon
	 	- [ ] Enable Monitor
	 	- [ ] Enable Manage
	- [ ] Image Captcha
	 	- [ ] Enable for add comments
	- [ ] oEmbed Instagram
	- [ ] Sugar Events Calendar Lite
	- [ ] Protect
	- [ ] oEmbed Gist
	- [ ] Enable Media Replace
- [ ] Install and configure optional plugins

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
