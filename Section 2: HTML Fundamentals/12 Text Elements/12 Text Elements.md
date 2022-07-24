In this lecture,

we will continue learning how to markup text.

So we will keep using some headings,

some paragraphs,

and we will also learn how to make text bold and italic.

And let's actually start with headings.

So usually the goal of headings

is to break up big blocks of text

into more logical sections,

and to basically add a title to each of the sections.

Now you already learned about the h1 heading,

but there are actually six different headings.

So there's a hierarchy of headings

so that we can establish a hierarchy in our text.

So we can go all the way from h1 to h6.

So let's grab this text here

and create all of these six different headings,

just so you can see how they look different visually

in the browser.

So the h1 we can call the "Primary heading",

and then the secondary heading is the h2.

And I'm pasting the exact same text here

so we can see the visual difference between them.

So we have h1, h2,

and then for the tertiary heading

we use h3.

Pasting the same text there.

And now we just have to repeat all of this

all the way down to h6.

All right,

and as you're typing this,

these characters,

so this code,

all of this will start getting into your brain

and you will start getting practice writing HTML.

So h6,

and then let's give it a save

and then reloading the browser.

And so you can see very nicely

that this really created a visual hierarchy basically

between these six headings.

So the first one is the biggest one by far,

and then this last one,

which is the h6

is kind of small.

And then in between we have all these different variations.

Now okay.

So now we know how these different headings work,

but now let's take a look

at our demo page actually

just to see which kind of headings we actually need.

So we have basically the name of this block,

so the code magazine,

and this is the biggest heading.

Then below that we have the name of the article,

so of this block post,

and this one is a little bit smaller,

so it's not a primary heading anymore,

but it is a secondary heading.

Then inside of this text here,

and remembered how I said that heading

is basically to break up texts into logical sections, right?

And so here in between this text

we have another section.

And so here inside this,

let's say block post,

and we have another heading.

And so this should probably be an h3.

All right.

And so let's now create a markup for this kind of structure.

So we have all these texts that we need actually here.

So we just need to copy paste this code here,

or this text.

All right.

So I'm leaving this here for now for reference.

And so,

remember we are going to start with the primary heading.

So I'll just paste this here

and then close the h1.

Now okay.

Then let's create our secondary heading.

And again I will grab

the texts from here.

And so that's...

Well that's actually the one that we already had before.

So this one is exactly the same as this one,

but that doesn't really matter.

It's no problem.

And then let's get our h3

which is what is HTML.

Let's just write that.

And then let's check out what this looks like

and here we go.

Nice.

So this is kind of the structure

of our text right now,

and now we just need to fill it up

with the paragraphs in between.

So basically for each of these paragraphs

that we have in the text

we can simply create a paragraph and a code.

Right?

And we already used the paragraph element before,

and so that's kind of a generic element

that we use to mark up bigger blocks of text.

So remember that's the "p" element,

and let me just grab the content here.

So the first one that we have here

is posted by Laura Jones on Monday, June 21st.

Let me copy it.

Oh and do you see that now

this element was again closed automatically.

Let's give it a save here.

And now let's create some additional paragraphs here.

So the p element,

and let me actually close it immediately here,

and then let's grab our text.

So it's this one here.

So copy

and paste.

And so by now we are starting

to build a really our project at the same time

as learning about these elements.

So this one here as well,

so I'm copying it again

and then pasting it inside of the p element.

So let's give it a save

and reload it again

and that's looking nice already.

Great.

Let's take a look,

and now let's just grab two more,

so these two paragraphs here.

So after the h3 that we have down here,

so "p" and closing it immediately as well.

So just double clicking to selecting all of it,

just a nice technique.

And then let's just add the final one.

And you'll see that in the meantime

it formatted to code here

and that's because of the auto save

and the auto format.

Okay,

now I saved it manually actually.

Let's go here

and there is our content again.

Now to clean this up a little bit

let's now actually get rid

of all of these six headings here.

So now you already know how they work

and that they exist.

And actually instead of getting rid of them,

we can use something called "Comments" in HTML.

So a comment in HTML

is a way of writing some code

that will not be visible in the browser.

And this is very useful

because it allows us to write comments about our code,

or also to simply hide some code

that we do not want to be rendered on the browser.

Now to write a comment

it's a little bit of a weird syntax.

So again we write the less than symbol,

then an exclamation mark,

then dash dash,

and then to close the comment VS code

already automatically created,

this dash dash closing part.

So this opens a new comment

and this closes that same comment.

Now let's remove this part here

