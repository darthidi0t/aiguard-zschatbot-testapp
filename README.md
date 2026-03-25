Create a .env file in root directory with following content.




# Required:
PROXY_API_KEY="enter api guard key here"

# Proxy endpoint (default is the one you asked)
PROXY_URL="https://proxy.us1.zseclipse.net/v1/chat/completions"

# Model name passed to proxy (must be supported by your proxy)
MODEL_NAME="gpt-4.1-mini"

# Optional (only if you enable web_search tool usefulness):
TAVILY_API_KEY=""





Replace proxy_api_key with AI Guard API key and make sure Proxy URL is correctly pointed to AI Guard url.
