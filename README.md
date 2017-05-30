# Eail Exclude Regex
When validating emails we want to exclude cirtain domains. Note the bold domains, please add to this list in order to exclude

/^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@(?!(?:gmail|hotmail|yahoo|aol|comcast|facebook|gmx|googlemail|google|mac|me|mail|msn|live|sbcglobal|verizon|games|hush|hushmail|icloud|inbox|lavabit|love|outlook|pobox|rocketmail|save-mail|wow|ygm|ymail|yandex|iname|zoho|fastmail|bellsouth|charger|comcats|cox|earthlink|juno))((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/i


Exclution list taken from [mailcheck/mailcheck](https://github.com/mailcheck/mailcheck/wiki/List-of-Popular-Domains)
