# SOFA Support PRD Questionnaire

Bilingual interactive owner-approval questionnaire for the SOFA Support WordPress chat feature.

## Submission flow

- Drafts autosave in the respondent's browser (`localStorage`).
- Respondents can download a complete JSON backup at any time.
- Completed responses are sent over HTTPS through FormSubmit to `sgamal2593@gmail.com`.
- The first submission triggers a one-time activation email to that address.

No email credentials, API keys, or private chat data are stored in this repository.

## Local preview

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.
