# AI Prompt Repository

## Description

Welcome to the AI Prompt Repository, a curated collection of prompts designed to unlock the full potential of language models. Whether you're working with OpenAI's GPT models or exploring the capabilities of Midjourney, you'll find a variety of prompts to suit your needs. This project aims to provide a valuable resource for the AI community, focusing primarily on Natural Language Processing and other language model applications.

## Table of Contents

- [Introduction](#introduction)
- [How to Use](#how-to-use)
- [Categories](#categories)
- [Sample Prompts](#sample-prompts)
- [Contribution Guidelines](#contribution-guidelines)
- [Credits and Attribution](#credits-and-attribution)
- [License](#license)

## Introduction

The AI Prompt Hub was created by me Ecce, to just keep a collection of prompts that I have curated or created over a span of time, that I feel are very useful.

## How to Use

1. **Browse Categories**: Navigate through the categories to find a prompt that suits your needs.
2. **Copy Prompt**: Copy the prompt you would like to use.
3. **Execute**: Use the copied prompt with your language model of choice.

## Categories

- [Resumes](#resumes)
- [MidJourney](#midjourney)
- [Educational](#educational)
- [Coding](#coding)
- [Email](#email)
- [More to come...]

## Sample Prompts

- **Data Science**: "Analyze the given dataset and provide insights."
- **Natural Language Processing**: "Summarize the following text into three sentences."
- **Conversational Agents**: "Hold a conversation as if you were a personal assistant."


## Resumes

```text
Assume the persona of a career consultant specializing in placing candidates in top-tier organizations. Utilize insights gleaned from their professional history to offer strategic guidance on the actions they should undertake to secure their desired position
```
```text
Intent on securing a role as [insert job] at [company name], I present the following excerpt from the job listing:

[insert job posting]

First, distill the essential qualifications and experiences enumerated in this posting, prioritizing them based on your consultancy expertise. Subsequently, invite the client to share their relevant professional background for tailored guidance moving forward.
```

```text
Analyze the client's provided work experiences, which are as follows:


[INSERT WORK EXPERIENCE HERE]

Isolate the key elements that align closely with the job requirements. Furnish the client with a synthesized list of these pertinent experiences. Concurrently, compile a separate list detailing the experiential gaps the client has in relation to the job posting.
```

After this, you can ask for things like:

1. "What are the must-have skills for a software engineer's resume?"
2. "How should I format my CV for a UX Designer role?"
3. "Generate a compelling opening paragraph for a cover letter aiming for a Business Analyst position."
4. "What are common interview questions for a DevOps Engineer?"
5. "List certifications that would make my profile stand out for a Cybersecurity Specialist role."
6. "What action verbs should I include in my resume for a Product Manager position?"
7. "Suggest a career progression path for someone starting as a Junior Data Scientist."
8. "How can I tailor my LinkedIn profile for a career in Artificial Intelligence?"
9. "Recommend networking strategies for breaking into the FinTech industry."
10. "Provide tips for negotiating a higher salary for a Senior Developer role."
11. "What are key performance indicators that HR Managers look for during performance reviews?"
12. "List the types of projects that I should include in my portfolio for a Front-End Developer role."
13. "Generate a closing paragraph for a thank-you email after an interview for a Marketing Manager position."
14. "What are soft skills that are often overlooked but crucial for a Team Leader?"
15. "Suggest courses or workshops to improve my skill set for a Machine Learning Engineer position."



## MidJourney

First start with this prompt:

```text
I'm going to train this chat to create detailed image prompts for an AI art generator called
MidJourney. Before we begin, I need to give you context about MidJourney. I'm first going
to explain what MidJourney is, then we'll break down the prompts.
Midjourney is an artificial intelligence program and service created and hosted by a San
Francisco-based independent research lab Midjourney, Inc. Midjourney generates images
from natural language descriptions, called "prompts", similar to OpenAI's DALL-E and
Stable Diffusion.
Midjourney is currently only accessible through a Discord bot on their official Discord
server, by direct messaging the bot, or by inviting the bot to a third party server. To
generate images, users use the /imagine command and type in a prompt; the bot then
returns a set of four images.
Midjourney is one of the most popular text-to-image AI services online. Users can use a
chat application, Discord, to communicate with the bot to create images. It uses simple
commands and requires no coding experience to create aesthetically pleasing images. Its
founder, David Holz, described Midjourney: “We just want it to be easy to use and we want
the pictures to look good.”
According to the company’s website, Midjourney is: “An independent research lab.
Exploring new mediums of thought. Expanding the imaginative powers of the human
species.” Similar to other AI models, it uses a vast amount of images to train on with the
power of machine learning. When provided with text input, its bots find pictures matching
the description and combine them artistically to create a unique image.
I need to give you info about the latest v5 Update.
What's new with the V5 base model?
- Much wider stylistic range and more responsive to prompting
- Much higher image quality (2x resolution increase) improved dynamic range
- More detailed images. Details more likely to be correct. Less unwanted text.
- Improved performance with image prompting
- Supports --tile argument for seamless tiling (experimental)
- Supports --ar aspect ratios greater than 2:1 (experimental)
- Supports --iw for weighing image prompts versus text prompts
Style and prompting for V5
- It’s MUCH more ‘unopinionated’ than v3 and v4, and is tuned to provide a wide diversity
of outputs and to be very responsive to your inputs.
- The tradeoff here is that it may be harder to use. Short prompts may not work as well.
You should try to write longer, more explicit text about what you want (ie: “cinematic photo
with dramatic lighting”)
- This model can generate much more realistic imagery than anything we've released
before.
V5 is our second model trained on our AI supercluster and has been in the works for 5
months. It uses significantly different neural architectures and new aesthetic techniques.
V5 isn't the final step, but we hope you all feel the progression of something deep and
unfathomable in the power of our collective human imagination.
Store this to reference to better understand what MidJourney is. Next I will explain the
prompt structure. Ready?
```

Continue with this: 

```text
Here is an example MidJourney prompt:
high texture quality photo of biomechanical astronaut lying in a meadow of Blue Anemone flowers,
golden hour, Leica 50mm, f1. 4, night, in the style of photorealistic surrealism, dark pink, alan bean, nicolas bruno, flowerpunk,
stockphoto, solarizing master --ar 16:9"
The link at the start is an image reference used to help guide composition, colors, design, etc. based on an image similar to what
we want to create.
Next is a more plainword description of exactly what we want to see.
Next, we have a bunch of super specific descriptive bits, including specific cameras, location, camera angle, time of day, lenses,
lighting, styles, artistic influences, color schemes, aesthetic themes, use cases for the image, and so on.
Lastly the "--ar 16:9" is a parameter for aspect ratios. I won't always want a 16:9 image, but the format will be the same. So a
portrait photo would be in "--ar 2:3" or "--ar 3:2" for example.
Style, aesthetic, descriptive terms can all be pulled from anything you're already aware of or that I give you as examples, as long
as they relate to the image I tell you we're trying to make and help build that image based on what we're describing.
Examples for descriptive details include (but are not limited to):
● Wide angle photo
● close up photo
● macro photograph
● golden hour
● night time
● neon lights
● cinematic lighting
● epic scene
● center frame
● plain color background
● die cut sticker
● cute

Examples of other aesthetic themes we might want to include are (but not limited to):
cyberpunk, glitchpunk, cybercore, hikecore, forestcore, warmcore, forestpunk, stockphoto, for anime, for magazine cover, for
album art, photorealistic, ray tracing, unreal engine 5, octane render, pixar style, uhd image, 4k, 8k, 16k, 32k, highly detailed
When I ask for a prompt, I will provide some example prompts to use as primers to help give you an idea of what relevant
terms to come up with, but you should not be copying the prompts verbatim. The goal is to deliver prompts more
detailed/achieving better results than my primer examples. Understood?
```

Then take this prompt: 

```text
Okay, for our first prompt, I want to create an image of an astronaut with its back facing
the "camera" (aka our view) as they look upon the fabric of space and time tearing in front
of them.
I have a reference image I will be using here, which shows the back view of an astronaut,
with a bright glowing colorful space visual flowing out from around him. He is facing bright
glowing light, obscuring its view from us.
Here is a sample prompt:
"An illustration of an astronaut's full body, floating in the vastness of the universe, full of
stars, makoto shinkai, trending on artsation, detailed depiction of nature, psychedelic
palette, light amber and turquoise"
Here are four more sample prompts:
"the image depicts an astronaut standing in space, in the style of intricate underwater
worlds, hard edge painter, imax, calming effect, i can't believe how beautiful this is,
adventure themed, solarizing master --ar 51:91"
"an astronaut in space walking across a planet with open space, in the style of intricate
underwater worlds, cyril rolando, uhd image, guillem h. pongiluppi, thiago valdi, realistic
attention to detail, high-angle --ar 51:91"
"space wallpaper hd art sci, digital art, wall decal, abstract art, in the style of quiet
contemplation, 32k uhd, detailed character illustrations, atmosphere landscapes --ar
51:91"
"an astronaut looks over an earth, in the style of cyril rolando, dark themes,
32k uhd, intricate underwater worlds, jakub schikaneder, thiago valdi, detailed
background elements --ar 51:91"
I want this to be in the aspect ratio of 13:19 to print as a beautiful high-quality
poster on my Canon Pixma IP8720.
Please generate me a specific, detailed prompt for Midjourney to achieve
my desired image
```

Finish with this prompt:

```
Please make a table breaking down the composition of our intended image into
categories.
Example categories are:
● Composition
● Camera angle
● style
● subject/focal point
● what subject is doing
● What subject is wearing/looks like (where relevant)
● Textures
● Detail
● Color Palette
● Mood
● Time of Day/Lighting
● Location
● Addition styles/weird aesthetics
Make this table have 10 rows. Each of the above categories should be individual columns.
First generate this table as a generic table with no specifics and store it for reference for
later. Store as "Prompt category labels table" whenever I ask for that.
```

Now you can give prompts like 
```
Now, ACT as a [profession] and use rich,
descriptive language to build an awesome MidJourney prompt based on what you have
learned so far and on this [selected row], with [aspect ratio]
```



## Educational

### Coming soon

## Coding

### Coming soon
- "Explain the difference between a class and an object in Python."
- "Provide a JavaScript code snippet for a function that reverses a string."
- "List common use-cases for using Git in software development."

## Email

### Coming soon
- "Draft an email to a client apologizing for a delayed project."
- "Compose a follow-up email after a job interview."
- "Write an email announcing a new product release to existing customers."



## Credits and Attribution

This repository is managed by Ecce Jönsson, and contributions from the community are highly appreciated. Special thanks to all contributors and supporters.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
