# Survey Form

## Project description
This is a survey form from the e-learning platform freeCodeCamp written in HTML and styled with CSS. The form makes use of tags such as `label`, `input`, `forms`, `radio` buttons, `checkbox` as partly shown below;
``` html
    <form action="/submit-date" method="POST" class="survey-form" id="container">
            <div class="form-info">
            <label for="name" id="name">Name</label>
            <input type="text" placeholder="Enter your name" required class="input-field">
            </div>
            <div class="form-info">
            <label for="email" id="email">Email</label>
            <input type="email" placeholder="Enter your email" required class="input-field">
            </div>
            <div class="form-info">
            <label for="age" id="age">Age(optional)</label>
            <input type="number" placeholder="Age" class="input-field">
            </div>

            <div class="form-info">
                <p>Which option best describes your current role? </p>
                <select name="role" id="current-role" required class="input-field">
                    <option value="role">select current role</option>
                    <option value="student">Student</option>
                    <option value="job">Full Time Job</option>
                    <option value="learner">Full Time Learner</option>
                    <option value="none">Prefer not to say</option>
                    <option value="other">Other</option>
                </select>
            </div>
```
*Sample screenshot of the survey form*
![freeCodeCamp survey form](/assets/images/sampleSurvey.png)


## Author

**Love Asoh**

- GitHub: [@loveasoh](https://github.com/AsohLove)
- Twitter: [@loveasoh](https://x.com/LoveTheModifier)
- LinkedIn: [love asoh](https://www.linkedin.com/in/asohlove/)


## License
This project is [MIT](./LICENSE) licensed.
