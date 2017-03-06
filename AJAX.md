AJAX ( Asynchronous Javascript And Xml )
is middleware for interacting with the browser asynchronously without the need for reloading.
It mainly uses 4 methods
#Get
used to get data 
```javascript
app.get( '/path', ( req, res) => {
    res.render( 'path', {
    } )    
} )
```
#Post
used to send data
```javascript
app.post( '/path', ( req, res ) => {
  upload req.body to somewhere
} )
```
#Put
can be used to edit something
Delete
can be used to delete something


