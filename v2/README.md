### Edgewise v2 GraphQL API

#### Prerequisites
* Python 3.x
* Requests
* PyYAML

Convert your mTLS .pfx file to cert/key PEM format:  
`openssl pkcs12 -in <mtls_cert_file>.pfx -nokeys -out cert.pem -nodes`  
`openssl pkcs12 -in <mtls_cert_file>.pfx -nocerts -out key.pem -nodes`  

#### Instructions
* Clone the repo and cd to `./python`
* Update `config.yaml`
* Install Python 3
* Install the prerequisites: `pip3 install -U requests pyyaml`
* Run the script: `python3 script.py`

