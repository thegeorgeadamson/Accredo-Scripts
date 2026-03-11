# Accredo Scripts

Custom MaxBasic scripts and forms for Proline Protective Coatings' Accredo Saturn system.

## Scripts

| File | Description |
|------|-------------|
| `MixBank_NewLine.pfs` | Opens the current MIXJOTUN invoice and appends a new line ready for entry |
| `OrderPicking.pfs` | Launches the Proline Order Picking form |

## Custom Forms

| File | Description |
|------|-------------|
| `OrderPicking_Proline.pfd` | Rebuilt order picking form — keyboard/mouse friendly, with unprocessed orders list and "Pick All" workflow |

## Folders

- `barcoding/` — Original Accredo barcoding custom forms (reference/fallback)
- `proline/` — Proline-specific custom forms

## Setup

Scripts (.pfs) and forms (.pfd) need to be copied to the Accredo server at:
```
H:\DBNZ\Warehouse\George Custom Accredo Scripts\
```

Scripts can be run from Accredo via `Script > Play Script` or linked as Navigator shortcuts.

## Accredo API

The Accredo API is a RESTful OData 4 JSON API using OAuth 2.0 (password grant).

- Demo API base URL: `https://demo.accredo.co.nz:6569/saturn/odata4/v1/Company('demo')`
- Common endpoints: `ARCustomerList`, `ICProductList`, `INInvoiceList`, `OEOrderList`
- Full documentation: see `Accredo_Complete_Documentation.md` (not in repo)
