Android-rating-dashing
======================

Android rating dashing

##Preview

![]()

## Description

Display your Android App Rating info. 
It uses [Goolge Play Store website](https://play.google.com/store/apps/details?id=com.researchNow.eRewards) as the source.

##Usage

To use this widget, copy `appstore.html`, `appstore.coffee`, and `appstore.scss` into the `/widgets/appstore` directory. Put the `app_store.rb` file in your `/jobs` folder.

You'll also need the [Google logo](). Download it, and put it in your `/assets/images` folder. 

To include the widget in a dashboard, add the following snippet to the dashboard layout file:

	<li data-row="1" data-col="1" data-sizex="2" data-sizey="1">
	  <div data-id="Android e-Rewards Mobile" data-view="Google" data-title="Android e-Rewards Mobile"></div>
	</li>

##Settings

You'll need to set the URL path to your application on the iTunes Store website in the app_store.rb.

    appPageUrl = 'https://play.google.com/store/apps/details?id=com.researchNow.eRewards' # e-Rewards Mobile

Rating is fetched every 24 Hours, but you can change that by editing the job schedule.
