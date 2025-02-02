---
layout: essay
type: essay
title: "Help Yourself by Asking Better Questions"
# All dates must be YYYY-MM-DD format!
date: 2025-02-01
published: true
labels:
  - Smart questions
---

<img width="200px" src="../img/question.png">

Image Source: [Pixabay](https://pixabay.com/illustrations/question-question-mark-response-1015308/)

## Importance of Smart Questions
In a world of busy yet helpful people, many are willing to help each other out, but there are always some limitations. Since providing answers is voluntary, it is only fair that the question being asked is thoughtful and accompanied by courtesy. The internet (ie: Google, Safari, FireFox, etc.) is easily accessible, so it is reasonable and recommended to search for your answers on your own first. There are also a lot of free AI generative tools that  are also an option for a search for answers. If those tools don’t work, they can assist you in writing a smart question about your issue to ask the public.

A question is more likely to be answered if it is well thought out, structured logically, symptoms presented in chronological order, while displaying your willingness to learn by asking for guidance in the right direction. This approach prevents misunderstandings, reduces confusions, and saves time for everyone involved. Smart questions lead to smart answers. There's also a possibility that your question may also help the receiver touch up on misunderstandings. 

## Example of an Effective Question
The title should clearly indicate the type of software being used and a brief description of the issue or goal. A well-written description should provide context about the application’s purpose, explain a specific goal, previous attempts and their outcomes, and well formatted code. Tags are also important as it can attract experts experienced in the field. 

One well structured question on Stack Overflow followed these bases effectively. The user working with Codename One asked if there was a shorter or more efficient alternative to disable all components in an Android application until the user closes a popup dialogue. They listed unsuccessful methods, `form.setEnabled (false)`, `form.getComponentCount ()`, and provided a working but inefficient solution.

```java
form.setScrollable (false); 
  for (Component component : containerOne ) { 
    component.setEnabled(false); 
  } 
  for (Component component : containerTwo ) { 
    component.setEnabled(false); 
  } 
  for (Component component : containerThree ) { 
  component.setEnabled(false); 
  } 
  buttonOne.setEnabled(false); 
  buttonTwo.setEnabled(false); 
  textFieldOne.setEnabled(false); 
  textFieldTwo.setEnabled(false);
```

Since they find their approach inefficient, they asked whether a single-line or simpler method exists. By structuring their question properly, they received relevant answers. This example demonstrates the importance of clear problem statements, well explained attempts, and concise examples in technical discussions.

Here is a link to [a well structured question](
https://stackoverflow.com/questions/63981568/codename-one-get-and-disable-all-components-and-sub-components)

## Example of an Lacking Question
No one can answer a question effectively if they are expected to know what another person’s code is doing without proper context or visual representation of the issue. It is recommended to use clear formatting to improve code readability, breaking it into multiple lines instead of pasting one long unformatted line mixed into a paragraph. This user on Stack Overflow failed to do so, while asking one question in the title and then a different one in their explanation

`Display.getInstance().sendMessage(new String[] {currentRow.getString(2)}, fileName, m);`

Additionally, this user is asking for a direct solution, rather than guidance, without demonstrating any efforts in solving their issue in Codename One. Before asking, the user should have searched for relevant guides and documentation on the Codename One websites. There is a lack of context regarding where the Share Popup is called when sendMessage is issued, what it does, and this relates to turning popup off. Furthermore, the user does not specify what platform they are using or provide a complete description of their issue’s symptoms. As of right now, there are no responses which may indicate that this user’s issue is difficult to solve.

Here is a link to [a poor structured question](
https://stackoverflow.com/questions/79406055/can-someone-tell-me-where-the-share-popup-is-called-when-i-issue-sendmessage)


## Impact of Different Quality Questions
The quality of responses depends on how a question is asked. Clarity ensures the user receives the help they need, while efficiency in problem solving saves time by disregarding unnecessary information. Making an effort before asking a question leads to better learning outcomes because users often learn new things along the way. Additionally, stating previous attempts narrows down relevant working solutions. In contrast, vague questions cause confusion, delays, or may leave unanswered. Instead of gaining valuable insights, the only takeaway may be the realization that the question was poorly structured. 

If the user had provided more context, listed previous attempts, they would have received a faster and more detailed response. Asking a question online is similar to communicating in person. It requires clear, respectful, and well thought wording to receive useful feedback. Next time help yourself by structuring your questions properly to maximize the quality of responses and show consideration for others offering assistance.
