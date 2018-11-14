# Web Storage API

< Work in Progress >

> Using local storage in the browser with JavaScript.
> - A basic webpage with a search bar to input and store terms in the browser.
> - Search terms are saved in local storage and displayed on page.
> - Terms persist between browser sessions.
> - Clear search terms when needed.




## Tech & Dependencies

- [Express.js](https://expressjs.com/)
- [Syntactically Awesome Style Sheets (SASS)](https://sass-lang.com/)
- JavaScript


## Set-Up & Install Dependencies

- Clone repo
- Move to directory and run npm install
```
    npm install
```

## Notes

- Web storage limit is around 5-10MB.
- Stores on hard-drive.
- Persistent storage.
- Provides two objects for storing data on the client: `window.localStorage` and `window.sessionStorage`.
- `window.localStorage` - stores data with no expiration date
- `window.sessionStorage` - stores data for one session and data is lost when the browser tab is closed.
- Storage objects are strings in the form of key-value pairs and they stay intact during page loads.
- Web storage is accessed similar to objects.
- Integers will be stored as type string.
- Local storage can only be read by client-side while cookies are read by the server.

## Sources

- [Treehouse: Using Local Storage with JavaScript](https://teamtreehouse.com/library/using-local-storage-with-javascript)
- [MDN: Web Storage API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API)
- [MDN: Using the Web Storage API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API/Using_the_Web_Storage_API)
- [MDN Web Storage Demo](https://mdn.github.io/dom-examples/web-storage/)
- [W3 Schools: HTML 5 Web Storage](https://www.w3schools.com/html/html5_webstorage.asp)
- [HTML Storage APIs](https://medium.com/@ramsunvtech/onfocus-html5-storage-apis-b45d92aa424b)
- [Dr.Dobbs: The Local Storage API](http://www.drdobbs.com/web-development/the-localstorage-api/240000682)
- [Dr.Dobbs: Understanding Client Side Storage in the Web](http://www.drdobbs.com/web-development/understanding-client-side-storage-in-web/232900805)



