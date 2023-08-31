Using 0000-00-00 for date in the filename, because I want to use :slug (based on filename title) for permalink. This forces the filename titles to be unique, so the slugs will be unique, and the permalinks will be unique. Otherwise when using :slug and two filenames differ only in date, one of the posts will not be served.

The flipside is this approach is that the date needs to be specified in the frontmatter.
