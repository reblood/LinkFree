# LinkFree

A free and open source alternative to LinkTree. Based on the project of [MichaelBarney](https://github.com/MichaelBarney/LinkFree)

[Website](https://reblood-link.web.app/)

<img src="https://firebasestorage.googleapis.com/v0/b/reblood-d3002.appspot.com/o/images%2Flink%2FReblood-LinkFree.png?alt=media&token=3f5859d9-bf45-4314-8869-9dca00d62381" alt="Screenshot of Reblood LinkFree on phone" width="250px">

## How to Use
### index.html
 1. **Title**
    This is the name that is given to the page.
	   ```
	   <title>Your Title Here</title>
	   ```
 2. **(Optional) Favicon** 
	To change the favicon, just replace the "favicon.ico" file. You can generate the .ico file in a website like [favicon.io](https://favicon.io/).
 3. **Image**
	 This is the user image that is shown. Make sure it is square and substitute the "src" property with its url. You can generate the url in a website like [imgur](https://imgur.com/).
	```
	<img  id="userPhoto"  src="https://i.imgur.com/t8ZX9um.jpg"  alt="User Photo">
	```
 4. **Links**
 To add your clickable links just substitute, delete or copy the "a" tags inside the "links" div with your desired hyperlinks.
	```
	<div  id="links">

		<a  href="https://reblood.app"  target="_blank">Download aplikasi Reblood</a>

		<a  href="https://app.reblood.com"  target="_blank">Pengguna iOS? Gunakan web app</a>

	</div>
	```
### style.css
 5. **Colors**
	 Substitute the background and accent colors with your desired pallete.
	 ```
	 --bgColor: white;
	--accentColor: #DC3827;
	 ```
 6. **Fonts**
	 You can import the font from a website like [Google Fonts](https://fonts.google.com/) and substitute the "--font" variable with its implementation.
	 ```
	 @import  url('https://fonts.googleapis.com/css?family=Karla:400,700&display=swap');
	 
	 --font: 'Karla', sans-serif;
	 ```
