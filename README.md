# Srividya's portfolio

A static website. There is no server or database: everything lives in two files.

- `index.html` holds the content, the styles (in the `<style>` block at the top) and a small script at the bottom.
- `photo.jpg` is your portrait. Keep it in the same folder as `index.html`.

Open `index.html` in a browser to preview it. Edit it in any text editor, such as VS Code.

## Where to change things

- **Colors:** the `:root` block at the top of the `<style>` section (`--bg`, `--teal`, `--marigold` and so on).
- **Text:** each section is marked by its `id`: `work`, `projects`, `papers`, `toolkit`, `education`, `contact`.
- **Project results:** the bars use `style="--v:76.7%"`. Change that number and the printed value beside it.
- **Paper links:** the three `href="https://ieeexplore.ieee.org/..."` links inside `id="papers"`.
- **GitHub and LinkedIn:** in the contact section, replace the text `github/srividya` and `linkedin/srividya` with real links, for example `<a href="https://github.com/yourname">github.com/yourname</a>`.
- **Phone number:** not on the page by default. Add it in the contact section if you want it public.

## Getting a public link

Any of these hosts a static folder for free:

- **GitHub Pages:** push the two files to a repository, then turn on Pages in the repository settings.
- **Netlify Drop:** drag the folder onto app.netlify.com/drop.
- **Vercel or Cloudflare Pages:** import the repository or upload the folder.
