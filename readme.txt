To add a new branding the following need to be added:
	_{brandName}.scss in /shared
	reference to that file in main.scss
	Header and footers created in Self Admin
	_NCC.scss display: none; for the new header and footer

to compile run the following in Command prompt with Ruby
sass main.scss:main.css --style compressed