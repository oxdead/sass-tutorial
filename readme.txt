//sass tutorial

1. install Live Sass Compiler(by Ritwick Dey) extension for VSCode
2. install Live Server (by Ritwick Dey) for more convenient development
3. Go to settings(ctrl+,) type sass and find Live Sass Compile >Settings, click edit json
4. Add settings to json:
	"liveSassCompile.settings.formats":[
		// //default, savePath=null means save in the same folder where scss is situated
		// {
		// 	"format": "expanded",
		// 	"extensionName": ".css",
		// 	"savePath": null,

		// },
		// //minified version, good for production
		// {
		// 	"format": "compressed",
		// 	"extensionName": ".min.css",
		// 	"savePath": "/dist/css",

		// },
		//good for development		
		{
			"format": "expanded",
			"extensionName": ".css",
			"savePath": "/dist/css",

		}
	]
5.create folders for project (in our case it's "dist/css")
6.after creatin of html file and scss file go to scss file, in VSCode there will be a button "Watch Sass", click it
7.click at Go Live button for Live Server too




