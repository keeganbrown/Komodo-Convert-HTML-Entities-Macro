This is a quick Komodo IDE/Edit 7.0.* Macro that will convert Unicode characters in a block of selected text into HTML Encoded Entities.

For example, it will take "™" and make it in to: "&amp;trade;".

You probably don't need to download "HTML_Entities.js" to use it.
Just copy the JS from the raw view of the [HTML_Entities.js](raw/master/HTML_Entities.js) file,
create a new macro in Komodo 7.* (probably works just fine in 6.* too), and paste the code into the macro's content.
Make sure to select Javascript as the Language.

All in all, this is a fairly simple macro. Note that UTF encoded Apostrophies will be converted to &amp;quot; because not all browsers support &amp;apos;.

Also, be aware that if you run this macro on existing HTML markup, it will convert brackets ("<",">"), and ampersands ("&") into their HTML Entity equivalent.
