PCRE.js
=======

PCRE for javascript

If you are reading this you are probably frustrated with javascripts RegExp class (or at least in the browser standard).

This project is about building a bridge between native javascript RegExp and PCRE support / standards.

It works by parsing RegExp or RE Strings into Native supported RegExp pieces that are chained together to support PCRE.

Named captures are simply maintained by keeping the named index that is then used to return the capture.  DEFINEs and recursion are supported by recalling the RE within the recursion piece.

Classes are supported by replacing themselves internally with whatever they represent.  IE ::alpha:: [a-zA-Z]

For those of you who don't know what PCRE is, it is basically Perl Compatible Regular Expressions, you can read more about this standard at http://www.pcre.org/ and http://en.wikipedia.org/wiki/Perl_Compatible_Regular_Expressions.

In the weeks to come I will add the source and API documentation with examples.

Thanks for your interest.
