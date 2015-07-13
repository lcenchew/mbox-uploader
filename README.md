# mbox-uploader
Imports Thunderbird MBOX files to GMail

## Requirements:
   * Python 2.7
   * Google Python API (https://pypi.python.org/pypi/google-api-python-client/)
   * Google Console API Client ID and Secret
   
This script allows the contents of Thunderbird MBOX files to be imported into
a Google Mail account.

## Setup
1.  Extract Google Python API to same folder containing mbox-uploader.py script
2.  Modify credentials.py and set values for CLIENT_ID and CLIENT_SECRET

## Usage

There are two command line switches:

--reauth : forces reauthentication
--redoall: forces reimporting of all messages in MBOX
