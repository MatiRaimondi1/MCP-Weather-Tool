# ☔ MCP Weather Tool 🌧️
This is a simple MCP weather server that allows LLMs fetch forecast and weather alerts.

## ⚙️Setup
Connect the server to your LLM, for example, If you are using Claude Desktop add this to your config file:

    {
    "mcpServers": {
        "weather": {
            "command": "uv",
            "args": [
                "--directory",
                "C:\\ABSOLUTE\\PATH\\TO\\PARENT\\FOLDER\\weather",
                "run",
                "weather.py"
            ]
        }
    }

## 🔨 Commands
+ Get weather alerts for a US state. (Two letter US state code required).
+ Get weather forecast for a location. (Latitude and Longitude of the location required).
