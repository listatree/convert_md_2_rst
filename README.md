# convert_md_2_rst

A simple Sphinx Doc extension to convert Markdown files to reStructuredText format

Convert Markdown to reStructuredText extension for Sphinx

Scans for '.md' files and converts them to '.rst' files using pandoc.

For use it just copy the file 'convert_md_2_rst.py' to your source directory and add
'conver_md_2_rst' to the 'extensions' value of your 'conf.py' file.

Ensure that the source path is in the Python sys path. For that
purpose you may add this line to 'conf.py':

sys.path.insert(0, os.path.abspath('.'))
