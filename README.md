
# Valentine Proposal Page ❤️

A single-file, cute proposal page you can host anywhere and share as a link.

## Personalize with URL parameters
You can personalize the page text using URL parameters:

```
?to=TheirName&from=YourName&msg=Your%20custom%20message
```

**Example:**
```
https://your-domain.example.com/?to=Alex&from=Poorvitha&msg=Every%20day%20with%20you%20feels%20like%20magic.%20Will%20you%20be%20my%20Valentine%3F
```

## Easiest hosting options

### Option A: Netlify Drop (fastest)
1. Go to https://app.netlify.com/drop
2. Drag & drop the `index.html` file.
3. Netlify will give you a public link you can copy and share.

### Option B: GitHub Pages (free, permanent)
1. Create a new repository on GitHub (e.g., `valentine-proposal`).
2. Upload `index.html` to the repository root and commit.
3. Go to **Settings → Pages → Build and deployment**.
4. Under **Source**, select **Deploy from branch**; choose branch `main`, folder `/root`.
5. Click **Save**. GitHub Pages will publish to a URL like:
   `https://<your-username>.github.io/valentine-proposal/`

## Optional customization
- Change colors: edit `--accent` and `--accent-2` in the CSS `:root` block.
- Replace the main text inside the `<p class="message">` element.
- Swap the background animation by tweaking the `.stars` or adding your images.

Good luck and have fun! 💐
