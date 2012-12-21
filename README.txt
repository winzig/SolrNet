Forked from https://github.com/mausch/SolrNet

This fork adds:

 * Strong Name support, for easier compiling with other libraries that require it.
 * Soft Commit support, new in Solr 4.0. Call solr.SoftCommit() rather than Commit() (where "solr" is an ISolrOperations<T> object).