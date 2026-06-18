# FlipClock website

Static site for the **FlipClock** iOS app — landing page, privacy policy, and
support page. Served via GitHub Pages at <https://makekamac.github.io/flipclock/>.

| Page | URL |
|------|-----|
| Landing (Marketing URL) | https://makekamac.github.io/flipclock/ |
| Privacy Policy | https://makekamac.github.io/flipclock/privacy/ |
| Support | https://makekamac.github.io/flipclock/support/ |

## Editing the support / contact email

The contact address appears in `support/index.html` and `privacy/index.html`,
each marked with a `<!-- SUPPORT_EMAIL -->` comment. Change those, commit, and
push — Pages redeploys automatically.

## Local preview

```sh
python3 -m http.server 8000   # then open http://localhost:8000/flipclock/ won't match;
                              # use a path-rewrite or just open the files directly
```

Plain HTML + one CSS file, no build step. `.nojekyll` disables Jekyll processing.
