# Contribution

## How to Fork, Clone, Push & Pull Request

Read <a href="https://desainerhub.com/cara-kontribusi-open-source">this article</a> for complete Tutorial to Fork, Clone, Push & Pull Request.

<hr>

## What should you Add and Edit

Please read carefully, you only need to focus in 3 item:

1. [Profile Picture](#profile-picture) (Upload Your Photo)
2. [Profile Page](#profile-page) (Create Your Profile)
3. [Member Gallery](#member-gallery) (Add Link and Tumbnail)

<hr>

### Profile Picture

**Add** your Photo inside <a href="https://github.com/bekasidev/bekasidev/tree/master/assets/img/faces">this directory</a>:

- PATH: <code>/assets/img/faces/</code>

Name it as simple as possible:

- FILE: <code>myname.jpg</code>

**Example**:

- Full Path to File: <code>/assets/img/faces/rifai.jpg</code>

**Live**:

- <a href="https://bekasidev.org/assets/img/faces/rifai.jpg">https://bekasidev.org/assets/img/faces/rifai.jpg</a>

Remember your image path and file name, this image you will use in profile and gallery below.

Recommended image size is square 500x500px, with clear face or close-up, like identity card. 

<hr>

### Profile Page

**Add** your profile page inside <a href="https://github.com/bekasidev/bekasidev/tree/master/member">this directory</a>:

- PATH: <code>/member/</code>

**Name** it as simple as possible:

- FILE: <code>myname.html</code>

Or **Copy** and **Edit** <a href="https://github.com/bekasidev/bekasidev/blob/master/member/profile-template.html">this template file</a>:

- Full Path to Template File <code>/member/profile-template.html</code>

Copy, change it's name with your name, then do this simple edit:

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

- Full Path to Example/Edited File: <code>/member/rifai.html</code>

**Live**:

- <a href="https://bekasidev.org/member/rifai.html">https://bekasidev.org/member/rifai.html</a>

Remember to edit other contents like description and social media links with your own.

>Social Links:

```html
<div class="card-profile-stats d-flex justify-content-center">
  <div>
     <a href="https://facebook.com/username">
       <span class="heading"><i class="fa fa-facebook"></i></span>
     </a>
  </div>
   .......<!--Add your own links here-->
</div>
```

>Description:

```html
<div class="text-center mt-5">
    <h3>Jhon Thor<span class="font-weight-light">, 20</span></h3>
        <div class="h6 font-weight-300">
           <i class="ni ni-pin-3 mr-2"></i>Bekasi Utara, Kota Bekasi
        </div> <!--Your Location-->
        <div class="h6 mt-4">
           <i class="ni ni-briefcase-24 mr-2"></i>Frontend Enginer - Bekasidev.org
        </div> <!--Your Occupation-->
        <div>
           <i class="ni ni-hat-3 mr-2"></i>Universitas Pagar Makan Tanaman
        </div> <!--Your Education-->
</div>
<div class="mt-5 py-5 border-top text-center">
    <div class="row justify-content-center">
        <div class="col-lg-9">
           <p>Hello my name is Bekasidev, I am a developer, programmer, designer.</p>
           <a href="https://www.google.com/search?q=bekasidev&oq=bekasidev">Show more</a>
           <!--Your Description-->
        </div>
    </div>
</div>
```

>Github Card:

```html
<!--Github Card for profile and repositories-->
 <div class="container">
    <div class="github-card" data-github="github-username" data-width="100%" data-height="" data-theme="medium"></div>
    <div class="github-card" data-github="github-username/repository" data-width="100%" data-height="" data-theme="medium"></div>
 </div>
```

<hr>

### Member Gallery

This gallery is a page to archiving or listing of all members, you only need to add tumbnail and URL to your profile.

**Edit** this file carefully, **don't copy** or change it's file name <code>index.html</code>

Don't edit or delete anything belong to another members, you may add new row if there no more space for you.

- Full Path to File <code>/member/index.html</code>

Inside that file, change <code>myname.html</code>, <code>myname.jpg</code>, ***"My FullName"*** below with yours.


>Default Snippet

```html
<div class="col-sm-3 col-6">
    <figure class="figure">
         <a href="myname.html" data-toggle="tooltip"
              data-original-title="My FullName">
             <img alt="My FullName" class="img-fluid rounded-circle shadow" src="../assets/img/faces/myname.jpg">
          </a>
        <figcaption class="figure-caption text-center">My FullName</figcaption>
    </figure>
</div>
```

>Example Edited

```html
<div class="col-sm-3 col-6">
    <figure class="figure">
         <a href="rifai.html" data-toggle="tooltip"
              data-original-title="Maksum Rifai">
             <img alt="Maksum Rifai" class="img-fluid rounded-circle shadow" src="../assets/img/faces/rifai.jpg">
          </a>
        <figcaption class="figure-caption text-center">Maksum Rifai</figcaption>
    </figure>
</div>
```

**Live**:

- <a href="https://bekasidev.org/member">https://bekasidev.org/member</a>

## Summary

what you should add/edit:
- add profile picture (`yourname.jpg`)
- add profile page (`yourname.html`)
- add tumbnail and link to your profile in member archive/gallery (`member/index.html`)

## Documentations

We use **Argon Design System** for Main Landing Page (bekasidev.org), Refer to <a href="https://demos.creative-tim.com/argon-design-system/docs/getting-started/overview.html">Offical Docs</a> if you want to customizing properly.
