Now it's time for the first big coding challenge

in this course, so let's get started.

Now, before we start with the actual challenge,

I want to first make some changes to the file structure

that we have in this project right now.

And in particular, what I want to do

is to put all the images into one folder,

so that I can then show you how we can include the images,

like this, when they are located in a specific folder.

So right now they are all, as we can see here,

they are all in the same, exact same folder

as the index.html.

And so that's why all we have to do

is to declare the name here,

and the browser will then find them

basically in the same folder as the HTML document.

But now let's create a new folder by clicking this icon,

and I'm gonna call it IMG,

and then I'm going to put all of the images there.

So just dragging and dropping them like this.

Okay.

And so now if we reload the page,

and not this one, which is our demo,

but the one we're working on.

And by the way, this time I had to actually

manually reload the page,

because I had my computer turned off in the meantime.

And so whenever you do that,

the very first time you come back,

you will have to manually reload the page here,

when you are running the live server extension.

Okay, so remember that we installed that in the last video,

and so if I do some change here now,

then that should probably just work just before.

So you see there is some change, and there it appears.

But anyway, you see that now that we have

these images inside of the IMG folder,

they are no longer found in the same folder as index.html.

So that's why they don't appear up here.

So what we need to do here

is to change the path to the image now,

and that's not a difficult problem.

All we have to do is to start a new path

with the name of the folder.

So that's IMG. and then slash, and so here we go.

So you see the image appears here now again, in this gutter.

And so let's do the same thing here,

give it a save, and here are our images back.

Okay.

So usually we always put the images in a separate folder.

And so I thought that was important to show you,

especially now before this challenge,

where we are going to use some more images.

So about the challenge, and being here,

back in the demo page,

and so essentially what I want you to do

is to code on your own this part here.

All right, and let me actually show you

where that should be in our markup, so in our HTML,

and it is right here after the article.

Okay?

So this section here about the related posts

is no longer part of the article.

It's also not part of the footer,

and so here we will need another element.

And this one I will actually write for you.

So here we are going to use the aside element,

and the aside element is usually used

for some secondary information

that compliments the information

in the main part of the page.

So in this case, the main part of the page is the article.

And then the aside, which is secondary information

is basically some related posts

that are related to the article, so to the main part.

Okay?

Now visually many times we use the aside element

as a sidebar,

but it doesn't have to be that way.

Okay, but now about the challenge itself.

So you see that it starts here with this heading.

So you can experiment which heading is best here.

So one of the headings, H1, two, three, four, five, and six,

remember, and then here you see

that this is actually a list, right?

You can see that because of these bullet points.

And so here for this part, you should probably use a list.

Now, what we didn't do before was to have multiple elements

inside of one list item.

So up here, for example, we have the list item,

and in there there's only some text,

but you see that here in each item, there is an image,

a link, and then some more texts here.

And that's no problem at all.

So inside of each list element,

there can be multiple other child elements, right?

And so with that information,

I think you are now able to build this.

Now, finally, just about the images here,

that some are information that you need.

They are also in this folder,

and they are called related-1, two, and three.

And the dimensions want you to give them is 75 by 75 pixels.

And now I think I gave you everything,

so please pause the video now,

and take a couple of minutes, 10, 15 minutes maybe,

to write up the HTML for this section.

So good luck with that, and I'll see you once you're ready.

All right.

So hopefully you did this just fine.

So let me show you how I did it.

And I hope that you start to see how helpful it is

that VSCode now automatically closes

our HTML elements, right?

So the source here is in the IMG folder, and then related-1.

Then the alt text, let's just say,

that this is a person programming.

And of course, your alt text

doesn't have to be exactly the same as mine.

So if your alt text is a bit different,

that is not a problem at all.

And now we need to close it as well.

And so that's the image part.

Next, we have a hyperlink, so an anchor tag,

and here the href, which is something that I didn't mention,

but hopefully you figured it out,

that this is one of the links

that should not point anywhere for now.

So How to Learn Web Development.

And now finally there's some text with the author there,

and so we can use a paragraph for that.

So by Jonas Schmedtmann.

Okay, giving it a save.

Now it's nicely formatted, and it should appear down here.

And indeed here it is.

Great, oh, I'm just missing here the heading actually.

So let me go back, and put that

even before the unordered list, so I'm using an h4 for that.

But anyway, let's continue now building our list here

with the next list item.

And by the way, if you did your code

a little bit different from mine,

that's really not a problem.

What matters here is that you

tried writing the code on your own.

That is really the most important thing

that I was expecting you to do here.

So width of 75, the height also 75.

(keys tapping)

Then again, a link pointing nowhere.

And this one is The Unknown Powers of CSS,

and by Jim Dillon.

And I'm not going to check out the result just yet,

let's just finish it.

So another image.

So the goal of this part here was really

to have you practice writing this same code basically,

or very similar code over and over again,

'cause this is the only way

that this stuff really gets into your brain.

So let's call this one JavaScript code on a screen,

and again, the width of 75, and the height of 75.

And you notice I'm writing this

a little bit faster right now,

because we don't want to waste a lot of time

writing this repetitive code.

This was really just for you to practice, is awesome.

Finally the paragraph,

give it a save, and beautiful.

So this looks just like in our demo,

and we have now all this content

that we want to display here nicely marked up

in a very logical way.

So you might be wondering why we used

a list here in this case.

And the reason for that

is basically the idea behind Semantic HTML,

that I explained a little bit earlier.

So if we think about these related posts,

we can very easily argue

that it is essentially a list of related posts, right?

And so if it is a list, we should mark it up in our HTML,

so we should write our HTML as a list.

And so that's just what we did.

Later with CSS, we will then remove these bullet points,

because they don't make a lot of sense in this context,

but even with the bullet points removed,

we still want a meaning of this element,

So of all of this here to be a list.

But anyway, that's enough for this video.

So I really hoped that you completed this challenge,

and that you enjoyed doing it, even if it took some time,

and even if you had to review some concepts

from the previous lectures.

That's completely normal,

and that's exactly how it should be actually.

Now in order to practice a little bit more even,

there is another coding challenge coming up,

which is completely detached from this project,

but it's a really exciting one.

So I hope to see you there soon.