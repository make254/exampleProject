# Example project
This is my example projec to see how a project template would look at

## .make254

Our metafile. Primary function is so we can identify this as a prject folder.

The inside of this file can be optional? Project_name can be pulled out of the first header also and we an put on a default license.

```
# If Project_name does'nt exist, well just grab the first header and go from there.
Project_name: My awsome example project
# We don't require a license, we'll have a default one
License: GPL3
```


## Code

code blocks can be used to document code

```
This is my code block.
I like my code block like this!
There are many code blocks out there,
	But this one is mine.
```

And if the markdown language can include code from other files we'll just link to it.

## Images
Images in a 500px width as standard? it should'nt be that hard to scale them on server.
Picture of kittens maybe? Or at least one.

![cat](pictures/cat.jpg)

Mmmm.... :p

Or maybe in a flick url?
![cat nr. 2](https://farm6.staticflickr.com/5286/5339239144_7eb95ba291_z_d.jpg)
Pictures taken by Magnus Bråth (www.sunsetseo.com). I stole them form flickr.com. Mad props to him or putting them out on a creative commons license. :)


## File inclusion
we actually don't care where anything are stored, but lets say we recommend that all code should be put into a src folder.