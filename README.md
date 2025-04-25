# Basic example of a FastAPI application.

Create an Application:
- mkdir FaskAPI
- cd FastAPI
- python3 -m venv venv
- source venv/bin/activate
- pip install requirements.txt

Start App:
- uvicorn main:app --reload

Run a post request example:
- curl -X POST -H "Content-Type: application/json" 'http://127.0.0.1:8000/items?item=Banana'
- Or use Postman with "item = Banana" with URL - http://127.0.0.1:8000

View UI and Docs:
- http://127.0.0.1:8000/docs
