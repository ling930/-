{
  "name": "DMXS1",
  "url": "https://www.dmxs1.com",
  "version": 1,
  "search": {
    "method": "GET",
    "url": "/search?q=${key}",
    "charset": "utf-8",
    "list": "div.book-list > div.book-item",
    "name": "h2 > a",
    "author": "div.author",
    "cover": "img.cover",
    "detail": "h2 > a"
  },
  "detail": {
    "method": "GET",
    "charset": "utf-8",
    "name": "h1.book-title",
    "author": "div.book-author",
    "cover": "img.book-cover",
    "intro": "div.book-intro",
    "update": "div.book-update",
    "catalog": "div.book-catalog > a"
  },
  "catalog": {
    "method": "GET",
    "charset": "utf-8",
    "list": "div.chapter-list > div.chapter-item",
    "name": "a",
    "url": "a"
  },
  "chapter": {
    "method": "GET",
    "charset": "utf-8",
    "content": "div.chapter-content"
  }
}
