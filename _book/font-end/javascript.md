```javascript
function Book(title, pages, isbn) {
    this.title = title;
    this.pages = pages;
    this.isbn = isbn;
    this.showPages = function(){
        console.log(this.pages);
    }
}
Book.prototype.showTitle=function(){
    console.log(this.title);
}

var book = new Book('title', 'pag', 'isbn');

book.showTitle();
book.showPages();

```