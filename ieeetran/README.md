# ieeetran Template

Template using the ieeetran conference document class.

# Template Variables

Variables have two potential configuration points, which will be described here. The first point is the frontmatter variable name, which is used by the underlying system to identify the value at build time. The second point is the placeholder value, which can be replaced during the new command, or manually edited later. For the following description, variables will be named in the format `Variable Name, Placeholder Name - Description`

## MultiMarkdown Frontmatter
1. `latex author`,`$AUTHOR` - name of the paper author
2. `latex title`, `$TITLE` - title of the document
3. `bibtex`, `$BIBTEX` - defines the Bibtex file to process for this document. Delete this line to eliminate bibliography support
8. `myassociation`,`$ASSOCIATION` - if included, association of the paper author
9. `my abstract` - `$ABSTRACT` - location of the abstract file
10. `myacknowledgments` - `$MYACKNOWLEDGMENTS` - if included, the location of the acknowledgments file
6. `my packages` - `$PACKAGES` - if included, injects the contents of this file into the document before the document begins, allowing additional packages or LaTeX options to be defined.

## LaTeX Variables

These variables are not included in the frontmatter by default, since they aren't always in use. Some of these variables require being defined in a LaTeX file (e.g. the packages file) due to requiring LaTeX commands.

1. `my columns` - defines the number of columns for the document to use, defaulting to `onecolumn` if undefined.
2. `my doc class` - defines the document style to use, either `conference` (default) or `journal`.
3. `my association` - if included, association of the paper author(s). This will require being defined in a LaTeX file.
3. `my keywords` - keywords for this document
