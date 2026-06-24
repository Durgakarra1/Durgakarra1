# gemini.md — Data Schema (PLACEHOLDER)

## Input Schema

{
  "jiraId": "VWO-48",
  "jiraBaseUrl": "https://your-domain.atlassian.net",
  "jiraEmail": "user@example.com",
  "jiraToken": "<token>",
  "groq": {
    "model": "openai/gpt-oss-120b",
    "endpoint": "https://api.groq.example/"
  }
}

## Output Schema

{
  "testPlan": {
    "title": "",
    "description": "",
    "testCases": [
      {
        "id": "",
        "title": "",
        "steps": [""],
        "expected": "",
        "type": "manual|automated"
      }
    ]
  }
}

Please confirm or edit this schema before implementation.
