To check Similarity using spacy

Register First
http://127.0.0.1:5000/register (POST)
example BODY RAW JSON
{
	"username" : "raka",
	"password" : "12345"
}

http://127.0.0.1:5000/detect (POST)
example BODY RAW JSON
{
	"username" : "raka",
	"password" : "12345",
	"text1" : "this is a cute dog",
	"text2" : "wow,this dog is so cute"
}
Example response
{
    "msg": "Similarity score calculated successfully",
    "ratio": 0.5532207983640599,
    "status": 200
}

http://127.0.0.1:5000/refill
example BODY RAW JSON
{
	"username" : "raka",
	"admin_pw" : "abc123",
	"refill" : 4
}