# Jobrex Client

Jobrex Client is a Python package that provides a simple interface to interact with the Jobrex API, which offers AI-powered recruitment services including resume parsing, job matching, and more.

## Features

* Resume parsing and analysis
* Job description extraction and analysis
* Resume and job matching
* Zoom meeting creation for interviews
* Indexing and searching of resumes and jobs
* Resume rewriting and tailoring for job applications

## Installation

You can install Jobrex Client using pip:
```
pip install jobrex-client
```
## Usage

Here's a simple example of how to use the Jobrex Client to parse a resume:
```python
from jobrex import ResumesClient

# Initialize the client with your API key
client = ResumesClient(api_key="your_api_key_here")

# Parse a resume
resume_response = client.parse_resume("path/to/your/resume.pdf")
print(resume_response)
```
For more examples and documentation, please refer to the [Jobrex Client documentation](https://github.com/jobrex-ai/jobrex-client).


## License

Jobrex Client is licensed under the MIT License.
