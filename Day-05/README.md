import sys

# to read the system variable from cmd prompt.
num1 = sys.argv[1]


os module for environment variables.env vars are mainly used for senstive information like passwords,API keys,API tokens,certs etc.

# set the password 

export password = "value"

import os

# to retrieve the password
password = os.getenv("password")
