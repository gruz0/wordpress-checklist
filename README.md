# WordPress Checklist

## Inspired by

* [https://github.com/SteadfastCollective/wordpress-going-live-checklist](https://github.com/SteadfastCollective/wordpress-going-live-checklist)
* [https://github.com/douglasanro/wordpress-live-site-checklist](https://github.com/douglasanro/wordpress-live-site-checklist)
* [https://github.com/janikvonrotz/wordpress-checklist](https://github.com/janikvonrotz/wordpress-checklist)
* [https://github.com/douglasanro/wordpress-seo-checklist](https://github.com/douglasanro/wordpress-seo-checklist)
* [https://www.wpbeginner.com/beginners-guide/checklist-11-things-to-do-before-launching-a-wordpress-site/](https://www.wpbeginner.com/beginners-guide/checklist-11-things-to-do-before-launching-a-wordpress-site/)
* [https://capsicummediaworks.com/killer-wordpress-checklist/](https://capsicummediaworks.com/killer-wordpress-checklist/)
* [https://premium.wpmudev.org/blog/ultimate-wordpress-security-checklist/](https://premium.wpmudev.org/blog/ultimate-wordpress-security-checklist/)
* [https://makeawebsitehub.com/wordpress-website-checklist/](https://makeawebsitehub.com/wordpress-website-checklist/)
* [https://wpengine.com/es/wp-content/uploads/2016/03/WP-EBK-PreLaunchCheck-Torque-v05-PUB.pdf](https://wpengine.com/es/wp-content/uploads/2016/03/WP-EBK-PreLaunchCheck-Torque-v05-PUB.pdf)

## Backend

- [ ] Use latest WordPress version
- [ ] Change `admin` username
- [ ] Set correct admin's email
- [ ] Enable two-factor authentication
- [ ] Limit login attempts
- [ ] Delete unused plugins (Hello Dolly, etc.)
- [ ] Delete unused themes
- [ ] Disable pingbacks and trackbacks
- [ ] Delete all Lorem Ipsum posts, pages and comments
- [ ] Delete empty pages without content
- [ ] Update admin's last name and first name
- [ ] Add favicon
- [ ] Enable site to be crawled (Settings -> Reading)
- [ ] Configure the permalinks settings
- [ ] Use SEO friendly urls
- [ ] Disable `WP_DEBUG`
- [ ] Place `define( 'DISALLOW_FILE_EDIT', true )` in the `wp-config.php` file
- [ ] Delete `wp-config-sample.php` file
- [ ] Delete `readme.txt` file
- [ ] Delete `xmlrpc.php` file (https://www.iplocation.net/defend-wordpress-from-ddos)
- [ ] Check 404 page HTTP status
- [ ] Test search page (https://domain.tld/?s=query)
- [ ] Check loading speed
- [ ] Check `robots.txt` file
- [ ] Prevent directory access
- [ ] Delete install & upgrade files (`/wp-admin/install.php`, `/wp-admin/upgrade.php`)
- [ ] Ensure file permissions are correct
- [ ] Hide login error messages
- [ ] Check broken links
- [ ] Add "Privacy Policy" and "Terms and Conditions" pages
- [ ] Ensure you've set WordPress secret authentication keys
- [ ] Check RSS feeds
- [ ] Implement cookie warning

## Plugins

### [Akismet](https://wordpress.org/plugins/akismet/)

- [ ] Get free license

### [WordPress SEO by Yoast](https://wordpress.org/plugins/wordpress-seo/)

- [ ] Generate XML sitemap
  - [ ] Remove tags from sitemap
  - [ ] Don't index image attachment pages
  - [ ] Send sitemap to search engines
- [ ] Provide Open Graph meta tags
  - [ ] [Facebook](https://www.wpbeginner.com/wp-themes/how-to-add-facebook-open-graph-meta-data-in-wordpress-themes/)
  - [ ] [Twitter](https://www.wpbeginner.com/wp-tutorials/how-to-add-twitter-cards-in-wordpress/)
- [ ] Test Facebook sharing
- [ ] Test Twitter sharing
- [ ] Test VK sharing

### [Broken Link Checker](https://wordpress.org/plugins/broken-link-checker/)

### [WP Super Cache](https://wordpress.org/plugins/wp-super-cache/)

### [Contact Form 7](https://wordpress.org/plugins/contact-form-7/)

- [ ] Check all forms are working correctly

### [Mistape](https://wordpress.org/plugins/mistape/)

### [BackWPup](https://wordpress.org/plugins/backwpup/)

- [ ] Create a backup

### [Wordfence Security – Firewall & Malware Scan](https://wordpress.org/plugins/wordfence/)

## Server

- [ ] Install Let's Encrypt certificate
- [ ] [Check SSL certificate health](https://www.ssllabs.com/ssltest/) daily
- [ ] Test redirect from HTTP to HTTPS
- [ ] Test redirect from www to non-www domain
- [ ] Is external monitoring enabled?
- [ ] Are Yandex.Disk backups enabled?
- [ ] Are Amazon backups enabled?

## Services

- [ ] Add [Google Analytics](https://analytics.google.com/)
- [ ] Add [Google Webmasters](https://www.google.com/webmasters/)
- [ ] Add sitemap to Google Webmasters
- [ ] Set up non-www https as the preferred domain
- [ ] Add [Yandex.Metrika](https://metrika.yandex.ru/)
- [ ] Add [Yandex.Webmaster](https://webmaster.yandex.ru/)
- [ ] Add sitemap to Yandex.Webmaster
- [ ] Add [ManageWP](https://managewp.com/)
- [ ] Try subscribing to a newsletter (with MailChimp widget, etc.)
