1.Install python 3
2.Go through web.py and create code.py
	Documentation: https://webpy.org/docs/0.3/tutorial
3.How to resolve
	ImportError: No module named web
	Refere: https://stackoverflow.com/questions/56254294/got-importerror-no-module-named-web
		try downloading from, github: git clone git://github.com/webpy/webpy.git
	$python3 -m pip install web.py==0.62	//This command worked for me
4.Run web server
	G:\Tryouts\Python\FirstWeb>python code.py
	http://0.0.0.0:8080/
5.Check from browser
	http://localhost:8080/
	==>It should show: Hello, world!