# GitHub markdown problems

## Can't specify the theme in which an image is shown to inside repository wiki markdowns
[Broken example in wiki](https://github.com/anttiharju/github-bugreport/wiki)

[Working example in repo](light-dark-example.md)

Both pages use the same markdown.

I think this feature would be important to have inside wikis to make the content look more professional. For example some mathematical notations are easiest to include with a transparent png and now the workaround is to add a background which is bound to look ugly in one of the themes. 

## Mermaid graph rendering breaks heading-specified links on first page load

It's caused by mermaid diagrams rendering after the viewport has been moved to the heading.

You might need to disable caching via your browser's debug console.

[Example](broken-heading-link.md#absolute-abroad-strawberry). Note that the viewport should be at bottom of page. The text at the bottom of the page best illustrates the need to fix this.
