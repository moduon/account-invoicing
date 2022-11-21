
[![Runboat](https://img.shields.io/badge/runboat-Try%20me-875A7B.png)](https://runboat.odoo-community.org/builds?repo=OCA/account-invoicing&target_branch=15.0)
[![Pre-commit Status](https://github.com/OCA/account-invoicing/actions/workflows/pre-commit.yml/badge.svg?branch=15.0)](https://github.com/OCA/account-invoicing/actions/workflows/pre-commit.yml?query=branch%3A15.0)
[![Build Status](https://github.com/OCA/account-invoicing/actions/workflows/test.yml/badge.svg?branch=15.0)](https://github.com/OCA/account-invoicing/actions/workflows/test.yml?query=branch%3A15.0)
[![codecov](https://codecov.io/gh/OCA/account-invoicing/branch/15.0/graph/badge.svg)](https://codecov.io/gh/OCA/account-invoicing)
[![Translation Status](https://translation.odoo-community.org/widgets/account-invoicing-15-0/-/svg-badge.svg)](https://translation.odoo-community.org/engage/account-invoicing-15-0/?utm_source=widget)

<!-- /!\ do not modify above this line -->

# account-invoicing

TODO: add repo description.

<!-- /!\ do not modify below this line -->

<!-- prettier-ignore-start -->

[//]: # (addons)

Available addons
----------------
addon | version | maintainers | summary
--- | --- | --- | ---
[account_invoice_blocking](account_invoice_blocking/) | 15.0.1.0.1 |  | Set a blocking (No Follow-up) flag on invoices
[account_invoice_change_currency](account_invoice_change_currency/) | 15.0.2.0.0 | [![luisg123v](https://github.com/luisg123v.png?size=30px)](https://github.com/luisg123v) [![rolandojduartem](https://github.com/rolandojduartem.png?size=30px)](https://github.com/rolandojduartem) | Allows to change currency of Invoice by wizard
[account_invoice_check_picking_date](account_invoice_check_picking_date/) | 15.0.1.0.0 | [![carlosdauden](https://github.com/carlosdauden.png?size=30px)](https://github.com/carlosdauden) | Check if date of pickings match with invoice date
[account_invoice_check_total](account_invoice_check_total/) | 15.0.1.0.0 |  | Check if the verification total is equal to the bill's total
[account_invoice_date_due](account_invoice_date_due/) | 15.0.1.0.0 | [![luisg123v](https://github.com/luisg123v.png?size=30px)](https://github.com/luisg123v) [![joao-p-marques](https://github.com/joao-p-marques.png?size=30px)](https://github.com/joao-p-marques) | Update Invoice's Due Date
[account_invoice_fiscal_position_update](account_invoice_fiscal_position_update/) | 15.0.1.0.2 | [![alexis-via](https://github.com/alexis-via.png?size=30px)](https://github.com/alexis-via) | Changing the fiscal position of an invoice will auto-update invoice lines
[account_invoice_fixed_discount](account_invoice_fixed_discount/) | 15.0.1.0.0 |  | Allows to apply fixed amount discounts in invoices.
[account_invoice_payment_term_date_due](account_invoice_payment_term_date_due/) | 15.0.1.0.0 | [![ivantodorovich](https://github.com/ivantodorovich.png?size=30px)](https://github.com/ivantodorovich) | Display invoices date due when using payment terms
[account_invoice_refund_link](account_invoice_refund_link/) | 15.0.1.0.1 |  | Show links between refunds and their originator invoices.
[account_invoice_search_by_reference](account_invoice_search_by_reference/) | 15.0.1.0.0 |  | Account invoice search by reference
[account_invoice_section_sale_order](account_invoice_section_sale_order/) | 15.0.1.0.2 |  | For invoices targetting multiple sale order addsections with sale order name.
[account_invoice_supplier_ref_unique](account_invoice_supplier_ref_unique/) | 15.0.1.0.0 |  | Checks that supplier invoices are not entered twice
[account_invoice_tax_note](account_invoice_tax_note/) | 15.0.1.0.1 |  | Print tax notes on customer invoices
[account_invoice_tax_required](account_invoice_tax_required/) | 15.0.1.0.1 |  | This module adds functional a check on invoice to force user to set tax on invoice line.
[account_invoice_transmit_method](account_invoice_transmit_method/) | 15.0.1.1.0 | [![alexis-via](https://github.com/alexis-via.png?size=30px)](https://github.com/alexis-via) | Configure invoice transmit method (email, post, portal, ...)
[account_invoice_tree_currency](account_invoice_tree_currency/) | 15.0.1.0.0 |  | Show currencies in the invoice tree view
[account_invoice_triple_discount](account_invoice_triple_discount/) | 15.0.1.0.0 |  | Manage triple discount on invoice lines
[account_move_exception](account_move_exception/) | 15.0.1.0.0 |  | Custom exceptions on account move
[account_move_post_block](account_move_post_block/) | 15.0.1.0.1 |  | Account Move Post Block
[account_move_tier_validation](account_move_tier_validation/) | 15.0.1.1.1 |  | Extends the functionality of Account Moves to support a tier validation process.
[account_move_tier_validation_forward](account_move_tier_validation_forward/) | 15.0.1.0.0 |  | Account Move Tier Validation - Forward Option
[account_tax_group_widget_base_amount](account_tax_group_widget_base_amount/) | 15.0.1.0.0 | [![chienandalu](https://github.com/chienandalu.png?size=30px)](https://github.com/chienandalu) | Adds base to tax group widget as it's put in the report
[portal_account_personal_data_only](portal_account_personal_data_only/) | 15.0.1.0.0 |  | Portal Accounting Personal Data Only
[purchase_stock_picking_return_invoicing](purchase_stock_picking_return_invoicing/) | 15.0.1.0.0 | [![pedrobaeza](https://github.com/pedrobaeza.png?size=30px)](https://github.com/pedrobaeza) [![MiquelRForgeFlow](https://github.com/MiquelRForgeFlow.png?size=30px)](https://github.com/MiquelRForgeFlow) | Add an option to refund returned pickings
[sale_line_refund_to_invoice_qty](sale_line_refund_to_invoice_qty/) | 15.0.1.0.0 |  | Allow deciding whether refunded quantity should be considered as quantity to reinvoice
[sale_order_invoicing_grouping_criteria](sale_order_invoicing_grouping_criteria/) | 15.0.1.0.2 | [![pedrobaeza](https://github.com/pedrobaeza.png?size=30px)](https://github.com/pedrobaeza) | Sales order invoicing grouping criteria
[stock_picking_return_refund_option](stock_picking_return_refund_option/) | 15.0.1.0.1 | [![sergio-teruel](https://github.com/sergio-teruel.png?size=30px)](https://github.com/sergio-teruel) | Update the refund options in pickings

[//]: # (end addons)

<!-- prettier-ignore-end -->

## Licenses

This repository is licensed under [AGPL-3.0](LICENSE).

However, each module can have a totally different license, as long as they adhere to Odoo Community Association (OCA)
policy. Consult each module's `__manifest__.py` file, which contains a `license` key
that explains its license.

----
OCA, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit
organization whose mission is to support the collaborative development of Odoo features
and promote its widespread use.