and now you'll see that everything turned gray.

So all of this is a comment now,

but we actually want the comment

to end right here.

So "dash dash" and close,

and now only this part here is gray,

which means that this is now the comment

and it will now not be rendered.

So let's check that out.

And if I reload,

now it is gone from the page.

Nice.

But we can still keep it here in the code

just so you know that h1, 2, 3, 4, 5, and six also exist.

Now just one thing that I didn't mention earlier

about the headings

is that each and every page

should only have one h1 one heading.

So only one primary heading.

That it's very important to keep in mind.

This is not really mandatory

so it doesn't violate any HTML rules

if we have multiple h1's,

but it is a very good practice

to always just have one of them.

Now about all the other ones,

we can have of course multiple of them.

So for example,

I think on our page we actually have

another of these headings here

in the middle of our text.

And so in our case,

these are h3 headings.

So you see,

here is another one.

So of course we can also add that here

right away,

why not?

So h3,

"Why should you learn HTML?",

and then of course closing it.

Okay.

Now just to finish,

let me also quickly show you

how we can create bold

and a italic text.

So here in our demo site

we have this name of the author,

which is "Laura Jones" in bold.

So how can we do that in HTML?

Well there is a special element for that,

or actually two elements.

And let me start with a simpler one,

which is simply called "b".

So B stands for "Bold".

And so the part that we want to be bold,

so "Laura Jones" in this case,

all they have to do

is to put it inside of a b element.

So we can just write

b like this

in the beginning

and then at the end of the content

we simply add our closing tag.

So that's "/b",

close it,

and now once we reload or own page.

So take a look here at "Laura Jones",

if we reload that

then you see that it turned bold,

and great.

Now however,

the use of b is actually not a good practice.

So b is actually an older HTML element

and starting in HTML five,

we should always use the strong element instead of "b".

The reason for that

is that b doesn't have any so-called semantic meaning,

and more about that a little bit later in this section.

But essentially what this means

is that b is simply an element,

but without a specific meaning,

while on the other hand the strong element means that

this is really an important element

that we want to stand out from the page.

So if we say "Strong" on the opening tag,

and then of course also in the closing tag,

then it will look exactly the same in the browser.

So let's confirm.

Yeah it's still bold,

but now it has a meaning

that it is a more important text.

And that is essentially the idea of semantic HTML.

And again,

we will talk more about semantic HTML

by the end of this section.

So for now just know that don't use "b",

but use "Strong" to make text bold.

Now let's also make some text italic here,

and let's choose this word here.

So just fundamental.

And just like with "b",

there are actually two ways of doing it.

The older one

is the "i" element.

So wrapping whatever part of the text we want

to be italic inside of the i element.

"i" just stands for italic,

and indeed,

you see that now it changed,

but one more time in order to make this a semantic HTML,

we should no longer use the "i" element,

but the "em" element,

which stands for "Emphasize".

So we want to emphasize this text here

and that is the reason why we make it italic.

So that's also the reason why the browser

then shows it as italic,

right?

So if we reload it is still italic,

but now we basically gave it the meaning

of an emphasized text.

Now okay, great.

This is great progress.

You're doing really well up until this point.

Now just to finish this lecture,

I actually already want to give you

your very first small coding challenge.

So what I want you to do

is basically this.

Let me show it to you here.

So I want you to make the first letter of these words,

so "Hyper Text Markup Language",

I want you to make the H, T, M, and L bold.

All right.

So basically that is this text right here.

So this H,

this T,

this M,

and this L,

they should all be bold.

So they should be displayed here in bold

just like I have it in the demo page.

So do you think that you can do that

and write some HTML code on your own

for the very first time?

Well I really hope that you try it

because as I said before,

these coding challenges

are really really important for you

to start practicing your skills,

even if it's just something really simple like this.

So please go ahead

and pause the video right now

and make each of these four letters bold,

and I will be back here in a second with you

to show you how it's done.

So did you manage to do this?

Well this is how it works.

So once again,

we just need to wrap the parts

that we want to be marked as bold,

into a strong element.

And in this case,

that is just the "h"

and so that's why we're closing

this strong element right here

in the middle of the word.

Then here we want the "T" and so again,

we write...

And so again,

a strong element here.

So the opening tag,

and then the other one right here.

And of course then the same for the other two letters.

Now okay.

So hopefully I didn't do any mistake there.

Let's reload

and there you go.

HTML is now marked in bold.

Great.

So again,

I hope that you manage to do this on your own

as this is really important for your learning process.