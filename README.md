# Alfred-workflow-create-uc-image-markdown-link
Create an image link to include in workflow User Configuration

# Usage

1. Choose the workflow for which you wish to include an image in the User Configuration. (The image should already be in either the folder of that workflow or a first level sub-folder of that folder.)

2. In Alfred right click on the workflow name, in the list of workflows, and choose `Open in Finder`.

3. Select a `.png` image, press your Universal Action hotkey (<kbd>⌘/</kbd> by default) and run this workflow.

4. The name of the *destination* workflow (i.e., the workflow in the User Configuration of which the image is to be used) will be shown.

If the name is correct all you have to do is to press <kbd>⏎</kbd>. Otherwise you can edit the name (but do note it *must* be identical to that of the workflow in the configuration for which you are including the image) and then press <kbd>⏎</kbd>.

5. The link will be assembled and copied to the clipbboard (with a confirmatory notification). You can then simply paste the markdown link from the clipboard into the workflow configuration.

# Notes

- The workflow works only with `.png` files (although could be easily modified to work with JPEG files by including those within the scope of the initial `File Action`).
- The workflow works only with a single selected file (as opposed to multiple selected files).
- Don't use this workflow to create more general links, in other apps, to markdown images. It's intended only to create the sort of links required by Alfred's User Configuration.
