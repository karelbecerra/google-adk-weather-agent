# Google ADK Sample

This is a sample project that demonstrates how to use the Google ADK.

## Setup

Create a `.env` file or copy `.env.sample` inside the directory with the following environment variables:

```bash
GOOGLE_GENAI_USE_VERTEXAI=FALSE
GOOGLE_API_KEY=YOUR_GOOGLE_API_KEY
```

To install the dependencies, run the following command:

```bash
uv sync
```

## Running the project

```bash
uv run adk web
```

![Web App](iamges/web.png)


```bash
uv run adk run weather_agent
```

![Terminal](iamges/terminal.png)
