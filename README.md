# SocialCops Intern Challenge
---
#### Make a text editor with the following requirements

Build your editor/notepad with following features: 

1. Each enter will create a new paragraph. 

2. The user can drag and drop the paragraphs to rearrange their order. 

3. On double-clicking a word, show a tooltip with three options: make the word bold, underlined, and change the text color to Red. 

4. Users can enter links in the text editor by using tags. For example, “<a>This is a link </a>”. When the user clicks “Done”, the editor should detect if the user has entered a link tag in the editor. If so, add that text as an actual link (like this: This is a link (http://www.google.com/)) to the bottom of the page (outside of the text editor). The links at the bottom of the page should be colored red and blue alternatively, and they do not need to actually link to another site. 

#### Advanced Task:

Here is a way to generate random English words: http://randomword.setgetgo.com/. 

Replace all the four letter words on your page with the random words generated by using the above link. If the original word was styled, then the new word replacing it should also be styled in the same way.

### Tasks completed successfully:

* Enter Creates a new paragraph
* Paragraphs are draggable
* Tooltips are shown on doubleclick with the required functions
* Anchor tags are shown in the bottom of the text editor.
* The 4 letter words are replaced with random words generated using the API.

### Known Issues:

* In the Tooltip, if the user makes the text red, he/she can't revert back to original state by clicking the options again.
* The random word API sometimes fails to serve the request and in such case four letter words will be replaces with 'undefined'.
* The random word API limits the number of requests to 1/second.

**Note:** The entire challenge helped me a lot in exploring some portions like regular expressions in depth and improved my knowledge of JavaScript functions even further. I feel very curious about how these little things, make huge difference in real life applications. 


 