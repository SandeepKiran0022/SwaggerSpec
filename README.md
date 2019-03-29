# SwaggerSpec
Swagger Spec

# I have done the swagger spec alone for product mgt system

# Implemenatation is still not completely done..

# I have done a swagger generated server


## Models

<br>
<img src="https://github.com/SandeepKiran0022/SwaggerSpec/blob/master/screenshots/1.PNG">
</br>

<br>
<img src="https://github.com/SandeepKiran0022/SwaggerSpec/blob/master/screenshots/1.PNG">
</br>

<br>
<img src="https://github.com/SandeepKiran0022/SwaggerSpec/blob/master/screenshots/1.PNG">
</br>

# Sample implementation of node js

app.get('/user/login',function(req, res) {

  let page = req.query.username;
  let limit = req.query.password;
  let ans="400";
  //console.log("entered");
  res.send("successful user login");
});

//app.listen(3000);


app.post('/product',function(req,res)
{
res.send(req.body);
});
