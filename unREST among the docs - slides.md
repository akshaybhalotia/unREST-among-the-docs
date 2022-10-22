---
theme: default
size: 16:9
title: unREST among the docs
author: Akshay Bhalotia
description: At times, you have to build docs that cover not only REST-y APIs but also frontend SDKs. What do you do, when you have to offer docs for multiple such SDKs, based on different frameworks, under rapid, uncoordinated development with multiple feature enhancements per iteration and at times, with breaking changes, but versioned and searchable?
keywords: docs
# url:
# image:
marp: true
backgroundColor: #f7ede2
color: #482c3d
---

# unREST among the docs

---

<!--
paginate: true
header: unREST among the docs
-->

# What are we going to talk about

- Designing the docs
- For a better developer experience

---

# Who is this discussion for

- Technical writers - because they are faced with such problems and dilemmas almost daily
- Designers - who are working on technical information systems
- Developers - who want to be better at writing systems

---

<!--
<style scoped>
p {
        text-align: center
    }
</style>
-->

# `whoami`

- Akshay Bhalotia
- Professional interests
  - Payment systems
  - Developer SaaS
- Personal interests
  - Cats - proud dad to 2 cats
  - Boardgames
  - Mechanical keyboards

<p style="text-align:right; font-size: 40px">
    Find me here <a href="https://axy.one/twitter"><img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/twitter.svg" alt="https://axy.one/twitter" width=40></img></a> <a href="https://axy.one/github"><img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" alt="https://axy.one/github" width=40></img></a> <a href="https://axy.one/linkedin"><img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/linkedin.svg" alt="https://axy.one/linkedin" width=40></img></a> <a href="mailto:letstalk@axy.one"><img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/envelope.svg" alt="letstalk@axy.one" width=40></img></a>
</p>

---

# But why would you listen to me

I've seen some :poop: in my life

- an iOS Developer at an outsourcing boutique and a FinTech API startup
- an account manager at tech events and media company
- support and solutions engineer at another FinTech API startup
- developer relations manager at a real-time video API startup
- and now, a product manager at a data gateway API company

---

# Problem

---

# Docs are hard

- Primary function: **give info**
- But
  - in an easily readable manner
  - in an easily findable manner
  - help with the next steps
  - give enough but not too much
  - expect returning users

---

# What is harder

- Documenting frontend SDKs
- Documenting UI features
- With version control
- Feature-based releases, without a release cycle
- Breaking changes

---

# Let's see a few examples of how I've tried tackling some of these challenges

---

### Razorpay - Payment APIs for India

<img src="./razorpay_1.png" height=400></img>

An intro page helps the reader navigate to their appropriate section.

---

### Razorpay - Payment APIs for India

<img src="./razorpay_2.png" height=400></img>

When you click on any of the options, you land on the related overview section, but all the other options are available in the sidebar for easy navigation.

---

### Razorpay - Payment APIs for India

<img src="./razorpay_3.png" height=400></img>

All the steps are listed within the context, even if they are not related to the front end. Context matters. Complete information helps developers make better decisions.

---

### Razorpay - Payment APIs for India

<img src="./razorpay_4.png" height=400></img>

Clear differentiation and code samples for available options.

---

### Razorpay - Payment APIs for India

<img src="./razorpay_5.png" height=400></img>

Proper reference for all parameters.

---

### Razorpay - Payment APIs for India

<img src="./razorpay_6.png" height=400></img>

Switching to some other platform, say iOS, follows a very similar structure so the reader can expect what to find here.

---

### Razorpay - Payment APIs for India

<img src="./razorpay_7.png" height=400></img>

Platform-specific instructions and videos/gifs for steps to be performed in the IDE.

---

### Razorpay - Payment APIs for India

<img src="./razorpay_8.png" height=400></img>

Using callouts to draw attention to specific points.

---

### Dyte - real-time audio and video call APIs

<img src="./dyte_1.png" height=400></img>

The landing page shows all the available options.

---

### Dyte - real-time audio and video call APIs

<img src="./dyte_2.gif" height=360></img>

One of the best things we think we designed is the navigation. See how both the UI SDK and Core SDK are housed under the Web SDK section but at the top level. And within each of them, you can select a different platform or framework. The best part? When you select a component or page and switch the framework, the context is preserved!

---

### Dyte - real-time audio and video call APIs

<img src="./dyte_3.png" height=400></img>

Strong belief in "show not tell" - live editor!

---

### Dyte - real-time audio and video call APIs

<img src="./dyte_4.png" height=400></img>

Strong belief in "show not tell" - a visual representation

---

### Dyte - real-time audio and video call APIs

<img src="./dyte_5.png" height=400></img>

Strong belief in "show not tell" - actual renders

---

### Dyte - real-time audio and video call APIs

<img src="./dyte_6.gif" height=400></img>

Strong belief in "show not tell" - gifs which show the effect of code change

