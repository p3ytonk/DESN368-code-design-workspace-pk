# DESN368 - Peyton Knox Product Landing Page

## Project Description

Eclectic Vinyl Records is a retro-inspired product landing page for a fictional record shop. The page is based on my Figma design and built with semantic HTML and modern CSS. It includes:

A fixed navigation bar with in-page links

A hero quote and spinning logo record

A “Featured Spins” section with vinyl product cards

A “The Art of the Press” video section explaining how records are made

A “Pressing Details” table comparing different editions

A newsletter sign-up form with a confetti thank-you popup

The goal of the project was to translate a detailed Figma layout into clean, accessible, responsive HTML/CSS while matching the color palette, type hierarchy, and overall vibe of the original design.

## Which CSS transform I implemented
On hover (or keyboard focus), each product card gently lifts up and scales slightly larger. This makes the cards feel more tactile, like you’re picking up a record from the bin.

(There is also a transform on the large hero logo record so it spins on hover, but the card lift/scale is my “official” transform for the requirements.)

## Which CSS animation I implemented
The main tagline “Because the best music is meant to be held” fades in and slides up when the page loads. This sets the tone of the site and draws attention to the main value proposition right away.

(Additional animations are used for the glowing price buttons and the falling confetti, but the hero fade-up is my primary animation choice for the rubric.)

## Which table content type I chose
For the required table, I chose product details / specs and pricing:

Table ID: data-table

Columns: Album, Pressing, Speed, Color, Price

The table compares a few featured pressings (Hotel California, American Idiot, Thriller, and a “Mystery Mix”) so users can see speed, color variants, and price at a glance.

This fits the “product data / comparison” category listed in the brief.

## Challenges encountered and solutions
Getting all the sections to match the Figma layout

Challenge: The header, stripes, hero, and record logo all needed to line up in a very specific way to match the screenshot.

Solution: I reorganized the HTML into clear sections (header, main, section, footer) and used flexbox and margin/padding adjustments. I also separated the nav stripe (.nav-divider) from the regular red/white section dividers so they could be styled differently.

Images not showing up (logos and vinyl artwork)

Challenge: Some images didn’t load because of file path issues and inconsistent folder structure.

Solution: I simplified the paths by putting the key images in the same folder as index.html and updated the src attributes to match the exact filenames (e.g., eagles-vinyl.png, header-logo.png, etc.).

Product card layout and unwanted “extra” boxes

Challenge: Earlier versions of the vinyl cards had inner boxes and drop shadows that didn’t match the design, and the album images were too small. Unwanted shadow boxes included in product cards.

Solution: Unfortunately, this one got me.

Embedding the video and adding custom play/pause buttons

Challenge: The YouTube video needed to sit inside a “TV frame” with two circular buttons underneath that actually control playback.

Solution: I wrapped the iframe in a .video-frame and .video-frame-inner, then used the YouTube Iframe API (onYouTubeIframeAPIReady) to connect the custom buttons to player.playVideo() and player.pauseVideo().

## Key learnings
I got a lot more comfortable using semantic HTML (header, main, section, article, table, etc.) and it made the page feel more organized and easier to read.

I learned how picky file paths and filenames are — if one letter is off, the image just won’t show. Keeping all my images in a consistent place helped a ton.

I realized it’s better to keep layouts simple. Once I stopped overcomplicating the vinyl cards and just used one main card + one big image, everything clicked into place.

I saw how a small amount of animation and transform (like a soft hover or fade-in) can make the site feel more alive without being distracting.

I figured out how to control a YouTube video with custom buttons using the iframe API, which made the “TV” section feel more like a real interaction.

Overall, I learned that redoing and refining the code is normal. The site got better each time I cleaned things up and fixed one problem at a time.

## Disclaimer

(Created with the assistance of ChatGPT to help clean up and organize code/figure out how to manipulate certain elements the way I intended)
