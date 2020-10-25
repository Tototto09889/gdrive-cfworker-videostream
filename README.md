# gdrive-cfworker-videostream
A cloudflare worker that provides direct links to files on google drive. 



<h3>Setup</h3>
<b>Follow the instructions on this page for an easy setup</b>
https://gdrive-cfworker.glitch.me/

<h3>Usage</h3>
After you create the cloudflare worker, take note of its url which looks like https://x.y.workers.dev:

The requests you can make to this url are:
<ol>
  <li>x.y.workers.dev/search/searchterm     --> this will return the search results on an html page </li>
  <li>x.y.workers.dev/searchjson/searchterm --> this will return the search results in json format </li>
  </ol>




Credits go to https://github.com/maple3142/GDIndex for some parts of the code
