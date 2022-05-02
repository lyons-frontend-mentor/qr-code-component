# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- HTML
- TailwindCSS

## Reflection

I chose this basic project to practice using TailwindCSS, including setting up my development environment. In particular, I followed [this video on setting up the Tailwind Prettier plugin](https://www.youtube.com/watch?v=_CntOc4hBcg), which sorts Tailwind classes. I'm not familiar with Prettier, so I needed to read this [Goku's answer to this StackOverflow question about saving on format](https://stackoverflow.com/questions/59433286/vs-code-prettier-format-on-save-doesnt-work).

With that set-up out of the way, it was mostly a simple matter of translating the Figma design sheet to Tailwind classes. For this simple example, the design maps pretty directly to the classes. To get the custom colors given by Frontend Mentor, I followed [Tailwind's documentation on customizing colors](https://tailwindcss.com/docs/customizing-colors).

I'm not used to reading Tailwind classes in the HTML to figure out what the CSS is doing. Usually I use a BEM naming convention, and to look at the styles for an element I can read all the applied styles either in the `.css` file or by inspection in the browser. I initially tried splitting each class string along multiple lines, with each line corresponding to a different aspect of styling (e.g. margin, backgrounds and borders, padding, text, etc.), but this doesn't seem like how most people write Tailwind. Instead, most Tailwind code I see favors single-line class strings. At the moment these class strings are a bit illegible to me. I'm hoping that the sorting from the Prettier plugin will help, as having some sort of set order for the CSS rules should help me get used to the single-line notation.

### Continued development

I'll continue working on simpler Frontend Mentor challenges to get used to Tailwind. For my next challenge I'd like to work with some basic Flex-layout stuff.
