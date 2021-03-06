headTag
===
Everything that you may need to include in a &lt;head>.
In this file(Readme.md) you'll find everything you need. But for more info visit [Refrences.md](/Refrences.md).

Contribute
---
All contributions are welcomed.

&lt;head>
---
+ [CSS](#css)
+ [Doctype](#doctype) (Mostly html5)
+ [Doctype rules](#doctype-rules)
+ [Favicon](#favicon)
+ [Human.txt](#human.txt)
+ [IE realted](#ie-realted)
+ [JS](#js)
+ [Meta](#meta)
    + [Charset](#charset)
    + [Mobile Apps](#mobile-apps)
        + [Apple](#apple)
        + [Android](#android)
+ Modernizer / HTML5Shiv
+ [Robots.txt](#robots.txt)
+ [Title](#title)


### CSS
+ Inline Styles:
    ```
    <p style="color:cyan;margin-top:2em;">This is a paragraph.</p>
    ```

+ Internal Style:
    ```
    <head>
        <style>
            p {margin: 0 25px;}
            body {background:rgba(37,20,55,0.8);}
        </style>
    </head>
    ```
+ External Style:
    ```
    <link rel="stylesheet" href="mystyle.css">
    ```

### Doctype
+ HTML5:
    ```
    <!DOCTYPE HTML>
    ```

### Doctype rules
+ Don't add ```/``` at the end of self-closing tags in HTML5.

### Favicon
+ [Favicon Generator](http://realfavicongenerator.net/)
+ [Favicon Cheat Sheet](https://github.com/audreyr/favicon-cheat-sheet)

### Meta

#### Mobile Apps

##### Apple
**Promoting Apps with Smart App Banners:**
```
<meta name="apple-itunes-app" content="app-id=myAppStoreID, affiliate-data=myAffiliateData, app-argument=myURL">
```
+ app-id: (Required.) Your app's unique identifier. To find your app ID from the iTunes Link Maker, type the name of your app in the Search field, and select the appropriate country and media type. In the results, find your app and select iPhone App Link in the column on the right. Your app ID is the nine-digit number in between id and ?mt.
+ affiliate-data: (Optional.) Your iTunes affiliate string, if you are an iTunes affiliate. If you are not, find out more about becoming an iTunes affiliate at http://www.apple.com/itunes/affiliates/.
+ app-argument: (Optional.) A URL that provides context to your native app. If you include this, and the user has your app installed, she can jump from your website to the corresponding position in your iOS app. Typically, it is beneficial to retain navigational context because:
    + If the user is deep within the navigational hierarchy of your website, you can pass the document’s entire URL, and then parse it in your app to reroute her to the correct location in your app.
    + If the user performs a search on your website, you can pass the query string so that she can seamlessly continue the search in your app without having to retype her query.
    + If the user is in the midst of creating content, you can pass the session ID to download the web session state in your app so she can nondestructively resume her work.

    You can generate the app-argument of each page dynamically with a server-side script. You can format it however you'd like, as long as it is a valid URL.

### Title
```
<title>TITLE GOES HERE</title>
```

