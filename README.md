# Audiobooks (Audible) metadata agent

This metadata agent will receive data from [Audible.com](http://www.www.audible.com/).

I've discovered that the first two genre tags show up in the top right when viewing the album/book.  If the book is identified as part of a series, it will list there and when clicked display other books of that series.  The same goes for the Narrator.


Metadata supplied:

Full Title
Audthor (as Artist)
Book/Album Cover (as Poster)
Release Date (audiobook, not print or e-book)
Production Studio (as Record Label)
Publisher's Summary (as Review)
Narrator(s) (as Genre Tag)
Genres (as Genre Tag, duh)


Library Creation Options:
DO NOT check 'Use Embedded Tags'

DO check 'Store Track Progress'

Agent - Select Audiobooks


Tips for greatest success:

Set "Album" tag in audio file as the book title
Set "Artist" tag in audio file as the book author
None of the other tags really matter for searching and matching.
Manual 'match' will use the Author/Artist field if it's present, but you cannot enter it manually.  Only the title.
Make sure all the tracks have the same artist and album.
Store each in a folder

Notes:

Title data in parens ()  such as (Unabridged) is automatically removed before search.  I've found this improves the results and matching.



Todo:

-Author Data
Not sure what to do about author data.  I don't know of a good site to scrape for author data.  In the absense of my script providing this, plex seems to automatically search Last.fm using it's internal plugin.  Some authors are listed there and it pulls data much like it does for a music artist.  For now I suggest contributing to that wiki style page to help populate data until Audible comes up with an artist detail page.


-Genre Tags
The only tags you can filter by in Music library's are the artist tags.  So while I'm populating the album genres, it's just there to be pretty and look complete.  Maybe in a future release this will become useful data.

