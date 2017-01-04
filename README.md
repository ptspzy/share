### Using GitBook  (For more:[Setup and Installation of GitBook](https://github.com/GitbookIO/gitbook/blob/master/docs/setup.md))

##### Install with NPM

The best way to install GitBook is via **NPM**. At the terminal prompt, simply run the following command to install GitBook:

```
$ npm install gitbook-cli -g
```

`gitbook-cli` is an utility to install and use multiple versions of GitBook on the same system. It will automatically install the required version of GitBook to build a book.

##### Create a book

GitBook can setup a boilerplate book:

```
$ gitbook init
```

If you wish to create the book into a new directory, you can do so by running `gitbook init ./directory`

Preview and serve your book using:

```
$ gitbook serve
```

Or build the static website using:

```
$ gitbook build
```