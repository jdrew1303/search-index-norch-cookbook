# Matcher
Most search engines has a matcher and a searcher. While the searcher is trying to find documents, the matcher tries to find words or terms. [`search-index` uses the matcher](https://github.com/fergiemcdowall/search-index/blob/master/doc/autosuggest.md#autosuggest-and-matching) to find words/terms that starts with what the user is typing and that is present in the documents. It sorts these terms with most used first.