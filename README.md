# Marketing Refactor

## Description 

Horiseon, a **fictitious** marketing agency, requested a refactoring of its website to improve accessibility. This project included the following improvements to the existing code:
* Replacement of non-semantic elements with semantic ones
* Adherence to a logical structure of elements independent of styling or positioning
* Addition of alt attributes for all images and icons
* Sequencing of headings
* Addition of a concise, descriptive title


[View the live Horiseon site](https://rmoscoe.github.io/marketing-refactor/)
<br>

## Technologies

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |   
| Git | [https://git-scm.com/](https://git-scm.com/)     |   

## Learning Points

Because I had previously learned some HTML, CSS, and Git on Codecademy, this project mainly provided a refresher for me on some of the basics. In addition, I developed a deeper understanding of two important concepts:
* **Semantic HTML Elements.** I improved my ability to distinguish between semantic and non-semantic elements, and I learned that semantic elements are not necessary for site functionality but improve accessibility and SEO performance.
* **Git Workflow.** Although I had learned several git commands previously, this project gave me an understanding of how those commands work together to create a unified workflow.

## Usage

This proejct is a static website. See the screenshots below.

![screenshot of Horiseon website](./assets/images/Horiseon1.png)
*Figure 1*

<br />

![screenshot of Horiseon website](./assets/images/Horiseon2.png)
*Figure 2*
<br />

## Refactoring Example

The starter code included several instances of repetitive CSS rule sets, including the following example:

<br />

```CSS
.benefit-lead img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-brand img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```
<br />

The images referenced in the code above all appear within the aside element on the page, and the declarations were identical. Therefore, I consolidated the code above as shown below:
<br />

```CSS
aside section img { 
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
```
<br />

## Installation

N/A

## Credits

Starter code provided by Trilogy Education Services, LLC, a 2U, Inc. brand, in conjunction with the University of California, Berkeley, Coding Bootcamp.