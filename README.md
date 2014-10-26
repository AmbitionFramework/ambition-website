# ambition-website

This contains the source markup for the ambitionframework.org web site. The wiki
and static files are deployed into a Skra instance, which then parses the
markdown hierarchy.

To test changes to a file, get a Skra instance working from the examples
directory in the ambition repository, and symlink static and wiki from this
repository into that directory. You may then start a local instance of Skra
and navigate the site.

The wiki directory will follow the Skra conventions, where the directory path
under /wiki is the same path in the URL. The Markdown content is in the 'index'
file. Please do not commit Skra history pages (\d+) if you use Skra to alter
the content.
