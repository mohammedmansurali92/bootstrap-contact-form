# bootstrap-contact-form
Bootstrap Contact Form validation
<div class="contact-section p-3 bg-primary my-5 text-white">
          <div class="title text-left my-5">
      <h3 class="font-weight-bolder background-light text-center">Contact Me</h3>
     <form action="" class="w-50 m-auto was-validated">
      <div class="form-group">
         <label for="fullname">Fullname:</label>
        <input type="text" class="form-control" name="fullname" required>
        <div class="valid-feedback">Valid</div>
        <div class="invalid-feedback">Please write your fullname as soon as possible</div>
        </div>
       <div class="form-group">
          <label for="email">Email:</label>
        <input type="email" class="form-control" name="email">
      </div>
       <div class="form-group">
          <label for="subject">Subject:</label>
        <input type="text" class="form-control" name="subject">
      </div>
       <div class="form-group">
          <label for="message">Message:</label>
        <textarea name="message" style="resize: none" class="form-control" cols="30" rows="10"></textarea>
      </div>
      <div class="form-group">
        <input class="btn btn-secondary" type="submit" value="submit" placeholder="">
        <input class="btn btn-secondary" type="reset" value="Reset">
      </div>
     </form>
       </div>
     </form>
    </div>
       </div>

