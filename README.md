# Focus Pocus

Read hard things, one block at a time.

Focus Pocus breaks long, dense texts into bite-sized blocks. You still do the reading; when a passage gets hard, **Explain** opens a short, readable paragraph on what the block means and **Summarize** condenses it. On the last block, Summarize also condenses the whole text.

- Library of seven short excerpts about AI and datasets (Prince, Vaswani et al., GPT-3, Villalobos et al., Shumailov et al., Kang et al.) and the opening of *Alice's Adventures in Wonderland*.
- Focus mode (one block at a time) and Full text mode (the whole text, current block lit). Progress is saved in the browser, with a Reset progress button in the library. The top bar stays in view as you scroll.
- Block size: `−` and `+` make blocks about 25% shorter or longer per press. `−` splits long blocks at sentence ends, `+` joins short ones. The percentage between the buttons goes back to the original blocks. A resized block shows the explanations and summaries of the blocks it comes from.
- Highlighter (`H` or the marker button): the block starts unpainted and paints forward as the pointer moves over it, with no click. Right-click switches the pointer between paint, pause (to reach Explain without painting) and eraser. `Space` paints the next phrase and `Backspace` erases one; the clear button wipes the block. The reader always opens with the highlighter off.
- Highlight strength: the strip of five yellows in the bottom bar goes from watery to full highlighter, and the choice is remembered.
- Keyboard: `J`/`K` or arrows to move, `E` explain, `S` summarize, `−`/`+` block size, `F` full text, `H` highlighter, `Esc` back to the library.
- Explanations and summaries are written ahead of time, so the page works anywhere with no setup and no API key.

## Publish on GitHub Pages

1. Create a repository and add `index.html` (and this README).
2. Settings → Pages → Source: `main` branch, `/ (root)`.
3. The site appears at `https://<user>.github.io/<repo>/`.

## Sources

Short excerpts for educational purposes, with links to the originals: Prince (2023), *Understanding Deep Learning*; Vaswani et al. (2017), *Attention Is All You Need*; Brown et al. (2020), *Language Models are Few-Shot Learners*; Villalobos et al. (2024), *Will We Run Out of Data?*; Shumailov et al. (2024), *Nature*; Kang et al. (2025), *Demystifying Synthetic Data in LLM Pre-training*; Lewis Carroll (1865), public domain via Project Gutenberg.

Built with Claude.
