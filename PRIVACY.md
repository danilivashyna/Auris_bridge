# Auris Bridge — Privacy Policy

  This Custom GPT Action ("Auris Bridge") connects to a private LLM server
  running locally on the operator's Mac, exposed via ngrok.

  ## What data is sent
  - Messages you send to the GPT are forwarded to the local server (`/chat` endpoint).
  - The server processes them with Qwen3.6-35B + S1/FAB layer and returns a response.

  ## What data is stored
  - Each exchange (message + response) may be saved as a local KV-cache file
    in `chronicles/` on the operator's Mac, used as memory for future calls.
  - No third-party services receive message content.
  - The operator (Daniil Ivashina) does not collect, share, or sell any data.

  ## Infrastructure
  - Ngrok logs connection metadata (timestamps, IP addresses) per its own terms.
  - The local server requires a secret token in the request header for access.

  ## Contact
  For questions or removal requests: danil.ivashina@gmail.com
