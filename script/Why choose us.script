 
const testimonials = [
    {
      name: "James Carter",
      job: "Office Director",
      image: " ../images/home1-image18.jpg",
      testimonial:
      "I run a small business and rely on this platform to find reliable service providers. It's saved me countless hours of searching and has become an essential tool in managing my operations."
     },
    {
      name: "Michael Nguyen",
      job: "Web Designer",
      image: "../images/home1-image19.jpg",
      testimonial:
"Finding and hiring services through this platform has been a breeze!The reviews and ratings help me make informed decisions, and the whole process is smooth and hassle-free."
    },
    {
      name: "Samantha Patel",
      job: "Sale Manager",
      image: "../images/home1-image20.jpg",
      testimonial:
"I was able to find the perfect match within days and was impressed by the professionalism and expertise of the freelancer I hired."
    },
    {
      name: "Benjamin Lee",
      job: "Manager",
      image: "../images/home1-image21.jpg",
      testimonial:
"I run a small business and rely on this platform to find reliable service providers. It's saved me countless hours of searching and has become an essential tool in managing my operations."
    },
  ];
  
   let i = 0;
   let j = testimonials.length;
  
  let testimonialContainer = document.getElementById("testimonial-container");
  let nextBtn = document.getElementById("next");
  let prevBtn = document.getElementById("prev");
  
  nextBtn.addEventListener("click", () => {
    i = (j + i + 1) % j;
    displayTestimonial();
  });
  prevBtn.addEventListener("click", () => {
    i = (j + i - 1) % j;
    displayTestimonial();
  });
  
  let displayTestimonial = () => {
    testimonialContainer.innerHTML = `
      <p>${testimonials[i].testimonial}</p>
      <img src=${testimonials[i].image}>
      <h3>${testimonials[i].name}</h3>
      <h6>${testimonials[i].job}</h6>
    `;
  };
  window.onload = displayTestimonial;