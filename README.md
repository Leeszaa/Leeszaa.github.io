# Weazel News Tools

This is a standalone project containing the Kleinanzeigen Generator and Wetter Generator tools.

## Structure
- `index.html`: Main hub / landing page.
- `kleinanzeigen_generator.html`: Tool for generating classified ads HTML.
- `wetter_erstellen.html`: Tool for generating weather forecast images.
- `Module/`: Contains HTML templates for the Kleinanzeigen generator.

## How to upload to Git

1.  **Initialize Git**:
    Open a terminal in this folder (`j:\Weazel-Tools\`) and run:
    ```bash
    git init
    ```

2.  **Add files**:
    ```bash
    git add .
    ```

3.  **Commit**:
    ```bash
    git commit -m "Initial commit for Weazel Tools"
    ```

4.  **Push to GitHub**:
    - Create a new repository on GitHub (e.g., `weazel-tools`).
    - Follow the instructions to push an existing repository:
    ```bash
    git remote add origin https://github.com/YOUR_USERNAME/weazel-tools.git
    git branch -M main
    git push -u origin main
    ```

## How to publish on Netlify

1.  **Login to Netlify**: Go to [app.netlify.com](https://app.netlify.com) and log in.
2.  **Add New Site**: Click "Add new site" -> "Import from an existing project".
3.  **Connect to GitHub**: Choose GitHub and select the repository you just pushed (`weazel-tools`).
4.  **Deploy**:
    - **Build command**: (Leave empty, this is a static site)
    - **Publish directory**: (Leave empty or set to `/`, it detects the root `index.html` automatically)
5.  Click **Deploy Site**.

Alternatively, you can drag and drop this `Weazel-Tools` folder directly into the "Sites" area on Netlify if you don't want to use Git.
