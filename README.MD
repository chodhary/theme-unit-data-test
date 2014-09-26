My name is [Rajat Chodhary](http://www.chodhary.com), and I am WordPress theme developer. I always look around find optimal solution to increase my productivity. Most of the time I review WordPress themes on my own.

As per [WP-TRT](https://make.wordpress.org/themes/about-old/how-to-join-wptrt/)guidelines, you need to download WordPress [Theme Unit Test Data file](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml)from Theme Unit Test page. But, couple of the time importing fails ( _**most of the time on slow Internet Connection**_ ). So, I have found a way around to make your life simple and less frustrating.

Use following steps for hassle free import:

* Start with a fresh and clean WordPress installation.
* Download and extract latest version of WP Theme Unit Test Data archive from github repository.
* Download and install WordPress Importer and Search and Replace plugins from WordPress Plugin repository.
* Log in to your WordPress Dashboard. Go to Plugins > Add new instead of search use upload to install your downloaded plugin archive.
* When your plugins installed, go to installed plugins and active WordPress Importer and Search and Replace.
* Go ahead to Select Tools > Import from WordPress menu. On Import page, click WordPress, and on leading page click browse button. Guide and select theme-unit-test-data.xml from extracted folder.
* On next page, you will be asked to assign user for imported posts and pages. Don’t do anything and leave as it is.
* In Import attachments section/division, make sure to check download and import file attachments.
* Once it is done, copy all content uploads/ folder from extracted archive folder and copy it to your wp-content/uploads/
* Now, go to Tools > Search & Replace. On the page, in Search for input field – search for wpthemetestdata.wordpress.com and replace with localhost
* Search again for wpthemetestdata.files.wordpress.com and replace with localhost/wp-content/uploads

NOTE: If you are importing localhost-theme-test.xml. Then, all you need is to import localhost-theme-test.xml and copy content of uploads/ to wp-content/uploads/ . And, you are ready to go.

I am extremely thankful to all you peoples, and WordPress and Automattic team for giving such a great to to express yourself.


My name is Rajat Chodhary, and I am WordPress theme developer. I always look around find optimal solution to increase my productivity. Most of the time I review WordPress themes on my own.

As per <a title="How to Join WordPress Theme Review Team" href="" target="_blank">WP-TRT</a> guidelines, you need to download <a title="Use Right click and save as ..." href="https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml">WP Theme Unit Test Data file</a> from Theme Unit Test page. But, couple of the time importing fails ( most of the time on slow Internet Connection ). So, I have found a way around to make your life simple and less frustrating.

Use following steps for hassle free import:
<ol>
	<li>Start with a fresh and clean WordPress installation.</li>
	<li>Download and extract latest version of WP Theme Unit Test Data archive from github repository.</li>
	<li>Download and install <a title="Use Right click and save as ..." href="https://downloads.wordpress.org/plugin/wordpress-importer/">WordPress Importer</a> and <a title="Use Right click and save as ..." href="https://downloads.wordpress.org/plugin/search-and-replace/">Search and Replace</a> plugins from <a title="Official WordPress Plugins Repository" href="https://downloads.wordpress.org/plugin/">WordPress Plugin repository</a>.</li>
	<li>Log in to your <strong>WordPress Dashboard.</strong> Go to <em><strong>Plugins &gt; Add</strong></em> new instead of <em>search</em> use <em>upload</em> to install your downloaded plugin archive.</li>
	<li>When your plugins installed, go to installed plugins and active WordPress Importer and Search and Replace.</li>
	<li>Fo ahead to Select <em><strong>Tools &gt; Import</strong></em> from <strong>WordPress</strong> menu. On Import page, click WordPress, and on leading page <em><strong>click browse button</strong></em>. <span style="text-decoration: underline;"><em>Guide and select theme-unit-test-data.xml from extracted folder</em></span>.</li>
	<li>On next page, you will be asked to assign user for imported posts and pages. Don't do anything and leave as it is.</li>
	<li>In Import attachments section/division, make sure to check <span style="text-decoration: underline;"><em>download and import file attachments</em></span>.</li>
	<li>Once it is done, copy all content <strong>uploads/</strong> folder from extracted archive folder and copy it to your <em><strong>wp-content/uploads/</strong></em></li>
	<li>Now, go to <em><strong>Tools &gt; Search &amp; Replace</strong></em>. On the page, in <em><strong>Search</strong></em><strong> for</strong> input field - search for <strong>wpthemetestdata.wordpress.com</strong> and replace with <strong>localhost</strong></li>
	<li>Search again for <strong>wpthemetestdata.files.wordpress.com</strong> and replace with <strong>localhost/wp-content/uploads</strong></li>
</ol>
<span style="text-decoration: underline;"><strong>NOTE:</strong></span> If you are importing localhost-theme-test.xml. Then, all you need is to import localhost-theme-test.xml and copy content of uploads/ to wp-content/uploads/ . And, you are ready to go.

I am extremely thankful to all you peoples, and WordPress and Automattic team for giving such a great to to <em><strong>express yourself</strong></em>.
