[![Theme Unit Test Data Offline by Rajat Chodhary](screenshot/screenshot.jpg)](http://www.chodhary.com)

My name is [Rajat Chodhary] (http://www.chodhary.com), and I am [WordPress theme developer](http://profiles.wordpress.org/rajatchodhary). I always look around find optimal solution to increase my productivity. If I am not developing wordpress theme then I am busy in review of new WordPress themes (On my own). If you appriciate my effort that follow me, and star this repo

As per [WP-TRT](https://make.wordpress.org/themes/about-old/how-to-join-wptrt/) guidelines, you need to download WordPress [Theme Unit Test Data file](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml) from Theme Unit Test page. But, couple of the time importing fails ( _**most of the time on slow Internet Connection**_ ). So, I have found a way around to make your life simple and less frustrating.

**MAKE SURE THAT YOU'RE DISCONNECT FROM INTERNET ON YOUR DEVELOPMENT MACHINE / UNPLUG INTERNET :D**

Use following steps for hassle free import:

* Start with a fresh and clean [WordPress.org] (https://wordpress.org/download/) installation.
* Download and extract latest version of WP [Theme Unit Test Data] (https://github.com/chodhary/theme-unit-data-test/archive/master.zip) archive from [github] (https://github.com/) repository.
* Download and install [WordPress Importer](https://wordpress.org/plugins/wordpress-importer/) and [Search and Replace](https://wordpress.org/plugins/search-and-replace/) plugins from [Official WordPress Plugin repository](https://wordpress.org/plugins/).
* Log in to your **WordPress Dashboard**. Go to _**Plugins > Add new**_ instead of search use upload to install your downloaded plugin archive.
* When your plugins installed, go to installed plugins and _**activate WordPress Importer**_, and _**Search and Replace**_.
* Go ahead to Select _**Tools > Import**_ from WordPress menu. On Import page, click WordPress, and on leading page **click browse button**. _Guide and select **theme-unit-test-data.xml** from extracted folder._
* On next page, you will be asked to assign user for imported posts and pages. _Don’t do anything and leave as it is_.
* In Import attachments section/division, make sure to check download and import file attachments.
* Once it is done, copy all content **uploads/** folder from extracted archive folder and copy it to your **wp-content/uploads/**
* Now, go to _**Tools > Search & Replace**_. On the page, in Search for input field – search for **wpthemetestdata.wordpress.com** and replace with **localhost**. Make sure that radio button next to **All - search and replace!** is checked.
* Search again for **wpthemetestdata.files.wordpress.com** and replace with **localhost/wp-content/uploads**

**NOTE:** _If you are importing **localhost-theme-test.xml**. Then, all you need is to import **localhost-theme-test.xml** and copy content of **uploads/** to **wp-content/uploads/** . And, you are ready to go._

I am extremely thankful to all you peoples, and [WordPress.com](https://wordpress.com/), [WordPress.org](https://wordpress.org/) and [Automattic team](https://wordpress.org/) for giving such a great tool to **Express Ourselves**.
