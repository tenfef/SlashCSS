+++
title = "Input"
date = "2018-04-11T09:16:45+12:00"
family = "Single"
draft = false
description = "The input component provides various form input fields."
+++

### Basic Input

The `input` component is basic form input field that can be modified.

<input type="text" placeholder="Basic text input" class="input">

### Sliding Input

Input fields can be modified to produce sliding labels similar to Material Design.

<div class="max-width:400px padding-y:u6">
  <div class="card elevate">
    <form class="form">
      <div class="card/content">
        <h5 class="font font-weight:medium margin-bottom:u4 align:center">Sliding Label</h5>
        <div class="form/item">
          <div class="input:slide">
            <input type="email" placeholder=" " class="max-width:100%">
            <label>Email</label>
          </div>
        </div>
        <div class="form/item">
          <div class="input:slide">
            <input type="password" placeholder=" " class="max-width:100%">
            <label>Password</label>
          </div>
        </div>
        <div class="form/item">
          <div class="input:slide-select max-width:100%" label="What's your favourite ice cream?">
            <select>
              <option>How did you find us?</option>
              <option>Vanilla</option>
              <option>Strawberry</option>
            </select>
          </div>
        </div>
        <div class="form/item">
          <label class="input:checkbox">
            I agree to the <a href="#">Terms and Conditions</a>
            <input type="checkbox"/>
            <div class="input/symbol"></div>
          </label>
        </div>
      </div>
      <div class="card/footer padding:u0">
        <a class="button button-style:flat fill:blue width:100% border-radius:sharp border-radius-bottom">
          Sign in
        </a>
      </div>
    </form>
  </div>
</div>

```html
<div class="input:slide">
  <input placeholder=" " class="max-width:100%">
  <label>Email</label>
</div>
```

### Disabled Fields

The disabled attribute disables clickable state.

<div class="max-width:400px padding-y:u6">
  <div class="card">
    <div class="card/content">
      <form class="form">
        <div class="form/item">
          <label>Email</label>
          <input placeholder="Email" value="jin@google.com" disabled="disabled" class="max-width:100%">
        </div>
        <div class="form/item">
          <label>Username</label>
          <input type="text" placeholder="atjinsu" value="@jinsu" disabled="disabled" class="max-width:100%">
        </div>
        <div class="form/item">
          <label class="input:checkbox">Disabled
            <input type="checkbox" disabled="disabled" checked="checked"/>
            <div class="input/symbol"></div>
          </label>
        </div>
        <div class="form/item">
          <label class="input:radio">Disabled & checked
            <input type="radio" name="radio2" disabled="disabled" checked="checked"/>
            <div class="input/symbol"></div>
          </label>
        </div>
        <div class="form/item">
          <div class="input:select">
            <select disabled="disabled" class="max-width:100%">
              <option>Disabled</option>
              <option>Option</option>
              <option>Option</option>
            </select>
          </div>
        </div>
      </form>
    </div>
  </div>
</div>

```html
<div class="card">
  <div class="card/content">
    <form class="form">
      <div class="form/item">
        <label>Email</label>
        <input placeholder="Email" value="jin@google.com" disabled="disabled" class="max-width:100%">
      </div>
      <div class="form/item">
        <label>Username</label>
        <input type="text" placeholder="atjinsu" value="@jinsu" disabled="disabled" class="max-width:100%">
      </div>
      <div class="form/item">
        <label class="input:checkbox -checkbox">Disabled
          <input type="checkbox" disabled="disabled" checked="checked"/>
          <div class="input/symbol"></div>
        </label>
      </div>
      <div class="form/item">
        <label class="input:radio">Disabled & checked
          <input type="radio" name="radio2" disabled="disabled" checked="checked"/>
          <div class="input/symbol"></div>
        </label>
      </div>
      <div class="form/item">
        <div class="input:select">
          <select disabled="disabled" class="max-width:100%">
            <option>Disabled</option>
            <option>Option</option>
            <option>Option</option>
          </select>
        </div>
      </div>
    </form>
  </div>
</div>
```

### Input States

Form input fields can have states for various types of highlighting.

<div class="max-width:400px padding-y:u6">
  <div class="card elevate">
    <div class="card/content">
      <form class="form">
        <div class="form/item">
          <label>Name</label>
          <input type="text" placeholder="Text input" class="input max-width:100% is-alert">
          <span class="form/message is-alert">Check spelling</span>
        </div>
        <div class="form/item">
          <label>Username</label>
          <input type="text" placeholder="Username" value="SlashCSS" class="input max-width:100% is-success">
          <span class="form/message is-success">This username is available</span>
        </div>
        <div class="form/item">
          <label>Email</label>
          <input type="text" placeholder="Email" value="made@" class="input max-width:100% is-warning">
          <span class="form/message is-warning">Email is invalid</span>
        </div>
      </form>
    </div>
  </div>
</div>

```html
<label>Name</label>
<input type="text" placeholder="Text input" class="max-width:100% is-alert">
<span class="form/message is-alert">Check spelling</span>

<label>Username</label>
<input type="text" placeholder="Username" value="SlashCSS" class="max-width:100% is-success">
<span class="form/message is-success">This username is available</span>

<label>Email</label>
<input type="text" placeholder="Email" value="made@" class="max-width:100% is-warning">
<span class="form/message is-warning">Email is invalid</span>
```


### Special Fields

Standard text fields can have icons.

<div class="max-width:400px padding-y:u6">
  <div class="card elevate">
    <div class="card/content">
      <form class="form">
        <div class="form/item">
          <div class="input:icons">
            <input type="text" placeholder="Username" value="SlashCSS" class="max-width:100% padding-left:u10">
            <div class="input/icon position-left">
              <i class="far fa-user"></i>
            </div>
            <div class="input/icon position-right">
              <i class="fas fa-check color:green"></i>
            </div>
          </div>
        </div>
        <div class="form/item">
          <div class="input:icons">
            <input type="text" placeholder="Email" value="made@" class="max-width:100% padding-left:u10">
            <div class="input/icon position-left">
              <i class="far fa-envelope"></i>
            </div>
            <div class="input/icon position-right">
              <i class="fas fa-times color:red"></i>
            </div>
          </div>
        </div>
        <div class="form/item">
          <div class="input:icons">
            <input type="text" placeholder="Email" value="docs" class="max-width:100% padding-right:u14 padding-left:u4">
            <div class="input/text">
              .slashcss.com
            </div>
          </div>
        </div>
      </form>
    </div>
  </div>
</div>

```html
<div class="input:icons">
  <input type="text" placeholder="Username" value="SlashCSS" class="max-width:100% padding-left:u10">
  <div class="input/icon position-left">
    <i class="far fa-user"></i>
  </div>
  <div class="input/icon position-right">
    <i class="fas fa-check color:green"></i>
  </div>
</div>

<div class="input:icons">
  <input type="text" placeholder="Email" value="made@" class="max-width:100% padding-left:u10">
  <div class="input/icon position-left">
    <i class="far fa-envelope"></i>
  </div>
  <div class="input/icon position-right">
    <i class="fas fa-times color:red"></i>
  </div>
</div>

<div class="input:icons">
  <input type="text" placeholder="Email" value="docs" class="max-width:100% padding-right:u14 padding-left:u4">
  <div class="input/text">
    .slashcss.com
  </div>
</div>
```
