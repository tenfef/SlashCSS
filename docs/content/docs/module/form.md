+++
title = "Form"
date = "2018-04-11T09:16:45+12:00"
family = "Module"
draft = false
description = "The form component provides styling for standard forms."
+++

### Basic Usage

The form component acts as a structure for building out form components. Defined with `form` form fields are grouped with the `form/item` child element. Form labels can have a required asterisk with the `required` class.

<div class="max-width:400px padding-y:u6">
  <div class="card elevate">
    <form class="form">
      <div class="card/content">
        <h5 class="font font-weight:medium margin-bottom:u4 align:center">Basic Form</h5>
        <div class="form/item">
          <label class="required">Email</label>
          <input placeholder=" " class="max-width:100%" required>
        </div>
        <div class="form/item">
          <label class="required">Password</label>
          <input type="password" placeholder=" " class="max-width:100%" required>
        </div>
        <div class="form/item">
          <label class="input:checkbox">
            I agree to the <a href="#">Terms and Conditions</a>
            <input type="checkbox" required/>
            <div class="input/symbol"></div>
          </label>
        </div>
      </div>
      <div class="card/content padding:u0">
        <a class="button button-style:flat fill:blue width:100% border-radius:sharp border-radius-bottom">
          Sign in
        </a>
      </div>
    </form>
  </div>
</div>


```html
<form class="form">
  <div class="form/item">
    <label class="required">Email</label>
    <input placeholder=" " class="max-width:100%" required>
  </div>
  <div class="form/item">
    <label>Password</label>
    <input type="password" placeholder=" " class="max-width:100%" required>
  </div>
  <div class="form/item">
    <label class="input:checkbox">
      I agree to the <a href="#">Terms and Conditions</a>
      <input type="checkbox" required/>
      <div class="input/symbol"></div>
    </label>
  </div>
</form>
```


### Multi-Column Form

Here is an example of a Company Information form in multi-column format. For multi-column layout utilise row and column components.

<div class="max-width:600px padding-y:u6">

  <div class="card elevate">
    <div class="card/content">
      <form class="form">
        <h5 class="font margin-bottom:u4 font-weight:medium font:underline">
          Company Information
        </h5>
        <div class="form/item">
          <div class="row row-gutter:u4 margin-bottom:u4">
            <div class="column:12 column@sm:6 margin-bottom:u4 margin-bottom@sm:u0">
              <label>Company</label>
              <input type="text" placeholder="Company" class="max-width:100%">
            </div>
            <div class="column:12 column@sm:6 margin-bottom:u4 margin-bottom@sm:u0">
              <label class="">Title</label>
              <input type="text" placeholder="Digital Designer" value="Digital Designer" disabled="disabled" class="max-width:100%">
            </div>
          </div>
        </div>
        <div class="form/item margin-bottom:u4">
          <label>Address</label>
          <input type="text" placeholder="Level 5, Graham St" class="max-width:100% margin-bottom:u2">
          <input type="text" placeholder="Central" class="max-width:100%">
          <span class="form/message">Help message example</span>
        </div>
        <div class="row row-gutter:u4 margin-bottom:u2">
          <div class="column:12 column@sm:6 margin-bottom:u4 margin-bottom@sm:u0">
            <div class="form/item">
              <label>City</label>
              <input placeholder="City" class="max-width:100%">
            </div>
          </div>
          <div class="column:12 column@sm:6 margin-bottom:u4 margin-bottom@sm:u0">
            <div class="form/item">
              <label>State</label>
              <input id="website" type="Website" placeholder="State" class="max-width:100%">
            </div>
          </div>
        </div>
        <div class="row row-gutter:u4 margin-bottom:u4">
          <div class="column:12 column@sm:6 margin-bottom:u4 margin-bottom@sm:u0">
            <div class="form/item">
              <label>Zip</label>
              <input placeholder="City" class="max-width:100%">
            </div>
          </div>
          <div class="column:12 column@sm:6 margin-bottom:u4 margin-bottom@sm:u0">
            <div class="form/item">
              <label for="text">Country</label>
              <div class="input:select">
                <select>
                  <option>USA</option>
                  <option>New Zealand</option>
                  <option>Australia</option>
                </select>
              </div>
            </div>
          </div>
        </div>
        <div class="form/item margin-bottom:u4">
          <label>Country</label>
          <textarea class="max-width:100%"></textarea>
        </div>
        <div class="form/item margin-bottom:u4">
          <label class="input:radio float:left margin-right:u4">First radio
            <input type="radio" name="radio1" checked="checked"/>
            <div class="input/symbol"></div>
          </label>
          <label class="input:radio float:left">Second radio
            <input type="radio" name="radio1"/>
            <div class="input/symbol"></div>
          </label>
        </div>
        <div class="form/item">
          <label>Attach CSV</label>
          <label class="form/file button button-grow:u3 button-style:outline font-size:body font-case:none">
            <i class="fas fa-cloud-upload-alt margin-right:u2"></i>
            Upload File
            <input type="file" placeholder="City" class="max-width:100%">
          </label>
        </div>
        <div class="form/item">
          <button type="submit" class="button button-grow:u6 button-style:flat fill:blue float:right">
            Save
          </button>
        </div>
      </form>
    </div>
  </div>
</div>


### Local Variables

You can override this component using the following local variables.

```scss
:root {
  --form-label-weight: var(--body);
  --form-label-size: var(--tiny);

  --form-success-color: var(--green);
  --form-alert-color: var(--orange);
  --form-warning-color: var(--red);
}
```
