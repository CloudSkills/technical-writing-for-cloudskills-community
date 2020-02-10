
# Converting a blog post for dev.to

After your post has been published on CloudSkills.io , you'll want to upload it to dev.to as well. This will increase the reach of the post

## Introduction

Dev.to is another blogging platform that we create content on, in addition to CloudSkills.io. Dev.to has grown from a platform predominantly used for developers to collaborate and network on. The platform has organically grown to include subjects such as DevOps, IaC and Cloud Native, all of which are core CloudSkills subject areas.

## Step 1- Create a dev.to account and join the CloudSkills org

To get started, set up an account at [dev.to](https://dev.to/) if you don't already have one.  Next, we will add your account to the CloudSkills.io organization, you need to message Mike to get the organisation secret. Navigate to the [dev.to organization settings](https://dev.to/settings/organization) and paste in the secret obtained from Mike.

## Step 2 - Convert your content

Now your ready to create a blog post. Select the **WRITE A POST** button:

![writeapost](/Images/writeapost.PNG)

Select the dropdown on **Publish under an organization** and select **CloudSkills.io**. Then paste in the contents of your blog post. You need to paste the contents from the CloudSkills GitHub repo as that is the final reviewed version. The blogging tool uses the same markdown format so it will be a straight paste at this stage.

## Step 3 - Set the canonical URL

Select the **...** icon in the upper right corner:

![organization](/Images/organization.PNG)

Fill in the **Canonical URL** with the link to your blog on the cloudskills.io site. If you are creating a blog series, insert a title under **Series Name** as well. Select **Done**:

![canonical](/Images/canonical.PNG)

## Step 4 - Convert the images

Each image in your blog post must be imported to the dev.to image store. To import an image and set the cover image, select the **Image** icon in the upper right corner to the left of the **...** button. When you upload an image, you will get a **Markdown Image** snippet that you can copy and paste into your blog to replace the image links. The image is hosted in an S3 by dev.to. Also note that when you upload the **Cover Image** it may be cut off and you may need to crop it:

![mdimage](/Images/mdimage.PNG)

## Step 5 - Preview, save draft and table of contents

At the bottom is the **Save Draft** button, save often. Also use the **Preview** button to get a view of what the post will look like. You can add a fancy table of contents to your post that looks like the following:

![tableofcontents](/Images/tableofcontents.PNG)

Just include the following syntax for the table formating:
```
# Table Of Contents

* [Prerequisites](#Prerequisites)
* [Step 1 — Resource Provisioners](#Step 1 — Resource Provisioners)
* [Step 2 — Destroy Provisioners](#Step 2 — Destroy Provisioners)
* [Step 3 — Null Resource Provisioners](#Step 3 — Null Resource Provisioners)
* [Conclusion](#Conclusion)
```

To link a heading to the table, format the heading with the tag like so:
```
## Prerequisites <a name="Prerequisites"></a>
```

## Step 5 - Publish

Your content has already been reviewed and published on CloudSkills.io, so once you are ready to publish select **Publish**:

![toolbar](/Images/toolbar.PNG)

You've now successfully published a blog post on dev.to. Just sit back and watch those Hearts and Unicorns pour in!

## Step 6 - Follow CloudSkills on dev.to

Mike will put a shout out about new content for CloudSkills.io blog on Slack for contributors to tweet and like. To increase the reach for content on dev.to it's customary for contributors to follow each other and the CloudSkills organisation on dev.to. This is a simple way to see when others convert and post their content, so you can drop them a heart or two.