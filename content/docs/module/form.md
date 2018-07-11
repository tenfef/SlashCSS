+++
title = "Form"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The form component provides styling for standard forms."
+++

##### Basic Form

To initialize add the `form` class. The form module contains child items to seperate rows, add the `-last` modifier to the last row to remove bottom margin. By default all input fields have a set max-width, you can make span full width with the `-fluid` modifier. Additionally adding `form/label:fluid` will automatically add the required asterisk at the end of your label.

<div class="row row-gutter:2 row-gutter@sm:3 padding-y:5">
  <div class="column:12 column@sm:6">
    <div class="card elevate" style="max-width: 460px;">
      <form class="form">
        <div class="card/content">
          <h6 class="font font-weight:medium margin-bottom:3 align:center">Modern Style</h6>
          <div class="form/item form/item-style:slide">
            <input id="email" type="email" placeholder=" " value="born@studiobeneath.com" class="input-size:5 max-width:100% is-warning">
            <label for="email">Email</label>
            <span class="form/help is-warning">This account does not exist</span>
          </div>
          <div class="form/item form/item-style:slide">
            <input id="password" type="password" placeholder=" " class="max-width:100%">
            <label for="password">Password</label>
          </div>
          <div class="form/item">
            <label class="form/checkbox">
              I agree to the <a href="#">Terms and Conditions</a>
              <input type="checkbox"/>
              <div class="form/checkbox-indicator"></div>
            </label>
          </div>
        </div>
        <div class="card/footer padding:none">
          <a class="button button-style:flat fill:blue width:100% border-radius:sharp border-radius-bottom">
            Sign in
          </a>
        </div>
      </form>
    </div>
  </div>
  <div class="column:12 column@sm:6">
    <div class="card elevate" style="max-width: 460px;">
      <form class="form">
        <div class="card/content">
          <h6 class="font font-weight:medium margin-bottom:3 align:center">Classic Style</h6>
          <div class="form/item">
            <label for="email" class="form/label:required">Email</label>
            <input id="email" type="email" placeholder=" " class="max-width:100%">
          </div>
          <div class="form/item">
            <label for="password">Password</label>
            <input id="password" type="password" placeholder=" " class="max-width:100%">
          </div>
          <div class="form/item">
            <label class="form/checkbox">
              I agree to the <a href="#">Terms and Conditions</a>
              <input type="checkbox"/>
              <div class="form/checkbox-indicator"></div>
            </label>
          </div>
        </div>
        <div class="card/footer padding:none">
          <a class="button button-style:flat fill:blue width:100% border-radius:sharp border-radius-bottom">
            Sign in
          </a>
        </div>
      </form>
    </div>
  </div>
</div>


