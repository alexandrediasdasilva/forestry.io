---
title: Full Speed Ahead in 2019
description: ''
date: 2019-04-08 04:00:00 +0000
authors:
- DJ Walker
publishdate: 2019-04-08 04:00:00 +0000
expirydate: 2030-01-01 04:00:00 +0000
headline: ''
textline: ''
images:
- "/uploads/chuttersnap-776317-unsplash.jpg"
categories:
- CMS
tags: []
cta:
  headline: ''
  textline: ''
  calls_to_action: []
private: false
weight: ''
aliases: []
photo_credit: chuttersnap / Unsplash
menu: []

---
We have a big update to share with you today! Today’s release marks the culmination of a lot of feature work, with one major goal in mind:

**We wanna go fast.**

Today, we’re launching:

* **Instant Previews**, which will enable your previews to build faster;
* **Git LFS** **support for media** which will speed up Git operations on image-heavy sites; and
* **Gatsby Support**, allowing you to use Forestry with a “_blazing fast”_ Gatsby frontend.

Ready to go fast? Read on…

## Instant Previews

Our preview feature has always been particularly important to us. The ability to preview your changes is an expected feature when using a traditional CMS, but is a significant technical hurdle with a modern Headless CMS. This is because the website code and the management interface can exist so far away from each other.

**Instant Previews** is our next iteration toward powerful and intuitive previewing capability in our CMS. Instant previews take advantage of your static site generator’s built-in **development server** to generate previews faster and shorten the feedback loop for editors.

{{% youtube "6HRoIgftMEc" %}}

To set up instant previews on your site, head over to our [instant previews documentation](https://forestry.io/docs/previews/instant-previews/).

Special thanks to all of our beta testers for helping us bring this feature to production!

## Git LFS Media

We believe that there are distinct advantages to storing content in version control, which is [why we created a Git-backed content manager](https://forestry.io/blog/why-we-created-a-git-backed-content-manager/) in the first place. However, large assets can decrease the performance of Git operations on a system, so keeping images in version control isn’t always a great solution for image-heavy sites. This has been our motivation for integrating our media library with [Cloudinary](https://forestry.io/docs/media/s3/) and [Amazon S3](https://forestry.io/docs/media/s3/), and now we’re happy to announce that you can also use Git’s [Large File Storage](https://git-lfs.github.com/) to handle your media files.

Git LFS will still keep your media files in the same logical repository and allow you to version them, but won’t cause the same repo bloat and performance degradation that is expected when committing large files to a repository.

Check out our [Git LFS guide](https://forestry.io/blog/versioning-large-files-with-git-lfs/) to learn how to set it up for your project.

### Netlify Large Media

In addition to supporting Git LFS through GitHub and GitLab cloud providers, you can also use [Netlify Large Media](https://www.netlify.com/blog/2019/02/26/manage-your-code-and-assets-together-with-netlify-large-media/) with Forestry, giving you the benefits of using Git LFS for large files while also enabling you to use Netlify's [image transformations](https://www.netlify.com/docs/image-transformation/).

{{% tip %}}
To use Netlify Large Media in forestry, change your media settings to **Netlify Large Media** and connect to Netlify from the settings screen.
{{% /tip %}}

## Gatsby Support

![](/uploads/gatsby.svg)

The Gatsby hype train shows no signs of slowing, and for good reason! Gatsby is a static site generator that builds your content into a React-based Progressive Web App. Gatsby straddles the line between static site generator and application framework for React projects, making it a versatile solution for building frontends.

Gatsby sites that source content from Markdown files can now be used with Forestry. Just select Gatsby as the project type when importing, and you’re good to go!

If you’re curious about using Gatsby with Forestry but aren’t sure where to start, [check out our demo projec](https://forestryio.github.io/gatsby-starter-forestry/)t and [import it into Forestry](https://app.forestry.io/quick-start?repo=forestryio/gatsby-starter-forestry&branch=master&engine=gatsby)!

Once again, we'd like to thank our beta testers who helped us bring Gatsby to Forestry!

## Come see us at Jamstack Conf NYC!

![](/uploads/jamstackconf.png)

The hottest static site party of 2019 is happening in New York tomorrow! Forestry is proud to be a Gold Sponsor of [jamstack_conf_nyc](https://jamstackconf.com/) this year, and we’ll be in New York to hang out and talk about all things Jamstack. We’d love to see you there — be sure to stop by our booth for high fives and a little swag!

## We’re Not Done Yet

We’re excited about these updates, and hope you are too, but don’t think for a second that we’re finished! We have plenty more to bring you in 2019, so check back soon!
