# Tutorial

## How to Fork, Clone and Push

Read <a href="https://desainerhub.com/cara-kontribusi-open-source">this article</a> for complete Tutorial.

<hr>

## What should you Add and Edit

### Photo

- **Add** your foto inside <a href="https://github.com/bekasidev/bekasidev/tree/master/assets/img/faces">this directory</a>:

PATH: <code>/assets/img/faces/</code>

- Name it as simple as possible:

FILE: <code>myname.jpg</code>

**Example**:

Full Path to File: <code>/assets/img/faces/rifai.jpg</code>

**Live**:

<a href="https://bekasidev.org/assets/img/faces/rifai.jpg">https://bekasidev.org/assets/img/faces/rifai.jpg</a>

- Remember your image path and file name, this image you will use in profile and gallery below.

<hr>

### Profile

- **Add** your profile page inside <a href="https://github.com/bekasidev/bekasidev/tree/master/member">this directory</a>:

PATH: <code>/member/</code>

- **Name** it as simple as possible:

FILE: <code>myname.html</code>

- Or **Copy** and **Edit** <a href="https://github.com/bekasidev/bekasidev/blob/master/member/profile-template.html">this template file</a>:

Full Path to Template File <code>/member/profile-template.html</code>

- After copy that file, change it's name with your name, do this simple edit:

>Default title:

```html
  <title>
    Profile Template
  </title>
```

>Edit to:

```html
  <title>
    My FullName
  </title>
```

>Default Profile Picture/Image:

```html
<div class="card-profile-image">
 <a href="javascript:;">
  <img src="/assets/img/logo-green.png" class="rounded-circle">
 </a>
</div>
```

>Edit to:

```html
<div class="card-profile-image">
 <a href="javascript:;">
  <img src="/assets/img/faces/myname.jpg" class="rounded-circle">
 </a>
</div>
```

**Example**:

Full Path to Example/Edited File: <code>/member/rifai.html</code>

**Live**:

<a href="https://bekasidev.org/member/rifai.html">https://bekasidev.org/member/rifai.html</a>

- Remember to edit other contents like description and social media links with your own.

<hr>

### Gallery

This gallery is a page to archiving or listing of all members, you only need to add tumbnail and URL to your profile.

**Edit** this file carefully, **don't copy** or change it's file name:

Full Path to File <code>/member/index.html</code>

>Do Simple edit

```html
<div class="col-sm-3 col-6">
    <figure class="figure">
         <a href="myname.html" data-toggle="tooltip"
              data-original-title="Your Name">
             <img alt="Widi" class="img-fluid rounded-circle shadow" src="../assets/img/faces/myname.jpg">
          </a>
        <figcaption class="figure-caption text-center">My FullName</figcaption>
   </figure>
</div>
```

**Live**:
<a href="https://bekasidev.org/member">https://bekasidev.org/member</a>



