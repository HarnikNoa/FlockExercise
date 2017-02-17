# Flock Exercise
Here is my submitted project for the Flock code challenge.  Included in this solution is an email form that does very basic validation.  When the user clicks on submit, the template changes to a meetup search by zip code that makes a call to an external API.

# Answers to Task 1
I have limited experience with webpack and Gulp.  I used webpack in a personal project after I did not use any bundler when I made my website.  I quickly realized that using one made performance incredibly faster and deploying the project was also much easier.  So if you want to be able to ship quickly, simply and have good performance, it would make sense to use some form of environment tooling.

I have worked at companies where we used both automated UI testing and manual testing, and companies where we only used manual testing.  It seems like it's good to write the tests because they help you realize mistakes as you go, but they can be rendered useless so quickly if you're on a large team where everybody is constantly touching and changing things.  If I were to outsource a web project to a freelance company, I would require them to implement testing in order to try and catch as many mistakes as possible, but whether that would be manual or automated depends on the project scope, the team size, and the workflow of the project.  At the very least they should have code reviews with their check-ins.

My experience with javascript frameworks has been been working with Angular, Telerik UI, and various small plug ins.  I think Javascript frameworks are most valuable when you are not trying to recreate the wheel, so to speak.  If you need something custom then vanilla JS could do the job.  Otherwise why not cut down on time, as long as what you're using plays nice with whatever else is in your project?

# Links and shortcomings
I had the most difficult time with my api call.  I tried using an angular GET method and ran into some CORS issues, and finally (after about 30 minutes and frantically searching through what felt like hundreds of websites) I found this post: 
http://stackoverflow.com/questions/29547003/angularjs-no-access-control-allow-origin-header-is-present-on-the-requested-r

If I could make more changes, I would add better styling and add user friendly things like a little message that says, "loading meetups".
