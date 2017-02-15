This is an export filter for JabRef which matches the author
guidelines of Edward Elgar.

Actually ther are only layouts for entry types "book", "article",
"incollection", "techreport" and "misc" -- but I think layouts for
other entry types could be added quite easily.

Names of authors and editors are formatted as in the following
example:

    van Dyke, N., S. Soule and V. Taylor (2004), 'The Targets of Social
    Movements. Beyond a Focus on the State', in Myers, D.J. and D.M.
    Cress (eds.), Authority in Contention, Research in Social Movements,
    Conflicts and Change, Vol. 25, Amsterdam: Elsevier, pp. 27-54.

I took the examples of the standard "Harvard RTF" export filter and
adjusted them as needed. To handle multiple authors and editors
correctly I defined the following two "name formatters". 

For current versions of JabRef (I guess up to 2.4) you have to define
the following to name formatters manually (under "Options" ->
"Preferences" -> "Name formatter"):

    Formatter Name: AuthorsEdwardElgar

    Format String:  1@*@{vv }{ll}{, f.}@@2@1@{vv }{ll}{, f.}@2@ and {f. }{vv }{ll}@@*@1@{vv }{ll}{, f.}@2..-2@, {f. }{vv }{ll}@-1@ and {f. }{vv }{ll}

    Formatter Name: EditorsEdwardElgar

    Format String:  1@*@{vv }{ll}{, f.} (ed.)@@2@1@{vv }{ll}{, f.}@2@ and {f. }{vv }{ll} (eds.)@@*@1@{vv }{ll}{, f.}@2..-2@, {f. }{vv }{ll}@-1@ and {f. }{vv }{ll} (eds.)

For future versions of JabRef (post 2.4) there will be an option to
read name formatters from a file in the filters directory instead of
defining them manually. Therefore I have included the file
"edward_elgar.formatters" which contains two lines with the name
formatters given above.

Please note: The formatters don't honor {j} -- the "Jr." part of the
Bibtex name scheme (as described in the JabRef user manual). The
guidelines for authors from Edward Elgar didn't give any hint about
this.
