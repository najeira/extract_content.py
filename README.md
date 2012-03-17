extract_content
===============

Extract content from html.
与えられた html テキストから本文と思わしきテキストを抽出します。


Usage
-----

    from extract_content import ContentExtractor
    extractor = ContentExtractor()
    body, title = extractor.analyse(html)

analyseメソッドに渡す引数は、
PythonのUnicode型、もしくはUTF-8の文字列型。


License
-------

* Copyright: 2012 by najeira <najeira@gmail.com>.
* License: BSD.


Based on
--------

* http://labs.cybozu.co.jp/blog/nakatani/2007/09/web_1.html
* Author:: Nakatani Shuyo
* Copyright:: (c)2007 Cybozu Labs Inc. All rights reserved.
* License:: BSD
