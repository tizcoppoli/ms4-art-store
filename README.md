<h1 align="center">Painters Canvas Shop</h1>

[View the live project here](https://ms3-online-cookbook.herokuapp.com/)

This is the Painters Canvas Shop. In this ecommerce the user can find and buy different cavas with the most famous paintings in the world. It is designed to be responsible and accessible on multiple devices, making it easy to navigate for users on every device.

<h2 align="center"><img src="static/doc/mockup.png"></h2>

## User Experience (UX)

### Project Goals

The site's primary goal is to sell canvas to the visitors who are looking for something to decorate their home, or make a gift to someone really passionate about paintings. The site has 2 target audience and an admin role:

- Guest users (first time visitors)
- Casual customers (people who buy something without registering)
- Registered customers (people who like the website and want to purchase more products)
- Admin (can manage the products and the categories)


### User stories

  - ### Guest User Goals

    1. As a Guest User, I want to find easily the products.
    2. As a Guest User, I want to browse all canvas and use the search function.
    3. As a Guest User, I want to explore the product page, check more info about the shop like deliveries, returns and details.
  

  - ### Casual Customer Goals

    1. As a Casual Customer, I want to add a product to the bag and continue to browse the categories.
    2. As a Casual Customer, I want to check the bag anytime and have a have a look about how much I'm spending.
    3. As a Casual Customer, I want to update or remove a product from the bag.
    4. As a Casual Customer, I want to go to the checkout and pay.
    5. As a Casual Customer, I want to receive notifications to know if everything works or not.
  

  - ### Registered Customer Goals

    1. As a Registered Customer, I want to save my profile info for the next purchase.
    2. As a Registered Customer, I want to check my previous purchases in my profile page.
    3. As a Registered Customer, I want to edit my profile info to keep my profile updated.

  - ### Admin Goals

    1. As an Admin, I want to manage the products and categories.
    2. As an Admin, I want to access to the administration panel.
  

### UX - Five Planes Method

#### 1. Strategy
  The primary goal is to sell canvas to the visitors who are looking for something to decorate their home, or make a gift to someone really passionate about paintings.
  
#### 2. Scope
  Everything should be easy to understand. There is a simple navigation bar on the top. The user should be able to register, sign in, browse the products, add a product to the bag, and go to the checkout.

#### 3. Structure
  There is a home page which all the details about the site, and the button to browse the products. There is product page with all the products and each has an individual page with its details, picture, price, description, and a button to add to the bag. From the bag the user can go the checkout page and made the purchase, edit the bag and update/remove products. The registered user can go to the profile page and update the personal information.

#### 4. Skeleton
  The site is made with django. There are differents custom django apps:
  - home
  - products
  - checkout
  - bag
  - profile
  Each app manage a specific function of the website. The templates are made with a base template that is used for the navbar and the footer. Each app has templates that extend the base template. Check the wireframes for more details.

#### 5. Surface
  The website has a simple design with a few elemnts. The predominant colors are gold/black/white and the font style is handwritten and serif. Check the design section for more details.

### Design

#### Colour Scheme

- The palette has been generated with [Coolors](https://coolors.co/)

<img src="static/doc/palette.png">

  - Black: #000000
  - Spanish Orange: #ef6c00
  - Persian Green: #26a69a
  - Cultured: #f6f5f3
  - White: #ffffff

#### Typography

- "Montserrat" is the main font used throughout the whole website, with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly.
- "Pattaya" is a clean font used for headings.

#### Imagery
- Imagery is important. The images are all high quality pictures, designed to be striking and catch the user's attention. It also has a modern, energetic aesthetic.

### Wireframes

- Home Page - Desktop Wireframe - [View](static/doc/home_desktop.pdf)
- Home Page - Tablet Wireframe - [View](static/doc/home_tablet.png)
- Home Page - Mobile Wireframe - [View](static/doc/home_mobile.png)
- Recipe Page - Desktop Wireframe - [View](static/doc/recipe_desktop.pdf)
- Recipe Page - Tablet Wireframe - [View](static/doc/recipe_tablet.png)
- Recipe Page - Mobile Wireframe - [View](static/doc/recipe_mobile.png)
- Profile Page - Desktop Wireframe - [View](static/doc/profile_desktop.pdf)
- Profile Page - Tablet Wireframe - [View](static/doc/profile_tablet.png)
- Profile Page - Mobile Wireframe - [View](static/doc/profile_mobile.png)

## Features

- Responsive on all device sizes
- Interactive form controls
- Button hover animations
- Modal used to add a new recipe and category
- Add likes and comments to the recipes
- Pagination
- User Sign In/Sign Up
- Edit user informations
- Upload new recipes feature
- Default images for users and recipes
- Random suggestions in each recipe page
- Search function

### Features Left to Implement

- Users management
- More filter to improve the search function

## Technologies Used

### Languages Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- [JavaScript](https://en.wikipedia.org/wiki/JavaScript)
- [Python](https://en.wikipedia.org/wiki/Python_(programming_language))

### Frameworks, Libraries & Programs Used

**Front-End**
* [Materialize](https://materializecss.com/) 
* [Font-Awesome](https://fontawesome.com/)
* [Google Fonts](https://fonts.google.com/)
* [jQuery](https://jquery.com/)
* [Balsamiq](https://balsamiq.com/)
* [Paint.net](https://www.getpaint.net/)

**Back-end**
* [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [Jinja](https://jinja.palletsprojects.com/en/2.11.x/)
* [MongoDB](https://www.mongodb.com/1)
* [Werkzeug](https://werkzeug.palletsprojects.com/en/1.0.x/)

**Deployment**
* [Heroku](https://dashboard.heroku.com/)
* [Git](https://git-scm.com/)
* [Github](https://github.com/)
* [Gitpod](https://gitpod.io/)

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

- [W3C HTML Validator](https://validator.w3.org/) - [Results](static/doc/html_valid.png)
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - [Results](static/doc/css_valid.png)
- [Esprima JS Validator](https://esprima.org) - [Results](static/doc/js_valid.png)
- [PEP8 online](http://pep8online.com/) - [Results](static/doc/python_valid.png)

The deployed site was tested with Lighthouse for performance evaluation and with Responsinator for responsiveness.

- [Lighthouse](https://developers.google.com/web/tools/lighthouse) - [Results](static/doc/lighthouse_report.png)
- [Responsinator](http://www.responsinator.com/) - [Results](http://www.responsinator.com/?url=https%3A%2F%2Fms3-online-cookbook.herokuapp.com%2F)

### Testing User stories from User Experience (UX) Section

- #### Guest User Goals

  - As a Guest User, I want to find easily the recipes.
    1. Upon entering the site, users can immediately wiew a few recipes in carousel, and click the callout button.
    2. The home page provide a great variety of recipes divided by categories.

  - As a Guest User, I want to browse all recipes and use the search function.
    1. In the home page there are multiple links to the recipes page.
    2. In the navbar there is the link to visit the recipes page.
    3. In the recipes page there is the search bar.

  - As a Guest User, I want to explore the recipe page, check the comments and how many likes the recipe has.
    1. Each recipe has its own page.
    2. In the recipe page there is the number of likes in the heading next to the recipe name. The comments are in a section below the recipe steps.

- #### Contributors Goals

  - As a Contributor, I want to add likes and comments to the recipes.
    1. A logged user can add/remove a like to a recipe with the same button in the recipe page.
    2. A logged user can leave a comment on a recipe.

  - As a Contributor, I want to upload my own recipes and share them with the community.
    1. A logged user can upload a new recipe on the website and other users can like or comment it.

  - As a Contributor, I want to edit my recipes or delete them.
    1. In the profile page there is the list of personal recipes, and the user can edit or delete them.
  
  - As a Contributor, I want to edit my preferences on my profile page, like email, user image.
    1. In the profile page it is possible to edit the preferences.
  
  - As a Contributor, I want to find community links.
    1. In the footer the user can find the the social links.

- #### Customers Goals

  - As a Customer, I want to find the purchase link for the recipe book.
    1. In the home page there is a section dedicated to the recipe book, and the purchase link.

  - As a Customer, I want to find the email address to contact the staff.
    1. In the footer the user can find the contact email address
    2. The user can contact the staff about improvements on the website or the book.

  - As a Customer, I want to subscribe to the newsletter to see the offers and new products.
    1. The user can subscribe to the newsletter in the dedicated home page section.
    2. The is no need of registration to subscribe to the newsletter.

- #### Admin Goals

  - As an Admin, I want to be able to edit or delete the recipes.
    1. The admin can edit or delete every recipe from the recipe page.
    2. The admin like other users can edit or delete the recipes from the user page.

  - As an Admin, I want to create a new category, edit an existing one or delete it.
    1. The admin can create, edit or delete categories in the manage categories page.

### Further Testing

- The Website was tested on Google Chrome, Firefox and Microsoft Edge.
- The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX, iPad.
- A large amount of testing was done to ensure that all pages were linking correctly.

### Solved Bugs

- It wasn't possible to have multiple buttons on the carousel. Solved with javascript:

```
function changeLinkToButton() {
    href = $(".carousel-item.active").attr("href");
    $("#carousel-button").attr("href", href)
}
```

- Use render_template send the same POST request ad each page refresh, solved with a redirect:

```
return redirect(url_for("get_categories"))
```

- Request.form.get() doesn't get an array. Solved using:
```
ingredient_list = request.form.getlist("ingredient_list[]")

```

# Deployment

### Installation Prerequisites

To be able to run the project the following technologies need to be installed in your IDE environment.
- Python3
- Git 
- pip3

You will need to be signed up to the following services:
- [Heroku](https://signup.heroku.com/?c=70130000000NeLCAA0&gclid=Cj0KCQjwpdqDBhCSARIsAEUJ0hMbGWS3dMlZowadFExUalBu2L_UVf27xViAk9dBlCKLsRQI7V2PuScaAmCPEALw_wcB)
- [AWS](https://aws.amazon.com/)
- [Stripe](https://stripe.com/gb)

### Cloning on GitHub

1. Login to GitHub.com.
2. Open rhysseddon/Vision-Furniture-MS4-Project.
3. Click "Code" then under "Clone" copy the link with the HTTPS URL.  
4. Go to the terminal in your IDE environment. 
5. Change the working directory to where you want the clone to be saved by typing `cd` and the name of the directory.
6. Type `git clone` and paste the copied HTTPS URL.
7. After pressing enter the clone will be saved to your chosen directory.

### Local Deployment On Gitpod

1. After cloning repository on GitHub. Go to your chosen IDE environment and open the clone directory.
2. Install the libraries from the requirements.txt, in the terminal type - `pip3 install -r requirements.txt`.
3. Set your environment variables in your gitPod settings or in an env.py file.
4. If setting variables within an env file add this to the .gitignore file so your variables are not exposed 
when pushing to gitHub.
5. Your environment variables will need to be set as follows:
- os.environ["DEVELOPMENT"] = "True"
- os.environ["SECRET_KEY"] = "Your Secret key"
- os.environ["STRIPE_PUBLIC_KEY"] = "Your Stripe Public key"
- os.environ["STRIPE_SECRET_KEY"] = "Your Stripe Secret key"
- os.environ["STRIPE_WH_SECRET"] = "Your Stripe WH_Secret key"
6. Create the database from the models by typing in the terminal `python3 manage.py makemigrations`. Followed by
`python3 manage.py migrate`
7. Load the data fixtures by typing in the terminal: `python3 manage.py loaddata products`
8. Create a superuser so you can log in to the Django admin by typing in the terminal: `python3 manage.py createsuperuser`
9. The site can now be run locally by typing in the terminal `python3 manage.py runserver`

### Heroku Deployment

1. After logging in to Heroku, select "Create New App" Choose the region closest to you and select "Create app".
2. On the resources tab, to provision the database in the add on field search for and select "Heroku Postgres".
3. A pop up should appear and under "Plan name" use "Hobby Dev-Free" and select "Provision".
4. Go to your IDE and type `pip3 install dj_database_url` and `pip3 install psycopg2-binary` as these need to be 
installed to use Postgres. Also `pip install gunicorn` for the webserver.
5. To make sure Heroku installs all of the apps when deployed save the requirements by typing in the terminal
`pip3 freeze > requirements.txt`
6. Back on Heroku under settings, select "Reveal config vars" and copy the key from DATABASE_URL.
7. In the project folder on settings.py in the database setting, comment out the current database setting.
8. Replace with: 
```
DATABASES = {
    'default': dj_database_url.parse('<Enter the copied DATABASE_URL key here>')
}
```
9. Add the data to the postgres database by typing in the terminal `python3 manage.py makemigrations`. Followed by
`python3 manage.py migrate`
10. Load the data fixtures by typing in the terminal: `python3 manage.py loaddata products`
11. Create a superuser so you can log in to the Django admin by typing in the terminal: `python3 manage.py createsuperuser`
12. Return to database setting in settings.py and remove code added in step 8 and uncomment the previous database setting.
13. Create a Procfile and add `web: gunicorn vision_furniture.wsgi:application`
14. Login to Heroku through the cli `heroku login -i`
15. Temporarily disable collect static by typing `heroku config:set DISABLE_COLLECTSTATIC=1`
16. Add `vision-furniture.herokuapp.com, localhost' to ALLOWED_HOSTS in settings.py.
17. The app can now be deployed by typing in the terminal `heroku git:remote -a vision-furniture` and `git push heroku master`
18. On Heroku dashboard under "Deploy" set "Deployment method" to connect to Gitub. Under "Automatic Deplays" set 
"Enable automatic deploy" so the code is automatically deployed to Heroku and GitHub.

### Add Static Files to AWS

1. Go to AWS and find S3 under services and create a new bucket, selecting the region closest to you and 
allowing all public access.
2. Go to the new bucket and under properties tab, turn on static website hosting.
3. Under permissions tab the CORS configuration tab and enter the following:
```
[
  {
      "AllowedHeaders": [
          "Authorization"
      ],
      "AllowedMethods": [
          "GET"
      ],
      "AllowedOrigins": [
          "*"
      ],
      "ExposeHeaders": []
  }
]
```

4. Go to the bucket policy tab. And select "policy generator" so we can create a security policy for this bucket.
5. Add in the following:
- Policy type: S3 bucket policy 
- Effect: Allow
- Principal: `*`
- Action: GetObject
- Copy the ARN from the bucket policy tab. And paste it into the ARN box at the bottom.
- Click Add statement. Then generate policy.
6. Copy the policy into the bucket policy editor.
7. Add `/*` onto the end of the resource key. Click Save.
8. Go to access control list tab and set the list objects permission for everyone under the Public Access section.
9. Create a user to access the bucket by selecting IAM from the servies menu.
10. Select "Groups" and select "Create new group". Add in a new group name and click next, next again then "create new group"
11. Create a policy to access the bucket, by selecting "policies" then "create policy". Select JSON tab and import managed policy. Search for 
s3 and import "AmazonS3FullAccess".
12. Copy the bucket policy ARN from the bucket policy in s3 > permissions. Paste it into the JSON resource key on create policy twice 
giving the second paste a `/*` at the end. Select "review policy". Give the policy a name and description and create the policy.
13. Go to "groups", select the new group, select "attach policy", search for the newly created policy and attach it to the policy.
14. Go to "users", add user, create a user name, give them programmatic access and select next.
15. Add the new user to the group and select next to create user then download the .csv file.
17. Go to your IDE terminal type: `pip3 intsall boto3` and `pip3 intall django-storages` to install the packages 
to connect to django. Type: `pip3 freeze > requirements.txt` so they get installed on heroku when its deployed.
18. Add 'storages' to installed apps on the settings.py file. Add the following code to tell Django which bucket to 
communicate with:
```
if 'USE_AWS' in os.environ:
    # Bucket Config
    AWS_STORAGE_BUCKET_NAME = 'vision-furniture'
    AWS_S3_REGION_NAME = 'eu-west-2'
    AWS_ACCESS_KEY_ID = os.environ.get('AWS_ACCESS_KEY_ID')
    AWS_SECRET_ACCESS_KEY = os.environ.get('AWS_SECRET_ACCESS_KEY_ID')
    AWS_S3_CUSTOM_DOMAIN = f'{AWS_STORAGE_BUCKET_NAME}.s3.amazonaws.com'

    # Static and media files
    STATICFILES_STORAGE = 'custom_storages.StaticStorage'
    STATICFILES_LOCATION = 'static'
    DEFAULT_FILE_STORAGE = 'custom_storages.MediaStorage'
    MEDIAFILES_LOCATION = 'media'

    # Override static and media URLs in production
    STATIC_URL = f'https://{AWS_S3_CUSTOM_DOMAIN}/{STATICFILES_LOCATION}/'
    MEDIA_URL = f'https://{AWS_S3_CUSTOM_DOMAIN}/{MEDIAFILES_LOCATION}/'
```
19. On Heroku add the AWS keys from the .csv file to the config vars. Also add USE_AWS: True, so the that the setting file knows 
to use the AWS configuration when deploying to Heroku. Remove the COLLECTSTATIC variable.
20. Push all the changes to Github. Which will trigger an automatic deployment to Heroku.

## Credits

I used the Code Institute Boutique Ado Mini-Project by Chris Zielinski as the main basis of my own project.

### Code

- [Bootstrap](https://materializecss.com/): CSS library used throughout the project mainly to make the site responsive using the grid system.

### Content

- All content was written by the developer.
- Psychological properties of colours text in the README.md was found [here](http://www.colour-affects.co.uk/psychological-properties-of-colours)

### Media

- Pictures: [Canva](https://canva.com/)
- Editing is made by the developer.

### Acknowledgements

- My Mentor for continuous helpful feedback.
- Tutor support at Code Institute for their support.
