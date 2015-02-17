# convert_md_2_rst

Convert Markdown to reStructuredText extension for Sphinx Doc

Scans for '.md' files and converts them to '.rst' files using pandoc.

For use it just copy the file 'convert_md_2_rst.py' to your source directory and add
'convert_md_2_rst' to the 'extensions' value of your 'conf.py' file.

Ensure that the source path is in the Python sys path. For that
purpose you may add this line to 'conf.py':

sys.path.insert(0, os.path.abspath('.'))

IMPORTANT: The code assumes that you use the folder 'source' for your Sphinx Doc
files. If different, just change it in the 'convert_md_2_rst.py' file.
