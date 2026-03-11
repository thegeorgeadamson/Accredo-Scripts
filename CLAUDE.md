# Accredo Scripts - Project Rules

## Project Structure
- Only generate shared modules (auth, config, API helpers, .gitignore, README, etc.) when they are actually needed by a script being built — not upfront.
- Keep things lean. Don't over-engineer or scaffold beyond what's required for the current task.

## Accredo API Reference
- Full Accredo documentation is available at: /Users/georgeadamson/Documents/Accredo Scraper/accredo_documentation/Accredo_Complete_Documentation.md
- The Accredo API is a RESTful OData 4 JSON API using OAuth 2.0 (password grant) for authorisation.
- Demo/test API base URL: https://demo.accredo.co.nz:6569/saturn/odata4/v1/Company('demo')
- Common endpoints: ARCustomerList, ICProductList, INInvoiceList, OEOrderList
