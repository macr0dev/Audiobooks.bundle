# NO LONGER IN DEVELOPMENT

This was a fun little project that I started many years ago.  I never really expected it to get as big as it did, and many people have splintered this off into even larger projects than I imagined would ever be.  Please consider visiting one of them for your future needs.  I won't be updating this anymore, and haven't for some time.  But I will leave it here for anyone to borrow/steal from.  Thanks!





# Audiobooks (Audible) metadata agent

Metadata agent for Audiobooks stored in a music library. **Now available in the Unsupported App Store!**

This agent scrapes from Audible.com. It uses the Album Artist as the books Author and uses the Album Title as the Book Title. All audio files will need to be tagged correctly in order for this thing to do it's job. You can manually search for each book if you don't have them tagged ahead of time. 

Download: https://github.com/macr0dev/Audiobooks.bundle/archive/master.zip

Source: https://github.com/macr0dev/Audiobooks.bundle


**Metadata supplied:**

Full Title
Author (as Artist)
Book/Album Cover (as Poster)
Release Date (audiobook, not print or e-book)
Production Studio (as Record Label)
Publisher's Summary (as Review)
Series Title (if exists)
Narrator(s) (as Genre Tag)
Genres (as Genre Tag)


**Library Creation Options:**

Create a BASIC MUSIC LIBRARY (not a premium Plex muisc library)

DO NOT check 'Use Embedded Tags'

DO check 'Store Track Progress'

Agent - Select Audiobooks


**Agent Congiration Options:**

If you're in the US and want to scrape from Audible.com - you're all set!
If you're NOT in the US, or just want more flexibility with your searches you have options.

Manually Select Audible Site:
  This option allows you to manually select which site you're going to scrape.  If this is not checked, the language you selected for
  the library, or the language selected for a manual match will be used to select which site to scrape from.

Select Audible site to use:
  This option is ignored if the above box is not checked.

**Tips for greatest success:**

Set "Album" tag in audio file as the book title
Set "Artist" tag in audio file as the book author
None of the other tags really matter for searching and matching.
Manual 'match' will use the Author/Artist field if it's present, but you cannot enter it manually.  Only the title.
Make sure all the tracks have the same artist and album.
Store each in a folder

**Notes:**

-Title data in parens ()  such as (Unabridged) is automatically removed before search.  I've found this improves the results and matching.

-Currently, I don't have a great source for author data. What populates now (if any) is being done automatically from last.fm. You're welcome to go add some data there. This was kind of a happy accident.

-The first two genre tags show up in the top right when viewing the album/book.  Genre tags are listed in the following order: Series [if exists], Narrator(s), Genre.

-You can filter by the various tags that are added to each book. Be it author, series, narrator, etc.
