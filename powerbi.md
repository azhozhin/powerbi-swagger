# Power BI for Python
> see https://aka.ms/autorest 

## Getting Started 
To build the SDK for PowerBI API, simply install AutoRest via `npm` (`npm install -g autorest`) and then run:
> `autorest powerbi.md`

``` yaml
input-file: swaggers\swagger.json
use-extension: 
    "@autorest/python" : "6.9.7"
python:
    output-folder: src
    add-credentials: true
```
