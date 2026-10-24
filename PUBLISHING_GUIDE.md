# Publishing FulKay on GitHub Pages

## Before publishing
1. Keep a backup of the old `blognation` repository. Do **not** copy its Django configuration, database, or historical credentials into this website.
2. Rotate/revoke any old credentials that remain active; archiving an old repository does not secure exposed secrets.
3. Review the biography, proposed project descriptions, and the wording of all pages.

## Create the website repository
1. Sign in to GitHub as `Fulkay`.
2. Click **New repository**.
3. Name it exactly **Fulkay.github.io** (the spelling of your GitHub username is case-insensitive for this purpose; using lowercase `fulkay.github.io` is also fine).
4. Set visibility to **Public** and create the repository. Do not initialise with a README if you intend to upload this starter's files.
5. Use **Add file → Upload files** to upload the *contents* of this starter directory, including `_config.yml`, `_layouts`, and `assets` (not the containing folder itself). GitHub's browser upload can be awkward for nested folders; GitHub Desktop or a local Git push is the more reliable method.
6. Commit the files to the default branch.

## Enable Pages
1. Go to the new repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select your default branch (`main`) and `/ (root)`, then save.
4. Wait for GitHub's build/deployment to finish.
5. Open **https://fulkay.github.io** and test Home, About, Projects, Knowledge Hub, Contact, and mobile layout.

## Easiest upload using GitHub Desktop
1. Extract the starter ZIP locally.
2. Create or clone `Fulkay.github.io` with GitHub Desktop.
3. Copy all files and folders *inside* the extracted starter folder into the local repository folder.
4. Review the changes; commit with message `Initial FulKay website`.
5. Push origin. Enable Pages as above.

## Editing content
- Homepage: `index.html`
- About: `about.md`
- Projects: `projects.md`
- Knowledge Hub: `knowledge.md`
- Contact: `contact.md`
- Colours and spacing: `assets/css/style.css`
- Shared header/footer: `_layouts/default.html`
- Site metadata: `_config.yml`

## Later enhancements
- Add detailed case studies, tutorial pages, and an article index.
- Add optional search or category filters.
- Add a custom domain only after confirming the preferred brand name and domain availability.
- Add a professional contact route once approved.
