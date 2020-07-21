## Read: 13 - Local Storage
**What is HTML Web Storage?**
With web storage, web applications can store data locally within the user's browser.

Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.

Unlike cookies, the storage limit is far larger (at least 5MB) and information is never transferred to the server.

Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.

HTML web storage provides two objects for storing data on the client:

```window.localStorage``` - stores data with no expiration date
```window.sessionStorage``` - stores data for one session (data is lost when the browser tab is closed)
Before using web storage, check browser support for localStorage and sessionStorage:
```
if (typeof(Storage) !== "undefined") {
  // Code for localStorage/sessionStorage.
} else {
  // Sorry! No Web Storage support..
}
```
![Local storage](https://lh3.googleusercontent.com/proxy/g1QcSv1r4hG9gseJS-oyijhU1rDexYVz5GrQAaGrn9vfruT2G8Q0YoikK-ac9XYJtiYmRId5V36b8UuP5zI27xGB6aVgZr8Ux9uL5Zxbfj29LXlQZfKON1d8-kJHNm54vjWhL4FpPafY9Qg6lZnWKWw99NO-botXN-qpl4oHIDdLTTF5s3dnpWXmYfdzSWur_XFTFnQ0BHaSykAvpbmv)