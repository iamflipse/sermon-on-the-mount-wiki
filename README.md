# Sermon on the Mount Wiki — Complete Text with Jordan Peterson's Commentary

The complete Sermon on the Mount (Matthew 5–7, all 111 verses) in the **King James Version** and the **World English Bible**, side by side, paired passage by passage with a plain-language guide to **Jordan B. Peterson's** lecture series on the sermon.

**Public copy:** https://iamflipse.github.io/sermon-on-the-mount-wiki/ (read-only; static build served from the `gh-pages` branch)

## Contents

- **The Text:** Matthew 5, 6 and 7, every verse numbered, KJV and WEB in parallel. Each passage block links to its commentary.
- **27 commentary pages**, one per passage, from the Beatitudes to the crowd astonished. Each has the verses in full, Peterson's reading in plain words, key ideas, 2–4 short quotes (under ~30 words), questions to explore and related links.
- **Study aids:** cheat sheet, themes index (modern search words mapped to passages), curated quotes, and a verse-and-lecture map listing the five verses the lecture never reads aloud.
- **Sources:** Bible text from eBible.org (KJV 1769 and WEB 2020, both public domain; KJV under Crown patent in the UK). Commentary distilled from a private ~81k-word transcript of the lectures; the transcript itself is not published. See `src/about.md`.

## Layout

- `src/` — markdown source pages (`text/`, `commentary/`, study aids)
- `book/` — mdbook-generated static site (committed for GitHub Pages)
- `tools/mdbook` — mdbook v0.4.21 binary (aarch64 Linux, built from source)

## Rebuild + republish

```sh
./tools/mdbook build -d book
git add -A && git commit -m "update" && git push origin main
# republish: recreate orphan gh-pages branch with book files at root + tools/mdbook, force push
git checkout --orphan gh-pages-new && git rm -rf --cached . >/dev/null
# copy book/* to the root, keep tools/mdbook, commit "Publish: ...", then:
git push -f origin gh-pages-new:gh-pages
```
