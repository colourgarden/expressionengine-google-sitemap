ExpressionEngine Google XML Sitemap template
====

Usage
----

1. Create a new template in EE with type XML
2. Copy the code from googlesitemap.xml into your new template
3. Add/delete/change the code blocks to suit your site structure
4. Submit the template URL to Google Webmaster Tools.

There are three blocks used to generate the sitemap XML.

- Homepage. The 'entry_id' should be changed to that of your homepage (this isn't included in the pages block as URL needs to be hardcoded to avoid '/home' being appended)
- Pages. Loops the pages of your site. Separate each entry ID with a pipe in the 'entry_id' attribute
- Channels. Loops a specific channel. In the example, this is the 'products' channel which creates an XML entry for each product in a shop. The 'channel' attribute can be updated to any relevant channel you wish to be spidered.