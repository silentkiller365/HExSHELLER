
# HExSHELLER

HExSHELLER is a command-line tool designed to check the accessibility of live shell paths on websites. It is particularly useful for web security researchers and developers. This tool is intended for educational and research purposes only.


## Installation

Clone the Repository:

```bash
  git clone https://github.com/yourusername/HExSHELLER.git


```

Install Required Packages:

```bash
  pip install -r requirements.txt



```

Run Script:

```bash
  python3 HExSHELLER.py 


```
    
## Usage/Examples

Single URL Mode

```bash
python HExSHELLER.py --url http://example.com

```
Batch Mode

```bash
python HExSHELLER.py --websites websites.txt --endpoints endpoints.txt

```
```bash
-w, --websites: Specify the file containing the list of websites (default: websites.txt).

-e, --endpoints: Specify the file containing the list of endpoints (default: endpoints.txt).

-t, --threads: Specify the number of concurrent threads (default: 10).

-u, --url: Specify a single URL to check.
--user-agents: Provide a list of user-agent strings.
```
## Example Files




websites.txt

```bash
http://example1.com
http://example2.com
http://example3.com
```

websites.txt

```bash
shell.php
admin.php
test.php
```
## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/)
 License. See the LICENSE file for more details.

## Disclaimer 



HExSHELLER is intended for educational and research purposes only. Use responsibly and ensure compliance with legal and ethical standards. Always obtain permission before testing any websites.
