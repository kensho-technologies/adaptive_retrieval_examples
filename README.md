# Adaptive Retrieval Examples

Example notebooks for [Adaptive Retrieval](https://docs.kensho.com/adaptive-retrieval/overview), Kensho's data retrieval service for accurate, trusted access to S&P Global data from any GenAI application. These notebooks let you experiment with Adaptive Retrieval through custom queries, view results in easy-to-read formatted tables, and inspect the full API responses for deeper analysis.

## Notebooks

- **[`search/adaptive_retrieval_search_external.ipynb`](search/adaptive_retrieval_search_external.ipynb)** &nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12cGA03pLwS3wRJ5ZJrmzaul7aqvpmaFR?usp=sharing)

  A straightforward interface for testing Adaptive Retrieval queries, selecting datasets, and displaying results in a tabular format using standard Python and pandas.

- **[`react_agent/adaptive_retrieval_react_agent_external.ipynb`](react_agent/adaptive_retrieval_react_agent_external.ipynb)** &nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1AOuULeSxJ-FgaV2BfRyMYPEiYPEzYEij?usp=sharing)

  A ReAct-style agent integrated with Adaptive Retrieval, providing out-of-the-box support for multi-step reasoning over the API.

## API Access

To request access to Adaptive Retrieval, contact [commercial@kensho.com](mailto:commercial@kensho.com).

The notebooks call the Adaptive Retrieval API (`POST https://grounding.kensho.com/api/v2/search`) and require an access token. There are two ways to obtain one:

- **Browser login (interactive users):** Sign in at [grounding.kensho.com/login-spgi](https://grounding.kensho.com/login-spgi) and copy the access token shown on the page. Tokens are valid for 1 hour.
- **Keypair authentication (service accounts):** Use the OAuth 2.0 `private_key_jwt` client credentials flow with your S&P Global client ID and private key.

See the [API Guide](https://docs.kensho.com/adaptive-retrieval/api-guide) for full authentication details and the [API reference](https://grounding.kensho.com/redoc) for the endpoint schema.

## License

Licensed under the Apache License, Version 2.0. See [LICENSE](LICENSE) for details.

Copyright 2026-present Kensho Technologies, LLC.
