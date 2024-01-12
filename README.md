/pokemons/${pokeObj.id}.png  
place the images folder inside the public folder.

the images can be accessed in this way.

https://stackoverflow.com/questions/37644265/correct-path-for-img-on-react-js

The public folder serves as a static directory for assets that are 
directly served to the client without any processing by Webpack or Babel.

It's a place to store files that need to be publicly accessible from the browser, such as:
Images
Fonts
Icons
Static HTML files
Favicons
Manifest files
Locally accessible JSON or text files

Build Process: The contents of the public folder are copied directly to the build output directory.

<img src={window.location.origin + `/pokemons/${pokeObj.id}.png`} />
images placed inside the public folder can be accessed by this source.
