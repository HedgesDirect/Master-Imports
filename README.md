# Master-Imports

This GIT Repo contains:

StructureImportMaster.csv
ProductAttributesMaster.csv
KitAttributesMaster.csv
VariablesMaster.csv
ProductComponantsMaster.csv
FullHierachicalOutput.csv

Details:

FullHierachicalOutput.csv

A full output & export from the current development website. This in inludes all data references below.



StructureImportMaster.csv

This is the 'scaffolding' for our tree structure in SellerDeck. It contains sections and products.


ProductAttributesMaster.csv

This is the attribute data at a SKU level - with a 1:1 relationship to SKU's in the the MasterStructureImport. It contains hedging products - Pots, Bare Roots & Rootballs.


KitAttributesMaster.csv

This is the attribute data at a SKU level - with a 1:1 relationship to product SKU's in the ProductComponantMaster. It contains hedging products - Pots, Bare Roots & Rootballs.



VariablesMaster.csv

An export of only variables as used in SellerDeck.


ProductComponantsMaster.csv

A master listing of all 'Pallet Deals' and 'Discounted Packs'. These are Products made up of multiple other (pre-existing) SKU's, and are assembly items (the single items are taken from stock, these have no stockholding). The Products and Componants are nested - this file assumes that the products have already been added to MasterStructureImport (and imported) and that attributes for the products are added to KitAttributesMaster.csv