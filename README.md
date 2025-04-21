# ai.hackclub.com

**ai.hackclub.com** is an experimental service provided by Hack Club offering free and unlimited access to OpenAI-compatible `/chat/completions` endpoints. This service is intended for educational use by teenagers participating in Hack Club. No API key is required.

---

## Features

- Unlimited access to a `chat/completions` endpoint.
- No authentication or API key required.
- Compatible with OpenAI’s Chat API format.
- Designed for educational and experimental use.

---

## Endpoint

```
POST https://ai.hackclub.com/chat/completions
```

---

## Example Usage (cURL)

```bash
curl -X POST https://ai.hackclub.com/chat/completions \
  -H "Content-Type: application/json" \
  -d '{
    "messages": [{"role": "user", "content": "Tell me a joke!"}]
}'
```

---

## Request Format

The request should follow OpenAI’s Chat API format, using a `messages` array with roles such as `"system"`, `"user"`, and `"assistant"`.

```json
{
  "messages": [
    { "role": "user", "content": "Hello, who are you?" }
  ]
}
```

---

## Intended Use

This service is provided for:

- Learning how chat-based AI models work
- Building prototypes, bots, and educational tools
- Exploring prompt engineering and conversational interfaces
- PROJECT USE ONLY - no personal use. This means no Cursor AI, or anything like that. 

Misuse or abuse of the service may result in access being revoked. 

---

## More Information

For more details about Hack Club and its offerings, visit [https://hackclub.com](https://hackclub.com).
