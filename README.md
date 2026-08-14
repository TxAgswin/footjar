# footjar.com

Deployed automatically by Netlify from this repository.

    index.html           ->  footjar.com
    pipeline/index.html  ->  footjar.com/pipeline

**Do not edit these files by hand.** They are generated. Editing the source and
rebuilding is the only thing that sticks:

    python3 footjar/web/build_site.py     # dashboard  -> pipeline/index.html
    python3 footjar/web/build_home.py     # landing page -> index.html

To publish: open GitHub Desktop, write a summary, Commit to main, then Push origin.
Netlify picks it up and republishes in about twenty seconds.
