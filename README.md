# sdctools
Tools for working with Structured Data on Commons (SDC) on Wikimedia Commons

Since there is no support for SDC in pywikibot or other frameworks, this Jupyter notebook contains a addClaims
routine to add SDC statements to Wikimedia Commons. By default it will add a predicate-object as a P and Q number 
in Wikidata, but optionally the object can be an arbitrary string such as an external identifier (eg. VIAF, LC, ISBN, etc)

The code is based on Botmultichill routines
