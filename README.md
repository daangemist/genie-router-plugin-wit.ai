This is a plugin for the [https://github.com/matueranet/genie-router](genie-router)
project. It uses the [wit.ai](https://wit.ai) service to create a brain that generates a
reply to the input from a client.

# wit.ai Setup

Create an app at wit.ai, navigate to its settings and copy the API key from the _API Details_
section.

# Genie Router configuration

Add a `wit` entry under the `plugins` section, and configure the accessToken retrieved from wit.ai.

```json
{
  "plugins": {
    "wit": {
      "accessToken": "<token goes here>"
    }
  }
}
```
