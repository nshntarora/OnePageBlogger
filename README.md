# OnePageBlogger
##a one page template for Blogger (Blogspot) blogs

OnePageBlogger is a one page template for Blogger. You can use it to create your own personal web page, or get to work using your HTML & CSS skills and make something interesting.

The best part, there is no compulsion for you to give credits to me or a link to my github profile. I know how much that sucks :p

That said, I have added my name and my twitter handle as a comment in the source code (It won’t be visible to the public), for humanity’s sake, let it be there :)

###[demo link]

##Installation:
1. Open your blog’s dashboard.
2. Click on Template option on the left sidebar.
3. Now click on that small “gear” icon below the mobile site option.
4. Select “No. Show desktop template on mobile devices” and save it.
(This is important, otherwise mobile users will the default mobile template instead of our OnePageBlogger)
5. Scroll to the bottom of the template page and click on “Revert to classic templates”. In the dropdown options, click on revert to classic template.
6. Now on the classic template page, head for the “Change Navbar” option and turn the Navbar off.
7. Now delete all the code from the Edit HTML template option.
8. Paste all the code from onepageblogger.xml in to the Edit HTML template box.
9. Edit the code with your content,  add URLs for images and save it.


##Editing Images
Editing the text content is easy, just replace the placeholder content with whatever you want. Editing the logo and the favicon is even simpler.

1. In a new tab open your blog’s dashboard, click on the new post icon.
2. On the post page click on the image upload icon.
3. In the option popup, click on Choose Files >> select your 16x16 favicon file and your logo image >> Upload them. But don’t yet close that upload popup.
4. When your upload finishes, right click on the favicon image and click on “Copy image link”.
5. Now head to the template HTML code and search for the below line of code (you might find it somewhere between line 6 to 9).

```
<title><$BlogPageTitle$></title>
  <$BlogMetaData$>
```

In the next line, you'll see the link tag which imports the favicon.

6. Replace the existing URL (after href within "") with the URL of the image you just copied and save the template.

You just changed the favicon.

Now do the same thing for changing your Logo. Copy the link of your uploaded logo and search for the below code.

```
<ItemPage><a href="<$BlogURL$>"></ItemPage>
```

Below this line you'll see an img tag, replace the existing source URL with the URL of your logo and save the template.

You just changed the logo.

###Now you’re good to go.
[demo link]:http://onepageblogger.blogspot.com
