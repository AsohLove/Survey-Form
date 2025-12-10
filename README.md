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
*Preview*
![freeCodeCamp survey form](/assets/images/sampleSurvey.png)

## Project Technical
Built with;
> HTML
> CSS

## Installation
A local copy of this project can be obtain at [this repository](git@github.com:AsohLove/Survey-Form.git), navigate to the survey form page and open on a browser.

**Deployment link**
You may as well do well to check out the [Deployed page](https://asohlove.github.io/Survey-Form/)


### Author

**Love Asoh**

- GitHub: [@loveasoh](https://github.com/AsohLove)
- Twitter: [@loveasoh](https://x.com/LoveTheModifier)
- LinkedIn: [love asoh](https://www.linkedin.com/in/asohlove/)


## License
This project is [MIT](./LICENSE) licensed.
