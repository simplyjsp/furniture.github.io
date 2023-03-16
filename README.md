# Install

- Login to Github, click on "Fork" and change the repo name to "your_username.github.io"

# Setup a domain name

- https://hackernoon.com/how-to-set-up-godaddy-domain-with-github-pages-a9300366c7b
- https://www.geeksforgeeks.org/publish-websites-on-github-pages-with-a-custom-domain/

# Edit individual pages

## Click on the file, then click on the "Pencil" icon to edit it. Then click "Commit changes".

- It takes around 30-60 seconds for Github to update the website. You may need to Ctrl + R or clear cache.

## Set the logo, website contact details and footer info:

- \_config.yml

## Edit about, contact and FAQ pages:

- about.md
- contact.md
- faq.md

## Edit the sliders, boxes and info on the homepage:

- index.html

# Add new products or stores

## Add a new product:

- Click on the "/\_products/" folder
- Click "Add file" -> "Create new file"
- Set the name to "store-product.md" e.g. "walmart-upholstered-armchair.md"
- Copy and paste the PRODUCT_TEMPLATE.md into the box
- Fill out the product info and click "Commit new file"

## Add a new store:

- Click on the "/\_stores/" folder
- Click "Add file" -> "Create new file"
- Set the name to "store.md" e.g. "walmart.md"
- Copy and paste the STORE_TEMPLATE.md into the box
- Fill out the store info and click "Commit new file"

## Add a new blog post:

- Click on the "/\_posts/" folder
- Click "Add file" -> "Create new file"
- Set the name to "year-month-day-title.md" e.g. "2023-03-15-how-to-choose-a-chair.md"
- Copy and paste the 2023-03-15-POST_TEMPLATE.md into the box
- Write the blog post and click "Commit new file"

# Upload images

- Click on the "/assets/image/" folder
- Click "Add file" -> "Upload files"
- Select your images and click "Upload"
- The image URL is in this format: https://bestchairs.com/assets/image/filename.jpeg

# Setup the contact form

- Get a free access key from https://web3forms.com/#start
- Edit the file "/\_layouts/contact_form.html"
- Change this code to your own access key:

`<input type="hidden" name="access_key" value="xxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx" />`

# Markdown guides

- https://www.reddit.com/wiki/markdown/
- https://www.markdown-cheatsheet.com/
