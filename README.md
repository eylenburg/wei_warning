# Web Environment Integrity browser check & warning banner  
If a visitor is using a WEI-enabled browser (e.g. Chrome, Edge, Chromium) they will get a full-page warning that their browser is harmful, with a link to the [FSF's explanation of why WEI is bad](https://www.fsf.org/blogs/community/web-environment-integrity-is-an-all-out-attack-on-the-free-internet) and download links to various browsers that oppose WEI (currently: Firefox, Safari, Brave, Pale Moon, GNOME Web).

The user has to close the warning banner to view the website content.

__How to use:__  
Just copy the content of _wei_check_ and paste it into your website's source code.

__Possible enhancements:__
- [ ] Easier wary of embedding, e.g. by linking an external resource rather than having to paste the code to each webpage.
- [ ] Check directly for WEI API functionality rather than indirectly via the the user agent
- [ ] Set a cookie to dismiss the banner for a certain amount of time, so that you can have the banner on every single webpage without annoying your visitors too much.
- [ ] Recommended browsers should depend the visitor's OS (e.g. don't mention Safari on non-Apple devices).
- [ ] Concise and easy to understand explanation why WEI is bad and you should feel bad, rather than just linking to the FSF.
- [ ] Make it look more professional, like one of these "you need to deactivate your adblocker" warnings.

Pull Requests are very welcome! I have no tech background and I'm not quite sure how to implement these enhancements.
