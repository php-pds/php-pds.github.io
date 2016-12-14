# PHP Package Development Standards

This initiative researches the PHP package ecosystem to recognize commonly
adopted development practices. It rationalizes and refines those practices, then
publishes them as PDS packages for reference by PHP package authors.

PDS publications are derived from and supported by common practices existing in
real packages, as adopted by existing authors who have a continuing interest in
the quality and consistency of their own work.

## Publications

- [pds/skeleton](https://github.com/php-pds/skeleton/tree/1.0.0-dev1) 1.0.0-dev1

## Usage

You can indicate your package attempts to comply with a PDS publication by
requiring it in your package manager manifest.

For example, under Composer, `{"require-dev": {"pds/skeleton": "1.0.0"}}`
indicates your package attempts to comply with the `pds/skeleton` publication
in its first stable state.

> N.b.: Adding a publication to your package manager manifest helps with
> ongoing research as to adoption levels of that publication.

## Naming and Versioning

PDS publications are named, instead of numbered. This makes them easier to
recognize, and easier to publish as packages in their own right.

PDS publications are versioned. This makes it easier to show the status of a
particular publication, easier to provide clarifications and additions in the
text of a publication, and easier to deprecate older standards as newer ones
supplant them.

Version numbers are `X.Y.Z(-state)`, where:

- `X` is conflicting changes from the prior version of the publication (major).
- `Y` is substantial additions, without conflicting changes from prior (minor).
- `Z` is insubstantial changes: clarifications, grammar, typos, etc. (fixes).
- `-dev(#)` means research is ongoing and interested parties are invited to review.
- `-alpha(#)` is unstable, ready for public review, not ready for wide adoption.
- `-beta(#)` is stabilizing, ready for public review, ready for wide adoption.
- No `(-state)` means the the publication is stable and complete; further
  changes should be on a subsequent version number.

This versioning approach is inspired by [SemVer](http://semver.org).


<!-- Start of StatCounter Code for Default Guide -->
<script type="text/javascript">
var sc_project=11190781;
var sc_invisible=0;
var sc_security="9a8c09c6";
var sc_https=1;
var scJsHost = (("https:" == document.location.protocol) ?
"https://secure." : "http://www.");
document.write("<sc"+"ript type='text/javascript' src='" +
scJsHost+
"statcounter.com/counter/counter.js'></"+"script>");
</script>
<noscript><div class="statcounter"><a title="shopify
analytics ecommerce" href="http://statcounter.com/shopify/"
target="_blank"><img class="statcounter"
src="//c.statcounter.com/11190781/0/9a8c09c6/0/"
alt="shopify analytics ecommerce"></a></div></noscript>
<!-- End of StatCounter Code for Default Guide -->
