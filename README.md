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
    hobbies='playing video games 🎮, exercising 🏃‍♂️, playing soccer ⚽️, and playing the guitar 🎸'
    personalSite='https://csilva2810.github.io/'
  />,
  document.getElementById('root')
)
```

<!--
**csilva2810/csilva2810** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
