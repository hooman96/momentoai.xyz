# Momento AI: Next-Generation Cloud Mapping

**Momento AI GPT**

[Try our custom GPT](https://chatgpt.com/g/g-2m6AzGbPX-cloud-optimization-advisor-momentoai-gpt)
* You can insert your codebase from Github URL and get an analysis of your cloud services, security score, etc
* Feel free to upload your cloud providers bill for additional insights
* Stay tuned for our own custom RAG model as we scale our business

**Momento AI Usage**
* We built robust APIs and easy to use SDK, here is an example:

```python
from momento import CacheClient, Configurations, CredentialProvider
import requests

momento_client = CacheClient(
    configuration=Configurations.Laptop.v1(),
    credential_provider=CredentialProvider.from_env_variable("MOMENTO_AUTH_TOKEN"),
    default_ttl_seconds=600  # Time-to-live for cache entries in seconds
)

momento_client.create_cache(cache_name="my-momento-cache")

cache_result = momento_client.get(cache_name, api_url)
```

[Read our about our memo](http://momentoai.xyz/memo)

**Conclusion**

Momento AI empowers businesses to take control of their cloud environments, reduce costs, and drive innovation. Start your cloud optimization journey with Momento AI today! Email us at [hooman@momentoai.onmicrosoft.com](mailto:hooman@momentoai.onmicrosoft.com)
