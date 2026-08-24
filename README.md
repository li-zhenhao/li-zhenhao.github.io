# Zhenhao Li — GitHub Pages homepage

## Publish the site

1. Create a public repository named `<your-github-username>.github.io`.
2. Upload the **contents** of this folder to the root of that repository.
3. Open `Settings` → `Pages`.
4. Choose `Deploy from a branch`, `main`, and `/(root)`.
5. Save and wait a few minutes.

## Edit your information

Open `_data/content.yml` on GitHub, click the pencil icon, edit the text, and
commit the change. This is normally the only file you need to edit.

## Add a portrait or other image

Upload image files to `assets/images/`. Then set, for example:

```yaml
photo: "/assets/images/profile.jpg"
```

For a publication image, set `image`, `image_alt`, and `image_caption` in that
publication's entry in `_data/content.yml`.

## Add the CV

Upload it as `assets/files/CV.pdf`, then set:

```yaml
cv: "/assets/files/CV.pdf"
```

