# Adjacent Web Development


### Access

* Contact Yen to get access to the Wordpress backend, and get *super-admin* privileges
* Ensure you have been added as a member to the Github organization (https://github.com/Adjacent-ITP)
* Ask Yen to create a new site for the issue. (Or if you are very comfortable with WP already, do this yourself, following the existing pattern of sites)
* Add editors to the issue (https://itp.nyu.edu/adjacent/issue-7/wp-admin/users.php?page=ldap_admin_functions.php) and give them Author or Editor privileges.

### WP Privileges

_"With great power comes great responsibility"_

* Super admin privileges are required to be able to upload a theme, add users, plugins etc -- **they can also be used to make a complete mess of WP and break everything, so be cautious**
* Only designers, developers and managing editors should be given super-admin status. (This might upset Yen, but it might be a pain if all these people do not have privileges for reasons below.)
* If a non-super-admin edits an article, any `iframe`s in the article are likely to get deleted. It is best to have editors simply put down the link for the `iframe` and somebody with super-admin status can insert the HTML once editors are done with their work.

### WP Theme Development

* If you are not familiar with WP, this would be a good time to either find someone who is, or read up about WP theme development - it is a little peculiar
* Use git and create a repo for the theme code in the GitHub organization
* If you use an existing theme as a starting point, ensure you change the theme's name
* If you create a child theme, ensure that all assets are included within your child theme
* You will need to use the *Advanced Custom Fields* (ACF) plugin (already installed) to create additional fields for the articles
* Some fields might require authors to insert HTML, where you would provide them with the correct formatting needed
* While you could use react or a similar front-end framework, it is not recommended as it will make maintenance difficult for Yen.


### Workflow and Deployment

* Create a local instance of WP and develop the theme with that
* Install ACF locally (https://www.advancedcustomfields.com/)
* Use WP's DB export feature to periodically get the data editors are putting into the live instance of WP
* Use ACF's json sync feature to sync up fields (https://www.advancedcustomfields.com/resources/local-json/)
* After committing changes, create a zip file of the theme code, and use the WP admin interface to upload the theme. (https://itp.nyu.edu/adjacent/wp-admin/network/themes.php)
* For subsequent updates, you will first need to *delete* the old version of the theme and then re-upload it.
* This is far from the ideal deployment process, but it is what it is.
* Once the Issue is completed, be sure to add a new post for it on the 'Landing Page' website. (https://itp.nyu.edu/adjacent/wp-admin/edit.php)

### Site requirements

Here is a list of required elements for the site, based on previous years

* There are generally 3 templates:

  * Home (listing of all articles)
  * About (Blurb about Adjacent, and blurb about the issue)
  * Article template - below...

* An *article* should have the following fields:

  * Title
  * Author
  * Artwork / Illustrator Name
  * Blurb / Description
  * Author Bio / Blurb
  * Featured image / iframe

* Design Elements

  *Styling should be specified for the following elements on the article page:*

  * Footnotes (+ superscript to link to footnotes)
  * Quotes (+ quote author)
  * At least 3 levels of headings
  * Links
  * Paragraphs, along with italic and bold styling
  * Image captions
  * Styling for the the article fields

  *Additional elements:*

  * Menu styling
  * Mobile styling
  * Footer with links to accessibility page and newsletter link

* SEO

  * Include meta tags for the site, and article-specific meta tags for the pages. Where possible, include the featured image for the article in the meta tags. You can see a preview of the shared format here https://metatags.io/
  * In general, this can be improved for past issues and the landing page too.

* Accessiblity

  * This has fallen through the cracks for the past few issues. The Web Accessibility team at ITP should be consulted for best practices and tools that can be used to ensure the site meets NYU's accessibility requirements / WCAG 2.0 standards.

### Other notes

* Editors should be given formatting for footnotes and other HMTL elements they need to input
* They should also be given instructions about headers, and specific header should be used for each level
* Editors should ensure that links are set to open in a new tab
* Update this document with changes as they occur



### SOS

* Reach out to Vince (vinceshao1992@gmail.com) or Sukanya (sukanya.aneja@gmail.com) if nobody else can answer your development-related questions.
