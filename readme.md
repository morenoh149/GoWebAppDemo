# Writing Web Applications in Golang

use `go build` to compile the .go files

ex. `go build wiki.go`

run the executable like `./wiki`

See https://golang.org/doc/articles/wiki/

## Todo

* Store templates in tmpl/ and page data in data/.
* Add a handler to make the web root redirect to /view/FrontPage.
* Spruce up the page templates by making them valid HTML and adding some CSS rules.
* Implement inter-page linking by converting instances of [PageName] to 
<a href="/view/PageName">PageName</a>. (hint: you could use regexp.ReplaceAllFunc to do this)
* Deploy to web hosting that can run a binary
