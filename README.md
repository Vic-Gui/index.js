const express = require ('express')
const app = express();

app.use(express.static(__dirname + '/views');

app.listen(3000, function(){
  console.log(" o servidor esta no ar - porta: 3000!")
});

const bodyParser = require("body-parse");
app.use(bodyParser.urlencoded({extended:true}));
