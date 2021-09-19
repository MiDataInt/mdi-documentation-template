## MDI Documentation
{% include mdi-project-documentation.md %}{% include repository-overview.md %}
<div style="display: {% if site %} none {% else %} block {% endif %};">
  
## Template description

The **mdi-documentation-template** repository is a starting point
for all 
[GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)
documentation sites for repositories that are 
part of, or associated with, the **Michigan Data Interface**.

This template uses the open source documentation theme 
[Just the Docs](https://pmarsceill.github.io/just-the-docs/).

## Template usage

Clone, copy or download this repository. Etc.

Please keep the first tag of README.md as '## MDI Documentation'. 
'MDI Documentation' will then appear as the last page link in your table of 
contents and will display the two markdown files included at the top of this file. 

## Just the Docs usage
Please see the 
[Just the Docs](https://pmarsceill.github.io/just-the-docs/) 
documentation.

## Bug note

Given how GitHub Pages are
built, you _cannot_ include Jekyll front matter in README.md. If you do,
you will get a 404 Page Not Found error. Accordingly, you
_cannot_ use 'nav_exclude' to prevent README.md from being indexed by
Just the Docs, nor can you use 'nav_order' to force it to be listed first.
You also _cannot_ simply remove README.md as this will 
also cause GitHub Pages to return a 404 error. Ensuring that README.md
is always present but last is an effective workaround for this behavior.
  
</div>

