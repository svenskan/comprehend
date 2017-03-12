# Comprehend

A tool for checking Swedish pronunciation using [Google Cloud Speech API][1].

## Installation

```bash
brew install sox --with-flac
pip install google-api-python-client
export GOOGLE_APPLICATION_CREDENTIALS="<PATH TO YOUR SERVICE ACCOUNT’S CREDENTIALS>"
```

The instructions for setting up a service account can be found [here][2].

## Usage

```bash
./bin/comprehend                 # check an arbitrary phrase
./bin/comprehend Hej då!         # check a specific phrase
./bin/comprehend phrases.txt     # check random phrases from a file
```

[1]: https://cloud.google.com/speech/
[2]: https://cloud.google.com/speech/docs/common/auth#service-accounts
