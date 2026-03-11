# Accredo Scripts

Custom MaxBasic scripts and forms for Proline Protective Coatings' Accredo Saturn system.

## Directory Structure

```
scripts/
  order-picking/     Our order picking forms and launcher script
  tinting/           Tinting (Jotun Mix Bank) forms and test scripts
  mixbank/           MixBank utility scripts
reference/
  barcoding/         Original third-party barcoding scripts (read-only reference)
docs/
  accredo/           Accredo documentation split by topic (see INDEX.md)
_archive/            Old pre-git backups (gitignored, local only)
```

## Scripts

### Order Picking (`scripts/order-picking/`)

| File | Description |
|------|-------------|
| `OrderPicking.pfs` | Launcher script — opens the Proline order picking form |
| `OrderPicking_Proline.pfd` | Main order picking form with unprocessed orders list, pick workflow, GRP detection |

### Tinting (`scripts/tinting/`)

| File | Description |
|------|-------------|
| `TintingForm.pfd` | Modal form for entering tinted product lines — triggered when GRP products detected in an order. Writes lines to MIXJOTUN invoice on Complete. |
| `Qty_Entry_Tint.pfd` | Simple quantity entry dialog for changing line quantities |
| `TestTintingForm.pfs` | Test script to open TintingForm standalone with a fake invoice number |

### MixBank (`scripts/mixbank/`)

| File | Description |
|------|-------------|
| `MixBank_NewLine.pfs` | Opens the current MIXJOTUN invoice and appends a new line ready for entry |

## Server Deployment

Scripts (.pfs) and forms (.pfd) are deployed to the Accredo server at:
```
H:\DBNZ\Warehouse\George Custom Accredo Scripts\
```

All scripts reference forms using full server paths. After editing locally, copy the changed files to the H: drive. The server directory is flat (no subfolders) — all .pfs and .pfd files go in the same folder.

Scripts can be run from Accredo via `Script > Play Script` or linked as Navigator shortcuts.

## Accredo API

- RESTful OData 4 JSON API with OAuth 2.0 (password grant)
- Demo base URL: `https://demo.accredo.co.nz:6569/saturn/odata4/v1/Company('demo')`
- Common endpoints: `ARCustomerList`, `ICProductList`, `INInvoiceList`, `OEOrderList`
- Full docs: `docs/accredo/` (see `INDEX.md`)
