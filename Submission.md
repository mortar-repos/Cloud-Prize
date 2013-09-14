
## Which Categories Best Fit Your Submission and Why?
* Best example application mash-up
* Best portability enhancement

## Describe your Submission
We have [integrated the Lipstick job visualizer with our Hadoop PaaS](http://blog.mortardata.com/post/60765120319/domesticating-pig-with-lipstick).  Doing so required several modifications to the Lipstick code base to make it more extensible (ie - allowing for alternative storage backends, making the front end customizable).  All of these changes have been submitted to the Netflix/Lipstick repo in pull requests.  

Additionally, we have open sourced two tools we created that make running Lipstick much easier.  A [chef cookbook](https://github.com/mortardata/chef-lipstick) which can be used for automated installation and configuration of a Lipstick server, and [try-lipstick](https://github.com/mortardata/try-lipstick) a package that lets you easily try out running Hadoop jobs with Lipstick via a single command through Vagrant.  We discussed these tools and some details of the the integration in depth in a [recent blog post](http://blog.mortardata.com/post/61026715305/using-chef-and-vagrant-to-put-lipstick-on-a-pig).

Adding Lipstick for our users has empowered them to understand their jobs with an ease they had never had before, but we expect this won’t be the only benefit.  The changes we have submitted upstream along with our published experiences should make similar integration projects far simpler in the future.  In addition, the tools we have released drastically lower the bar to getting started with Lipstick.  We feel these contributions will result in a wider adoption of Lipstick in the coming future.

## Provide Links to Github Repo's for your Submission
* https://github.com/mortardata/chef-lipstick
* https://github.com/mortardata/try-lipstick
* https://github.com/Netflix/Lipstick
* https://github.com/mortardata/Lipstick
