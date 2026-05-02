# Universal Links (Apple)

This folder must be deployed **as-is** to your site root so this exact URL works:

**`https://betternights.app/.well-known/apple-app-site-association`**

## Important

- The file is named **`apple-app-site-association`** — **no** `.json` extension (Apple requirement).
- Deploy the whole **`.well-known`** directory, not only the file, so the path above resolves.
- If you copy files by hand, recreate: `web/.well-known/` → site `.well-known/`.

## Optional copy for editing

If your editor hides extension-less files, you can duplicate the contents into `apple-app-site-association.json` locally — **do not** upload the `.json` name to production; only the extension-less file is valid for Apple.
