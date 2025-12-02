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
For the required table, I chose product details / specs and pricing:

Table ID: data-table

Columns: Album, Pressing, Speed, Color, Price

The table compares a few featured pressings (Hotel California, American Idiot, Thriller, and a “Mystery Mix”) so users can see speed, color variants, and price at a glance.

This fits the “product data / comparison” category listed in the brief.

## Key learnings
I got a lot more comfortable using semantic HTML (header, main, section, article, table, etc.) and it made the page feel more organized and easier to read.

I learned how picky file paths and filenames are — if one letter is off, the image just won’t show. Keeping all my images in a consistent place helped a ton.

I realized it’s better to keep layouts simple. Once I stopped overcomplicating the vinyl cards and just used one main card + one big image, everything clicked into place.

I saw how a small amount of animation and transform (like a soft hover or fade-in) can make the site feel more alive without being distracting.

I figured out how to control a YouTube video with custom buttons using the iframe API, which made the “TV” section feel more like a real interaction.

Overall, I learned that redoing and refining the code is normal. The site got better each time I cleaned things up and fixed one problem at a time.

## Disclaimer

(Created with the assistance of ChatGPT to help clean up and organize code/figure out how to manipulate certain elements the way I intended)
