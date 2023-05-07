# statnice-poznamky

Poznámky pro přípravu k bakalářské státní zkoušce z Informatiky,
specializace Počítačocá grafika, vidění a vývoj her na MFF UK.
Nejnovější verze poznámek je k dispozici jako build fragment
posledního commitu na `master` v `Actions` tabu. Většina komunikace
zde na GitHubu je v angličtině, ale poznámky samotné jsou až na
vyjímky v češtině.

Git related things in this repository are in English. The
text contained in the notes is in Czech only. However, if you'd
like to contribute even partial english text, feel free to create
a pull request.

## How to contribute

If you find any problems with the notes, e.g. mistakes, typos,
etc. please create an issue so we can make the notes better.

In case you'd like to contribute directly, please follow the
following guidelines. They are by no means complete. Use common
sense where these guidelines aren't clear. But as this
is a fairly small project, I don't expect that detailed notes on
this will be necessary.

1. Before you start writing anything, please check existing
Issues to be sure that no one else is working on the same thing.
You might save yourself some time. In case there is no existing issue,
please make one so others do not waste their time either.
2. When writing the notes, please keep the style of the LaTeX sources
consistent with the rest of the notes. More on that in the next section.
3. Each pull request should only target a single chapter at a time.
Even if you're just fixing typos, please do not combine multiple chapters
into a single pull request.
4. Make sure that your branch is up to date with `master` before you
create your pull request. In case it is not, please rebase your changes
to master first.
5. When creating your pull request, please allow the reviewer(s) to push
additional changes to your branch.

## LaTeX style

These are some basic rules to follow when writing contributions to these notes.
Not following them to the letter it not the end of the world. However,
keeping the style consistent makes it easier for everyone.

1. Keep the length of each line within 120 characters.
2. Use `\[ \]` for math blocks instead of `$$ $$`.
3. Prefer using dedicated blocks such as `align` or `multline` instead
of bare math blocks where applicable.
4. Prefer using `varepsilon` and `varphi` over `epsilon` and `phi`.
