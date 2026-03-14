# AVI MetaEdit

___Embed, validate, and export AVI files metadata___

AVI MetaEdit is a tool that supports embedding, validating, and exporting of metadata in AVI files.

This tool can also enforce file structure and metadata recommendations and specifications from U.S. National Archives, Microsoft, and IBM.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub net.mediaarea.AVIMetaEdit
flatpak run net.mediaarea.AVIMetaEdit
```

## Building

```bash
git clone git@github.com:flathub/net.mediaarea.AVIMetaEdit.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install net.mediaarea.AVIMetaEdit.json
```