{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<form class="form">
  <div class="form/item">
    <label for="email" class="form/label:fluid">Username</label>
    <input id="email" type="email" placeholder="Email" class="max-width:100%">
  </div>
  <div class="form/item">
    <label for="email" class="form/label:fluid">Username</label>
    <input id="email" type="file" placeholder="Email" class="max-width:100%">
  </div>
  <div class="form/item">
    <label class="form/checkbox">
      I agree to the <a href="#">Terms and Conditions</a>
      <input type="checkbox"/>
      <div class="form/checkbox-indicator"></div>
    </label>
  </div>
  <div class="form/item">
    <button type="submit" class="button button-size:2 button:fluid -broad">
      Submit
    </button>
  </div>
</form>
```
{{% /codeblock %}}


##### Disabled Fields

The disabled state fades into the background and disables clickable state.

<div class="card margin-bottom:2" style="max-width: 360px;">
  <div class="card/content">
    <form class="form">
      <div class="form/item">
        <label for="email">Email</label>
        <input id="email" type="email" placeholder="Email" value="jin@litmos.com" disabled="disabled" class="max-width:100%">
      </div>
      <div class="form/item">
        <label for="password">Username</label>
        <input id="email" type="text" placeholder="atjinsu" value="@jinsu" disabled="disabled" class="max-width:100%">
      </div>
      <div class="form/item">
        <label class="form/checkbox -checkbox">Disabled
          <input type="checkbox" disabled="disabled" checked="checked"/>
          <div class="form/checkbox-indicator"></div>
        </label>
      </div>
      <div class="form/item">
        <label class="form/radio">Disabled & checked
          <input type="radio" name="radio2" disabled="disabled" checked="checked"/>
          <div class="form/radio-indicator"></div>
        </label>
      </div>
      <div class="form/item">
        <div class="form/subitem">
          <select disabled="disabled" class="max-width:100%">
            <option>Disabled</option>
            <option>Option</option>
            <option>Option</option>
          </select>
          <div class="form/arrow"></div>
        </div>
      </div>
    </form>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<form class="form">
  <div class="form/item">
    <label for="email">Email</label>
    <input id="email" type="email" placeholder="Email" value="jin@litmos.com" disabled="disabled">
  </div>
  <div class="form/item">
    <label for="password">Password</label>
    <input id="password" type="password" placeholder="Password" disabled="disabled">
  </div>
  <div class="form/item">
    <label class="form/checkbox -checkbox">Disabled
      <input type="checkbox" disabled="disabled" checked="checked"/>
      <div class="form/checkbox-indicator"></div>
    </label>
  </div>
  <div class="form/item">
    <label class="form/radio">Disabled & checked
      <input type="radio" name="radio2" disabled="disabled" checked="checked"/>
      <div class="form/radio-indicator"></div>
    </label>
  </div>
  <div class="form/item">
    <div class="form/subitem">
      <select disabled="disabled">
        <option>Disabled</option>
        <option>Option</option>
        <option>Option</option>
      </select>
      <div class="form/arrow"></div>
    </div>
  </div>
</form>
```
{{% /codeblock %}}

##### Multi-Column Fields

Here is an example of a Company Information form in multi-column format. For multi-column layout utilise grid layout.

<div class="row margin-bottom:2" style="max-width:600px;">
  <div class="column">
    <div class="card">
      <div class="card/content">
        <form class="form">
          <h5 class="font margin-bottom:3 font-weight:medium font:underline">
            Company Information
          </h5>
          <div class="form/item">
            <div class="row row-gutter:1 margin-bottom:3">
              <div class="column:12 column@sm:6">
                <label for="firstname" class="form/label:fluid">Company</label>
                <input id="firstname" type="text" placeholder="Company" class="max-width:100%">
              </div>
              <div class="column:12 column@sm:6">
                <label for="lastname" class="">Title</label>
                <input id="lastname" type="text" placeholder="Digital Designer" value="Digital Designer" disabled="disabled" class="max-width:100%">
              </div>
            </div>
          </div>
          <div class="form/item">
            <label for="username" class="form/label:fluid">Address</label>
            <input id="username" type="text" placeholder="Level 5, Graham St" class="max-width:100% margin-bottom:1">
            <input id="username" type="text" placeholder="Central" class="max-width:100%">
            <span class="form/help">Help message example</span>
          </div>
          <div class="row row-gutter:1 margin-bottom:3">
            <div class="column:12 column@sm:6">
              <div class="form/item">
                <label for="email">City</label>
                <input id="email" type="email" placeholder="City" class="max-width:100%">
              </div>
            </div>
            <div class="column:12 column@sm:6">
              <div class="form/item">
                <label for="email">State</label>
                <input id="website" type="Website" placeholder="State" class="max-width:100%">
              </div>
            </div>
          </div>
          <div class="row row-gutter:1 margin-bottom:3">
            <div class="column:12 column@sm:6">
              <div class="form/item">
                <label for="email">Zip</label>
                <input id="email" type="email" placeholder="City" class="max-width:100%">
              </div>
            </div>
            <div class="column:12 column@sm:6">
              <div class="form/item">
                <label for="text">Country</label>
                <div class="form/select">
                  <select class="form/select:fluid">
                    <option>USA</option>
                    <option>New Zealand</option>
                    <option>Australia</option>
                  </select>
                </div>
              </div>
            </div>
          </div>
          <div class="form/item">
            <label>Country</label>
            <textarea class="max-width:100%"></textarea>
          </div>
          <div class="form/item">
            <label class="form/radio float:left margin-right:2">First radio
              <input type="radio" name="radio1" checked="checked"/>
              <div class="form/radio-indicator"></div>
            </label>
            <label class="form/radio float:left">Second radio
              <input type="radio" name="radio1"/>
              <div class="form/radio-indicator"></div>
            </label>
          </div>
          <div class="form/item">
            <label>Attach CSV</label>
            <label class="form/file button button-grow:1 button-style:outline font-size:body font-transform:none">
              <i class="fas fa-cloud-upload-alt margin-right:1"></i>
              Upload File
              <input type="file" placeholder="City" class="max-width:100%">
            </label>
          </div>
          <div class="form/item">
            <button type="submit" class="button button-grow:2 button-size:3 button-style:flat fill:blue float:right">
              Save
            </button>
          </div>
        </form>
      </div>
    </div>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<form class="form">
  <div class="row margin-bottom:3">
    <div class="column:12 column@sm:6">
      <div class="form/item">
        ...
      </div>
    </div>
    <div class="column:12 column@sm:6">
      <div class="form/item">
        ...
      </div>
    </div>
  </div>
  <div class="form/item">
    ...
  </div>
  <div class="form/item">
    ...
  </div>
</form>
```
{{% /codeblock %}}

##### Form States

Form input fields can have states for various types of highlighting.

<div class="card margin-bottom:2" style="max-width: 500px;">
  <div class="card/content">
    <form class="form">
      <div class="form/item">
        <label class="form/label:fluid">Name</label>
        <input type="text" placeholder="Text input" class="max-width:100% is-alert">
        <span class="form/help is-alert">Check spelling</span>
      </div>
      <div class="form/item">
        <label>Username</label>
        <input type="text" placeholder="Username" value="zapcss" class="max-width:100% is-success">
        <span class="form/help is-success">This username is available</span>
      </div>
      <div class="form/item">
        <label>Email</label>
        <input type="text" placeholder="Email" value="zap@" class="max-width:100% is-warning">
        <span class="form/help is-warning">Email is invalid</span>
      </div>
    </form>
  </div>
</div>

{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<form class="form">
  <div class="form/item">
    <label class="form/label:fluid">Name</label>
    <input type="text" placeholder="Text input" class="max-width:100% is-alert">
    <span class="form/help is-alert">Check spelling</span>
  </div>
  <div class="form/item">
    <label>Username</label>
    <input type="text" placeholder="Username" value="zapcss" class="max-width:100% is-success">
    <span class="form/help is-success">This username is available</span>
  </div>
  <div class="form/item">
    <label>Email</label>
    <input type="text" placeholder="Email" value="zap@" class="max-width:100% is-warning">
    <span class="form/help is-warning">Email is invalid</span>
  </div>
</form>
```
{{% /codeblock %}}


##### Special Fields

Standard text fields can have icons on the left and right.

<div class="card margin-bottom:2" style="max-width: 500px;">
  <div class="card/content">
    <form class="form">
      <div class="form/item">
        <div class="form/special form/special-content:left form/special-content:right">
          <input type="text" placeholder="Username" value="zapcss" class="max-width:100%">
          <span class="form/icon">
            <i class="far fa-user"></i>
          </span>
          <span class="form/icon">
            <i class="fas fa-check color:green"></i>
          </span>
        </div>
      </div>
      <div class="form/item">
        <div class="form/special form/special-content:left form/special-content:right">
          <input type="text" placeholder="Email" value="zap@" class="max-width:100%">
          <span class="form/icon">
            <i class="far fa-envelope"></i>
          </span>
          <span class="form/icon">
            <i class="fas fa-times color:red"></i>
          </span>
        </div>
      </div>
      <div class="form/item">
        <div class="form/special form/special-content:right">
          <input type="text" placeholder="Email" value="docs" class="max-width:100%">
          <span class="form/text">
            .zapcss.com
          </span>
        </div>
      </div>
    </form>
  </div>
</div>


{{% codeblock key="language" definition="html" margin="bottom" %}}
```html
<form class="form">
  <div class="form/item">
    <div class="form/subitem -fluid -icon-left -icon-right">
      <input type="text" placeholder="Username" value="zapcss" class="max-width:100%">
      <span class="form/icon">
        <i class="fas fa-user"></i>
      </span>
      <span class="form/icon -right">
        <i class="fas fa-check"></i>
      </span>
    </div>
  </div>
  <div class="form/item">
    <div class="form/subitem -fluid -icon-left -icon-right">
      <input type="text" placeholder="Email" value="zap@" class="max-width:100%">
      <span class="form/icon">
        <i class="fas fa-envelope"></i>
      </span>
      <span class="form/icon -right">
        <i class="fas fa-times"></i>
      </span>
    </div>
  </div>
  <div class="form/item">
    <div class="form/subitem -fluid -text-right">
      <input type="text" placeholder="Email" value="docs" class="max-width:100%">
      <span class="form/text -right">
        .zapcss.com
      </span>
    </div>
  </div>
</form>
```
{{% /codeblock %}}
