# Blockchain

Requires use of API client such as cURL or Postman

$ python3 blockchain.py
 * Running on http://xxx.xxx.x.x:5000 (Press CTRL+C to quit)

Using cURL

# Make GET request
$ curl -X GET "http://localhost:5000/mine"

# Make POST request
$ curl -x POST -H "Content-Type: application/json" -d '{
 "sender": "sender-address",
 "recipient": "recipient-address",
 "amount": x
}' "http://xxx.xxx.x.x:5000/transactions/new"

# To view Blockchain
http://localhost:5000/chain

# POST request template
{
 "sender": "sender-address",
 "recipient": "recipient-address",
 "amount": x
}
