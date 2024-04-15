Victor Aldecoa website
======================

Develop
-------
```bash
clj -M -m cljs.main -d "victoraldecoa.github.io/out" -c victoraldecoa.static-website -r
```

Compile
-------
```bash
clj -M -m cljs.main -O advanced -c "victoraldecoa.static-website"
```

Based on
--------
https://betweentwoparens.com/blog/deploy-clojurescript-to-github-pages/#fn-step-2-commit