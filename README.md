# api-trigger-test



```
curl -X POST https://circleci.com/api/v2/project/github/AwesomeCICD/api-trigger-test/pipeline/run \
  --header "Circle-Token: $CIRCLE_TOKEN" \
  --header "content-type: application/json" \
  --data '{
  "definition_id": "323ab245-b4a7-58e1-aaba-12ab89350e4c",
  "config": {"branch": "main"},
  "checkout": {"branch": "main"},
  "parameters": {
    "param1": "Automation",
    "param2": "in",
    "param3": "software",
    "param4": "development",
    "param5": "helps",
    "param6": "streamline",
    "param7": "complex",
    "param8": "processes",
    "param9": "and",
    "param10": "reduce",
    "param11": "human",
    "param12": "errors",
    "param13": "while",
    "param14": "enhancing",
    "param15": "efficiency",
    "param16": "and",
    "param17": "consistency",
    "param18": "across",
    "param19": "deployments",
    "param20": "making",
    "param21": "CI/CD",
    "param22": "pipelines",
    "param23": "a",
    "param24": "critical",
    "param25": "tool"
  }
  }'

```
