Welcome to the first actual lecture

of this course.

Now there is a good chance that this course

is going to be your very first contact

with any web development.

And so before we start writing HTML and CSS code,

I think it might be a good idea

to actually begin this course

with a very high level overview

of this field of web development.

So we're going to talk about things like

clients and servers, front-end and back-end development,

static and dynamic websites.

And of course about the core languages

and core technologies of web development.

And I'm going to explain all this

around the process that happens

when we open up a webpage in a browser.

Just keep in mind again,

that this is just a high-level overview.

And so I'm going to leave out a lot of details here.

This is really just so you get familiar

with some of these concepts and terms

that all web developers know

before you start your own journey.

But anyway, let's say that we're trying to access a webpage

in our browser at omnifood.dev

And by the way, this is actually the website

that we're going to develop throughout this course.

Now what happens as we try to access this page

is that our browser will send a request to the server

where this page is hosted on the internet.

So each and every website is stored

on something called a Server, which is basically a computer

that is connected to the internet

and is able to receive requests like this one.

So again, when we browse to a certain website,

our web browser will send a request to the server

where the website is stored. So where it is hosted.

Then when the server receives the request,

it will take all the files that make up the website

and send them back to the browser.

And so we say that the server sends response to the browser,

which essentially contains all of these files

that the website is made of.

Now, as you can see from these file extensions,

we have some HTML, CSS, and also a JavaScript code here.

And these are precisely the three languages

that browsers can understand.

So what this means is that all of the code

that makes up a website needs to always be written

in HTML, CSS, and JavaScript.

Because again, these are essentially

the three core technologies that any browser can understand.

All right, now, once the browser receives

these HTML, CSS, and JavaScript files

from the service response,

it will take the code and render the website

that we were trying to access.

So based on that code, okay.

And with this, you already have a good understanding

of what actually happens when we browse to a website

and also about the technologies

that we use to build any website

and that process of writing HTML, CSS, and JavaScript code

that the browser can understand

is the process that we call Front-End Web Development.

So whenever you hear someone

talking about Front-End Development,

what they mean is developers writing the code

that is displayed in a browser,

which is basically the front-end of a website.

And in fact, this is essentially what we're going to learn

in this course, or at least the very, very fundamentals

of front-end development,

which is learning HTML and CSS.

Now, just as a side note here,

whenever the files that make up the website

are simply stored on a web server

and are then sent to the browser as they are,

we say that we have a static website.

Okay.

And this will make a little bit more sense in a minute

when we talk about what a dynamic website is,

but for now, just keep in mind that a static website

is basically a website where the files

are simply sent from the server to the browser as they are.

So without any transformation.

All right.

So I hope that from this,

you learned what front-end development is

and also about the three core technologies

that make up any website.

And so now, let's take it one step further

and talk about something called Back-end Development.

So let's try another example here.

And this time, let's try to understand

what would happen

when we try to access a website like udemy.com

So once again, the first step is that a request

is sent to the web server where udemy.com is hosted.

Now, why is a website like Udemy,

so different from something like the static Omnifood website

that I showed you earlier?

Well, a complex site like you udemy.com

is really completely different from a static site,

because there is a lot of content

that is always changing all the time.

Like on Udemy, there are always new courses

and new reviews being added to the site.

New ratings and new course length

are calculated for example,

and really a bunch of other things like that

are always happening.

And so in order to make a system like this work,

udemy.com needs a whole application

running on the server, and they also need a big database,

which basically contains all the courses

and all the reviews, all the users,

and really all the content

that is being displayed on their website.

Now to do all this, front-end technologies

like HTML and CSS are simply not enough.

So basically with what you're going to learn in this course,

you're not going to be able

to build something like udemy.com

All right.

So to write applications

that are actually executed on web servers,

developers use some kind of back-end language

like Node JS, PHP, or Python.

So what these languages do is to take data out of a database

and basically assemble that data into the final files

that will then be sent to the browser as the response.

And this whole process is called Back-end Development,

because this is basically the invisible part of a website.

And so it's the website's back-end.

Now in this situation, we say that we have a dynamic website

because the website is dynamically assembled

from different pieces on the server.

And that happens each time that someone visits the website.

So returning to the example of udemy.com

In fact, each time that you visit Udemy,

a new version of the website is going to be generated

from their database and sent to your browser.

Now, on the other hand, if udemy was a static website,

then the website files

would already be sitting on the server,

just waiting for someone to access them.

Okay?

So that's the big difference between static and dynamic

In static, the files are already done

and in dynamic, they first need to be generated

by an application that is running on the server.

All right.

But now the rest of the process

is actually the same as before.

So these files are now ready to be sent to the browser

as a response, which will then be converted

to the final website

like this one we see here of udemy.com.

Great. Now of course,

there is no need for you to memorize all these names

that I mentioned here,

and also no need to deeply understand this process.

All I want here is to give you an overview

of what front-end and back-end actually are,

what the browser and the server are.

And also what static and dynamic websites are,

because I really think that this is going to be

extremely helpful as you start your developer journey.

But now, just to finish, let's take a closer look

at the three languages of the front-end.

So HTML, CSS, and JavaScript.

And starting with HTML,

HTML is responsible for the content of the page.

So that's the text, the images, the buttons,

and really all the content that you see on a webpage

is always written inside an HTML file.

Then the CSS is responsible

for the presentation of that content.

So basically for styling

and for laying out the elements on the webpage.

Now finally, JavaScript is the actual programming language

of the front-end.

So it allows us to add dynamic

and interactive effects to webpages.

We can also use it to manipulate the content or the CSS

to load data from web servers

and even to build entire front-end applications,

which we then call web applications.

Now we can also use the analogy

of nouns, objectives, and verbs

to make the separation of roles here

a little bit easier to understand.

So in this analogy, HTML represents the nouns.

For example, saying that the P element is a paragraph.

So paragraph is the noun here.

The CSS then is the objective

because it basically describes the noun.

For example, like this piece of CSS

saying that the paragraph text is red.

And so red is the objective describing the noun.

All right.

Finally, JavaScript is of course the verb,

like saying hide the paragraph.

So we're actually doing something here.

And so we have a verb.

Okay. Does that make sense?

All right. And with this,

we finish our introduction to web development.

And so we're now ready to start working

with HTML and CSS code in his course