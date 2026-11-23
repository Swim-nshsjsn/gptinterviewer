# gptinterviewer

Practicing for a specific job starts with questions that match the role and your experience. gptinterviewer is a Python AI mock interview app that uses your resume and a job description to guide the conversation, with chat or voice interaction.

## Features

- Generate interview questions from an uploaded resume and a supplied job description.
- Choose a behavioral, professional, or resume-focused interview screen.
- Answer questions through chat or voice.
- Start a new interview session by refreshing the page.

## Installation

The commands below assume this standalone repository includes Python packaging and the command-line entry point shown in Usage. Those details are not established by the donor documentation and must be implemented before these instructions are release-ready.

From a local checkout:

```sh
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -e .
```

On Windows, activate the environment with `.venv\Scripts\activate` instead.

**Release setup:** Replace `YOUR_GITHUB_OWNER` with the repository owner. The download command assumes a source archive named `gptinterviewer-v0.1.0.tar.gz` has been attached to the `v0.1.0` GitHub release.

```sh
curl -fL https://github.com/YOUR_GITHUB_OWNER/gptinterviewer/releases/download/v0.1.0/gptinterviewer-v0.1.0.tar.gz -o gptinterviewer-v0.1.0.tar.gz
```

## Usage

The following is a proposed command-line interface for the standalone project, not a verified command from the donor:

```sh
gptinterviewer --resume ./resume.pdf --job-description ./job-description.txt --interview-type behavioral
```

In the interview interface, choose the relevant screen, upload your resume, and provide the job description. Select chat or voice, introduce yourself, and answer the generated questions. Refresh the page when you want to begin another session.

**Privacy:** Review your documents before uploading them. The donor identifies OpenAI as a technology dependency but does not document data retention or which document contents are sent to external services.

## License

MIT. This project is based on [jiatastic/GPTInterviewer](https://github.com/jiatastic/GPTInterviewer). Preserve the upstream copyright notice and MIT permission notice in any copied code or substantial portions of it, and include them with distributions.

## Related projects

The supplied related-project list identifies these as other repositories from the same author, but does not describe their functionality. Their purposes cannot be verified from the available information.

- [Hashswim/boxbilling](https://github.com/Hashswim/boxbilling): Listed related repository; no functional description was supplied.
- [nicolac93/ragtune](https://github.com/nicolac93/ragtune): Listed related repository; no functional description was supplied.
- [mayssahachim-dotcom/haven-platform](https://github.com/mayssahachim-dotcom/haven-platform): Listed related repository; no functional description was supplied.

