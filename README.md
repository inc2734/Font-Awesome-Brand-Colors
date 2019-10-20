# Font Awesome Brand Colors  
This project was made when I got inspired by a repo I found on Github, but it was outdated and a bit clumsy to use.  
So I decided to make a easier version that everyone can use and everyone is also free to help me keep this updated!

## Information
Supported Font Awesome version: **5.11.2**  
Amount of Brand icons colored: **432** *I think I missed one, help me find it! :P*

## Getting Started
#### Step 1
Import Font Awesome in your code, into the tag `<head>`:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/fontawesome.min.css">
```
For more information on how to obtain or use Font Awesome, make sure to visit their official platform at: [www.fontawesome.com](https://www.fontawesome.com)

#### Step 2
Download the [brand-colors.css](brand-colors.css) file and make sure to save it as `brand-colors.css`, you'll need this ofcourse or else it wont work.  
And to import this into your code, make sure to first import the correspondending Font Awesome version and after that import this project by doing
```html
<link rel="stylesheet" href="<Path To brand-colors.css>/brand-colors.css">
```

#### Step 3
Once you did that, you only have to add `color` after the Font Awesome classes, for example `fab fa-gitlab color`,  
and this will add the main color of the brand to the brand icon.  

So your code can look like this now
```html
<i class="fab fa-gitlab color"></i>
```
And this will add the dominating color of Gitlab's icon to the Font Awesome Gitlab icon in this case: `#fca326`

#### Step 4
Enjoy it! No more adding styling to the tags and searching for correspondending brandcolors, just simple adding `color` after the icon class and you are fine!