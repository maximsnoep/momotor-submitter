# Momotor Submitter

Automating Momotor file submissions using a simple Python script.

## Usage

PyCharm is recommended.

* Create a new project (preferably using a virtual environment).
* Install the dependencies from `requirements.txt` from the banner at the top.
* Create a run configuration for `submitter.py`, and provide the following environment variables:
  * SUBMITTER_USERNAME: A valid canvas username.
  * SUBMITTER_PASSWORD: A valid canvas password.
  * SUBMITTER_URL: A url to the assignment submission page.
  * SUBMITTER_DIR: The absolute path to the directory which contains the files to upload, ending with a slash.
  * SUBMITTER_FILES: A comma-separated list of all names of the files to upload.
* Lastly, run.

## Furthermore

Bless [Samuel](https://github.com/justsamuel "Github Account") and [Thomas](https://github.com/PHPirates "Github Account").
