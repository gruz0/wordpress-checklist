# WordPress Checklist

## Inspired by

* [https://github.com/SteadfastCollective/wordpress-going-live-checklist](https://github.com/SteadfastCollective/wordpress-going-live-checklist)
* [https://github.com/douglasanro/wordpress-live-site-checklist](https://github.com/douglasanro/wordpress-live-site-checklist)
* [https://github.com/janikvonrotz/wordpress-checklist](https://github.com/janikvonrotz/wordpress-checklist)
* [https://github.com/douglasanro/wordpress-seo-checklist](https://github.com/douglasanro/wordpress-seo-checklist)
* [https://www.wpbeginner.com/beginners-guide/checklist-11-things-to-do-before-launching-a-wordpress-site/](https://www.wpbeginner.com/beginners-guide/checklist-11-things-to-do-before-launching-a-wordpress-site/)

## Backend

- [ ] Change `admin` username
- [ ] Set correct admin's email
- [ ] Delete unused plugins (Hello Dolly, etc.)
- [ ] Delete unused themes
- [ ] Disable pingbacks and trackbacks
- [ ] Delete all Lorem Ipsum posts, pages and comments
- [ ] Delete empty pages without content
- [ ] Update admin's last name and first name
- [ ] Add favicon
- [ ] Site indexation enabled?
- [ ] Configure the permalinks settings
- [ ] Disable `WP_DEBUG`
- [ ] Place `define( 'DISALLOW_FILE_EDIT', true )` in the `wp-config.php` file

## Plugins

### Akismet

- [ ] Get free license

### WordPress SEO by Yoast

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

### Broken Link Checker

### WP Super Cache

### Contact Form 7

- [ ] Check all forms are working correctly

### Mistape

### BackWPup

- [ ] Create a backup

## Server

- [ ] Install Let's Encrypt certificate
- [ ] [Check SSL certificate health](https://www.ssllabs.com/ssltest/)
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
