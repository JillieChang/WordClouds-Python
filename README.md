# <p align="center"> HOW TO CREATE A CUSTOM WORD CLOUD WITH TWITTER DATASET<br/>  <em>By using Python and WordCloud library </em> </p>
<br/>
<p align="center";font-size:20pt>
  <img  src="https://user-images.githubusercontent.com/57914884/173212958-c59612a0-7f3d-4a61-a4b7-0ea88627d162.png">
</p>

<p style="text-align:justify"> A Word Cloud  or Tag Cloud is a graphical representation of word frequency within a text: the more often a word is used in a text, the bigger and bolder it is represented in a graph. It can be a useful tool to communicate at a glance the most important keywords in a particular text or topic in a effective and fun way. </p>

<p style="text-align:justify"> In this tutorial we will create a Word Cloud from a sample of nameless tweets extracted from Twitter for the period 3/16/2020 - 08/31/2020 in Peru. The dataset was modificated to respect Twitter private information policy and is used just as an example to show how to create a Word Cloud.  </p>

## Table of contents

We will do different examples of Word Clouds by using the following steps:

<ol>
  <li>Install packages and import libraries </li>
  <li>Import the dataset, clean it up and select the text you are going to work with (tweets) </li>
  <li>Perform the text preprocessing and create a clean variable </li>
  <li>Create your Word Cloud:
    <p>  </p>  
      <ul> 
        <em>
          <li> Example 1: Default model </li>  
          <br/>
              <p align="left";font-size:20pt>
              <img  src="https://user-images.githubusercontent.com/57914884/173214584-38251b13-c769-4576-bb29-b252df7c67aa.png">
              </p>
          <li> Example 2: Default model - customize parameters </li>
          <br/>
               <p align="left";font-size:20pt>
              <img  src="https://user-images.githubusercontent.com/57914884/173257072-7d433ae6-baa6-40d8-b8b4-62d7d1432905.png">
              </p>
          <li> Example 3: Customize shapes </li>
          <br/>
               <p align="left";font-size:20pt>
              <img  src="https://user-images.githubusercontent.com/57914884/173261971-3c7e7482-894f-488a-afa2-0ba695ec8958.png" width="350" height="350">
              </p>          
          <li> Example 4: Customize colors - set multiple colors with a mask </li>
          <br/>
              <p align="left";font-size:20pt>
              <img  src="https://user-images.githubusercontent.com/57914884/173262041-1b85e553-53d8-4461-8930-120ba14bcdbd.png" width="400" height="230" > 
              </p>   
          <li> Example 5: Customize colors - set a single color with a mask </li>
          <br/>
              <p align="left";font-size:20pt>
              <img  src="https://user-images.githubusercontent.com/57914884/173262146-7b1dedde-cbd7-48a6-9ac9-fae865d41224.png" width="400" height="230">
              </p>
          <li> Example 6: Customize colors - set multiple colors with a function</li>
          <br/>
               <p align="left";font-size:20pt>
              <img  src="https://user-images.githubusercontent.com/57914884/173262186-2043b2c8-0d3e-4618-b62b-2d3101ab0399.png">
              </p>  
          <li> Example 7: Customize content - set repeated words</li>
               <p align="left";font-size:20pt>
              <img  src="https://user-images.githubusercontent.com/57914884/173262214-cb818699-0f78-4a54-b210-c5332496738b.png">
              </p>  
          <li> Example 8: Customize content - set non-repeated words </li>
          <br/>
               <p align="left";font-size:20pt>
              <img  src="https://user-images.githubusercontent.com/57914884/173262225-d305c8a9-24e6-4b4a-8f3c-2365707c2c73.png">
              </p>          
       </em>     
      </ul>
  </li>
  <p>  </p>     
  <li>Finally, you can review Bibliography to look for more information. </li>   
</ol>
