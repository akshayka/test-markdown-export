# Exporting to markdown with outputs

* Set your notebook to snapshot as Ipynb (see intro.py), or export it to ipynb at the command line, whatever you like
* install uv, then `uvx jupyter nbconvert --to markdown intro.ipynb`
* images will be stored in a separate folder
* if you want to embed images inline (without a separate folder), run `npm install embed-images -g && embed-images intro.md > intro_with_inline_images.md`
