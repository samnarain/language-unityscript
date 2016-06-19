# UnityScript for Atom

UnityScript language support for Atom. It uses 99.9% the patterns from language-javascript. Minor changes, such as the use of ToString() instead of toString().  

The snippets are pretty straight forward organized. It is not intended to be a code completion package, but to prevent your UnityScript syntax highlighting breaks when Atom considers it as *everyday* JavaScript (which it is not...). And as I am lazy combined with UnityScript requiring explicit definitions, these snippets were born.

### It is bare bones.

The UnityScript language is a fun language. It is full of secrets I do not know.

### Less talk. Work, work!

Right. See all snippets in the Settings of this package - *or be a hero* and see **snippets/language-unityscript.cson**.

````x```` is the first character to type to have a sad form of code completion on common Unity data types.

````u```` is the first character to type to have those data types be prefixed by a colon.

````pv```` are first to type to have those data types be declared public.

````ppv```` are first to type to have those data types be declared private.

````mc```` are a sad excuse to type for some quick Mecanim parameters at this moment.

````ppv```` are first to type to have those data types be declared private.

````ue#```` is one of the directives you can type with the # as suffix.

````m```` is the first character to type to get a quick MonoBehaviour function.

You should have fun with ````go````, ````tr````, ````gc```` and ````dl````. Like all snippets in atom, press TAB to play.

### Whats in the CSON soup?

- shortcut snippets for public/private variables with Unity classes
- shortcut snippets for directives (pragma strict, unity editor.. etc.)
- shortcut snippets for GameObject (transform, GetComponent, Instantiate, Destroy.. etc.)
- shortcut snippets for common MonoBehaviour (Awake, Start, Update, FixedUpdate, LateUpdate.. etc.)

### This stinks

Feel free to change, fork or whatever makes you happy. I didn't found anything in the package list when I started
on this. Would love to see improvements here and there, as Atom is just my favorite editor for any coding.

*[Unity](https://www.unity3d.com) is a cross-platform game engine developed by Unity Technologies and used to develop video games for PC, consoles, mobile devices and websites. This is not an official package from Unity.*
