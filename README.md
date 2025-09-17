# PCPP_API
The API Backend for my Custom PCPP Android App.  
This Backend was built to be used in conjunction with the [PyPartPicker API](https://github.com/thefakequake/pypartpicker) created by thefakequake.  

Please follow their instructions for installation. Running the API locally or externally is essential for use of my custom Android App.

## Example Usage
Search for parts (CPU, GPU, etc):  
`GET http://localhost:5000/search?query=cpu&limit=10&page=1`

Fetch product details:  
`GET http://localhost:5000/product?url=<product_url>`

## Notes
Default region is `us`  
API runs on port `5000` by default

## Setup   
Clone the repo and install dependencies:
