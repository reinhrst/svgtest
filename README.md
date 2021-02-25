This is the repo used for testing ways to embed SVGs.

See https://claude-e-e.medium.com/ for more info (link should be updated to deep link as soon as blog post is live).

In order to run the examples, run a local webserver on port 8000.
A quick way to do so is:

`python3 -m http.server`

Then go to http://same.lvh.me/test.html .

Note: we assume that both same.lvh.me and cross.lvh.me will keep pointing to localhost.

Note that if you open the site on http://localhost:8000/, some things may be slightly different since there seem ro be special CORS rules for localhost.

The example works on Firefox 85.0.1 -- it also works on the latest Chrome and Safari, however some alignments are less nice there.
