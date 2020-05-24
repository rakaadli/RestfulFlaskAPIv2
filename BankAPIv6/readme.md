http://127.0.0.1:5000/register
{
	"username" : "BANK",
	"password" : "12345"
}

{
	"username" : "test1",
	"password" : "12345"
}

{
	"username" : "test2",
	"password" : "12345"
}

http://127.0.0.1:5000/add
{
	"username" : "test1",
	"password" : "12345",
	"amount" : 200
}

http://127.0.0.1:5000/transfer

{
	"username" : "test1",
	"password" : "12345",
	"to": "test2",
	"amount" : 40
}

http://127.0.0.1:5000/balance
{
	"username" : "test1",
	"password" : "12345",
	<!-- "to": "test2",
	"amount" : 40 -->
}

{
	"username" : "test2",
	"password" : "12345",
}

http://127.0.0.1:5000/takeloan
{
	"username" : "test2",
	"password" : "12345",
	"to": "test2",
	"amount" : 5
}