Welcome back.

So, the first thing that we need to learn about HTML is

the common HTML document structure.

So, a structure that each and

every HTML document needs to have.

But let's start by taking a very quick look

at the project that we're going to build

throughout this section.

So, we are building The Code Magazine.

So, as you can see here, and in this Code Magazine,

we are building this very simple kind of blog post called

"The Basic Language of the Web."

So we have some links here, we have images,

We have some bold texts.

We have, here, you see, we have some italic text.

We have lists.

And yeah, so there's a bunch of stuff

that we will learn in this section, so that by the end,

you will have learned the fundamentals of HTML

and we'll end up with this project.

Okay, but anyway, let's now finally get to work.

And the first thing that we need to do again is

to create our project folder.

So, let's go back to our desktop or to where you are working

with your files.

And what I'm going to do is to open up this folder

that we just downloaded in the last section.

So basically, the starter code,

and then I'm going to reach into this starter folder

and grab a copy of the starter files here.

So I will copy this folder and put it on my desktop,

right here.

Now, instead of doing that,

you could also simply go ahead and use this folder here

as your project folder,

but that might lead to some confusions.

So, I always prefer to simply copy this folder here

to somewhere else.

Okay, let's go back to VS code.

I can actually close this.

And then let's come here to the menu,

and then file, and open a new window.

All right, and then right here,

we can select open folder

or we can also expand the sidebar here

and click on open folder right here.

So remember that this will define our project folder.

So I'm going to my desktop and then select this folder

that I just created there.

So open, and there we go.

So, we can close this one now

and push this one to the left side.

This panel we don't need.

And then, here, inside of our project folder,

we can, just like before create a new file,

and we will once again, call it index.html.

So it's just a regular file with the html file extension

and the name of index, which should always be the main page

of any website.

All right, so, as I mentioned before,

we have some images here as our starter files,

and also this text file here.

So let's actually also open up this file

and now, I will click this icon here

to collapse the sidebar to give us some more space.

Okay, now, remember, how in the first section

we use this kind of cheat to create our HTML structure.

So we wrote the exclamation mark, and then type,

and that then gave us all of this structure.

However, to properly learn HTML,

we, of course, need to know how to write

all of this structure on our own.

And so, that should always be the first thing

that we learn in HTML.

So, we start with an empty page,

and then the first thing that we need to do is to declare a

so-called doc type.

So just write the less than symbol, exclamation mark,

and then doc type.

And to see that a VS code is actually trying to auto

complete this here for us,

but let's just write it all by hand

so that this code basically sticks in your memory, okay.

So we have to write an exclamation mark, doc type HTML in

order to basically tell the browser that this document uses

HTML. Next up, we need to create a HTML element.

So remember from the last lecture that to create an element

again, we use the less than symbol,

then the name of the element, which in this case is HTML,

and then we close that.

And once again,

a VS code automatically now closes that element for us.

So it created a disclosing tag.

Now, in case you don't want that,

you can actually turn off that functionality and

let me show you how.

So again, you come here to the settings

and then the name of this setting is called

auto close tags.

And actually I will turn this off for now

so that you can really write this code by hand

instead of having VS code helping you.

So we will turn this back on a bit later, but for now,

I really want you to learn how to write these elements

by hand, without any help now.

Okay, So we have the opening and the closing tag

of the HTML element. And now as for the content,

we will actually put another element inside it.

So let's give ourselves some space here.

And then inside of the HTML, we want first a head element.

So let's write it, opening and

I will then immediately close it actually,

because for now we will not put any content in there.

Okay.

So the head and then, the body.

And I will explain in a second,

what each of these actually is.

So each and every HTML document always needs to start

with the HTML element like this.

Then inside of this element, as we just put,

we need one head element and one body element.

Now the head element is basically for things

that are not visible in the browser window.

So this head will contain the page title,

some additional information about the page,

link to CSS files or other things.

And as we go through the course,

we will fill this head with all kinds of different elements.

But for now, all I want to do is to just specify the title.

So let's use the title element for that.

And this page, I want to call

'The Basic Language of the Web'

HTML.

So basically that's the title here of

this blog post as well.

Okay. At then, we need a closing tag of this element.

Okay.

Then the body is actually for all the elements

that will be visible on the page.

So all the elements that we see here in the browser

will always be inside of the body element.

And just to show it to you, instead of leaving it empty,

let me put some code here.

So I will again use the heading one element.

So H1 that we used in the very first coding lecture,

and let me just grab this text from here.

So that's the content that then again,

closing it, all right.

Now, we haven't saved this file yet, but as we do

prettier will again format this file for us.

So let's give it a save and you see that now we have the

correct indentation.

And by indentation, what I mean is that

since this head element, for example,

is inside the HTML,

it should have some space here to make that

visually obvious.

Okay, so basically this is just a tab here.

So if I hit the tab key,

then it will add another level of indentation.

And so now it's at the same level as the title,

which doesn't make sense because the title

is also inside of the head, right?

So we have the head inside of HTML and then inside of the

head, we have the title element.

And so therefore it has another level of indentation.

Okay.

Now this is just for aesthetic reasons to

make our code more readable.

So the browser really doesn't care about this indentation,

but it is still important for us

to be able to read the code.

So again,

let's give it a save and I think we are ready now to

actually go ahead and open this in the browser.

So let's come to our project folder and then double click

index.HTML, and nice, here it is.

Let's put it here first, close up this one,

but I will also leave this demo open just

so we see what we want to achieve in the end.

Okay, that's close up this one here.

And with this, we learned the basic structure of HTML.

So let's just quickly review.

So every HTML document always needs to start with these

so-called doc type.

And so this will let the browser know that we are actually

using HTML in this file and all browsers will then know

that they should use the HTML five specification to

render this HTML.

Then we have the HTML element,

which is always the parent element of both the head and of

the body element.

So this structure is really always the same

in all web pages.

We always need to have an HTML element with a head

and with a body.

Now, what we put into the head and the body is optional,

but having these two is not optional.

So we always need head and body.

Now in this situation,

all we put in the head is just a title element,

but here we can put all kinds of other stuff

that are not visible,

or that are not rendered here

in this main part of the browser.

On the other hand,

the content that we actually want to be rendered here

should go into the body.

And so that's why having this H1 element here,

then it appears to be visible on the page.

Okay, and that's it,

that's the basic HTML structure for each and every HTML

document that you really need to know.

And with that,

let's move on to the next lecture where we will learn a

couple of new elements for working with text.

So I hope to see you there soon