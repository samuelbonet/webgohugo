### What is Hugo?

Hugo is a `framework`, that is, it allows us to `create` websites with predefined `templates`. It also allows you to generate static websites, such as a `blog` or a portfolio. The content files are created by the user in html or in markdown that Hugo will translate to html.

### Characteristic
-It's cross-platform \
-Documented \
-Easy to use \
-Variety of configurable themes \
-Support other languages\
-Allows you to create tags and categories \
-Easy to unfold


### How to install Hugo on Ubuntu

If you didn't have snap installed 
```
sudo apt-get install snapd
```

Once the snap is obtained, we are going to install Hugo 
```
sudo apt-get install hugo
```

We will install in our case Visual Studio Code to be able to edit our website 
```
sudo snap install code --classic
```

We will create the site name 
```
hugo new site <page>
```

Once we access the site, we will move to the themes folder 
```
cd themes
```

In that folder we will clone our template via SSH or http from a repository, such as GitHub 
```
git clone https://github.com/theNewDynamic/gohugo-theme-ananke.git relearn
```

We will go to our page folder, and enter 
```
code .
```

In the configuration file (config.toml) we will change the title to the name of the template 
```
theme =['hugo-PaperMod']
```

Once all the previous steps are finished we can see our website from localhost 
```
hugo server
```


### Installing Hugo on Windows

For the installation we have to go to the following link
`https://github.com/gohugoio/hugo/releases`

We download the version we want in a zip
`hugo_extended_x.x.x_windows-amd64.zip`

Installation is done manually

We extract the zip and move the file `Hugo.exe` to the path `C:\Hugo\bin `

In the Windows search engine, we get into `Edit system environment variables`

The `System Properties` will appear and click on `Environment Variables'

In the list we will look for the variable Path, and we will add `C:\Hugo\bin`

We restart and we will have Hugo and accessibility.


### Extra Resources

https://gohugo.io/content-management/

https://github.com/gohugoio/hugo


{{<youtube hjD9jTi_DQ4>}}

---


---