---

### Dyte - real-time audio and video call APIs

<img src="./dyte_7.gif" height=400></img>

All relevant info at a single place.

---

### Dyte - real-time audio and video call APIs

<img src="./dyte_8.gif" height=400></img>

All relevant info at a single place.

---

### Dyte - real-time audio and video call APIs

<img src="./dyte_9.gif" height=400></img>

But also separately as a reference.

---

### Dyte - real-time audio and video call APIs

<img src="./dyte_10.png" height=400></img>

Bonus - Design for developers!

---

### Phyllo - Data gateway for the digital economy

<img src="./phyllo_1.png" height=400></img>

Clear demarcation for SDK and API sections

---

### Phyllo - Data gateway for the digital economy

<img src="./phyllo_2.png" height=400></img>

Glossary towards the beginning

---

### Phyllo - Data gateway for the digital economy

<img src="./phyllo_3.png" height=400></img>

Visual indicators for the flow

---

### Phyllo - Data gateway for the digital economy

<img src="./phyllo_4.png" height=400></img>

Visual reference for the components

---

### Phyllo - Data gateway for the digital economy

<img src="./phyllo_5.png" height=400></img>

A clear distinction between web (which is browser-based) and mobile native SDKs

---

### Phyllo - Data gateway for the digital economy

<img src="./phyllo_6.png" height=400></img>

There is a choice between two options

---

### Phyllo - Data gateway for the digital economy

<img src="./phyllo_7.png" height=400></img>

Which is clearly explained and differences highlighted

---

### Phyllo - Data gateway for the digital economy

<img src="./phyllo_8.png" height=400></img>

Along with a callout for the most common mistake/misunderstood path

---

### Phyllo - Data gateway for the digital economy

<img src="./phyllo_9.png" height=400></img>

And that misunderstood path - mobile in-app browsing - also gets a page of its own to explain things better

---

### Phyllo - Data gateway for the digital economy

<img src="./phyllo_10.png" height=400></img>

Try to keep the flow and explanation of steps same, or as much similar as possible

---

### Phyllo - Data gateway for the digital economy

<img src="./phyllo_11.png" height=400></img>

Maintain a changelog (this is probably not the best way but work with whatever you have)

---

# Let's see a few examples of how I've seen others give it a go

---

I tried turning towards two of the most popular frontend frameworks that are used to build modern apps, and here is what I find.

---

### React JS

<img src="./react_1.png" height=400>&nbsp;&nbsp;&nbsp;&nbsp;</img><img src="./react_2.png" height=400></img>

You would imagine something that is so popularly used to build interfaces and visual components would have more visual diversity in the docs.

---

### Vue JS

<img src="./vue_1.png" height=300></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="./vue_2.png" height=300></img>

But they are rather boring walls of method references and guides/tutorials.

---

### Lottie

<img src="./lottie_1.gif" height=400></img>

Something that is used to build animations has absolutely no animations on the docs and just a lot of text.

---

### Auth0

<img src="./auth0_1.png" height=300></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="./auth0_2.png" height=300></img>

Provide a lot of starter kits and guides for different frameworks.

---

### Agora

<img src="./agora_1.gif" height=400></img>

Make it a breeze to interoperate.

---

And lastly, we have the love of all documentation geeks, that probably everyone looks up to.

---

### Stripe

Stripe provides two frontend integrations - Stripe Checkout (pre-built complete checkout UI) and Stripe Elements (components to build the payments part of your checkout experience). Here is how they document both.

---

### Stripe

<img src="./stripe_1.png" height=300></img>&nbsp;&nbsp;&nbsp;&nbsp;<img src="./stripe_2.png" height=300></img>

Introduce the feature on a landing page and give the most common options to read further about.

---

### Stripe

<img src="./stripe_3.gif" height=400></img>

But why it works so well is that they also provide sort of a live code integration walkthrough. This is where you land when you click "get started with Elements".

---

### Stripe

<img src="./stripe_4.gif" height=400></img>

Very similar experience for the pre-built checkout section too, since most options on that screen (such as payment methods, collect address, etc.) are controlled by the API request you make before starting the payment.

---

### Stripe

<img src="./stripe_5.gif" height=400></img>

Despite this great step-by-step hand holding, they have complete references for their SDKs in case someone would like to make use of a specific component for a specific use case, or a tinkerer would like to tinker.

---

# Conclusion

I don't know if there are rules or guidelines that I can give you. It's all very contextual and that's not great.

## What we can certainly do

- Think of the user
- Think about what matters to them
- Try not to overwhelm
- But keep information accessible
- Interoperability and drawing parallels between frameworks help

---

# My sincere wish

Standards for method definitions, across languages and frameworks, including UI components

---

## Thank you for listening to my rant

<img src="./malai-makkan.jpeg" height=400></img>

_I can try answering your questions now, no guarantees though._
