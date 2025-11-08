
# toutatis-new

Repurposed and maintained by **Hirav Kadikar (HiravK)**.  
Originally based on Toutatis by megadose, licensed under GNU GPLv3 — see LICENSE.

## Overview
`toutatis-new` is a refined Python tool that retrieves public Instagram account metadata using a valid session ID.  
This version focuses on stability, cleaner output, and improved handling of obfuscated contact fields.

## Installation
```bash
git clone https://github.com/HiravK/toutatis-new.git
cd toutatis-new
python3 -m venv venv
source venv/bin/activate
pip install requests phonenumbers pycountry

Usage

python -m toutatis_new.core -u <username> -s <sessionid>
python -m toutatis_new.core -i <user_id> -s <sessionid>

License

Distributed under the GNU GPLv3 License.
See LICENSE for details.

Author: Hirav Kadikar
GitHub: HiravK￼
MD

git add README.md
git commit -m “Updated README with usage and overview”
git push

