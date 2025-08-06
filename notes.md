# Notes

## Tools
For editing, I chose Google Docs because of these features:
- collaborative editing (haven't used it yet, but it's a nice feature)
- saved in the cloud automatically
- easy to share, although with a lot of chrome (pun unintended)
- has many export formats to choose from (download as...)

For hosting, I chose GitHub because of familiarity, history, etc.

For publishing, I chose GitHub Pages

Rather than using a blogging platform, I chose to code everything.
- a home page in HTML, updated for each post
- an RSS feed, updated for each post
- updating a URL shortener for each post
- pushing updates to GitHub for each post

### Image editing
Combining three separate pictures into a collage was difficult in Preview
and impossible in Google Docs. I use Google Slides to do this because it
allows me to arrange them in any overlapping way, and then I can take a
screenshot to get the final result.

Most of the pictures are taken with my iPhone 14 but some were taken by others
and shared with me. From the phone, I email pictures, and then from the 
laptop download them for inclusion in a Google Doc (perhaps via a Slide).

## Publishing steps
These are the things that need to be done to publish a new post, which
I intend to do weekly. So far they have been named "Week 9" etc.

1. Share the Google Doc with everyone who has the link for reading
2. Copy the shared link (saved in [a Google Sheet](https://docs.google.com/spreadsheets/d/1Zdr9cvMxNHAiSy6hbB0NpQDC_OYiaTL-LwvpFOUlMKo/edit?usp=sharing))
3. Add it as a shortcut named "HHMweek9" on bruceatbyu.com/s
4. In GitHub, edit the docs/index.html file to include a link
5. In GitHub, edit the docs/feed.xml file to include it as an item

## Risks
I am dependent on multiple providers.
- Google for Google Drive
- GitHub
- Reclaim Hosting which runs my hand-built URL shortener

### Mitigation
Well, sort of. 
My plan is to export each post from Google Docs and keep them on my laptop
as well as checking them in to GitHub.
That would prevent loss in case Google went away and also my Reclaim Hosting
account.
Thinking about the possible problems hurts my head, so that's it for now!

### Google Docs export options
The ones that I have explored are:

- Just sharing. Works fine, but is cluttered
- Sharing by publishing to the web breaks the one place were I used two columns
- PDF. Works fine, but pageinates which sort of isn't web-like, but will be good for publishing to paper
- HTML breaks the place where I used two columns, so hand-fixed that
