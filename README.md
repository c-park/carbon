# Carbon
Carbon is a custom, free-to-use theme for [reddit.com](http://reddit.com). You can see a live preview of the theme at [/r/Carbon](http://reddit.com/r/carbon).

`Current release: v1.0`

## About

Carbon is a "dark" theme, similar to [RES](https://github.com/honestbleeps/Reddit-Enhancement-Suite) nightmode, and is an available option in the new [reddit themes](http://www.reddit.com/r/goldbenefits/comments/33ei8y/introducing_reddit_themes_change_the_appearance/) feature. The theme can also be used to style personal subreddits. See the [installation](#installation) details below for more information.

The theme is still **in development**. The following issues are on the to-do list:

* RES compatability
* RES nightmode compatability
* Cross browser discrepancies
* reddit Toolbox compatability

##### Feedback

If you notice any bugs, have any questions, or want to provide feedback/suggestions, please feel free to [leave a comment in this thread](http://www.reddit.com/r/carbon/comments/33g9qc/carbon_v10_bugs_and_feedback_thread/) or [submit a post to the /r/Carbon](http://www.reddit.com/r/carbon/submit?selftext=true). I really appreciate any feedback!

Thanks!

[/u/ggitaliano](http://reddit.com/user/ggitaliano)

**NB:** You are free to use and customise the theme as you see fit but please keep the small attribution in the footer. Thank you!

## Files & folders

* `README.md` - info
* `changelog.txt` – self-explanatory
* `css/` – CSS code
    * `carbon_rt.css` - CSS for the **reddit themes** version of Carbon
    * `carbon_rt_min.css` - CSS (minified) for the **reddit themes** version of Carbon
    * `carbon_sub.css` - CSS for **individual subreddit** version of Carbon
* `img/` - images
    * `spritesheet.png` - main image file
    * `snoo.png` - header image uploaded to subreddit/about/edit page
* `psd/` - .PSD image files

**NB:** Due to the 100kb limit on reddit stylesheets, the reddit themes version of Carbon must be minfied before being copied over.

## Installation 

#### Using reddit themes

1. [Go to your preferences page](http://reddit.com/prefs)
2. Locate the <b>reddit themes</b> panel

###### Option 1
3. Make sure the <b>use reddit theme</b> option is selected
4. Choose /r/carbon
5. Hit save!

###### Option 2
6. Make sure the <b>use theme from</b> option is selected
7. Enter `carbon` into the subreddit field
8. Hit save!

<b>NB:</b> If the <b>allow subreddits to show me custom themes</b> option on your [preferences page](http://reddit.com/prefs) is <b>ON</b> the Carbon theme will apply to your front page, your profile/messages pages, and any <b>unstyled</b> subreddits. To have the Carbon theme apply to <b>all</b> subreddits you'll need to switch <b>OFF</b> the <b>allow subreddits to show me custom themes</b> option. Note that you can still allow specific subreddits to show their custom styles by selecting the <b>Show this subreddit's theme</b> option in the sidebar of those subreddits.

#### On your personal subreddit

1. Go to /r/subreddit/about/stylesheet (replace `subreddit` with the name of your sub)
2. Paste the CSS from the `carbon_sub.css` file into the stylesheet field
3. Upload the images from the `/img/` folder (don't rename them)
4. Hit save!
