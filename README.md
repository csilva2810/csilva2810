<p align="center">
  <img src="https://user-images.githubusercontent.com/5983943/116801020-7ce76a80-aadc-11eb-9128-92cc1f4d00fe.png" width="100px" align="center" />
</p>
<p align="center">
  <a href="https://csilva2810.github.io/">Hi, I'm Carlos!</a>
</p>

```javascript
import React from 'react'
import ReactDOM from 'react-dom'

const Person = ({ name, jobTitle, country, technologies, hobbies }) => (
  <p>
    Hello, my name is {name}. I'm a {jobTitle} in ${country}. <br />
    I love building things using {technologies}. <br />
    My hobbies are {hobbies}. <br />
    You can visit my personal site at: {personalSite} <br />
    Nice to meet you!
  </p>
)

ReactDOM.render(
  <Person
    name='Carlos'
    jobTitle='Front-end Engineer'
    country='Brazil'
    technologies='Javascript, and React'
    hobbies='playing video games š®, exercising šāāļø, playing soccer ā½ļø, and playing the guitar šø'
    personalSite='https://csilva2810.github.io/'
  />,
  document.getElementById('root')
)
```

<!--
**csilva2810/csilva2810** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
