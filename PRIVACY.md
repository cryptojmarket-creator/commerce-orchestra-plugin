# Privacy

Commerce Orchestra is designed to keep account authentication and payment approval inside the user's existing commerce service.

The public Codex plugin does not itself collect passwords, card numbers, bank credentials, full delivery addresses, or raw app screenshots. A provisioned private runtime may process the minimum data needed to prepare a requested cart. Operational metrics should be limited to event time, platform, route, stage, outcome code, and duration.

Subscription checks send an installation identifier, request identifier, requested action, and plugin version to the entitlement service. The response contains access status, plan, remaining allowance, renewal timing, and a short-lived lease. Payment details are entered in the Toss Payments window and are not returned to Codex. The service retains the provider payment key and order identifier needed to verify, look up, or refund a transaction.

Users can stop the connection by disabling the plugin or removing the Commerce Orchestra MCP configuration.

This pilot notice will be replaced with the production privacy policy before public service launch.
