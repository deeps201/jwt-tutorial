# jwt-tutorial


#### How to get a secret key
In your command line >>> access Python >>> then type:

##### OS Approach:

     import os
     os.urandom(14)

##### UUID Approach:

     import uuid
     uuid.uuid4().hex

##### Secrets [ only for Python 3.6 + ]

    import secrets
    secrets.token_urlsafe(14)
    
