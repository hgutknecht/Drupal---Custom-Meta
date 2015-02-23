Custom-Meta
====================
## Custom Meta module for Drupal 6 and 7

[Project page on d.o](https://www.drupal.org/project/custom_meta)

While Nodewords (D6) and Metatags (D7) work well for adding things like Abstract, Description, Keywords, Robots, Copyright and even OpenGraph meta tags to your content. We continually found ourselves backed into a situation where we would have to release a tpl.php update or write a custom module to inject custom meta elements onto our platform.

A good example is the Smart App Banner from Apple. We received the info for early adoption but had to deploy code to implement. After adding one too many contrib modules or writing one too many custom modules to add small or bulk custom meta tags to our system, we came up with the idea for custom meta.

The module allows you to define and manage custom meta tags. Simply select the Meta attribute (property, name, http-equiv) and set the value and content value in the format and the module will add your meta tags to all non-admin content for your site.

I'd be happy to iterate on this and add additional functionality just leave a note in the issue queue if you have a feature request.

Token Support

As of 7.x-1.4, Custom Meta supports token replacement. Enable the token module and select "Browse available tokens" on the administration page.
