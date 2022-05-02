# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/learning-tailwindcss-HJ-IHKTB9)
- [Live site URL](https://lyons-frontend-mentor.github.io/qr-code-component/)

### Built with

- HTML
- TailwindCSS

## Reflection

I chose this basic project to practice using TailwindCSS, including setting up my development environment. In particular, I followed [this video on setting up the Tailwind Prettier plugin](https://www.youtube.com/watch?v=_CntOc4hBcg), which sorts Tailwind classes. I'm not familiar with Prettier, so I needed to read this [Goku's answer to this StackOverflow question about saving on format](https://stackoverflow.com/questions/59433286/vs-code-prettier-format-on-save-doesnt-work).

With that set-up out of the way, it was mostly a simple matter of translating the Figma design sheet to Tailwind classes. For this simple example, the design maps pretty directly to the classes. However, I can't get the website to match the provided design perfectly using Tailwind alone, due to a difference in design systems. For example, the heading has a font size of `22px` in Figma, but Tailwind's closest classes are `text-xl` (`20px`) and `text-2xl` (`24px`). To get used to using Tailwind's provided design system, I'll sacrifice matching the Figma perfectly in this case. Most projects that use Tailwind will probably use Tailwind's design system anyway, rather than using custom sizes everywhere.

As for the colors, I _do_ want to get the colors matching the Figma. This sort of tinkering would be required if the project's brand/accent color doesn't match any of Tailwind's provided colors. To get the custom colors given by Frontend Mentor, I followed [Tailwind's documentation on customizing colors](https://tailwindcss.com/docs/customizing-colors). I see doing this customization as more valuable than getting custom sizes for the typography, as I predict that the Tailwind sizes will usually be "good enough", whereas exact-matching of colors in a design is more urgent. For a real-world project whose entire size-design system differs from Tailwind's, I _would_ change the Tailwind system to match that system as well.

I'm not used to reading Tailwind classes in the HTML to figure out what the CSS is doing. Usually I use a BEM naming convention, and to look at the styles for an element I can read all the applied styles either in the `.css` file or by inspection in the browser. I initially tried splitting each class string along multiple lines, with each line corresponding to a different aspect of styling (e.g. margin, backgrounds and borders, padding, text, etc.), but this doesn't seem like how most people write Tailwind. Instead, most Tailwind code I see favors single-line class strings. At the moment these class strings are a bit illegible to me. I'm hoping that the sorting from the Prettier plugin will help, as having some sort of set order for the CSS rules should help me get used to the single-line notation.

### Continued development

I'll continue working on simpler Frontend Mentor challenges to get used to Tailwind. For my next challenge I'd like to work with some basic Flex-layout stuff.
