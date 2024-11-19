---
layout: blog
title: HTML
weight: 1
date: 2023-03-08T16:10:26.641Z
---
1. ## Code Snippet: Image Next To Text:

Use the following code 2

```
<table width="100%" BORDER="0">
  <td>
  <td width="50%">Put Text Here</td>
  </td><td>
  <td width="50%"><img src="ENTER IMAGE URL HERE" width="100%"></img></td>
  </td>
</table>
```

Go into page to edit in Netlify, enter markdown view and paste above in where you want it to display. 

Change "Put Text Here" to any text you want on the left of the image, and "ENTER IMAGE URL HERE" to the website address of the iamge (e.g. http://leamprov.com/uploads/image.png).

Example:

```
<table width="100%" BORDER="0">
  <td>
  <td width="50%">Hello my name is Dr Bean and I love beans. Come join me on my bean adventure.</td>
  </td><td>
  <td width="50%"><img src="https://leamprov.com/leamprovlogo.png" width="100%"></img></td>
  </td>
</table>
```

Would produce:

<table width="100%" BORDER="0" >
  <td>
  <td width="50%">Hello my name is Dr Bean and I love beans. Come join me on my bean adventure.</td>
  </td><td>
  <td width="50%"><img src="https://leamprov.com/leamprovlogo.png" width="100%"></img></td>
  </td>
</table>

Change the percentages within the code to change how the image/text is proportioned.