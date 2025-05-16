---
layout: essay
type: essay
title: "The Use of AI in ICS 314"
# All dates must be YYYY-MM-DD format!
date: 2025-05-06
published: true
labels:
  - AI
  - ChatGPT
---

<img width="250px" src="../img/chatgpt.png">

Image Source: [hatchwise]([https://pixabay.com/illustrations/question-question-mark-response-1015308/](https://www.hatchwise.com/resources/the-complete-history-of-the-chatgpt-logo))

## Introduction
---
The role of AI in education is a tool that students can utilize for learning assistance. It's almost like a 24 hour remote tutor. Although we shouldn’t heavily rely and fully believe what AI tells us (nothing is perfect), the functionality of it being interactive and personalized tailored to each unique individual is useful. Students have different ways of learning at different speeds, so using AI will be useful as it helps students with personalized study methods and advice.

In relevance to Software Engineering, students can ask AI for help when they need help understanding the functionality of a section of code, help explain a concept, help explain errors and bugs, and help scan a section of code for syntax errors students may have not noticed.

In ICS 314, I use ChatGPT to help me figure out why I’m getting errors and bugs in my code. Not only does it suggest possible solutions, it also provides optional tips to consider to prevent future bugs. Sometimes when my thoughts get jumbled up, using ChatGPT helps me organize and structure my ideas more clearly. In general, I use ChatGPT to help me understand difficult concepts in my other classes. I take advantage of its interactive feature by asking a lot of “why” and “how” questions to understand why things work the way they do. ChatGPT does a good job at summarizing large chunks of text so, I prefer to read a simplified version first to get a basic understanding of something, then go back to read the original version of the text to get a more in depth understanding.
<br><br>

## Personal Experience with AI
---
### Experience WODs
When I was doing the experience WODs I mainly used AI such as ChatGPT for syntax errors because I would usually already have a plan in my head on what to do but to type the actual code, the syntax of it slows me down. Once I get a bit familiar with it, I would try to avoid using ChatGPT to practice and remember the syntax. For example, E18: Experience Functional Programming 1, was when we first learned how to implement different function calls, I had a basic understanding of what the function calls do, but I needed some help trying to piece everything together. 

### In-class Practice WODs & In-class WODs
The same goes for In-class Practice WODS and In-class WODs. For In-class Practice WODs, I had to be at the same pace with my groupmates and since we couldn’t look at each other's screens, it made it a bit more difficult to discuss the syntax. This was mostly when we were using typescript playground. For In-class WODs, when we started using Visual Studio Code, I had a difficult time with resolving ESLint and Prettier errors because I had no idea what the errors were talking about which occasionally had me exceed the DNF time limit. Even with the help of ChatGPT then, I was still a bit confused. For example, it was one of the In-class Murphys using Next.js, there was something wrong with one of the files that was downloaded from the npx install. Another example was battling against the double and single quote errors.


### Essays
When I write essays, I usually end up writing overly long sentences which may most likely confuse the reader just as it confuses myself. Luckily with the help of AI, ChatGPT could understand me when I just list all of my thoughts down. It then organizes my thoughts into sentences or a paragraph, and after I read it, I try again to write all of my thoughts into my essay in my own words. Since I could understand what I was trying to say, it was easier to write more clearly. One example is my essay on reflecting on coding standards. I had an idea what ESLint was but I wasn’t sure how to make my words clearly related to the topic.

### Final project
ChatGPT was really helpful when we were working on our final project because, instead of watching tutorial videos like the Digits experiences, we were left on our own to use the skills we gained from those videos and apply them to our own project. Since Vercel requires a payment plan if we try to deploy our project using github organizations, I decided to use the hobby plan to deploy our project using my personal github account. Some bugs and errors weren’t detected in Visual Studio Code and Github, but were detected when our project was being built in Vercel leading it to not compile. Because of these issues, it made trying to understand our code a bit difficult. ChatGPT was useful when it came to explaining and solving those errors because since deploying Vercel in on my personal account and computer, I couldn’t really ask my teammates for help. For example, when I was trying to upload one of my teammate’s branches, there was a possible null session for a user if they tried to log in but it didn’t seem to be an issue on my teammate’s end.

### Learning a concept / tutorial
Since we learn a lot of new concepts and tutorials in this course, reading and trying to do them for the first time on our own was confusing. For example installing pgAdmin, PostgreSQL, Prisma, and Next.js were all new things to me and the readings were long and wordy. ChatGPT did a good job at breaking things down and explaining the concepts to me.

### Answering a question in class or in Discord
I haven't really answered a question in class or in Discord because I either also don’t understand or someone answers before me. I do take notes and save those questions for later to ask ChatGPT to help explain the answer to me. But if I was able to ask a question, I would ask ChatGPT how I would make my point clear so that the person who asked the question would understand and hope to get the answer that they were looking for.

### Asking or answering a smart-question
I noticed that if I ask ChatGPT a smart question, most of the time I get a better answer from it. During the final project, when I get errors deploying on Vercel, I would try to find solutions on my own first then tell ChatGPT what I have done, what I got out of those attempts, and ask if there is anything else I could do. For example, when I was trying to migrate something from the prisma schema, it was hooking up to a different server rather than the supabase one and wouldn’t go through. It provided me with a list of a few things I already did like making sure I got the correct connection string, and a few new things I never tried. After a few trial and errors I was able to get it to work.

### Coding example
While we were practicing functional programming in typescript playground, instead of asking ChatGPT to write a piece of  code for me while doing a WOD assignment, I asked it to provide an example of using and array function like reduce() and slice() so I can write my own version of my code. Even though we were given a few resources on how to use these array functions, I found ChatGPT to be helpful for being more clear and could ask any questions I have directly.

### Explaining, writting, and documenting code
When it came to fixing the bugs and errors in my teammate’s code for the final project, I was confused on how they were able to write the logic part of their code without coming across the errors that I was getting from my end. I wasn’t sure what their code meant so when I was asking ChatGPT to explain the errors I was getting, it would always first explain what the code is trying to do and the reason why it gave that error. After that it would write or revise the code so that it solves the problem. As it writes the code, it also helps document the code by writing comments on the side of what changed and only sometimes write comments of what the code does. Instead it would usually explain the code after it is done writing it. The null session error that I had before, was because of a certain way my teammate wrote the code. Following the code that ChatGPT wrote where I had to create a new file and define the session there, everything worked and the error was gone. After I understood what the code does, I would document the code and add comments in myself.

### Quality assurance
Most of my interactions with ChatGPT were copying and pasting my error messages and my code. For this example, I was confused about how to resolve an ESLint error. I ask ChatGPT “Where do I put the parentheses in this ESLint error? Here is my code:”:
```
Missing parentheses around multilines JSXeslintreact/jsx-wrap-multilines (property) JSX.IntrinsicElements.td: DetailedHTMLProps<TdHTMLAttributes<HTMLTableDataCellElement>, HTMLTableDataCellElement>

const EventItem = ({ id, name, description, location, month, day, year, host, isOwner}:EventItemProps) => (
  <tr>
    <td>{day}</td>
    <td>{name}</td>
    <td>{description}</td>
    <td>{location}</td>
    <td>{host}</td>
    {isOwner && <td>
      <Link href={/editevent/${id}}>Edit</Link>
      </td>}
  </tr>
);
```
At first, I tried to add the parentheses myself, put the tags on a new line, and adjust the indents but VSCode just kept complaining about every single thing that I did. So I thought it would just be easier to copy and paste in the correct formatting and this is what ChatGPT gave with no additional problems:
``` 
{isOwner && (
  <td>
    <Link href={`/editevent/${id}`}>Edit</Link>
  </td>
)}
```
### Other uses in ICS 314
There were many extra credit opportunities in ICS 314 as it was a way for us to bring up our grade by more learning and practice concepts we have learned. When we were learning how to use React, we made a basic tic-tac-toe board by following a tutorial. For extra credit, there was a list of challenges we can work through to add more features to our tic-tac-toe board. We were given a few hints on how to do them but it was still a bit difficult since we have no guide. ChatGPT was really helpful in explaining what needed to be used and why it works. Instead of being left more confused while attempting these challenges, the use of AI was helpful with expanding my capabilities. 
<br><br>

## Impact on Learning and Understanding
---
The incorporation of AI influenced my learning experience to be more enjoyable. If I did not understand how to do anything, I become unmotivated because trying to do something that you don’t know how to do leads to no progress which feels pointless. If I did know how to do something, attempting to do something becomes more interesting, making me want to learn more. Using ChatGPT has enhanced but also challenged my understanding of software engineering concepts. The way you can make AI explain and teach you concepts in a certain way impacts my learning comprehension in a positive way. It is really good at explaining and creating examples personalized to you. Your skills develop as you engage in a conversation with AI since you could interact by asking questions, implementing your code, and coming back to it for more questions to ask. Problem-solving abilities not so much since it just tells and explains to you what you should change in your code as a solution to fixing an error. But it does make you recognize the same error if you get it again and then now you would know how to resolve it. If anything, given the clues the error message gives you, you could ask ChatGPT for another hint for you to look at to try to fix the problem yourself. 

ChatGPT also makes searching for answers more convenient because its interaction and memorization feature make it easier to ask your questions to it rather than writing a whole paragraph or a piece of code into a Google search bar. Sometimes what it says could be wrong so Google is still useful to search up the answers that ChatGPT gives to make sure it is the same as the many reliable sources say.
<br><br>

## Practical Applications
---
A practical application in the real-world is Microsoft incorporating Github Copilot into Visual Studio Code. Many developers use this tool to help them code more productively. Github Copilot adapts to your development workflow and suggests code snippets based on your existing code while you type. It is also customizable so it can suggest code following your coding practices. I have not used this tool myself since I want to get more practice making up code on my own first. I have seen my classmates and a few professors use this tool and another feature that I saw that seems really convenient is that Github Copilot would highlight error messages in red on the same line where that error occurs in their code making it more easy to spot and read. The use of AI while coding makes the convenience of coding effective. As files of your project gets bigger, AI can assist developers by keeping track of their code.
<br><br>

## Challenges and Opportunities
---
One of the challenges that I experience of using AI in ICS 314 is that ChatGPT sometimes would repeat the same solutions it tells me to try out even though I already tried them and it did not work. Another challenge is that while asking ChatGPT for help solving for an error, it then breaks down to smaller errors going “off topic” then forgetting that we were trying to solve the first problem. I would have to lead the conversation back to that point if that subproblem was fixed but not others. During the final project, there were some limitations on trying to share my whole Vercel error message and multiple pieces of code because of the limited amount of characters available in the chat box. Not only that but you can’t really share your whole project with it so it can look through your files for the main cause of an error. Though I understand that this is my own team’s project to work on, it's a bit difficult when everyone is working on one thing, we encounter errors we have never seen before, they don’t have the same type of errors that I would get looking at their branches from my computer. 


Instead of asking AI to do things for us, students could additionally ask AI smarter prompts to make the use of AI in learning software engineering more effective. I noticed that just asking AI things like “can you explain what this error means and how to fix it?” or “can you explain this concept?” would simply just do as you ask where it gives an answer but sometimes not a full understanding. This could lead to confusion and in the meantime students often forget what they have been told. But if students learn how to ask AI better prompts, they could get more information and knowledge out of it. Some possible prompts may be “can you explain what this error means, what is the best way to fix it, and can you share some tips on how I could understand what the error messages are telling me?”, “can you help fix this ESLint error and give tips on how I could improve my formatting and documentation?”, and “can you explain this concept to me in a way that I could remember it? Could you make a practice exam based on this concept? and can you show how I could derive my answers and to other concepts based on what I know in an exam setting? (no open books).”
<br><br>

## Comparative Analysis
---
Traditional teaching methods in software engineering education such as lectures, articles, following tutorials, and coding assignments provide a well structured way to learn the important concepts. Everything is set up for students to follow along and practice the concepts they learned in their assignments and projects. In class, students can practice coding concepts with each other and ask professors for feedback. Professors and TAs are available in their office hours to provide extra help for students if they need help. This opportunity lets students engage with each other, hands on experience and practice helps with knowledge retention, and group work and team projects allow practical skill development. 

AI-enhanced approaches in software engineering education such as generating explanations and code, scanning text and code, and giving instant answers is a good tool for providing assistance. Even though AI may do a decent job at teaching, students rely on it to do things for them, not getting the practical skill development they need. AI has some limitations so it's important to give it good prompts to receive good feedback. The interactive chat feature enhances learning engagement and works well when students are working independently. But AI might not always be right, their explanations may sound right but not provide all the details often leading students confused and miss important details. AI also does not have any connections with the real world so students hardly get any real world experience.
<br><br>

## Future Considerations
---
AI alone in software engineering education should not be used since it may not provide all the information and skills students need. If AI is going to be used in education, it should be paired with traditional teaching methods along with teaching students how to use AI effectively. AI should be seen as a tool to provide assistance as students work on their assignments and projects to improve their skills themselves. Potential challenges is that students may rely on inaccurate information from AI and have it generate code for them because they may think knowing the concept and structure of it is good enough. They may understand the code when they see it but are not able to write code on their own. If education is going to be through AI, students would need to find out what to prompt it and as well as notice the connections between different concepts themselves since AI only does a decent job at linking everything together which calls for improvement. Potential advancements are possible but nothing would be better than an human expert with real world experience structuring a whole lesson plan building off of each other in a way many other students may understand. With AI, students wouldn’t experience the same understatement from someone else of how challenging a software engineering concept may be.
<br><br>

## Conclusion
---
AI takes a big part in software engineering education as it provides many help for students to rely on. Its personalized functionality makes it easy to interact with as it never fails to output an answer that a student may be looking for. If you have never seen an error before, need help writing code, need studying tips, AI will always have something to provide to help you understand. It may also be seen to be more welcoming than other people since its chat features looks like an indirect messaging platform available at any time you need it. However, AI is not perfect. There is always room for improvement but is always going to be limited as it is just a computer. It may be dynamic but it can’t impersonate a human. This doesn’t mean AI is not capable in the world of education, but it is a highly developed tool to provide assistance to learn and code smarter. AI needs humans to run it, it can’t work alone so pairing it with traditional teaching methods can make learning more effective. If students could use AI smarter then it can enhance their learning experience in another perspective.  
