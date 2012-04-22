OpenUDID.Web
============

cross-browser per device unique identifier

<h2>What is OpenUDID.Web</h2>

<h3>OpenUDID.Web is a new cross-domain unique idendifier solution.</h3>

during the research on OpenUDID.Net (https://github.com/jasonlamkk/OpenUDID.Net) , we found a new way to store an idendifier which is accessible across browsers. 

it is much more persistent than traditional browser cookies and it keep the same idendifier per user-device, across browser and domain. 

it is now possible for service provider in different domains tso share data for same user, and discover the in-depth web behavior for a single user.

even there are a few browsers operating at the same time, all browsering activities can be merged for centralized behavioral analysis.


<h2>How it works</h2>

in order to keep the identifier globally the same for all domains, we have hosted a central identifier generator, and feed the UDID to your website

see the html example for detailed usage (some AJAX experience is required )