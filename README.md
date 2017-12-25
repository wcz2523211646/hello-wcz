# hello-wcz
wcz
const connection = mysql.createConnection({
	host:'localhost',
	port:3306,
	user:'root',
	password:'',
	database:'1512'
})
connection.connect((err) => {
	if(err){
		throw err;
	}
})
