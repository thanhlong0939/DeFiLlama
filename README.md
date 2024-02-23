# DeFiLlama

[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)
[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-370/)
[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

[![Build](https://github.com/itzmestar/DeFiLlama/actions/workflows/python-package.yml/badge.svg)](https://github.com/itzmestar/DeFiLlama/actions/workflows/python-package.yml)

-------

### Unofficial [DeFi Llama API](https://defillama.com/home) client in python

For detailed information about the API endpoints, see [DeFi Llama API Documentation](https://docs.llama.fi/api)

### Installation:

use pip to install:

``` 
pip install DeFiLlama
```

-----------

### Authentication:

Endpoints are accessible without an API key.

-----------

### Example usage:

```
from defillama import DefiLlama

# initialize api client
llama = DefiLlama()

# Get all protocols data
response = llama.get_all_protocols()

# Get a protocol data
response = llama.get_protocol(name='uniswap')

# Get historical values of total TVL
response = llama.get_historical_tvl()

# Get protocol TVL
response = llama.get_protocol_tvl(name='uniswap')
```

# https://tea.xyz/what-is-this-file
---
version: 1.0.0
codeOwners:
  - '0x824259f3dD56f055482703E9609D4A7054FEFD9F'
quorum: 1
