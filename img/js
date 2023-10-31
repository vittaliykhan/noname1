// Creating a JavaScript object
const person = {
    name: "Vitaliy",
    age: 25,
    occupation: "Full-Stack Developer",
  };
  
  // Accessing and modifying object properties
  console.log(person.name); // Output: Vitaliy
  person.age = 26;
  console.log(person.age); // Output: 26
  
  // Using selectors and methods
  const submitBtn = document.getElementById("submitBtn");
  const fullnameInput = document.getElementById("email");
  
  // Event listener for form submission
  submitBtn.addEventListener("click", function (event) {
    event.preventDefault(); // Prevent form submission
  
    const fullname = fullnameInput.value;
    console.log("Submitted by:", fullname);
  });
  
  // Mouseover event listener
  const queryTextArea = document.getElementById("query");
  queryTextArea.addEventListener("mouseover", function () {
    console.log("Mouseover event occurred");
  });
  
  // Event listener for navbar brand click
  const navbarBrand = document.getElementById("navbarBrand");
  navbarBrand.addEventListener("click", function () {
    console.log("Navbar brand clicked!");
  });

  document.addEventListener("keypress", function (event) {
    console.log("Keypress event occurred. Key:", event.key);
    // Perform actions or call functions when a key is pressed
  });

  const aboutMeHeading = document.getElementById(".important-text h2");

aboutMeHeading.addEventListener("mouseover", function () {
  animateHeading();
});

function animateHeading() {
  aboutMeHeading.classList.add("animated");
  setTimeout(function () {
    aboutMeHeading.classList.remove("animated");
  }, 1000);
}


    var acc = document.getElementsByClassName("accordion");
    var i;

    for (i = 0; i < acc.length; i++) {
        acc[i].addEventListener("click", function() {
            this.classList.toggle("active");

            var panel = this.nextElementSibling;
            if (panel.style.display === "block") {
                panel.style.display = "none";
            } else {
                panel.style.display = "block";
            }
        });
    }



    const alertPlaceholder = document.getElementById('liveAlertPlaceholder')
const appendAlert = (message, type) => {
  const wrapper = document.createElement('div')
  wrapper.innerHTML = [
    `<div class="alert alert-${type} alert-dismissible" role="alert">`,
    `   <div>${message}</div>`,
    '   <button type="button" class="btn-close" data-bs-dismiss="alert" aria-label="Close"></button>',
    '</div>'
  ].join('')

  alertPlaceholder.append(wrapper)
}

const alertTrigger = document.getElementById('liveAlertBtn')
if (alertTrigger) {
  alertTrigger.addEventListener('click', () => {
    appendAlert('Nice, you triggered this alert message!', 'success')
  })
}
    

