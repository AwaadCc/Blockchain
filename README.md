# Blockchain

Requires use of API client such as cURL or Postman

$ python3 blockchain.py
 * Running on http://xxx.xxx.x.x:5000 (Press CTRL+C to quit)

Using cURL
$ curl -x POST -H "Content-Type: application/json" -d'{
 "sender": "sender-address",
 "recipient": "recipient-address",
 "amount": x
}' "http://xxx.xxx.x.x:5000/transactions/new"

POST request template
{
 "sender": "sender-address",
 "recipient": "recipient-address",
 "amount": x
}
