# jomae

A dead-simple password management tool by gpg

## Config

You need to define next environment variables:

- JOMAE_EMAIL ... the email of your gpg key
- JOMAE_DIR ... the directory to save password.csv.gpg
- JOMAE_EDITOR ... the editor when editing password.csv

## Usage

```bash
jomae setup
jomae generate     ## generate password
jomae add "url,id,password,memo"
jomae search "google"
jomae id "google"
jomae password "google"
```
