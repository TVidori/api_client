# Api Client v1

This is a repository used for explaining how to create a custom API client using aiohttp and asyncio. 
The whole tutorial can be found at: https://medium.com/@thomas.vidori/d9863b3ae7c2

If you need to adapt the code for a different API, modify the `API_BASE_URL` constant in `src/api_country_client.py` then adjust the existing two endpoints functions (`print_current_ip_and_its_country` and `get_ip_country`) to your needs. 
You can also add more endpoints.

This is a basic client and more complex ones (to handle tokens, parallelization...) will be created in new tutorials that will be released soon.
