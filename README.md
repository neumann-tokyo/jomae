# jomae

A dead-simple password management tool by gpg

## setup

```
sudo apt install gpg pwgen
```

## install

Please git clone this repository, and edit PATH in your `.bashrc` and stuff:

```
export PATH=/path/to/jomae/bin:$PATH
```

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

jomae help  ## See more documents
```
