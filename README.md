# Notes-Api Backend
The Notes API backend is a learning project focused on backend development.\
It is part of a collaboration with Dicoding Indonesia as a submission for course completion in Dicoding, within the ID Camp 2024 event.

## The Resouce of This Project Have.
- Adding new note (POST)
- Getting all note (GET)
- Getting note by id (GET)
- Changing value of note by id (PUT)
- Deleting note by id (DELETE)

## Initialisation Guide
### Requirement
- Node.js 18+

## Instalation & Clone this Repository.
### Cloning Repository.
```bash
cd ~
git clone https://github.com/PFebrianoooo/Notes-Api.git
cd Notes-Api
code .
```
## Routes URL
You cam simply use Postman for testing purpose only. by setting and sending data by JSON File Or using command below.
### Adding New Note (POST)
```bash
curl -X POST -H "Content-Type: application/json" -d '{"title": "This is first title", "tags": ["Android", "Web", "iOS], "body": "This is the message"}' https://localhost:PORT/notes
```
### Getting All Note (GET)
```bash
curl https://localhost:PORT/notes
```

### Getting Note by Id (GET)
```bash
curl https://localhost:PORT/ffadR7h
```
### Changing Value of Note by Id (PUT)
```bash
curl -X PUT -H "Content-Type: application/json" -d '{"title": "This is second title"}' https://localhosy:PORT/notes/ffadR7h
```

### Delete of Note by Id (DELETE)
```bash
curl -X DELETE https://localhost:PORT/notes/ffadR7h
```
