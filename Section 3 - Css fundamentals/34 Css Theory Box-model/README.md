The CSS box model is one of the most fundamental

parts of CSS.

And so you really need to understand it

in order to learn CSS.

And so that is exactly what we will do in this video.

Now, what exactly is the box model?

Well, the box model defines how elements are displayed on a

webpage and how they are sized.

So in this box model,

each and every element on a webpage can be seen as a

rectangular box and each of these boxes can have content,

a border and space inside and outside of it.

So let's define all of the pieces of the

box model one by one, and starting with the content

This is the actual content of the element.

So it can be text or images or a table,

a video, or really any other content that we might specify.

Using CSS properties, we can specify both the height and

the width of the content area,

which we will do in one of the next lectures.

Next, we can define a border that goes

all around the element.

And actually we already did that before. Remember?

And by the way, this border is technically

still inside of the element.

And now the next ingredient of the box model is the padding.

So padding is basically invisible white space that we can

create around the elements content.

So between the content and the border,

you can see that nicely in this diagram,

and it will make even more sense when

we start using this in practice.

But anyway, just like the border, the padding is also

still inside of the element.

So essentially padding is empty space that we can create

inside of elements.

Then similar to padding, we also have margin.

Now the difference is that margin creates

empty space around the element.

So outside of the element itself.

So in practice,

we use margin in order to create space

between elements on our page.

So if for example we want space between

two certain elements, we simply specify the

margin property on one of them.

So again, padding is empty space that we can

add inside of any element.

It will sit between the content itself and the border,

which is basically the outermost part of the element.

So the content, padding and border all together are the

visible parts of the element as we can see it on the page.

Then, around all that, we can add some margin

in order to create space between elements.

Now what's important to note here is that all of these are

actually optional,

so we don't have to specify paddings or a border or margins

so we can define none of them or some, or even all of them.

It all depends on how we want our layout to look like.

Finally, there is also something called

the fill area and this one can be a bit confusing,

but let's try to understand it.

So remember that the text content and

images are inside the content box, right?

Now, the same does not apply for background

images or the background color of an element.

These properties will actually be applied not only to

the content area, but to the entire fill area,

which also includes the padding and the border.

So basically if we apply a background image or a color,

it will occupy the entire visible part of the element.

Now, for some people,

this can all sound very abstract and hard to imagine

in the real world.

And so in these situations,

it's very useful to think of an analogy in the real world.

And one analogy that I personally find very helpful

is to imagine a frame on a wall.

So in this analogy,

the drawing or the image that is in the frame is

the content area.

Then, many frames actually have this like kind of

white paper between the drawing or the image

and the actual frame itself.

And so if we bring that back to our box model,

then that would of course be the padding.

So the space between the content area and the border.

And so in this analogy, the frame is of course the border,

right? So that makes a lot of sense.

Finally,

when we hang a picture on the wall using a frame like this,

then of course there might be some space between other

elements on the wall or even some other walls on the sides.

And so in our box model analogy,

that of course would be the margin.

So it is the space that is outside of the frame and

creating space between frames. So for example,

there might be another frame somewhere here on the wall and

the space between those frames, so outside of them,

is what we call the margin in the box model. Okay?

So hopefully this analogy from the real world helps you

bring these concepts back into the

more abstract world of CSS.

And now, just to finish, let's quickly learn

how the box model actually calculates

the exact size of an element based on

the content, border and padding.

So, as I mentioned,

we can specify the height and the width of the content area.

Now, if we choose not to define the height or width,

then the box model will simply

imply them based on the content.

However, these specified or implied heights and widths

are actually not the final sizes of the element.

And that's because the border and the padding

are also taken into account.

So the final width of an element as we see it in the

final layout is defined by the left border

plus the left padding plus the specified or implied width

plus the right padding plus the right border.

And the same logic of course applies to

the height of an element.

So it's the top border, plus the top padding

plus the specified or implied height

plus the bottom padding, and finally the bottom border.

Now, as you can see, the margin is of course

not part of the width or height calculations

of the elements, because again,

it is just space that is around them.

And as I said in the beginning of the lecture,

we can of course specify all these individual sizes using

certain CSS properties.

Now what's very important to note here is that this way of

calculating heights and widths is actually just the default

behavior of the box model.

However, we can change this default behavior

because it actually doesn't make much sense and

we will do that a bit later, but for now

I don't want to confuse you anymore

and so let's start by using this default behavior

starting right in the next video.
