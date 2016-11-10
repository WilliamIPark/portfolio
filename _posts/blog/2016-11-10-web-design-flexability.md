---
  layout: default-article
  title: Flexible Web Design
  meta: "If you're building a website that is anything more than an experiment it should always be in your interest to build a website as flexible as possible..."
  category: blog
  tags: [Web Development, Web Structure]
  date: 2016-11-10
---

If you're building a website that is anything more than an experiment it should always be in your interest to build a website as flexible as possible. But what do I mean by flexible?

If you're coming back to your website to make changes down the line, you'll want a flexible website. Something where you're not going to have to search through every file just to change a single word. Something where if your brand colours change it shouldn't be a nightmare replacing a bunch of hex codes in CSS.

## The Content

There's loads of ways out there to build a flexible website, so lets focus on the content first. Changing content is extremely important for most websites. You don't want content getting stale, because no one will want to revisit it. Depending on what you're doing you'll want to build off a database, or pull content from data centric files, like I'm doing here with YAML. Solutions like these allow you to build off data, using tools like Jekyll for a static site, or React for something more dynamic.

Tools like React, Angular, Jekyll, Vue, and loads more all allow you to take a component based approach to your website. Imagine you wanted to remake your navigation bar, which I am actually having to do on here soon. You won't have to replace code in every html file that includes your navigation, you can simply change the component and the rest will update automatically. Super flexible.

## The Style

When approaching the style for your website you should seriously consider using a tool like SASS or SCSS. These are fantastic pre-processors that will allow you to build more flexible stylesheets. They barely add any complexity into the mix most of the time and will save you a bunch of time if you ever need to come back to your stylesheets. This is because of features like variable support, where you can store values in keys. You can then use your keys as properties to your CSS rules. There's the massive added benefit here of being able to write modular CSS without additional http requests.

I have rules set up for all the fonts on this website so they can be easily changed, and a lot of the designs colour (or lack of) can be changed by changing the variable value.

## So...

Combining tools like these together can be a life saver if you are working on a big project or will be likely to return to your website. It will allow you to change stuff fast, and in turn will keep you more motivated to keep the website up to date and fresh.