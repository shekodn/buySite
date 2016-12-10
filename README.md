# Buy Site
Sample pre order site

# Steps
1. Create rails app:
```
rails _4.2.2_ new buySite  
```

2. Create index (home) page
```
rails g controller StaticPages home  
```
3. Create routes in config/routes.rb

```
root 'static_pages#home'
get  'static_pages/home'
```

4. Follow this tutorial https://github.com/mkhairi/materialize-sass.
Note: This will only install the gem. You also need to delete
Turbolinks from JS application file

5. 
