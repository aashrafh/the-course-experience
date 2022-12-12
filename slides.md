---
# try also 'default' to start simple
theme: geist
# apply any windi css classes to the current slide
class: "text-center"
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
drawings:
  persist: false
# use UnoCSS
css: unocss
layout: center
---

# The Course Experience

By Ahmed Ashraf

<div class="m-6 flex flex-col justify-center items-center gap-2">
  <span>
    <span>
      Frontend Engineer
    </span> 
    <a href="https://blink22.com/" target="_blank">@Blink22</a>
  </span>
  <a href="mailto:ahmed@aashrafh.me" target="_blank">ahmed@aashrafh.me</a>
  <div>
  <a href="https://www.linkedin.com/in/aashrafh/" target="_blank" alt="LinkedIn"
    class="text-xl icon-btn opacity-50 !border-none">
    <carbon-logo-linkedin />
  </a>
  <a href="https://github.com/aashrafh" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none">
    <carbon-logo-github />
  </a>
  <a href="https://twitter.com/aashrafh" target="_blank" alt="Twitter"
    class="text-xl icon-btn opacity-50 !border-none">
    <carbon-logo-twitter />
  </a>
  </div>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# What is The Course Experience?

This is a brief summary of my experience authoring the [Building Full-Stack Web Applications With Node.js and React](https://www.educative.io/courses/building-full-stack-web-applications-with-node-js-and-react) course at [Educative.io](https://www.educative.io/)

- 📝 **Educative Author** - applied at Educative.io as an author without a specific idea in mind
- 👩 **Author Acquisition** - got contacted by a representative to align their needs and my skills
- 👨‍💻 **Work Inspiration** - an ML project and one of its core functionalities depends on uploading a file
- 📁 **Upload File** - a good example of full-stack apps that can be considered as a helicopter view

<br>
<br>

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}

</style>

<!--
- I applied to Eucative author with nothing in mind, I just applied because I love to share what I know with others and, honestly, I didn't expect to get accepted especially that I had no experience in content creation before

- Got contacted by them and knew that they need more Nodejs content based on my skills but, of course, you may introduce other types of content

- I was working on a ML project that one of its core functionalities depends on uploading a file

- Decided that this is a good example to build upon something that introduces beginners to fullstack development

- Educative is a text-based, interactive courses for software developers, so, why text-based?
  -->

---

# Why a Text-Based Online Course?

A learner usually needs a combination of hands-on practice, multiple real-world examples, mixed media experience, and control over pace and content.

- ⏱️ Little to no control over the content and the pace of content consuming

- 📺 Watching a video requires less cognitive function, i.e. passive learning

- 📝 Highlight important ideas is difficult to handle

- 🔍 Skimming through a video to find answers to questions

<!--
- There is a notable difference between these approaches, and studies show that they trigger different parts of the brain.

- So, if the content does not differ between a video or a text-based course, how do we know what is best for learning software development online?

- A learner usually needs a combination of hand-on practice, multiple real-world examples, mixed media experience, and control over pace and content.

- Personally, I prefer text-based content over video-based one because video-based imposes many challenges on learners

- Video-based courses can be an excellent supplement to other forms of e-learning, but in my experience, they only impart surface-level knowledge on their own.

- Overall, you get more real-world practice, specialized control over how you learn, and a personalized your learning experience without scrubbing or rewinding.

- I was fascinated by the quality, comprehensive analysis, and convenience of Educative’s online courses.

-->

---

# Are We Done? 🤔

An appealing idea, an approved roadmap, and a signed contract doesn’t mean it will translate into a great content because crafting the content and making it digestible is a demanding task with a challenging learning curve for first-timers

<div class="w-full flex justify-center">
  <img
    class="absolute -bottom-9 -left-7 w-80 opacity-50"
    src="/assets/images/puzzle.png"
  />
</div>

<!--
- For example, I struggled with the visual design components of the course, especially when modeling sketches for my lessons in order to ensure compliance with Educative’s high standards.

- It's important to have some kind of feedback from trusted people especially at the beginning of your technical writing journey to review to make sure you are on the right track. In my case, the Educative team empowered me to achieve superior performance and gave me all the support required to override any issues that surfaced.
 -->

---

# Where Do Ideas Come From?

<div class="w-full flex">
  <div class="w-1/2">

• Find a problem that bothers you. As an engineer, our day-to-day life should be full of questions

• If you got stuck, there is a high chance that you don’t master this topic yet

