This is a super simple little api to run with ur app or postman to play with locally.
I used the example from StableLM and expanded it.
https://github.com/Stability-AI/StableLM

Make sure Cuda is installed.
```
Install from here if you dont have it
https://pytorch.org/get-started/locally/
```
i would recoment to use anaconda or miniconda

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