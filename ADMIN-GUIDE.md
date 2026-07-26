# Updating AFKKS products

The website reads its catalogue from `products.xlsx` in this folder.

1. Download `products.xlsx` from the GitHub repository.
2. Edit the **Products** sheet in Excel. Keep the column names unchanged.
3. Use `sale_unit` as `metre` or `piece`.
4. Enter the current quantity in `units_available`. Enter `0` to mark a product out of stock and disable its Add to Cart button.
5. Set `active` to `no` to hide a product without deleting its row.
6. Ensure `image_file` exactly matches the uploaded product image filename.
7. Upload the revised `products.xlsx` to the same place in GitHub and commit the change.

After GitHub Pages republishes, the catalogue, prices, sales units and stock details update automatically.