• You don't have to be the first one. The truth is that all ideas are really mashups of existing ideas [🔗](https://dev.to/andyhaskell/perfectionism-as-a-content-creator-and-what-i-do-about-it-3ika)

• Be careful about the illusion of knowledge, i.e. Dunning-Kruger Effect

<p v-click="2">🎯 Stay open to inspiration; Software engineers do this by tinkering with new frameworks and languages. Product managers might try new organization tools. Designers might have conversations with artists for inspiration.</p>

  </div>
  <div class="w-1/2">
    <img
      v-click="1"
      class=""
      src="/assets/images/dunning.webp"
    />
  </div>
</div>

<!--

- The reason to find a problem close to you is that you know what is the core of this problem that you and other people like you want to get solved.

- You will show full empathy for your audience.

- Telling people how things work either in speaking or writing is a great way to improve your knowledge on certain topics.

- Dunning-Kruger Effect: A little bit of knowledge is a dangerous thing. When you are learning a completely new thing, you will get excited and have a lot of questions. Don’t rush into writing because you are likely standing at the “Peak of MT Stupid”. When you are there, your output tends to be superficial. In my opinion, the ideal position for writing is “Valley of Despair” or “Slope of Enlightenment” because it helps you reach the “Plateau of Sustainability”.

-->

---

# Be Clear About Your Target Group

<div class="w-full flex">
  <div class="w-1/2">
  • Have a clear and succinct headline so learners will have some sort of expectations

• Answer your learners questions before the end of of the article, vidoe, or chapter

• Be comprehensive for all experience levels, i.e. fulfill the learner need with as clear and detailed information as possible without making assumptions about the reader’s background knowledge

• Make a good story, don't make it too technical; What is the problem? Why is it a problem for us? How can we solve it? Could you give some examples to support your statement? What is the advice for learners?

  </div>
  
  <div class="w-1/2 flex flex-col items-end">
    <div class="flex flex-row-reverse">
      <ol class="toc-list" role="list" v-click>
        <li>
          <a href="#">
              <span class="title">1. What's is MERN?</span>
          </a>
          <ol>
            <li>
              <a href="#">
                  <span class="title">MongoDB</span>
              </a>
            </li>
            <li>
              <a href="#">
                  <span class="title">Express</span>
              </a>
            </li>
            <li>
              <a href="#">
                  <span class="title">React</span>
              </a>
            </li>
            <li>
              <a href="#">
                  <span class="title">Nodejs</span>
              </a>
            </li>
          </ol>
        </li>
        <li>
          <a href="#">
              <span class="title">2. What's Heroku?</span>
          </a>
        </li>
        <li>
          <a href="#">
              <span class="title">3. Why deploy MERN app to Heroku?</span>
          </a>
        </li>
        <li>
          <a href="#">
              <span class="title">4. How to deply a MERN app to Heroku?</span>
          </a>
          <ol>
            <li>
              <a href="#">
                <span>How do you prepare a MERN app for Heroku?</span>
            </a>
            </li>
          </ol>
        </li>
      </ol>
    </div>
    <p v-click>🎯 Good technical content is correct and uses industry-standard terms without overwhelming new learners</p>
  </div>
</div>

<style>
  .toc-list, .toc-list ol {
    list-style-type: none;
  }
  .toc-list {
    padding: 0;
  }

  .toc-list ol {
    padding-inline-start: 2ch;
  }

</style>

<!--

- Different people surfing your technical content
  - through brwosing social media and get attracted by the headline. They open the page, read the introduction and quickly scroll the page to see if anything is interesting.

- When they have expectations, they fall into the second group.

- Another type of learners is the people who intention. They may googled about your course topic.

- These details give readers the information they need to grow their skills.

- You don't expect the user knowledge so you will be surprised by simple questionst they ask.

- While the focus of the article is on deploying a MERN application to Heroku, I’d probably devote 2-3 paragraphs explaining the basic terminology.

- Then, I’d link readers to more comprehensive resources (like the documentation) to let them explore these topics in more detail.

- This might seem like overkill, but an experienced reader will simply use the headers to skip down to the portion of the technical content they need.
-->

---

<div class="bg-dots h-full w-full" v-click="2"></div>

<div class="flex w-full gap-4 relative">
  <div class="w-1/2">

  <h1>Consistency</h1>
  
• The key to getting better at anything is to do it consistently, even if you’re not very good at first

• Your work on the course will be a side work so you need to Block Time for it

