# Tesla Fleet API
In order to use the Tesla Fleet API Tesla has to provide a partner authentication token.
This token can only be acquired by publishing a public key on a public accessible domain.

## Cloudflare pages
An easy method to present the public key is to use cloudflare pages linked to a git repository such as the one you are looking at.

**It is very important to only publish the public key and to place it in the exact same directory structure and follow the same naming convention as used in this repo. Otherwise Tesla won't be able to retrieve your public key**
