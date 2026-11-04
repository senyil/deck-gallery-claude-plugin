# Deck.gallery

![Deck.gallery](assets/icon.png)

Find ideas for your next presentation in pitch decks, brand guidelines and annual reports. Find examples of a specific slide, explore how a deck is structured and compare ways to present a product, visual identity or set of results.

Deck.gallery returns slide previews when available, deck outlines and links back to each reference. Results follow your connected account's existing access.

## Skills

Version 0.1.1 includes three skills for presentation reference research:

- `best-practices`: use references accurately, inspect supplied images and respect access limits.
- `search`: find relevant decks and slides, then refine and select useful matches.
- `analyze-deck`: explain a deck's story and visual choices using verified slides and source links.

The skills guide the existing reference tools. They do not add presentation editing or export tools.

## Connect

After adding the plugin in Claude, open its Connectors tab, add the Deck.gallery connector if needed, and connect your account through the sign-in flow. On an organization account, an owner may need to add the connector before members connect their own accounts. Claude Code connects to the declared remote server and uses its authorization flow.

## Try these prompts

- Find pitch decks for a SaaS startup and show how they introduce the product.
- Show me three different layouts for a pricing slide.
- Find a brand guidelines deck and walk me through its structure.

## Data and access

The plugin connects to `https://mcp.deck.gallery/mcp`. Requests send search text, selected deck identifiers, filters and pagination parameters to Deck.gallery. The service checks account permissions and usage limits before returning results. Its tools read the reference library.

Deck.gallery keeps account and service-usage records. The privacy policy explains data handling and account deletion. This bundle contains connection settings, listing text, three skill instruction files and the brand icon. It runs no local programs and includes no deck content or credentials.

## Help

If access is unavailable, check that the intended Deck.gallery account is connected. Contact support if a connection or result does not work as expected.

[Documentation](https://www.deck.gallery/mcp/) · [Support](https://www.deck.gallery/mcp/#support) · [Privacy](https://www.deck.gallery/privacy/#privacy) · [Terms](https://www.deck.gallery/privacy/#terms)

Deck.gallery is operated by Anymo Ltd.

## License

The configuration files and original README text use the MIT License. The brand icon has separate permission for unchanged distribution with this plugin and identification of Deck.gallery. The service and referenced presentations are excluded. See [LICENSE](LICENSE).
