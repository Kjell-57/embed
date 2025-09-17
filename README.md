# embed
The HTML tag &lt;embed&gt; need a function to make cross reference easy.

Hello

I have an important request when building a homesite.

I'm building a site with hundreds of documents where I need to have cross
refereces in all of them, placing it in a tooltip, and today there is no way to
make this work. If I change a bit of text in a document I also have to change
all references in all other documents that have a reference to it.

I have tried javascript but that does not work, because of some security rules:
You need to have both documents open at the same time. Who does?

There is a html tag that easily could be used to make it all work, if it had that
function, but it doesn't, today, and that is &lt;embed&gt;.

Today it works like this:
&lt;embed type="text/html" src="file.html"&gt;
and it works perfectly and instantly.

The problem with this tag is that I always get the whole document, not just that
part of the document that I want. And it always starts in the upper left corner.

But what if I could use &lt;embed&gt; by writing something like this:

&lt;embed type="text/element" src="#uniqueId"&gt;

And get only the text within that element, without any formatting or tags:
formatting takes place in the target place.

That would solve the problem instantly. Just one short line, and it's done.

I'm conviced that I'm far from alone with this request, and I'm also convinced
that it is far better to have as much functions as possible in html tags than in a
javascript or any other programming language.

I hope someone will see the great need and use of this function and grant us this
request. It would help a lot. Making a homesite should always be simple.

I post this, this way, because I dont know where turn to or whom to contact. 

Many thanks
Kjell-57

PS: I posted this to W3Scools and they liked it.
