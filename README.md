curl -X "PUT" -H "Content-Type: application/json" -d "{\"id\": \"123\", \"price\": 12345, \"name\": \"myitem\"}" https://pn2qh7tb2j.execute-api.us-east-1.amazonaws.com/items

curl -X "PUT" -H "Content-Type: application/json" -d "{\"id\": \"456\", \"price\": 789, \"name\": \"myitem4\"}" https://pn2qh7tb2j.execute-api.us-east-1.amazonaws.com/items

curl https://pn2qh7tb2j.execute-api.us-east-1.amazonaws.com/items

curl https://pn2qh7tb2j.execute-api.us-east-1.amazonaws.com/items/456

curl -X "DELETE" https://pn2qh7tb2j.execute-api.us-east-1.amazonaws.com/items/456

curl https://pn2qh7tb2j.execute-api.us-east-1.amazonaws.com/items