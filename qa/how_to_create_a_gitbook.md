It took me some efforts to figure out how to create books deployed on GitHub, especially the post [Can I host my content on GitHub?](https://help.gitbook.com/github/can-i-host-on-github.html) is not up-to-date.

The flow is:

1. Create a book on GitBook with the template (Book, API or Knowledge Base)
2. Clone your book locally
3. Push to a Github Repo
4. Create a book by "import and sync an existing Github repository"

Right now the link between GitBook and GitHub is settled. It's merely a webhook that modifications on GitHub repo would notify GitBook to update.
