# git_taxa
Use Git to manage a taxonomic classification.

GitHub provides a convenient interface to Git, one of the world's most battle-tested, accumulation-only, tree-based databases. You get:

- full version history of the tree
- clear auditing of who made what changes and when
- first-class access control (AuthN and AuthZ)
- communication tools for discussing changes
- checkpointing (fixed releases)
- ability to fork and maintain your own trees
- simple interface for merging pull requests

These are useful features for maintaining a taxonomic classification collaboratively. This example uses NSL's plant taxa (available here: https://biodiversity.org.au/nsl/services/api/export/taxonCsv ) filtered to only include accepted names (APC). Each directory uses the canonical name. Each node contains a JSON representation of the data for that taxon in a README file.