• If you're not consistent, it’s way too easy to fall into the trap of endlessly checking email, or scrolling through your Facebook feed

  </div>
  <div class="w-1/2" v-click="1">
    <h1>Organization</h1>

• You want to give new learners the ability to build up to difficult topics while giving experienced learners the ability to skip to the parts they care about

• Start everything with coding and outlining. Starting from an outline speeds up the writing process dramatically

• Having any organization method like Chronological, Importance, Problem and Solution, or Roundups will make your content better than most

  </div>
</div>

<style>
  .bg-dots{
    background-image: url("/assets/images/dots.jpg");
    background-color: #fff;
    background-size: cover;
    position: fixed;
    top: 0; right: 0; bottom: 0;
  }
</style>

<!--

- I was blocking my entire Friday and Saturday off for it. Don’t let it overwhelm you. The most important part is to start.


- Organization is a key important part in the course ceation process. You’re trying to deliver a topic to a diverse audience so  The only way to serve such diverse learners is to invest time in organizing.

- The outlining phase is where you prioritize ideas, identify weaknesses in your knowledge, and crystalize your main points.

- With a well-thought-out outline, writing becomes the mere act of connecting the dots. Without one, it’s an unintelligible mess.

- You should create the demo application and outline the steps before you start writing the rest of the content.

- If you do it this way, you’ll find the writing part is very quick.

- Methods: Chronological, Importance, Problem and Solution, and Roundups.

- Personally, I prefer the problem and solution method and fallback to Importance if it didn't work but, just having any system will make your content better than most.

-->

---

<div class="flex w-full gap-4 relative">
  <div class="w-1/2">

  <h1>Prove Your Point</h1>
  
• **Research**: a lot of people don’t verify the research they use very carefully which leads to a lot of technical content backed up by dubious claims taken out of context

• **Examples**: it is always good to show people what you are saying is something tangible, not rocket science. You can use your personal experience or illustrations.

  </div>
  <div class="w-1/2" v-click="1">
    <h1>Illustrations</h1>

• A graph doesn’t only say thousands of words but also creates a mental model for the learner.

• Abstract information can more easily be conveyed through visuals, whether a diagram, infographics, screen capture, GIF, etc.

• Visuals can present abstract information more concrete, portraying a process that would otherwise take many words to communicate.

  </div>
</div>

<!--

- "Good technical writing articles must be correct, so I pretend that my readers are all ornery skeptics hoping to poke holes in every statement I make."

- Research - Academic research typically has the highest bar, but business surveys or secondary research are sufficient for most informal technical content.

- Examples - People really like stories. While this can get naive readers into trouble, it’s helpful ammunition for writers. Personal experience or relevant anecdotes also help strengthen your claims. ==> React example.

- It helps to instruct your users visually instead of explaining an idea using just words, which may be inadequate or ambiguous.

-->

---

<img src="/assets/images/directory.png"/>

<div class="flex gap-4 justify-center pt-6" v-click>

• [Canva](https://www.canva.com/)

• [Draw.io](https://app.diagrams.net/)

</div>

---

<div class="w-full flex gap-4">
  <div class="w-1/2">

  <h1>Provide Code Snippets</h1>

• **Break them down into digestible chunks**. Don’t provide 80 lines of code and then tell your reader to copy and paste it

• **Format your code correctly**. Code that isn’t formatted correctly is difficult to read and, therefore, difficult to understand

• **Don’t forget about file structure**. This usually only applies to large projects, especially when working with React.

  </div>
  <div class="w-1/2" v-click>

```js
// backend/controllers/file.js

// ...rest of the code

exports.deleteFile = async (req, res) => {
  try {
    const { _id } = req.params;
    const file = await File.findOne({
      _id,
    });

    if (!file) {
      return res.status(404).send("The requested file does not exist");
    }

    await File.remove({
      _id,
    });

    res.status(200).json({ message: "File deleted successfully" });
  } catch (err) {
    console.log(err);
    return res.status(500).send(err.message);
  }
};
```

</div>
</div>

<!--

- It’s always helpful to provide unique code, dependencies, and configuration files that are required. You can provide a link to your completed project on GitHub if you want, but you’ll need to be selective about what code you include in the content itself.

- A few things to keep in mind as you include code samples:

- Better to choose smaller sections of code that are more digestible, making sure to explain what each line does.

- Find a style guide for the language you’re working in and make sure your code sticks to the standards agreed upon by the community.

- In these frameworks, the location of your files can affect how and if it runs. It’s sometimes helpful to provide the file name and path at the top of the code snippet in the form of a comment.

-->

---
