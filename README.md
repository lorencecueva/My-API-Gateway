# My-API-Gateway
1. Place the `my_api_gateway` folder in XAMPP's `htdocs/`.
2. Start Apache in XAMPP.
3. Test endpoints using:
   - `curl -H "X-API-Key: key123" http://localhost/my_api_gateway/api/users`
4. Valid API keys: `key123`, `key456`.
5. Rate limit: 10 requests/minute per key.
6. View logs at `my_api_gateway/logs/gateway.log`.
