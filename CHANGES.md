# What changed in Derrick's website, and why

All the words, sections, photos and colours are still your group's. These changes fix bugs and make the site work well on any screen.

## Bugs fixed

- **Repeated sections.** The Challenges and Solutions sections were each opened twice, and both sat inside the Tips section. Now each one is its own section with its own menu link.
- **Gallery squashed into one box.** All six photos were inside a single `div class="placeholder"` that was only 250 × 180 px. The photos now sit in a proper grid.
- **Missing spaces in `<img>` tags.** `alt="..."width="350"` had no space before `width`, so the browser ignored the sizes. The sizes now come from CSS, so every photo is the same shape.
- **Form fields had no `name`.** Without a name, a form sends nothing. Each field now has one.

## Improvements

- **Sticky menu:** the menu stays at the top while you scroll, and `scroll-behavior: smooth` makes the links glide down the page.
- **Colours saved once:** your green, `#2E8B57`, and darker green, `#1F5D3A`, are stored as CSS variables at the top of `style.css`. White text sits on the darker green so it is easy to read.
- **Challenges and Solutions** are styled as numbered cards, with each title on its own line.
- **Works on phones:** the gallery shows 3 photos per row on a computer, 2 on a tablet and 1 on a phone.
- **Thank you page:** sending the form now opens `thanks.html` instead of reloading the page.
- **Keyboard friendly:** a "Skip to content" link appears when you press Tab, and a yellow outline shows which link is selected.

## Try this next

- Add a short sentence under each gallery photo using `<figure>` and `<figcaption>`.
- Add one fact about education in Kenya, and write where you found it.
