One thing that our blog post

is still missing right now is some images.

And so let's now learn how to use the HTML <img> element.

So, if we check out the demo page,

then we notice that here we have two

kind of important images.

So, we have this big image here,

which kind of illustrates the blog post.

And then we also have this photo here of the author.

And so let's now start by incorporating this image here

into our blog.

So, the images are, of course, in our project folder.

So, they came with the starter files.

And the one that we are going to include here,

is this post image.

So you see when you double click,

so when you open this file,

then VSCode is actually able to display image files,

and without any problems.

So we want this image right here after this author.

So basically the image serves as a barrier

between the beginning of the article,

and the rest of the page, so the top part.

Now I think that here, actually this title here,

so this <h2> element should be before the author.

Let's move that down here.

Right, so first, of course,

like we have it here, needs to come the actual title.

So the heading element, and only then the author,

and then this image here.

Okay, but anyway, let's now include the <img> element.

So again, right here after this paragraph,

we want to include this image.

So just like any other element,

we start by writing it like this.

But now remember how I actually told you

in the first lecture of this section,

that the <img> element is a special element,

and that's because it doesn't have any content,

and therefore it also doesn't have a closing tag.

Instead, what we do is to simply add the slash

here at the very end of the element.

Now you might wonder if we don't specify any content here

for this <img> element,

then how will HTML know which element it should display.

And that is an excellent question,

which brings us to something new in HTML,

which are attributes.

So attributes are basically pieces of data,

which we can use to describe elements.

So there are lots of different attributes in HTML,

and one of them is the <source> attribute.

And so that's the one we are interested in right now.

So <source> goes like this, SRC, and then an equal,

and then we need double quotes like this,

and then we can simply specify the name of the image.

So remember, that is post-img.jpg.

And so we just write post-img,

and we could even allow VSCode to auto complete

that code for us, like by clicking here,

or going down, and actually that didn't work.

But if we just hit enter here,

then that would work just fine.

So again, we can write it manually,

or just use VSCode's auto complete functionality.

And that's actually it,

that's the very basics that we need

in order to display an image.

So if we reload this now,

you will see that indeed here it is.

Great, so again, let's just quickly recap.

We did not specify the image

using some content in this element.

Instead, what we needed to do was to specify an attribute.

And in this case, it's the <source> attribute.

And remember that an attribute

is basically like a piece of data,

so a piece of information describing this element.

So here we are describing the source

from which the browser should basically read the image.

All right.

Now, besides the <source> attribute,

there are other attributes that we can specify for images,

and one that we should never skip is the alt attribute.

So we write it like this,

and alt stands for alternative text.

So basically what we need to specify here

is some text that should describe what the image is about.

And this is very important for various reasons.

One of them is that it will allow search engines,

such as Google Chrome,

to actually know what is in the image,

because without this description,

search engines don't really have a know of knowing

what the image is actually about.

And second, and probably even more important,

is that by specifying the description of the image,

we can also allow blind people to use a website.

So users who use a screen reader

will not see the image,

but instead they will have the screen reader

read the alternative text, so the description to them.

So never skip this attribute.

It's very important to always write a good description.

So here, let's say that this image here is HTML code

on a screen.

Okay, now this will not visually change

actually what we see here.

So let's reload, unless the image for some reason

can not be found.

So let's say that we forgot the G here, for example.

And so now this image path is completely wrong.

So if we now reload,

then the browser will not be able to find the image,

but instead, what it will do

is to then print our description here.

So that's the HTML code on a screen that we gave it here.

Okay, so that is actually another use case of the alt text.

Let's put it back, and we are actually still not done.

So we can specify some more attributes here,

which are quite important in this case.

So the ones that I mean

are the image width and the image height.

So right now this image here is a little bit too big.

And so let's specify its width to 500 pixels,

and don't worry yet about what these 500 pixels mean,

or exactly what a pixel is.

We will talk more about that once we reach the CSS section,

but for now let's just write width, and set it to 500,

and then let's see, okay.

So now it's scaled the image to a width of 500,

and it automatically also maintained the aspect ratio

of the image.

All right, but we can also specify that.

So besides the width, we can also specify the height,

which should be 200.

And I know that because I know the image dimensions.

So if we open this up again,

you see here that the original image is a thousand by 400.

And so if I specify the width as 500,

which is just half of a thousand,

then the height must also be half of 400 here,

so that would be 200.

Okay, so that should now look the same.

And it does, but of course, if I want it,

I could make it a square, for example,

which would then completely distort the image,

just as we see here.

Of course we don't want that, so put it back and here we go.

Great, so this is how we include images

into an HTML document.

And to this one here was only the first one that we wanted.

The other image is this author image

right here above this author paragraph right here.

So the image that we want now is this one, Laura Jones,

and we want it with a height and a width of 50 pixels.

Okay, so I have another challenge for you.

And what I want you to do this time

is to include this image that I just showed you

on your own right here in this place.

Okay, so take a minute, and pause the video,

and include this image with 50 by 50 pixels.

And then I'll be back here in a minute with the solution.

All right, so hopefully you got some more practice there.

So image, and I will immediately start

writing the attributes, and I will then in the end,

close the element.

So here we want Laura Jones,

and now I will just hit enter or return

to auto complete the file name here.

And then the alt text,

let's say that this is a Headshot of Laura Jones,

and not Jonas, and a height, and here again,

we could now hit enter or return to auto complete this.

But I actually want you to write these attributes

by yourself by hand, so that they get into your head.

So that's really important.

So a height and a width of 50, and that's it.

So let's close the element, give it a save,

and then Prettier does this nice job

of putting each of these attributes here in one line,

which makes it really easy to see.

Actually let's close down our sidebar here, and let's see.

And here we go.

So here is that picture of Laura Jones now.

Okay, well done, nice progress.

So now we know how images work,

and how attributes work as well.

And actually we can specify attributes

also on some other elements in HTML.

And one where this is very important

is actually the HTML element itself.

So here in this HTML element,

we should specify the language that we use for this webpage.

So for this document, and we can do that by saying blank,

so specifying the lang attribute,

and then in this case, since it is English,

we can set it to EN,

but for other languages, there are other codes.

For example, for German, just probably DE,

or for Portuguese, it would be PT.

And if you have any other language,

you can just easily find out the code by Googling.

Another thing that we can, and actually should do,

which needs attributes is to specify the character set

that is used in the document.

So that is something that goes into the head,

because it is a piece of information

that describes the document.

So here we need another new element.

And this is simply called meta, which stands for metadata.

So metadata means data about the data.

And so here we are describing that the character set,

which we describe by this attribute.

So we say that the character said should be UTF-8,

which basically is all the simple characters that we use

in the English language.

Now this one here is another of these elements

that doesn't have a closing tag,

and so we just close it like this.

Okay?

Now I'm not spending a whole lot of time

on these elements, and on this kind of stuff,

because later when you actually built your own pages,

then this will all happen automatically.

Okay?

So this was just to show you that

this is just another way or another place

in which we need some attributes,

where we then need to specify a value for it.

All right?

So UTF-8 here is the value that we specified

for this character set attribute.

Okay, and yeah, I think that's it for this lecture.

So, see you in the next one.