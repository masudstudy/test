# FastApi

# *Installation*:

```xml
pip install fastapi
pip install "uvicorn[standard]"

**link : https://fastapi.tiangolo.com/tutorial/**
```

```python
#first code 
from fastapi import FastAPI

app = FastAPI()

@app.get("/")
async def root():
    return {"message": "Hello World"}
```

# ***To run the code Type*:**

```python
python -m uvicorn firstapi:app --reload
uvicorn main:app --reload
```

# ***To use Swagger Type***

[**http://127.0.0.1:8000/docs**](http://127.0.0.1:8000/docs)

![Untitled](FastApi%20f1893fcd2c09429a937b3fba3f53bb6a/Untitled.png)

Link : 

[FastAPI - A python framework | Full Course](https://www.youtube.com/watch?v=7t2alSnE2-I)

[Another Source link](https://www.notion.so/Another-Source-link-2c6e311f1a354d4d88e45c6583eb37d4?pvs=21)

![Untitled](FastApi%20f1893fcd2c09429a937b3fba3f53bb6a/Untitled%201.png)

![Untitled](FastApi%20f1893fcd2c09429a937b3fba3f53bb6a/Untitled%202.png)

[Database connection](https://www.notion.so/Database-connection-e5fff24bc60e437d8aa318859a06b6d2?pvs=21)

![Untitled](FastApi%20f1893fcd2c09429a937b3fba3f53bb6a/Untitled%203.png)