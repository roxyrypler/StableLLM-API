

Make sure Cuda is installed.
make sure you use anaconda or miniconda

install:
```
pip install -U pip
```
```
pip install accelerate bitsandbytes torch transformers
```
```
pip install flask
```

Api will be available on port 5555

POST endpoints
```
/llm
```
needs this bodyData
```
{
    "prompt": "What is life?"
}
```