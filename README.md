# public-domain-assets
a curated collection of public domain assets, converted to eps format, suitable for use in ttrpg projects

## Just right clicking on files will not save them properly; read below for how to use.

## extent

This is not intended to be a comprehensive repository of all public domain assets anywhere, or a display of such in their original formats, or warrantied to be of any use for any purpose. It is a curated repository; contributions are welcome, within that scope. The eps format may or may not be suitable for your project, as it tends to have a fairly distinctive look. The benefit to eps is that it is scalable and easy to edit as a vector. You can do some neat stuff with it!

[the website]()

## sourcing

All of these come from public domain (as in pre-1920s) works available on the [internet library](https://archive.org/) or similar museum sites. When possible I've tried to retain titles in file names, but you'll have to forgive me on the ones that passed through my Affinity workflow before I got the idea to do this repo! 

All files are converted from original scanned jp2, if available, to eps, using [potrace](http://potrace.sourceforge.net/) to eps format. The conversion to svg is using inkscape or exported through Affinity.

```bash
for file in *.eps; do
    inkscape --export-type="svg" ${file}
done
```

## how to use

The easiest way to get all the files is to clone the repo or to save as a zip file, using the green "Code" button.

You can navigate to "images/eps", click on an image's filename, and select "RAW" before using "save as". The resulting .eps file can be opened in Affinity and used as any other vector file.


## license

The original artists are long dead, and all copyright has expired (I'm not a lawyer but if someone from 1880 shows up to complain I'll gladly take a piece down, and run screaming after). I don't think simply converting between formats changes that, so the stuff in this repo, unless otherwise marked, should still be the public domain and ready for you to unleash your creativity upon it. 

As always, do what makes you comfortable! And I'd love to see what you make.
