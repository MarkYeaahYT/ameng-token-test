- create token with metadata
root@898f9e088eef:~# spl-token --program-id TokenzQdBNbLqP5VEhdkAS6EPFLC1PHnBqCXEpPxuEb \
create-token --enable-metadata
Creating token C61JRMyBri7bYTXYszoCDXQxCLjE2CjpPNLQapj3RFmb under program TokenzQdBNbLqP5VEhdkAS6EPFLC1PHnBqCXEpPxuEb
To initialize metadata inside the mint, please run `spl-token initialize-metadata C61JRMyBri7bYTXYszoCDXQxCLjE2CjpPNLQapj3RFmb <YOUR_TOKEN_NAME> <YOUR_TOKEN_SYMBOL> <YOUR_TOKEN_URI>`, and sign with the mint authority.

Address:  C61JRMyBri7bYTXYszoCDXQxCLjE2CjpPNLQapj3RFmb
Decimals:  9

Signature: 4tXXVoLtFMJcRpTgTZp3KbMR7Q7d4Xu1KKdSsdP9R2KZTJnhvRHqUPw8raubqdS6bvKztd9fdpQWTJFPbfYrvWDC

root@898f9e088eef:~# spl-token --program-id TokenzQdBNbLqP5VEhdkAS6EPFLC1PHnBqCXEpPxuEb \
initialize-metadata C61JRMyBri7bYTXYszoCDXQxCLjE2CjpPNLQapj3RFmb \
"Ameng" \
"AMG" \
"https://raw.githubusercontent.com/MarkYeaahYT/ameng-token-test/master/metadata.json"

Signature: 475wi3s3zbzeSYbKJky5gAPS3gPtkNSuSMkrmw47cmRi3jdTZVqdd8MXjPvY368cZWGdEaPbEMmtJGeiWKqLbv5k