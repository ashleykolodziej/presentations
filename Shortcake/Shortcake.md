<!-- background: #468499-->
<!-- color: #fff -->
<!-- font: frutiger -->

# **Nom Nom Shortcake**
Ashley Kolodziej, Boston University Interactive Design
[@ashleykolodziej](https://twitter.com/ashleykolodziej)

***

<!-- background: #468499-->
<!-- color: #fff -->
# **Shortcake!**
* [wp-shortcake/shortcake (0.6.2)](https://github.com/wp-shortcake/shortcake)
* [bu-ist/shortcake (0.4.0)](https://github.com/wp-shortcake/shortcake)
* [r-com/inc/shortcodes-ui.php](https://github.com/bu-ist/r-com/blob/master/inc/shortcodes-ui.php)

***

<!-- background: #468499-->
<!-- color: #fff -->
# **Story time**
* COM design needs to be SUPER flexible
* Metaboxes don't make sense
* HTML and shortcodes are easy to mess up and hard to remember

***

<!-- background: #468499-->
<!-- color: #fff -->
# **How do we fix that?**
* Custom Wordpress editor buttons?
* Custom style select?
* Other???

***

<!-- background: #468499-->
<!-- color: #fff -->
# **What is Shortcake?**
Shortcake gives you an easy way to specify a super friendly UI for adding a shortcode to a post.

***

<!-- background: #468499-->
<!-- color: #fff -->
# **Why Shortcake?**
* It's easier for users
* It uses stuff we already have in place
* It's a [candidate for integration into the Wordpress Core](https://make.wordpress.org/core/tag/shortcode-ui/)

***

<!-- background: #468499-->
<!-- color: #fff -->
# **[bu_list_child_pages] - before**
* Remember it exists
* Find / read [documentation](http://www.bu.edu/tech/services/comm/websites/www/wordpress/management/shortcodes/#children)
* Get parent ID from URL
* Copy/paste and edit code to include the ID

***

<!-- background: #468499-->
<!-- color: #fff -->
# **[bu_list_child_pages] - after**
* Add Media > Insert Post Element > Page List
* Pick the page and check a checkbox

***

<!-- background: #468499-->
<!-- color: #fff -->
# **How much work is it?**

***

<!-- background: #468499-->
<!-- color: #fff -->
# **Dang, that was easy**
*(styles not included)*

***

<!-- background: #468499-->
<!-- color: #fff -->
# **How about something more difficult?**

***

<!-- background: #468499-->
<!-- color: #fff -->
# **LIKE [COURSE FEEDS](http://www.bu.edu/tech/services/comm/websites/www/wordpress/how-to/embed-course-feeds/)**
omg numbers and acronyms and codes and things to think about EVERYWHERE

***

# **Course Feeds UI - before**
<!-- background: #468499-->
<!-- color: #fff -->
[bu-course-feed include="CASPY" exclude="CASPY105" period="2013FALL" use_bulletin="Y" blank_titles="N"]

***

# **Course Feeds UI - after**
<!-- background: #468499-->
<!-- color: #fff -->

***

# **Let's try to break things**
<!-- background: #468499-->
<!-- color: #fff -->
Shortcodes still work without UI ✔

Shortcodes can still be edited in text editor ✔

Shortcodes still work if the plugin is disabled ✔

***

# **Demo: COM**
<!-- background: #468499-->
<!-- color: #fff -->
[COM test site](http://nm.cms-devl.bu.edu/com/)

***

# **Gotchas**
<!-- background: #468499-->
<!-- color: #fff -->
* Still a plugin in progress
* Still coupled with Media Library
* Only inner_content supports full HTML
* inner_content must be at top

***
<!-- font: frutiger -->

# **What's available to you**
<!-- background: #468499-->
<!-- color: #fff -->
* Post Select / Select
* Inner Content (HTML)
* Textboxes
* Checkboxes
* Radio / Multiple Checkboxes
* and [more!](https://github.com/wp-shortcake/shortcake/wiki/Registering-Shortcode-UI)