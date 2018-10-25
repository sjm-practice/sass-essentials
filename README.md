# Sass Essentials
This project is based on following a Sass Essentials course by [Ray Villalobos on lynda.com](https://www.lynda.com/Sass-tutorials/Sass-Essential-Training/375925-2.html).

## Notes
* Primary Features of Sass
	- Variables
	- Nesting
	- Partials (modules)
		+ remember, file names beginning with underscore are by default not processed by sass, until imported
		+ when referring to the file to be imported, the underscore and file extension do not need to be included
			* @import "variables";  // would import "_variables.scss"
	- Extend (rule based on another rule, using @extend)
	- Operators (math, if / else)
	- Mixins (macros)
