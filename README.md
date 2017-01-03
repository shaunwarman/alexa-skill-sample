# alexa-skill-sample
A simple alexa skill

#### Gotchas
- Alexa skill must be deployed in US East (N. Virginia)
- Each version must have `Alexa Skill Kit` enabled as trigger
- Must have intent and utterance set against intent
- Must zip node_modules with upload and must use zip -r for recursive
- Must zip just files, not encapsulating folder
- intent name and event handler name must match
- You must upload a small and large thumbnail matching expected size before certification
- Need to further look at `alexa-sdk` for issues
