# nabih-directory

The service directory of the Nabih app: for each service, its name, sender
domains, category and official cancellation link.

The app downloads `services.json` from this repository once a day. The file
contains no personal data. Every link must be `https` and on the service's own
site (or apple.com, google.com, youtube.com, microsoft.com, amazon.com);
the app ignores any entry that breaks this rule.

To update a link: edit `services.json`, change `verified` to the day you
checked the link, and change `updated` at the top to today's date.
