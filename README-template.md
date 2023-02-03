# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![https://ssaava.github.io/Ssaava-frontend-mentor/](./images/solutionScreenShot.png)



### Links

- Solution URL: ![👉 here](https://github.com/Ssaava/Ssaava-frontend-mentor)
- Live Site URL: ![👉 here](https://ssaava.github.io/Ssaava-frontend-mentor/)

## My process

### Built with

- Semantic HTML5 markup
- CSS3 custom properties
- Flexbox
- Mobile-first workflow


### What I learned when solving this challenge

I wish to share with you the process i went through when solving this challenge and I would be happy for your feed back.
First of all I joined this challenge when am a complete beginner that is have no prior knowledge inprogramming and I was able to get introduced to some css components which am about to share with you in the code snnipets in the next part.
With the little experience i gained, i learnt that a even if the project is to small, it should be taken as a serious project by creating a folder for it
and also managing all the work flow in that same folder. This helps to organize all the comppnents that are to be used in the project and also play a big role when it comes to uploading the project on github.

#### I used internal CSS to complete the challenge therefore this means I only used one html file and this file only icluded html and css
Below is my html code snippet:
```html
	<div class="qr-div">
		<img src="images/image-qr-code.png" alt="QR Code Image">
		<h1>Improve your front end skills by building projects</h1>
		<p>Scan the QR code to visit front end mentor and take your coding skills to the next level</p>
	</div>
```
#### The snippet below show how i was able to add css to the body of the html

```css 
* {
		margin: 0;
		box-sizing: border-box;
		padding: 0;
	}
    body {
		background-color: hsl(212, 45%, 89%);
		font-family: 'Outfit', sans-serif;
		height: 100vh;
		display: flex;
		justify-content: center;
		align-items: center;
	}
```
#### The snippet below show how I was able to style the paragraph element that I used in the html
This paragraph tag contains simple instructions that you can follow to access frontend mentor website that I used to access this challenge.
```css 
	p {
		font-size: 15px;
		font-weight: 700px;
		color: hsl(220, 15%, 55%);
		text-align: center;
	}
```
#### The snippet below shows the CSS code for the QR-code container that holds the QR-image and also the paragraph tag and the header tag
```css 
	.qr-div {
		width: 310px;
		height: fit-content;
		margin: 0 auto;
		background-color: hsl(0, 0%, 100%);
		padding: 10px 10px 30px;
		border-radius: 12px;
	}
```
#### The snippet below shows the CSS for the img element I used to add the image of the QR-code in the html
```css 
	img {
		display: block;
		width: 100%;
		height: 310px;
		margin: auto;
		border-radius: 12px;
	}
```
#### Finally is the CSS snippet for the  header tag that i used in the html which presents to you the information about the QR-image
```css 
	h1 {
		color: hsl(218, 44%, 22%);
		text-align: center;
		margin: 20px 0;
		font-size: 20px;
		font-weight: 400px;
	}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Ssava Smmanuel](ssaava.github.io/ssavamiles/)
- Frontend Mentor - [@Ssaava](https://www.frontendmentor.io/profile/Ssaava)
- Twitter - [@pestcideUg](https://twitter.com/pestcideUg)

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
