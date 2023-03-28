# Alfred-workflow-create-uc-image-markdown-link
Create an image link to include in workflow User Configuration

# Introduction

This workflow is designed to assist with incorporating screenshots in the User Configuration of a workflow. It will work with a single `.png` file at one time stored in either:

- the workflow folder itself; or
- a first level sub-folder of the workflow folder.

(It will *not* work with sub-folders nested at any deeper level within the workflow folder.)

# Usage

1. Choose the workflow for which you wish to include an image in the User Configuration. (The image should already be in either the folder of that workflow or a first level sub-folder of that folder.)

2. In Alfred right click on the workflow name, in the list of workflows, and choose `Open in Finder`.

3. Select a `.png` image, press your Universal Action hotkey (⌘/ by default) and run this workflow.

4. You will be prompted to enter the exact name of the *destination* workflow (i.e., the workflow in the User Configuration of which the image is to be used).

5. The link will be assembled and copied to the clipbboard (with a confirmatory notification). The link will be in one of two forms depending upon whether you selected an image stored in the workflow folder or an image stored within a sub-folder of that folder.

`![Name of destination workflow](Name of image.png)`

`![Name of destination workflow](Images/Name of image.png)`

6. All you then have to do in order to incorporate the image in the User Configuration is to paste the link.

# Notes

- The workflow works only with `.png` files (although could be easily modified to work with JPEG files by including those within the scope of the initial `File Action`).
- The workflow works only with a single selected file (as opposed to multiple selected files).
- Don't use this workflow to create more general links, in other apps, to markdown images. It's intended only to create the sort of links required by Alfred's User Configuration.
