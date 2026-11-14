# Jharkhandi Tadka website — Version 3

## Upload these files to the root of your GitHub repository
- index.html
- menu.js
- poster.jpg
- litti-chokha.jpg
- veg-thali.jpg
- paneer-thali.jpg
- dal.jpg
- seasonal-sabzi.jpg
- chhachh.jpg

## Edit your menu directly on GitHub
1. Open https://github.com/gopal345742/jharkhandi-tadka
2. Open `menu.js`.
3. Click the pencil icon to edit.
4. Change the values for a food item.
5. Commit changes. GitHub Pages will update the live website after deployment.

Each item has:
- `name`: dish name
- `description`: short food description
- `price`: price in rupees
- `quantity`: serving size, e.g. "200 ml", "300 ml", "1 plate", "2 pcs"
- `available`: true or false
- `image`: filename of its photo
- `category`: menu category

To mark a dish unavailable, change `available:true` to `available:false`.
To change a photo, upload the replacement image to the repository and update its filename in `menu.js`.

No admin login, PHP or database is included. You manage the menu by editing `menu.js` in GitHub, as requested.
Orders continue to be sent to WhatsApp. The site does not save orders or process online payments.
