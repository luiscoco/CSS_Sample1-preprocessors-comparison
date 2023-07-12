# How to run the application

1. Open the application folder with VSCode

2. Install parcel
```
npm install -g parcel-bundler
```
"parcel" is like "yarn" or "npm"

3. Run the application
```
npm run start
```
4. Navigate to the URL: http://localhost:1234

5. To make the comparison of using the CSS preprocessor uncomment/comment the style file in the index.html file
```HTML
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />

		<!-- <link rel="stylesheet" href="comparison/sass.sass" /> -->
		<link rel="stylesheet" href="comparison/scss.scss" />
		<!-- <link rel="stylesheet" href="comparison/stylus.styl" /> -->
		<!-- <link rel="stylesheet" href="comparison/less.less" /> -->
		<title>Document</title>
	</head>
	<body>
		<h1>Hello from:</h1>
	</body>
</html>
```
