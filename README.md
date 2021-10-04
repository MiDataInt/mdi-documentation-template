<!--- README.md is always the 1st page loaded by GitHub Pages on github.io  --->
<!-- ## {{ site.title }} -->
<!-- {% include merged-overview.md %} -->

<div style="display: {% if site %} none {% else %} block {% endif %};">
  
## Template description

The **mdi-documentation-template** is a starting point for all 
[GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)
documentation sites that are part of, or associated with, 
the **Michigan Data Interface**.

This template uses a permanent, customized fork of the open source Jekyll documentation 
theme [Just the Docs](https://pmarsceill.github.io/just-the-docs/), called
[just-the-docs-mdi](https://github.com/MiDataInt/just-the-docs-mdi).

## Template usage

### Create a new repository from this template

From this template's repository on GitHub, click the big, green button 
labeled "Use this template". You will be prompted for the user and name
of the repository you would like to create and fill using this template.

Fork and clone your new repository as you normally would for any repository.

### Configure your new repository's basic information

Open and edit the following files, following the instructions in the comments
regarding which specific lines you need to edit to match your needs:

- _config.yml
- _docs/overview.md
- _includes/repository-overview.md
- README.md (to delete these instructions, if desired)
  
### Activate your documentation web page on github.io
  
Activate your new documentation site for loading via github.io as follows:

- navigate to your new repository on GitHub
- click "Settings"
- click the "Pages" tab on the left
- edit the "Source" to be branch 'main' and folder '/root'
- click 'Save'
  
After about a minute, your site will be live at the link indicated on the
Settings / Pages page.  It will track your respository to keep your site up
to date whenever you push or merge changes into the 'main' branch.
  
### Write your documenation files

Finally, create documentation page files within the '_docs' folder.
A few example files are present to help you see how pages are used,
which you can see in action here:

https://midataint.github.io/mdi-documentation-template/

## Just the Docs usage

Please see the 
[Just the Docs](https://pmarsceill.github.io/just-the-docs/) 
documentation.

## License

The content of this repository and web site is subject to
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/).

</div>
