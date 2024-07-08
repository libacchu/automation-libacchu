# Connected Mobility Academy - automation

## Endpoint
The web application has a single endpoint:

### GET /hello
 - Returns an HTTP status of 200.
 - Response in JSON format:
   ```json
   {
     "hello": "world"
   }
    ```

## Getting started

1. Clone the repository:
 ``` shell
git clone https://github.com/libacchu/automation-libacchu.git
cd automation-libacchu
 ```
2. Create a virtual environment:
``` shell
python -m venv venv
source venv/bin/activate
```

3. Install dependencies:
``` shell
pip install fastapi "uvicorn[standard]"
```

4. Run the application:
``` shell
uvicorn main:app --reload
```

5. Access the application:

```
http://localhost:8000/hello
```

