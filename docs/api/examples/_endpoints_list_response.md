<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-06T15:27:14Z",
			"hostport": "d0c9a3aa38c1.ngrok.paid:443",
			"id": "ep_2pqg5IJvHUvmIwWctiTTog8EwJt",
			"name": "command_line",
			"principal": {
				"id": "usr_2pqg2oXcRiSLdsfGbVigsJfaH82",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://d0c9a3aa38c1.ngrok.paid",
			"tunnel": {
				"id": "tn_2pqg5IJvHUvmIwWctiTTog8EwJt",
				"uri": "https://api.ngrok.com/tunnels/tn_2pqg5IJvHUvmIwWctiTTog8EwJt"
			},
			"tunnel_session": {
				"id": "ts_2pqg5J0lHMQAjGYZctG0wZq7OWH",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2pqg5J0lHMQAjGYZctG0wZq7OWH"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-06T15:27:14Z",
			"upstream_url": "http://localhost:80",
			"url": "https://d0c9a3aa38c1.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-06T15:27:11Z",
			"domain": {
				"id": "rd_2pqg4rgj0NO0X3v4Ycx4klBWo2R",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2pqg4rgj0NO0X3v4Ycx4klBWo2R"
			},
			"edge": {
				"id": "edgtls_2pqg4uiLK86CdoheFfo6hvtE1MU",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2pqg4uiLK86CdoheFfo6hvtE1MU"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2pqg4xU0MoEJKO9QjziQ8yHByXh",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-06T15:27:11Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
