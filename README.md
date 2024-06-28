# Wildcards
A fork of version of a script from https://github.com/AUTOMATIC1111/stable-diffusion-webui-wildcards.git
Allows you to use `__name__` syntax in your prompt to get a random line from a file named `name.txt` in the wildcards directory.

# Added feature

* Removed repeats when using the same wildcard twice.
* If you repeat the same tag in a wildcard file to increase odds, it will still not repeat, but keep the increased odds.
* Added option to turn original repeating generation back (if you want it back for some reaason).

## Install
To install from webui, go to `Extensions -> Install from URL`, paste `https://github.com/p4ul3rdo5/stable-diffusion-webui-wildcards.git`
into URL field, and press Install.

## Install manually
Alternatively, to install by hand:

From your base `stable-diffusion-webui` directory, run the following command to install:
```
git clone https://github.com/p4ul3rdo5/stable-diffusion-webui-wildcards extensions/stable-diffusion-webui-wildcards
```

Then restart the webui.
