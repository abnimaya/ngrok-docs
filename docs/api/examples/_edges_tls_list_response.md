<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-06T15:27:23Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2pqg6OZJ2Hksahnmwe4aUsy0BdG",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pqg6OZJ2Hksahnmwe4aUsy0BdG"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2pqg4uNwWWVO3AUBKNj0AtXAQAa",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2pqg4uNwWWVO3AUBKNj0AtXAQAa"
				},
				"enabled": true
			},
			"created_at": "2024-12-06T15:27:11Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2pqg4uiLK86CdoheFfo6hvtE1MU",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2pqg4uiLK86CdoheFfo6hvtE1MU"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
