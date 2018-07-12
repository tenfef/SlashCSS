+++
title = "Form DONE"
date = "2018-04-11T09:16:45+12:00"
draft = false
description = "The form component provides styling for standard forms."
+++

##### Basic Usage

Defined with `form` form fields are grouped with the `form/item` child element. Form labels can have a required asterisk with the `:required` modifier.

<div class="max-width:40 padding-y:3">
  <div class="card elevate">
    <form class="form">
      <div class="card/content">
        <h5 class="font font-weight:medium margin-bottom:3 align:center">Basic Form</h5>
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


{{% codeblock key="language" definition="html" margin="top" %}}
```html
<div class="card elevate">
  <form class="form">
    <div class="card/content">
      <h5 class="font font-weight:medium margin-bottom:3 align:center">Basic Form</h5>
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
```
{{% /codeblock %}}

##### Sliding labels

Form items can be modified to enable sliding labels with `form/item-style:slide`.

<div class="max-width:40 padding-y:3">
  <div class="card elevate">
    <form class="form">
      <div class="card/content">
        <h5 class="font font-weight:medium margin-bottom:3 align:center">Sliding Label</h5>
        <div class="form/item form/item-style:slide">
          <input id="email" type="email" placeholder=" " class="max-width:100%">
          <label for="email">Email</label>
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

{{% codeblock key="language" definition="html" margin="top" %}}
```html
<div class="card elevate">
  <form class="form">
    <div class="card/content">
      <h5 class="font font-weight:medium margin-bottom:3 align:center">Sliding Label</h5>
      <div class="form/item form/item-style:slide">
        <input id="email" type="email" placeholder=" " class="max-width:100%">
        <label for="email">Email</label>
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
```
{{% /codeblock %}}

##### Disabled Fields

The disabled attribute disables clickable state.

<div class="max-width:40 padding-y:3">
  <div class="card">
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
</div>

{{% codeblock key="language" definition="html" margin="top" %}}
```html
<div class="card">
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
```
{{% /codeblock %}}

##### Multi-Column Fields

Here is an example of a Company Information form in multi-column format. For multi-column layout utilise row and column components.

<div class="max-width:80 padding-y:3">

  <div class="card elevate">
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
        <div class="form/item margin-bottom:4">
          <label for="username" class="form/label:fluid">Address</label>
          <input id="username" type="text" placeholder="Level 5, Graham St" class="max-width:100% margin-bottom:1">
          <input id="username" type="text" placeholder="Central" class="max-width:100%">
          <span class="form/help">Help message example</span>
        </div>
        <div class="row row-gutter:1 margin-bottom:2">
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
        <div class="row row-gutter:1 margin-bottom:4">
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
        <div class="form/item margin-bottom:3">
          <label>Country</label>
          <textarea class="max-width:100%"></textarea>
        </div>
        <div class="form/item margin-bottom:3">
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

##### Form States

Form input fields can have states for various types of highlighting.

<div class="max-width:40 padding-y:3">
  <div class="card elevate">
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
</div>

{{% codeblock key="language" definition="html" margin="top" %}}
```html
<div class="card elevate">
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
```
{{% /codeblock %}}


##### Special Fields

Standard text fields can have icons on the left and right.

<div class="max-width:60 padding-y:3">
  <div class="card elevate">
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
</div>

{{% codeblock key="language" definition="html" margin="top" %}}
```html
<div class="card elevate">
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
```
{{% /codeblock %}}


##### Local Variables

You can override styling using the following local variables.

{{% codeblock key="language" definition="css" margin="bottom" %}}
```css
:root {
  --form-label-weight: var(--medium);
  --form-label-size: var(--tiny);

  --form-field-height: var(--u5);
  --form-field-border: var(--border);
  --form-field-fill: var(--white);
  --form-field-checkbox-fill: var(--blue);
  --form-field-color: var(--black);
  --form-field-radius: 4px;
  --form-field-padding: 1.5rem;

  --form-disabled-fill: var(--grey-light-5);
  --form-disabled-color: var(--grey-dark-1);
  --form-disabled-opacity: 1;

  --form-success-border-color: var(--green);
  --form-alert-border-color: var(--orange);
  --form-warning-border-color: var(--red);
}
```
{{% /codeblock %}}

##### Modifiers

The following modifiers are available.

<table class="table width:100% table:pile">
  <thead>
    <tr>
      <th>
        Property
      </th>
      <th>
        Modifier
      </th>
      <th>
        Responsive
      </th>
      <th>
        Description
      </th>
    </tr>
  </thead>
  <tr>
    <td data-label="Properties">
      <code>form/item-style</code>
    </td>
    <td data-label="Attributes">
      <code>:slide</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Enable sliding label
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>form/label</code>
    </td>
    <td data-label="Attributes">
      <code>:required</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Attach required asterisk
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>form/special-content</code>
    </td>
    <td data-label="Attributes">
      <code>:left</code> <code>:right</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Apply padding for icon
    </td>
  </tr>
  <tr>
    <td data-label="Properties">
      <code>form/help</code>
    </td>
    <td data-label="Attributes">
      <code>is-active</code> <code>is-alert</code> <code>is-warning</code>
    </td>
    <td data-label="Responsive">
      No
    </td>
    <td class="row:reverse">
      Attach message
    </td>
  </tr>
</table>
