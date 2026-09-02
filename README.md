# site-fonts-private

Licensed font files (PP Mori, Comico) used by chenxilin4312.github.io.

Kept in a private repo, not the public site source, per each font's EULA:
- PP Mori (Pangram Pangram): free licence's §2.1 does not cover use "on a
  publicly available platform such as a website" — see the open question in
  the site repo's FONTS.md.
- Comico (Fontshare / ITF): EULA §02 forbids "uploading them in a public server".

Checked out by the site repo's GitHub Actions deploy workflow via a
fine-grained PAT scoped read-only to this repo, then copied into
`public/fonts/` before the Astro build.
