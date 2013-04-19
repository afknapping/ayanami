---
title: Kindle Paperwhite review, freeing your ebooks from DRM and freeing yourself from the Kindle store
date: 2013-04-01 10:44 UTC
published: fals
tags:

---

# Kindle Paperwhite review, freeing your ebooks from DRM and freeing yourself from the Kindle store

**tl;dr:** awesome piece of hardware, well worth the money. Combine with Instapaper, de-DRM software, Calibre or custom firmware for more happy days.

The Kindle Paperwhite is my first Kindle. Actually, I had never really tried any eReader, mostly due to

- being uninitiated and 
- appalled by the DRM that surrounds eBooks (just like it was with music from the iTunes store [until that BS ended once and for all](http://www.macworld.com/article/1137946/itunestore.html)).

The other reason was, that, on average, consumer electronics hardware is cheap crap, built to fall apart as soon as the next season arrives. Just walk the endless shelves of MP3-players in your local electronics store, take them in your hand and press a few buttons.


### The Hardware

The device feels great and as is very light in comparison to an LCD-tablet. Being used to a retina display on my iPhone, I sometimes *feel* like I can spot pixels on the Paperwhite display – but actually I think I am imagining this. Illustrations look great as long as they don't depend on color.

The Paperwhite has one single button (for turning it off and on again) and a micro USB port. That's it, no schnickschnack here. It doesn't play MP3s, there is no dock available and it won't make coffee either. [Compare with older Kindle models](http://en.wikipedia.org/wiki/Amazon_Kindle#Devices) for a good laugh.

I could rant a bit about placing and ergonomics of the button (which os pretty moronic when you think about it), but it does its job.

The built-in light is perfect. It seems like the complete reading area is glowing. Acutally, imho, *the built-in light is actually the killer thing about it.* In a dark room, the lowest setting is just bright enough to read, without enlightening the whole room. I can read in bed again without disturbing the kids. How awesome is that?! All the clip-on lamps I've tried in the past where way too bright. Reading *under* the blanket is fun for two nights (feels like you are being a kid again, this time to hide from your own kids instead of from your parents), but not a real solution.

It is a bit disappointing that the light has neither a hardware control nor automatic setting. On the other side, that makes two less possible break points. Which is a good idea, more on that later.

The size of the device is exactly right, too. Anything that fits the front pocket of a zip hoodie is fit for field deployment.

Battery life keeps all the promises you hear about it. I read something around 20 to 30 hours within the first week (I caught a cold that week and read [Makers][makers] amongst other things) and the battery was at least still at 75% afterwards. I can only imagine what people refer to as "the insane battery life" Kindles generally have.

### Software

Though the display does do some greyscales, it feels monochrome. That induces a nice, minimalistic touch interface: no effects, no zooming, no dancing windows. Things appear, then they disappear, without any gloss or transparency or animations. Thank god.

If you are used to snappy native iOS or Android interfaces, the eInk-display will set you in the right mood for reading a book: *patience*. It will its thing, just give it a second.

The homescreen consists of either a list of books or a cover gallery, sorted by last read and new. You tap them, you continue reading where you left off the last time. Awesome.

The "Beta browser" is exactly that, though if you regularly read text-heavy sites, it might be useful. Scrolling is of course a pain in the ass. This part of the touch interface cannot work well due to the slowness of the eInk display.

One thing I find myself using with a lot of joy is the built in dictionaries. Just tap the word, get the definition. This is a bit like the good part of watching foreign films with subtitles – expanding knowledge on the go.

### Stuff which is not from the Kindle shop

The Kindle software supports [a ridiculous range of formats][kindleformats]: .txt, .mobi and (surprise) the Kindle .azw. (There is also PDF support, though I will talk about that in the use cases section.)

It gets obvious here why you would want a custom firmware (if it's not enough to fully control a device you own). No html support?! No Latex-support?! (I'm tempted to add "No [Hypercard][hypercard]-support?!", but well…)

Under the hood [the Kindle runs Linux](http://www.turnkeylinux.org/blog/kindle-root), so there is really no reason, it shouldn't be able to read all kinds of open standards.

However, I do not have a huge collection of documents in all kinds of formats yet. All I want to do is read ebooks. So actually I was kind of delighted to see the Kindle mounting as normal device and sporting a simple, unhidden `documents`-folder where all the content goes. I can copy inside it, I can copy out of it, without any restricitions. Awesome, I'll do the hacking some other time.

#### Managing content with Calibre

Copying files by hand works, but there is a great open-source tool out there called [Calibre][Calibre]. The UI needs a bit getting used to, but it is gift horse, so let's be happy we have it. Since calibre changes the filenames of your ebooks, it helps to keep a consistent "workflow":

- buy
- download
- dedrm
- put into library
- edit metadata
- sync to kindle
- read

Calibre does not care about the kindles `.sdr` files which store your marks and note, so those have to be synced manually if needed.

Calibre also provides you with a special goodie: converting `.epub` (which the Kindle refuses) to `.mobi` (which the Kindle accepts). This opens [a whole new old world][epubs-on-piratebay] to reading.

#### PDFs

PDF does really show its ugly side on the Kindle. If the author didn't have a paperback-sized format in mind, text will probably be unreadable, despite the high resolution of the display. Zooming is not really an option either because turning pages and moving within one page breaks your reading flow. Many PDFs come with a thick white margin, which is not easily removable.

Sometimes switching to landscape mode can be enough to wade through the pages. But once you read a book in a dynamic format, PDFs feel sluggish and yesterday.

After being somewhat disappointed I deleted the collection of PDF ebooks I accumulated over the years and understand now what they mean when they say:

> PDF is not an ebook format!

The point is not if a particular PDF is accidentally readable on this or that device. Ebooks should be dynamic by design, like HTML. PDF is by design a static format, made to get consistent output on print.

### Hackability

This depends what you understand by it. As said, I will root the device some other time, so I cannot give hints on where to start [that journey](https://www.google.com/#hl=de&safe=off&tbo=d&sclient=psy-ab&q=rooting+the+kindle+paperwhite&oq=rooting+the+kindle+paperwhite&gs_l=hp.3..0i19.1368.8401.0.8706.29.10.0.18.18.0.349.1018.8j1j0j1.10.0...0.0...1c.1.2.hp.nYVFMfn_56M&pbx=1&bav=on.2,or.r_gc.r_pw.r_qf.&bvm=bv.42080656,d.d2k&fp=fb64fd9fed45682e&biw=1199&bih=737).

[Hacking the Kindle-DRM](http://apprenticealf.wordpress.com/2012/09/10/drm-removal-tools-for-ebooks/) is actually not that hard, since everything is stored in the mentioned documents-folder. If you wonder, *why* you should hack the DRM that, have a look at the [Defective by Design](http://www.defectivebydesign.org/)-campaing by the [Free Software Foundation](http://www.fsf.org/).

### Use cases

Besides "consuming text"? Well, *learning* from book-exercises or tutorials is a breeze with this thing. This is me doing a lesson from [Land of Lisp](http://www.landoflisp.com/), a 500 page brick, which would be rather uncomfortable to work with on paper:

IMAGE

Not to mention carrying it around and doing a lesson on the train.

Which brings me to a personal use case: I start books, then start other books. It's not so much that I get easily bored. But I read mostly non-fiction and imho "80% of all non-fiction writing could be edited down to 20% of the size while keeping 80% of the relevant information".

So after a third or half of a book I usually need a break from all the bloated implied importance a writer tries to force on me, and switch to something else for a time.

Now with paper books, what do you do? Start carrying around two books? Five? Probably not. So my bookshelf is loaded with books sporting a reading mark somewhere around the middle. Never finished them.

This is an actual personal problem the Kindle does solve for me because I can continue any started book any time. Not to mention all the space it will free up, once I got rid of all the paper textbooks when I replaced them with electronic versions.

Another thing is the reading of text-heavy content from the web. [Syncing the Kindle with Instapaper][kindleinstapaper] is not exactly straightforward, but it works. "The missing link" is actually understating it a little, when forwarding editions of [Next Draft](http://nextdraft.com/) to the Kindle with two clicks and getting it out of my inbox after.

The touch interface is also very grateful for marking takeaways and quotes. Adding notes is somewhat tideous, again due to the lag of the display. It works to to add a couple keywords so you will remember your thought, but it is not made for typing. On the upside, you will find a simple text-file in the document folder called "clipboard", which has all your marked passages and notes you added. Writing book reviews should be much more fun this way, I will probably try that out one day.

### Verdict

If you think 130 Euros is "expensive" – compare it to an iPad mini. Which can do a lot more. But very little of what it can do  justifies its price in a "do I really need that"-way. The Kindle PW is a third of that price (depending on the configuration even a fourth or a fifth) and will not distract you with games or productivity apps (which you already have on your phone anyways). You can of course also compare it to a Kindle Fire. [But I wouldn't do that][kindle-fire-review].

The Paperwhite is for reading books, essays and articles. This is how I spent a lot of my life and I am happily, *finally* bringing that part of me over to the present, [after 500 years](http://en.wikipedia.org/wiki/Gutenberg_Bible). Reading on the eInk display is bliss as it is, but the built-in light made it my new best friend. I actually *do* carry it around in my hoodie pocket at home.



[makers]: http://craphound.com/makers/download/
[kindleformats]: http://www.amazon.com/gp/help/customer/display.html?nodeId=200505520&#recognize
[hypercard]: http://en.wikipedia.org/wiki/Hypercard
[kindleinstapaper]: http://david-smith.org/blog/2012/01/13/instapaper-on-the-kindle/
[kindle-fire-review]: http://www.marco.org/2011/11/17/kindle-fire-review
[Calibre]: http://calibre-ebook.com/
[epubs-on-piratebay]: http://thepiratebay.se/search/epub/