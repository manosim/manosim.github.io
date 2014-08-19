# ekonstantinidis.github.io
Repository containing the source for my website. Domain: iamemmanouil.com. 

       
## Project Setup
First create a virtual environment and activate it. Then install requirements file.
	
	virtualenv env
	source env/bin/activate
	pip install -r requirements.txt


## Development
Using fabric's `serve` to serve port 8000 and `regenerate`.

	fab regenerate
	fab serve


## Deployment

Coming soon.


## More Information

This is a static website build with [Pelican](http://www.getpelican.com/) in Python. The frontend is using [Bootstrap](http://www.getbootstrap.com/). It is hosted on [Github Page](http://pages.github.com/).