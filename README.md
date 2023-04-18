# argparsegui
Application that generates a GUI interface for Python programs that use Argparse module for parsing command line arguments.
Design plan: When developing a Python application, this module would be imported. The parser object would then be passed to the module and scanned for available options, from which a GUI interface would be generated. Then, when the program is invoked without arguments, the module would produce a GUI with the options, user would enter them, and program would run as usual. 
