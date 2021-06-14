# Tutorial

## How to Fork, Clone and Push

Read <a href="https://desainerhub.com/cara-kontribusi-open-source">this article</a> for complete Turorial.

## What should you Add and Edit

### Photo

**Add** your foto inside <a href="https://github.com/bekasidev/bekasidev/tree/master/assets/img/faces">this directory</a>:

PATH: <code>/assets/img/faces/</code>

Name it as simple as possible:

NAME: <code>myname.jpg</code>

Example:

Full Path to File: <code>/assets/img/faces/rifai.jpg</code>

Live:

<a href="https://bekasidev.org/assets/img/faces/rifai.jpg">https://bekasidev.org/assets/img/faces/rifai.jpg</a>

Remember your image path and file name, this image you will use in profile and gallery below

### Profile

**Add** your profile page inside <a href="https://github.com/bekasidev/bekasidev/tree/master/member">this directory</a>:

PATH: <code>/member/</code>

**Name** it as simple as possible:

NAME: <code>myname.html</code>

Or **Copy** and **Edit** <a href="https://github.com/bekasidev/bekasidev/blob/master/member/profile-template.html">this file</a>:

<code>/member/profile-template.html</code>

Example:

Full Path to File: <code>/member/rifai.html</code>

Live:

<a href="https://bekasidev.org/member/rifai.html">https://bekasidev.org/member/rifai.html</a>

Remember to edit title and profile image with your name and photo, and other content like description.add social media links.

If you decide to copy & edit <code>profile-template.html</code> file.

Default title:

```html
  <title>
    Profile Template
  </title>
```
Edit to:

```html
  <title>
    Your Name
  </title>
```

Default Profile Picture/image:

```html
<div class="card-profile-image">
 <a href="javascript:;">
  <img src="/assets/img/logo-green.png" class="rounded-circle">
 </a>
</div>
```

Edit to:

```html
<div class="card-profile-image">
 <a href="javascript:;">
  <img src="/assets/img/faces/myname.jpg" class="rounded-circle">
 </a>
</div>
```


### Gallery

**Edit** this file carefully:

<code>/member/index.html</code>

This gallery is a page to archiving or listing of all members, you only need to add tumbnail and URL to your profile.

