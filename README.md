# buiapiloopback

## 2.
### 4 Running the application
```
module.exports = function(server){
  var router = server.loopback.Router();
  router.get('/',function(req,res){
    res.send('')
  })
  server.use(router);
}
```
