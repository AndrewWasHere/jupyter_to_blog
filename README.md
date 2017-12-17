# Modify for Blog

A sed script to strip unwanted HTML and CSS settings from an HTML page
generated by Jupyter notebook so that the output is suitable for cutting
and pasting into a blog post.

Tested on Blogger.

## Use
    
   sed -f modify_for_blog < in > out

if you make this scripe executable:

   modify_for_blog < in > out

if you have xclip, or something similar, installed:

   modify_for_blog < in | xclip

then paste into the blog editor

where
   `in` is the file path to the Jupyter notebook HTML file.
   `out` is the file path to the edited HTML for cutting and pasting.

## License

This sed script is hereby released to the public domain.

