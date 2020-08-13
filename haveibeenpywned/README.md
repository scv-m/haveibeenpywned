# haveibeenpywned

A simple python wrapper for the www.haveibeenpwned.com API.

## Installation

Use the package manager [pip](https://www.google.com) to install foobar.

```bash
pip install haveibeenpywned
```

## Usage

```python

from haveibeenpywned import Pywned

pywned = Pywned("your-hibp-api-key")
resp = pywned.get_all_breaches_names_for_account("email@address.com")
print(resp)

['8tracks', 'AbuseWithUs', 'AntiPublic', 'BlankMediaGames', 'Dubsmash','MySpace'] 
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Authors
- **Sam** - [scv-m](https://gist.github.com/scv-m)
- **Eric** - [buzzlight](https://github.com/buzzlight)

See also the list of contributors who participated in this project.

## License
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/)
>
>In other words, you're welcome to use the public API to build other services, but you must identify Have I Been Pwned as the source of the data . Clear and visible attribution with a link to haveibeenpwned.com should be present anywhere data from the service is used including when searching breaches or pastes and when representing breach descriptions. It doesn't have to be overt, but the interface in which Have I Been Pwned data is represented should clearly attribute the source per the Creative Commons Attribution 4.0 International License.
>
> &mdash; https://haveibeenpwned.com/API/v3#License

## Acknowledgements
- [Troy Hunt](https://www.troyhunt.com/)
- [Have I Been Pwned](https://www.haveibeenpwned.com)