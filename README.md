# Pridly — AI copilot for PrestaShop (remote MCP server)

Ask Claude or ChatGPT about your PrestaShop sales, stock and orders — and make safe changes with preview and undo.

- **MCP server URL:** `https://mcp.pridly.gridlypaper.com/mcp` (Streamable HTTP, OAuth 2.1)
- **Website:** https://pridly.gridlypaper.com/?utm_source=github
- **Add in Claude:** Settings → Connectors → Browse → search "Pridly"
- **Registry name:** `com.gridlypaper/pridly`

## What you can ask
- How did my PrestaShop shop do last week compared to the week before?
- What's running low on stock right now?
- Show unpaid orders older than 3 days.
- Which products have no Spanish description? Write them from the French ones.
- Undo change 12.

## Safety
- Read-only unless you allow changes. Every change is previewed first and waits for your "yes".
- Every change gets a number; "undo change 12" restores it.
- We never store your orders, products or customers. Keys are encrypted. Disconnect anytime.

## Plans
Free plan included. Paid plans: https://pridly.gridlypaper.com/pricing

## Support & privacy
support@gridlypaper.com · https://gridlypaper.com/privacy · https://gridlypaper.com/terms

Pridly is an independent product by GridlyPaper, not affiliated with PrestaShop. This repository holds the public listing only; the server is hosted.
