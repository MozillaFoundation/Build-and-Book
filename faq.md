
## Questions

* [Why are we using GitHub?](#why)
* [When should I use GitHub Issues?](#when_gh)
* [When should I use Bugzilla?](#when_bz)
* [I'm ready to start. Now what?](#start)
* [I'm stuck!](#im_stuck)
* [Which GitHub repo should I use?](#whichrepo)
* Why are some of our repos listed under "mozilla" instead of "mozillafoundation"? 

* [What's the /plan repo?](#whatsplan)
* [Explain Heartbeats again?](#heartbeats)

## <a name="why"></a>Why are we using GitHub?

There are four factors that led us to choose to use GitHub issues:

* Our code lives in GitHub, and being able to refer to code changes (pull requests) in the same organizational model as the issue management makes eminent practical sense for managing bugs and feature progress.

* GitHub is a central point of activity for open source activity, especially web development, which is a large part of what we do.  There are network effects that we hope will yield more active volunteer contributions to our projects.

* GitHub is amazingly self-service and granular.  We can have as many repos, with as many teams and bug categorization systems as we want, without having to go through a manual process.  

* The GitHub API means we can build custom tools to fit the process we want, rather than having to adapt to the Bugzilla process.

There are definite downsides to not using Bugzilla, but we believe the tradeoff currently favors GitHub for our needs in 2015.  We can revisit next year.

## <a name="when_gh"></a>When I should you use GitHub issues? 

* When you're working with designers, developers or product management
* To let the rest of MoFo know about an important piece of work happening (because it may affects how others are planning).
* Whenever you think it would be helpful! Working in tickets/issues/bugs (instead of email threads) can be a great way to increase speed, collaboration, agility, openness and communication. Feel free to play around and make it your own! It's impossible to break anything.  It's easy, free and self-service to create a public repository and associated issue tracker in GitHub, so you may just find it handy. 


## <a name="when_bz"></a>When should I use Bugzilla or something else?

* When you're working closely with MoCo colleagues who use Bugzilla. Not all parts of MoCo use Bugzilla, but many do, in particular, legal, privacy, engagement, etc.  Anything confidential shouldn't be done in a GitHub public issue tracker (GitHub doesn't support making individual bugs "not-public").
* When you're working with Studio MoFo.   Instead, use their [intake form](http://studiomofo.org/#form-section)
* When you need the MoFo Operations team (finance, HR, admin) to do something. Their Bugzilla input is [here](https://bugzilla.mozilla.org/enter_bug.cgi?assigned_to=nobody%40mozilla.org&bug_file_loc=http%3A%2F%2F&bug_ignored=0&bug_severity=normal&bug_status=NEW&cf_fx_iteration=---&cf_fx_points=---&component=General&contenttypemethod=autodetect&contenttypeselection=text%2Fplain&flag_type-4=X&flag_type-607=X&flag_type-791=X&flag_type-800=X&flag_type-803=X&form_name=enter_bug&maketemplate=Remember%20values%20as%20bookmarkable%20template&op_sys=All&priority=--&product=Mozilla%20Foundation%20Operations&rep_platform=All&target_milestone=---&version=unspecified).



## <a name="start"></a>Getting started

1. [Create your GitHub account](https://github.com/) (if you don't already have one, it's free). If you pick a nickname that is close to your name, it'll make your colleagues life easier.
2. [Log in](https://github.com/login)
3. Fill out your [profile](https://github.com/settings/profile)
4. Ask one of the members of the [owners group](https://github.com/orgs/MozillaFoundation/teams/owners) to add you to the ["MozillaFoundation" organization](https://github.com/MozillaFoundation), so that your handle will come up in autocomplete for example.


### Want to play around?

Here's a [testing sandbox](https://github.com/k88hudson/githubtraining) you can play around in, to get your feet wet with filing, labeling and playing around with tickets  


### Top Tips

* Tweak your [email notifications](https://github.com/settings/notifications).  We suggest adjusting your settings to *only* receive emails on stuff you care about.   e.g., conversations your participate in. Or when someone mentions you. 

![email_settings](https://dl.dropboxusercontent.com/spa/6c38yp3crbxni5b/4z4y2u_n.png)

* If you say something in an issue, you'll get email whenever anyone else makes a comment or a change.  You can simply click the "unsubscribe" button on issues that you don't want/need to follow.

* Check out [build.webmaker.org](https://build.webmaker.org). It  makes a lot of this GitHub stuff waaaaay easier. (And we can improve it as we go). If you want to see what we're working on,  propose a new project idea, or get an overview of how we're using GitHub, this is a great place to start. 

We've put together some more [GitHub tips](/tips.html)


## <a name="im_stuck"></a>What should I do if I'm stuck or have a question?

* Ask in #webmaker IRC. 
* For Learning Networks: ask Lainie or Hannah. 
* For Learning Products: ask Wex, Cassie or Andrew. 
* For all else: ask OpenMatt. 
* If you don't know who any of these people are: ask a friend, colleague, anyone.

We're here to help -- no question is too big or small. 

(Q: can we overexplain this section for the sake of helping external contributors - i.e. link to our how to use IRC, and give contact details / twitter handles etc... Or that might be a seperate document?)




## <a name="whichrepo"></a>Which GitHub repo should I use?

There are _lots_ of repos, and many of them have their own issue trackers.  Mozilla has probably over 2000 repos overall.  The MoFo repos we know about are:

* the repos in the [MozillaFoundation organization](https://github.com/MozillaFoundation/) which are mostly about planning and advocacy
* the repos in the [mozilla org](https://github.com/mozilla/?query=mofo) which mention mofo in the title
* the [Hive](https://github.com/MozillaHive) repos
* the [Webmaker](https://github.com/mozilla/?query=webmaker) repos
* [ScienceLab](https://github.com/mozilla/sciencelab)
* [Source](https://github.com/mozilla/source)

Some notable repos:

* Webmaker.org: https://github.com/mozilla/webmaker.org/issues
* Webmaker App: https://github.com/mozilla/webmaker-app/issues
* Curriculum: https://github.com/mozilla/webmaker-curriculum/issues
* Webmaker Training: https://github.com/mozilla/school-of-webmaking
* Webmaker whitepapers: https://github.com/mozilla/webmaker-whitepaper
* Web Literacy Map: https://github.com/mozilla/webliteracymap
* Portland/Hive Cascadia: http://github.com/Saallen/Mentor-dev-doc-hub 
* HIve NYC: https://github.com/MozillaHive/HiveNYC.org
* Mozilla HIve: https://github.com/MozillaHive


### How about filing a bug?

If you're trying to file a bug on a website, it's a good idea to look for a repo with the name of the website under the mozilla org.  So, if you see a bug in **build.webmaker.org**, you can file a bug in [github.com/mozilla/**build.webmaker.org**/issues/new](https://github.com/mozilla/build.webmaker.org/issues/new)

Good candidates:

* [webmaker.org](https://github.com/mozilla/webmaker.org/issues)
* [the mobile webmaker app](https://github.com/mozilla/webmaker-app/issues)
* [build.webmaker.org](https://github.com/mozilla/build.webmaker.org/issues)
* [book.webmaker.org (this book!)](https://github.com/mozilla/book.webmaker.org/issues)

When in doubt, file under [webmaker.org](https://github.com/mozilla/webmaker.org/issues), we'll figure it out.


## <a name="whatsplan"></a>What's the plan repo?

It's the repo where we track the initiatives to resource and schedule them in heartbeats.  [Read](heartbeats/intro.html) all about it.

## <a name="heartbeats"></a>What are heartbeats again?

[Read](heartbeats/intro.html) all about it.

## <a name="wherenew"></a>Where should I create a repo?

Software generally should end up under the `mozilla` org, but it may make sense to start exploring in your personal repo until you're ready for collaborators.  We can transfer a repo from an individual to an org when that's needed (sometime after rough draft and before it shows up in a heartbeat, and well before it shows up in production).

Repos that are primarily used to either house documents or just issues can be in any of the orgs we have (`mozilla`, `MozillaFoundation`, `MozillaHive`).  Creating a new 'org' means you get a space that random people won't find easily, and that contributors won't find if they're not clued in, so we generally don't recommend it.

## <a name="more"></a>Unanswered questions


* Where's my "dashboard?" Where can I see all the tickets assigned to me? [this could move to FAQ]
* Updated documentation on all this is coming soon! Webmaker process conventions will be codified in the Design and Engineering handbooks https://github.com/MozillaFoundation/Mofo-Design-Handbook and https://github.com/MozillaFoundation/MoFo-Engineering-Handbook
* Want more? Join GitClub. Join GitClub every wednesday. It will go into far more detail on Git, including things like pull requests, forking, branches, etc. 
 https://etherpad.mozilla.org/gitclub 
* How do I mark tickets as "confidential?"

