---
---

<h2>Book Your Project</h2>

<form action="https://formspree.io/f/xwpkzkqb" method="POST">
  <div class="form-group">
    <label for="first-name">First Name*</label>
    <input type="text" id="first-name" name="first-name" placeholder="First Name" required />
  </div>

  <div class="form-group">
    <label for="last-name">Last Name*</label>
    <input type="text" id="last-name" name="last-name" placeholder="Last Name" required />
  </div>

  <div class="form-group">
    <label for="address">Address*</label>
    <input type="text" id="address" name="address" placeholder="Your Address" required />
  </div>

  <div class="form-group">
    <label for="phone">Phone Number*</label>
    <input type="tel" id="phone" name="phone" placeholder="Your Phone Number" required />
  </div>

  <div class="form-group">
    <label for="country">Country*</label>
    <input type="text" id="country" name="country" placeholder="Your Country" required />
  </div>

  <div class="form-group">
    <label for="budget">Project Budget*</label>
    <input type="text" id="budget" name="budget" placeholder="Your Project Budget" required />
  </div>

  <div class="form-group">
    <label for="email">Email Address*</label>
    <input type="email" id="email" name="email" placeholder="Your Email Address" required />
  </div>

  <div class="form-group">
    <label for="message">Message*</label>
    <textarea id="message" name="message" placeholder="What you want to do or choose from our services" required></textarea>
  </div>

  <div class="form-group">
    <label for="service">Choose a Service*</label>
    <select name="service" id="service" required>
      <option value="">Please Select</option>
      <option value="web-development">Web Development</option>
      <option value="app-development">App Development</option>
      <option value="seo-services">SEO Services</option>
      <option value="digital-marketing">Digital Marketing</option>
      <option value="graphic-design">Graphic Design</option>
    </select>
  </div>

  <div class="form-group privacy">
    <label for="privacy-consent">
      <input type="checkbox" name="privacy-consent" required />
      I agree to the privacy policy and consent to receive marketing updates.
    </label>
  </div>

  <button type="submit">Submit</button>
</form>

<!-- CSS for styling -->
<style>
  /* Style for form elements */
  form {
    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
    background-color:rgb(92, 89, 89);
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  h2 {
    text-align: center;
    font-size: 24px;
    margin-bottom: 20px;
  }

  .form-group {
    margin-bottom: 15px;
  }

  .form-group label {
    display: block;
    font-size: 14px;
    margin-bottom: 5px;
  }

  .form-group input,
  .form-group textarea,
  .form-group select {
    width: 100%;
    padding: 10px;
    font-size: 14px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
  }

  .form-group textarea {
    resize: vertical;
    height: 100px;
  }

  button {
    padding: 10px 20px;
    background-color:rgb(13, 29, 151);
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 16px;
  }

  button:hover {
    background-color:rgb(74, 5, 165);
  }

/* Apply to the privacy consent container */
/* Container for the checkbox and label */
.privacy {
  display: flex;              /* Use flexbox for precise alignment */
  align-items: center;        /* Vertically align the checkbox and label */
  margin-top: 10px;           /* Space from the previous element */
}

/* Styling the checkbox input */
.privacy input[type="checkbox"] {
  margin: 0;                  /* Remove default margins */
  width: auto;                /* Make sure checkbox width is automatic */
  height: auto;               /* Make sure checkbox height is automatic */
  vertical-align: middle;     /* Align vertically with the label text */
  margin-right: 8px;          /* Add some space between the checkbox and label */
}

/* Styling the label */
.privacy label {
  font-size: 14px;            /* Adjust label font size */
  font-weight: normal;        /* Remove bold weight */
  display: inline-block;      /* Ensure the label stays inline with the checkbox */
}



  /* Style for the submit button */
  button[type="submit"] {
    border: 2px solid rgb(105, 143, 240);
  }
</style>
