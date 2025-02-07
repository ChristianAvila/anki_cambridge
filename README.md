Anki Add-on for integration with Cambridge Dictionary web site - https://dictionary.cambridge.org/

IMPORTANT: This add-on doesn't use official API - only web-scraping.

What it's done (so far):
 - Creating notes from link to a word (word title, definition, grammar, IPA, sound, meanings, examples)
 - Fetching words from your wordlists - if you supply cookie for you account and wordlist IDs
 - Config settings management - save cookie, wordlist IDs
 - Native authentication - through Cambridge account
 
Please, follow these links for quick visual how-to guide.
https://ibb.co/94cq40m
https://ibb.co/WBzw37R

Your own cookie you can extract, for example, from web browser - Chrome - F12 and refresh page on cambridge 

## Auth with native authentication

- Click on Sign in
- Write your Cambridge email and password
- Click on Log in 
- Once you are authenticated, you can close the web window
- The cookie will be stored automatically in the configuration

To do (contributors are welcome):
 - OpenID authorization - through Google/Facebook
 - Token management - keeping and renewal
 - Refine UI

## Development

For local development create a symbolic link to your anki's add-on folder

```sh
ln -s {path_to_this_project} {path_to_anki_addon_folder}/anki_cambridge
ln -s /path/to/code/anki_cambridge "/path/to/anki/Anki2/addons21/anki_cambridge"
```
