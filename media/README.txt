DROP YOUR FILES IN THIS FOLDER USING EXACTLY THESE NAMES
========================================================

The website picks them up automatically. You never edit any HTML.
Until a file exists, a stock placeholder is shown in its place.

Names are case-sensitive on most web hosts. Keep them lowercase exactly
as written below.


THE FULL LIST (12 files, all optional)
--------------------------------------

TOP OF THE PAGE - fullscreen banner
  hero.mp4              the video that fills the screen when the site opens
  hero-poster.jpg       its first frame, shown while the video loads
  hero.webm             the same video in a second format, only if you have it

PROGRESS 01 - three wide pictures, one at a time, scrolling by themselves
  progress-01.jpg       picture 1
  progress-01-02.jpg    picture 2
  progress-01-03.jpg    picture 3

PROGRESS 02 - words on the left, ONE VIDEO on the right
  progress-02-video.mp4 the video. Plays by itself, loops, no sound
  progress-02.jpg       optional: the still shown while it loads

FINAL RESULT - words on the left, four portraits on the right
  progress-02-01.jpg    portrait 1
  progress-02-02.jpg    portrait 2
  progress-02-03.jpg    portrait 3
  progress-02-04.jpg    portrait 4

ABOUT - your text only. No picture, no video.

NOT SHOWN ON THE PAGE
  preview.jpg           1200 x 630. The picture that appears when the
                        link is shared on WhatsApp, Instagram, iMessage
                        and so on. Made from a frame of hero.mp4.
                        Replace it with any 1200 x 630 JPEG you prefer.


WHY THE FINAL PICTURES ARE CALLED progress-02
---------------------------------------------
That series used to sit in progress 02 and was moved down to the final
section, keeping its filenames. If the names bother you, say so and they
can be renamed to final-01.jpg ... final-04.jpg in one go - the page has
to be pointed at the new names at the same moment, so don't rename them
by hand.


HOW THE MEDIA BEHAVES
---------------------
PROGRESS 01 - the three wide pictures move on by themselves every 3
seconds, and the < and > arrows sit on top of them. The slideshow pauses
while that part of the page is off screen, and while you are on another
browser tab - so if nothing seems to move, scroll until the pictures are
actually in view.

PROGRESS 02 - one video, no arrows, nothing to click. It starts on its
own, loops forever and is SILENT. That is not a limitation to work
around: browsers refuse to autoplay anything with sound.

FINAL RESULT - four portraits, one at a time, standing beside the text.
Visitors move through them with the < and > arrows either side. These do
NOT move on their own; the arrows are the only way through.

ABOUT - words on their own. The small square photo that used to sit
beside them has been taken off the page.

A missing picture is replaced by a stock placeholder, so the page always
looks complete while you are still gathering files.

On a phone the text moves above the media instead of beside it.


SIZES
-----
THE FOUR FINAL PORTRAITS  ->  PORTRAIT, 1080 x 1920 (9:16)
  This is the shape phones shoot in held upright, so photos taken that
  way already fit. Anything else works but is cropped to 9:16 from the
  centre - keep what matters away from the top and bottom edges. On a
  large screen these display about 484 x 860.

progress-02-video.mp4  ->  PORTRAIT, 1080 x 1920 (9:16)
  It fills exactly the same 484 x 860 shape as the portraits above, and
  is cropped the same way, so a landscape video would lose its sides.

THE THREE PROGRESS 01 PICTURES  ->  LANDSCAPE, about 2000px wide
  Shown at 5:4 with a black margin around them, cropped from the centre,
  so keep what matters away from the top and bottom edges.

hero.mp4  ->  landscape, 1920 x 1080.
  Cropped to fill whatever screen it lands on, so keep the subject near
  the middle of the frame.


KEEP THE FILES SMALL
--------------------
Save pictures as JPEG at quality around 80. Photos straight off a camera
are often 8 MB each, and there are nine pictures here - that would make
the site painfully slow to open.

Videos: MP4, H.264. Both videos on this site start on their own, which
means every visitor downloads them whether they watch or not - so these
two files decide how fast your site feels. Aim under about 10 MB each.

Both have already been compressed:
  hero.mp4               31.3 MB  ->   4.4 MB
  progress-02-video.mp4  55.3 MB  ->   6.5 MB
Same length, same resolution, no visible difference. The silent audio
tracks were dropped, since the page mutes both videos anyway.

YOUR UNTOUCHED ORIGINALS ARE IN  media/_originals/  - nothing was
thrown away. That folder is excluded from the website, so it costs you
nothing to keep.

IF YOU REPLACE EITHER VIDEO with a fresh export, it will be big again.
Ask and it can be compressed the same way in a few seconds.


FILES IN THIS FOLDER THE SITE NO LONGER USES
--------------------------------------------
These are left here untouched in case you want them back. Nothing on the
page looks for them, so they are only taking up disk and cloud space:
  about-video.mp4, about-video cancelled.mp4, about-poster.jpg,
  final-video.mp4, final-01.jpg, final-02.jpg, final-03.jpg,
  final-04.jpg, CaroleDanaf_2.jpg (your photo - the About section no
  longer shows one)
That is about 500 MB. Say the word if you want them cleared out.


WHERE THE WORDS LIVE
--------------------
Nothing in this folder controls text. All the wording - titles,
paragraphs, your email, the menu - is in  content.js  in the folder
above this one. Open it with the "EDIT MY WEBSITE TEXT" shortcut.
