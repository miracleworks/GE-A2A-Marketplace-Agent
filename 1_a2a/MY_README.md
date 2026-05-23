# Run Server
uv run adk api_server --a2a --port 8001 remote_a2a/

#### Agent card URL
```
http://localhost:8001/a2a/remote_time_agent/.well-known/agent-card.json
```



# Run Client
uv run adk web

#### Agent Card URL
`
agent_card=
    (f"http://localhost:8001/a2a/remote_time_agent{AGENT_CARD_WELL_KNOWN_PATH}"
     ),
`
