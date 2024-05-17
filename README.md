const http=require('http');
const server=http.createServer();
server.on('request',(req,res)=>{
if(req.url=='/')=>{
res.end('hunan');
}
}
server.listen(3000,(req,res)=>{
console.log('success');
}
}
