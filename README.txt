Reservations Printable Contract

Development of this module is on Community Media Advanced on github here:
https://github.com/cm-advanced/cma_reservations_printable_contract

Formore info go here:
https://cmadvanced.wordpress.com/


Adds a printable contract option to Reservation nodes.

INSTALLATION
-------------------------
If you will be the replacing the Cost columns, you will need to add a
user-defined field to the reservable content types. The field name and header
for the column on the contract can be defined on the configuration page
(admin/config/reservations/contract) or the default values can be used.

      Label: User-Defined
      Machine Name: user-defined field [field_reservable_contract_text (default)]
      Field Type: Long text
      Widget: Text area (multiple rows)

Checking Replace Cost Columns with Accessories Column on the settings page will
allow the user-defined field to appear on the contract.