---
title: "Pocket Redesign"
layout: single
permalink: /work/pocket-redesign
date: 2016-03-23T11:48:41-04:00
toc: true;
toc_sticky: true;
toc_label: "Index"
toc_icon: false;

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/splash-trial.png
  actions:
    - label: "Download"
      url: "https://github.com/mmistakes/minimal-mistakes/"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: assets/images/splash-trial.png
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: assets/images/splash-trial.png
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/splash-trial.png
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: assets/images/pocket.gif
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: assets/images/splash-trial.png
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: assets/images/splash-trial.png
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---






# Project Overview 👀

**Context:** Personal Project

**Role:** Product Designer

**Deliverables:** User Research, User Experience Design, Interaction Design, Visual Design and Prototyping

**Timeline:** 3 Weeks (April 2021)

**Tools:** Pen, Paper, and Figma

One day I was scrolling through Twitter when I stumbled upon a tweet by Austen Allred (CEO of Lambda School) on Pocket.

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610127922397_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610127922397_image.png)

Tweet that was the idea trigger for this redesign

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621445393053_Frame+7.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621445393053_Frame+7.png)

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621445437687_Frame+6.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621445437687_Frame+6.png)

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621445462131_Frame+8.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621445462131_Frame+8.png)

Some of the comments to the tweet

As a Pocket user myself, I find myself doing the same thing. There is **no incentive** for users to go back and read the saved articles. As an upcoming product designer, inspired by this, I decided to **redesign the Pocket** app to accommodate incentives for people to read inside the app **regularly**. This case study documents my process of doing so.

During my intensive usage of the app for research and understanding purposes, I found out some other features of the app can be improved too. In this case study, I have also documented **improvements for one such feature - the discover tab.**

---

# Introduction

Pocket is a **read-it later** software. It allows users to save articles which they find on the internet. Users can later **read the saved articles** inside Pocket’s mobile and web apps which are designed for a rich reading experience.

Saving articles in Pocket is one of the lowest friction processes. With a simple click on Chrome extension on the Web app.

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610477770701_final_5ffdf04b5800b000296d850e_707665.gif](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610477770701_final_5ffdf04b5800b000296d850e_707665.gif)

1-click process!

On Mobile, sharing an article with Pocket saves it.

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610537497233_Hnet-image+1.gif](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610537497233_Hnet-image+1.gif)

However, this ease of saving articles in Pocket has a disadvantage too. Saving an article in Pocket **serves a dopamine kick**. When we save an article to Pocket, it is easy to assume that the thought is over.

Imagine this - you were on your daily rabbit hole exploration. You had several chrome tabs open. Each containing articles which you want to read. However, that rarely happens. To ease yourself psychologically, you just save the articles in Pocket. The open chrome tabs were [unfinished](https://twitter.com/thechrisyared/status/1257783812043522050?s=20) thought processes. By saving, we console ourselves that we got a grasp of the idea. **We delay the real confrontation with the idea.**

Austen’s tweet (which is now deleted :/) received around ~126 comments. Everyone chiming in with their views, unsurprisingly, almost everyone agreed with it. A tweet having **~126 comments** about a product is itself a gold mine for a product designer. In the comments, the users have explained their problems verbosely. They **did not shy away from expressing their experience** of using the product. This tweet became my main source for user research.

---

# Research 🧠

**The Consensus:** Pocket does not incentivize users to go back and read the saved articles

Here are some tweets which guided my process.

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610132291618_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610132291618_image.png)

---

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610132333109_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610132333109_image.png)

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610132346232_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610132346232_image.png)

---

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610132369037_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610132369037_image.png)

---

During my usage and research of the app, I found **discover/explore features** inside Pocket are not that great. Pocket usually offers recommendations from big publications inside the discover tab. At times, the recommendations, are listicles made to attract readership rather than to convey earnest thoughts.

Though it is wishful thinking, I wanted to design features or improvements which can be implemented. However, implementing a feature or improving an existing one requires a business case to do so. This made me deeply think about the business model of Pocket. Here is a quick detour explaining **Pocket’s business model**:

- Pocket is **free to use for the most part**. Being a part of Mozilla Corporation, the commercial arm of Firefox’s non-profit development group, it has hints of product thinking focusing more on user experience than revenue. For example - there are no ads even in the free tier.
- There are two tiers - **free and premium**. The marketed features of premium are -

    ![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610540596634_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610540596634_image.png)

    - Premium Memberships are the only source of revenue for Pocket as far as I can tell. Initially, it seemed to me that because the discover tab shows recommendations from big publications, maybe Pocket has business tie-ups with these publications. However, these tie-ups will only drive readership numbers and not an advertising base for the publications as Pocket is ad-free. Hence the case of tie-ups became unlikely.

