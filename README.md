[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/f6dTnkNL)

# Week 5 Installation Guide (Study Case: For Her Society)
<p>For Her Society is a non-profit organization engaged in women's empowerment and mental health. For Her Society provides training, support group system and health checks every 1-3 months.</p>
<p>If u Curious, click this link 
  
  [link](https://forhersociety.placeblog.site/)
</p>

## Development Process
<p>This section will document all the development stages of creating the website: design choices, considerations, development stages, etc. Side note: this website was built using HTML and CSS without any framework or Javascript.</p>

### Content Creation Process
<p>I came up with this idea because I was reminded of content related to women's empowerment and mental health (started from remembering the "semicolon project" and one part of my life story) and Brainstorming with some friends.</p>

### HTML 
<ol>
  <li>When developing the website, HTML semantic markup was used throughout the header, nav, main, section, article, etc.</li>
  <li>As best as I could, appropriate tags were also used, such as images, links, and other media elements. Hopefully by using this approach, accessibility and maintainability are improved on the website.</li>
</ol>

![image](https://github.com/RevoU-FSSE-2/week-5-zhafirahr/assets/47013275/2e9210fe-0b7e-4b13-a77c-08e8596be69a)

![image](https://github.com/RevoU-FSSE-2/week-5-zhafirahr/assets/47013275/d2099b2f-1d77-42e2-ab29-3afc51d528ef)

### CSS
<ol>
  <li>Media queries were utilized to adjust the styling and layout based on the user's device or screen width</li>
  <li>Most of the structures used flexbox and grid layouts were employed to create flexible and responsive designs across mobile, tablet, and desktop.</li>
  <li>A little of CSS transitions and animations were implemented to add subtle and engaging visual effects.</li>
</ol>

![image](https://github.com/RevoU-FSSE-2/week-5-zhafirahr/assets/47013275/6f24f73f-2837-4560-93b3-3a2586462e70)
![image](https://github.com/RevoU-FSSE-2/week-5-zhafirahr/assets/47013275/3f22b413-0ae0-4e77-b38f-67edcc0623c3)

## Result 
![image](https://github.com/RevoU-FSSE-2/week-5-zhafirahr/assets/47013275/bbb24bda-e963-480e-b0fd-6911c37990e4)
![image](https://github.com/RevoU-FSSE-2/week-5-zhafirahr/assets/47013275/7b42b46c-ad91-4dfa-8985-f5ff2930a685)

### Deployment
<ol>
  <li>The website was deployed using Netlify, with a custom domain from Niagahoster.</li>
  <li>To ensure seamless integration between Github and Netlify, connect your Netlify account with Github, and choose to deploy from your Github repository. This is done to ensure that Netlify will automatically initiate deployments whenever there are any changes in your GitHub repository.</li>
  <li>Cloudflare, a content delivery network (CDN), was employed to optimize the website's performance and provide enhanced security.</li>
  <li>I used a domain that I've already bought and set up for another website last week. Therefore, what's left is only redirecting it to a different website.</li>
  <li>It can be done by changing the target field to a different website and deleting the old one. I also use CNAME type because it is easier for Netlify.</li>
  ![image](https://github.com/RevoU-FSSE-2/week-5-zhafirahr/assets/47013275/5de9eb9f-f24f-4921-91ee-10a74115f379)
  <li>Afterwards add another record with CNAME type and fill the name field with www and target it to the custom domain website.</li>
  <li>Next, in Netlify, delete the used custom domain on the old website, and click "Add Domain" on your new website in the domain settings menu.</li>
  <li>Follow the instruction to add the custom domain. The finished result will look like this.</li>
  
  ![image](https://github.com/RevoU-FSSE-2/week-5-zhafirahr/assets/47013275/f310e489-03f2-41cf-ad26-cf3567abdacb)

  <li>Wait for a few minutes, and there we go~</li>

</ol>






