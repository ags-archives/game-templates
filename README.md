AGS game templates shipped with old engines
===========================================

you can find here the game templates shipped with engine versions 2.55 - 3.3.0.
older engines than 2.55 do not ship game templates.
the files shipped in those templates have been committed such that one can see
diffs between each version by checking out the commit history.
each version has a tag, e.g. `git checkout v2.60` to get the version that was in
the AGS 2.60 zip release.

the main purpose of this repository for me is to find the globalscript.asc
that matches the assembly of a specific game i'm interested in most closely,
which can significantly simplify the reverse engineering task.
though i'm certain other code librarians will find other uses for it.

templates for more recent games (and for producing new ones, for that matter)
can be found in the adventuregamestudio organization:
https://github.com/adventuregamestudio/ags-templates