Here-in lies my idea - **Pocket offers features (in Premium Memberships) that work well on top of extended amounts of reading/usage of the app**. For example, Highlighting - people who will use the app for reading a lot will find out that 3 highlights (offered in the Free tier) are not enough highlights to mark the useful takeaways of an article.

Therefore there lies a business incentive in increasing the in-app time spend of the users. The increased in-app time will make the users realize the need for premium features.

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621450247272_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621450247272_image.png)

To increase the time spent, we should focus on increasing the articles that are useful to the readers. For example, A) 10 ways you are related to Jon Snow (clickbait, SEO optimized) v/s B) How to become a product manager? (real advice written with meaningful purpose). Apart from entertainment purposes, there is no other reason to go and read articles of type A. Abundance of type A articles inside the app will shoo away a dedicated user with paying intent.

Articles like type B are *useful articles.* Reading these articles inside the Pocket app will make users realize the need for premium features. (I would want to highlight ‘how to prepare for a PM interview’ and not ‘why having a Husky as a pet makes you related to Jon Snow’). After a threshold of reading many type B articles inside the app, a user would want to convert into a paying premium user. Essentially, these type B articles become the trigger for buying the premium. Hence, I am calling these articles ‘monetizable articles’.

---

# Opportunities to Improve

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610608455646_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1610608455646_image.png)

## Opportunity 1: Incentivize users to read the saved articles

Pocket has **no motivation framework**. There are no statistics to determine how much are you reading. If there are no options for a user to measure their growth, it is easy for users to conclude that Pocket is not helpful for them. Pocket also has **no reminder system**. Reading is something people want to do, however since they are not reminded to do it on daily basis, they forget it easily.

## Opportunity 2: Increase the total number of monetizable articles

The articles in Pocket discover tab are “handpicked” by editors. However it easy for editors to have inherent biases (domain, country etc). There is a recommendation feature inside the app that shows recommendations by an individual.

However, the recommendation system by individuals is mediocre at best. A person reads widely, from different topics. There is no feature in the app which allows user to recommended articles (in other words - share the articles) according to their topics. The recommendations from a particular user are visible only in the order of date recommended.

Users will likely **read articles suggested by others**. By creating a feature that **builds upon the existing recommendation system and allows users to see articles of a particular topic together**, would incentivize users to save more articles. This would become the [viral loop](https://andrewchen.co/whats-your-viral-loop-understanding-the-engine-of-adoption/) for the product. As these articles would be from a particular theme, it would become easy for users to realize the value of the product. For example - reading 4 articles from different topics would v/s reading 4 articles from a single topic. Logically, the second option will make you feel more comfortable about that topic. It needs to be noted that the intention is not to turn Pocket into an educational platform. Reading 4 articles from different topic provide a sense of leisure and excitement. Some users may be using Pocket for that purpose only. That product emotion will remain as it is. The feature would be something additional built upon the current system.

---

# Design Process

## Working on Opportunity 1 - Creating incentives for users to read 📚

> How might we incentivize users to read the saved articles, maximizing the utility the app provides to users?

I tried to leverage gamification to incentivize users to use the app and read regularly. [Gamification is design that places the most emphasis on human motivation in the process. In essence, it is Human-Focused Design (as opposed to “function-focused design”).](https://yukaichou.com/gamification-examples/octalysis-complete-gamification-framework/)

Humans don’t mind hardship they thrive on it. Sense of achievement after overcoming hardships is one of the biggest motivators for humans. I have kept these motivations in mind while designing.

## Progress Tab

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621076973412_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621076973412_image.png)

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621078586712_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621078586712_image.png)

I created a statistics tab for helping the user to track their progress. It will also help users see if they meet their daily and weekly targets or not.

Some pointers on this:

- From the beginning, it was clear to me that a progress tracker must have **visual elements (like graphs)**. Just text with numbers is difficult to scan and make sense of. Also, a **streak system** to constantly keep you motivated could be designed easily on top of visuals.

- Something that I had to think about was the data points to include. There were a variety of different data points that can be tracked like - the number of articles read, the number of highlights made, time read, etc. All these data points had some kind of utility so it was necessary to decide on a few while moving forward. I decided on - **time read**. Why?
    - Number of articles read or number of highlights made is not a good metric to track. Why?
        - The number of articles is pretty easy to grasp data. It is **not a large or complex number**. Usually, the number of articles would be <10/day. Also, it doesn’t seem to be something that we should purposefully track. When you read three articles, those articles are usually of different topics and have different content. Due to different content, you **already know that you read three articles** - of topic A, B, and C. Another reason is that there might be a user who likes to read long articles and be as dedicated as a user who read many short articles. So, we must show appreciation for both. (User implicitly knows)
    - Number of highlights too didn’t seem to be a good metric to track. Why?
        - It’s a **highly variable** and **not tangibly useful** metric. The number of highlights depends on the content. If the content is an explanation to a complex technical problem, you would highlight more in comparison to if you are reading a story-line based fiction article. Hence, not as useful as time read. (Highly variable metric even for each user.)
    - Pocket already has an article read time option. Hence from a data-gathering point of view, read time is not difficult to collate metric. (Useful and easy to implement.)

