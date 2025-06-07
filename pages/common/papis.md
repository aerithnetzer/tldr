# papis

> Powerful and highly extensible command-line based document and bibliography manager
> More information: <https://papis.readthedocs.io/en/latest/>.

- Add a document to a library


`papis add {/path/to/document} --from {doi/arxiv/bibtex/pmid} {argument}`

- Initialize a library

`papis init`

- papis exp
  add        Add a document into a given library
  addto      Add files to an existing document
  ask        Ask questions about your library.
  bibtex     Interact with BibTeX files
  browse     Open document's url in a browser
  cache      Manage the cache or database of a Papis library.
  citations  Handle document citations
  config     Print configuration values
  doctor     Check for common problems in documents
  edit       Edit document information from a given library
  exec       Execute a python file in the environment of papis' executable
  explore    Explore new documents using a variety of resources.
  export     Export a document from a given library
  git        Run git command in a library or document folder
  init       Initialize a papis library
  list       List document metadata
  merge      Merge two documents from a given library
  mv         Move a document into some other path
  open       Open document from a given library
  rename     Rename document folders
  rm         Delete a document, a file, or a notes-file
  run        Run an arbitrary shell command in the library or command folder
  serve      Start a papis server
  tag        Change a document's tags.
  update     Update document metadata
