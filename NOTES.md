# Week 01 Notes

## 1. Pizza list evidence
Screenshot of GET /Pizza showing the original pizzas and my added pizza (Hawaiian):

![GET all pizzas](screenshots/get-all.png)

## 2. API operations

### GET
- Request: `GET /Pizza`
- Status: `200 OK`
- Response: (paste the JSON)

### POST
- Request: `POST /Pizza`
```json
{ "name": "Pepperoni", "isGlutenFree": false }
```
- Status: `201 Created`
- Response: (paste the JSON)

### PUT
- Request: `PUT /Pizza/1`
```json
{ "id": 1, "name": "Classic Italian Updated", "isGlutenFree": false }
```
- Status: `204 No Content`
- Response: empty body

### DELETE
- Request: `DELETE /Pizza/2`
- Status: `204 No Content`
- Response: empty body

## 3. Sales summary function
```csharp
(paste your full GenerateSalesSummary function here)
```