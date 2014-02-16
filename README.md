Woocommerce Multistep Checkout
==============================

Author: Fabian Wolf (http://usability-idealist.de/)

A prototype for a multistep checkout for WooCommerce, created as a WordPress plugin.

Analysis result
===============

My result of the analysis of existing (premium) themes so far:

- most themes either replace the checkout template with their own
- or add a switch / if clause (eg. using an option / theme setting ) to optionally use a multistep template

Those multistep templates reuse all already existing templates, in some cases there are also some markup changes to easily include these templates via the regular WooCommerce action hooks.

Goals
=====

First things first, so for the prototype I'd like to just quick'n'dirty(ly) slap together what I found out so far (see above), adapt it slightly, so that the latest changes of the current WooCommerce version is reflected in it, and then get it all working properly. So it's gonna mostly be a static set up.

After that, the next goal would be to rework all of this into something more liquid, action hook-based, so that one could simply install the plugin, create a template directory for this plugin inside the current theme directory (maybe as a subdirectory to checkout, eg. checkout/multistep/), drop multistep templates adapted to your own tastes and preferences into it - and off we go with a proper and nicely multistep checkout option ;)