- Finalized on three sub-metrics in time read
    - **Daily Average Time:** It is defined as total time read divided by the total number of days read.
    - **Daily Streak:** Number of days read consecutively without a break.
    - **Read time today**
    - **Read time this week**

An exploration to view monthly and weekly metrics didn’t end up in the final version because it felt too much. The basis of this design was to motivate users to read. Intensive data tracking was not a feature I wanted to incorporate.

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621169461658_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621169461658_image.png)

## Working on Opportunity 2 - Building a system that increases total number *monetizable* articles📚

> How might we urge users to save and share more articles?

The solution I built was on top of network effects. Here are two articles that shaped my thinking while coming up with the solution:

- [Viral Effects Are Not Network Effects](http://Viral%20Effects%20Are%20Not%20Network%20Effects)
- [The Network Effects Manual: 13 Different Network Effects (and counting)](https://www.nfx.com/post/network-effects-manual/)

![https://www.nfx.com/wp-content/uploads/2021/01/ViralNFX-Chart.jpg](https://www.nfx.com/wp-content/uploads/2021/01/ViralNFX-Chart.jpg)

Viral Effects Network Effects Chart NFX

Network Effect is something that builds defensibility in a product. Defensibility leads to value. *“If a product has no relationship between increased usage and more useful data production, then there is no network effect; it’s merely a scale effect.”*

Users use Pocket to save articles they want to read later. Saving an article is easy but still a thoughtful exercise. Every user considers the saved article of some utility. Why cannot we scale this utility?

For example - I want to become a product manager, I go around on the internet to find useful articles and save those articles. They are helpful to me. What if a) I can club those articles together somehow (since they are of a similar utility to me) and b) Share the clubbed articles so that others using Pocket can view this ‘folder’ of articles? This will save them the time of going and searching for articles on ‘how to be a product manager?’.

Coming back to the initial idea - when we have increased usage and useful data production (people searching and saving articles) why shouldn’t we build features that take advantage of this and builds network effects around it?

## Pocket Folders

Therefore, an idea built on top of this - Pocket Folders. A feature that will help you club the saved articles, share them through a link, or publish them on a community so that all the other Pocket users can take benefit.

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621174911526_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621174911526_image.png)

List view with folders

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621188369537_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621188369537_image.png)

As I mentioned earlier discover tab, is more of a handpicked collection of articles. Therefore I propose that we change the discover tab to the community tab. It will host the articles and folders shared by the users.

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621180527702_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621180527702_image.png)

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621180503739_image.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621180503739_image.png)

I also created folder creation and sharing/publication flow.

![https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621447066271_Folder.png](https://paper-attachments.dropbox.com/s_8CCA3008A086E44D79A387071615F510D7B8152ABF5C0467FCECBD1C834CA2FC_1621447066271_Folder.png)

For full quality follow along [this pdf](https://drive.google.com/file/d/1EwpmzA6-13WIht5RMHIaLdo-BWT9Yoxu/view?usp=sharing) or view it on Figma -



---

# Reflection and Takeaways 🌱

Thanks for sticking around for so long. This one of my first projects where I deep-dived into product and UX flows.

Building on top of an existing product confronts you with some challenges. The constraints from the existing product are something that needs to be catered to. The addition of new features is not just about how the new feature will benefit the product, but also how the new features gels with the existing product.

For example, take into consideration the recommendation system we have currently. Publishing and recommending have different emotions involved. Also, both are important because - article is something you would *recommend* since you have no contribution to it. A folder is however something you created by yourself and would like to *publish* it. Should the recommended articles be shown on the community screen? These are some critical questions that arise when a new feature is built into a product.

Some future explorations in this project would include

- **Folder updates:** How would you update a published folder? And the edge cases revolving around it. (You create a folder with some intention A → It reaches trending page → You update the folder and now folder has intention B. Would that be misleading?).
- **Collaborative folders:** different users coming together and creating and maintaining a folder.

Again, thank you for exploring my work, and I encourage you to leave any feedback or critique using comments or mailing it on `abhinavpandey027@gmail.com` 

*Cheers!*

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}


[EMail](abhinavpandey027@gmail.com) ✦ [LinkedIn](https://www.linkedin.com/in/abhinav-pandey-nit/) ✦ [Twitter](https://twitter.com/ab27hi) 
