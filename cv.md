# rsschool-cv

# **Vladislasv Stasenko**

# **Contact information:**
**Phone:** +375298596628
**E-mail:** vladiksts@gmail.com
**Telegram:** vlad_stas__

# **Briefly About Myself:**

### The beginning of my work began at Yandex.Market in the Customer Support Department (B2C). The next place of work is Kidskey online school, technical support department. The key responsibilities in this position are: setting up equipment for online conferences, solving hardware and software problems, creating and maintaining office infrastructure.

# **Skills and Proficiency:**
1. JavaScript Basics; 
2. Git, GitHub, GitLab;
3. VS Code;
4. amoCRM, ELMA;

# **Code example**
The sample code is taken from the EPAM test assignment for external courses

```
const checkBtn = document.querySelector(".check-btn");

checkBtn.addEventListener("click", (event) => {
  event.preventDefault();
  const comment = document.querySelector(".comment").value;
  const phoneNumber = document.querySelector(".phone-number").value;

  if (!comment) {
    document.getElementById("comment").value += "vladiksts@gmail.ru";
  }

  const phoneNumberRegexp = /^\+375\d{9}$/g;

  if (phoneNumber != null && !phoneNumberRegexp.test(phoneNumber)) {
    const invalidPhoneNumber = document.querySelector(".invalid-phone-number");
    invalidPhoneNumber.style.display = "block"

    const validPhoneNumber = document.querySelector(".valid-phone-number");
    validPhoneNumber.style.display = "none"
  } else {
    const validPhoneNumber = document.querySelector(".valid-phone-number");
    validPhoneNumber.style.display = "block"

    const invalidPhoneNumber = document.querySelector(".invalid-phone-number");
    invalidPhoneNumber.style.display = "none"
  }

});
```
# Courses
1. JavaScript Manual on learnjavascript.ru (in progress)
2. RS Schools Course «JavaScript/Front-end. Stage 0» (in progress) 