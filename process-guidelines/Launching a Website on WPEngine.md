
# Launching a Website on WPEngine

## Pre-launch
- [ ] **Update WordPress core and plugins**
- [ ] **Ask WPEngine to disable xmlrp.php requests**
- [ ] **Add all Redirections**
- [ ] **Run broken link checker:** Search for broken links ([Broken Link Checker](https://www.brokenlinkcheck.com/broken-links.php)) and correct ad needed
- [ ] **Add Domain to WPEngine Portal:** 
- [ ] **Add Google Analytics Scripts to theme:** (If necessary, get access to the client's account as contributors ([Google Analytics Help](https://support.google.com/analytics/answer/1009702?hl=en))
- [ ] **Backup the site** (create a fresh backup on WPE called "Pre-launch")

### SEO Tasks
- [ ] **Verify XML Sitemap**
- [ ] **Create Robots.txt via Yoast**

## Launch
- [ ] **Green light:** Obtain client’s confirmation to launch the site
- [ ] **Search and replace URLs:** Use Better Search & Replace
- [ ] **Update WP Admin:**
  - [ ] Change URL on General Settings (Site URL & Home URL)
- [ ] **Uncheck Discourage Search Engines:** Make sure "Discourage Search Engines" is checked until after launch
- [ ] **Update WPEngine Portal:**
  - [ ] Set the primary domain
  - [ ] Redirect www and .wpengine domains to the main domain
- [ ] **Point the domain:** Update DNS from the client’s Domain/Hosting provider
- [ ] **Wait for propagation** ([Check DNS Propagation](https://www.whatsmydns.net/))
- [ ] **Enable SSL:** Once propagation is complete

## Post Launch
- [ ] **Licenses:** Reinstate if needed (WPML, ACF, etc.)
- [ ] **Redirects / Permalinks:** Test to ensure they are working correctly
- [ ] **Google Analytics:** Confirm it is working
- [ ] **Forms:** Check primary email address is valid and form submissions are working as expected
- [ ] **Caches:** Clear all caches (WPEngine, etc.)
- [ ] **SSL:** Ensure all URLs are HTTPS
- [ ] **GTMetrix:** Run and save a performance report
- [ ] **W3 Validator:** Check for HTML validation issues
