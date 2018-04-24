# How to organise a talk based meet up

## Introduction

The purpose of this document is to provide a checklist and timeline for organising talk based meetups. This is based around the process used by the [London Rust User Group][link_lrug].

The expected audience for this document are people who are new to setting up meetups or organising this type of format.

Where relevant we will cite actual examples using the names of services or organisations (Skillsmatter, meetup.com, etc) that we currently use at the London user group.

Finally don't forget to:

- register your group using this google [form][link_signup_form] 
- join the [google group][link_google_group] for Rust meetups/user groups.

## Timeline / Checklist

- 4 weeks to go
  - Create a [new issue][link_demo_issue] in the [talks][link_talks_repo] repo. Placing your events in this repo, allows other meetup organisers to see which speakers are active.
  - Confirm speakers and get the following from each of them:
    - Speaker's bio
    - Title of talk
    - Synopsis of talk
    - Duration of talk - Generally talks fall under the following category based on their duration:
      - 5-15m lightning
      - 25m-45m regular talks + 5-10m Q&A
      - &gt; 60m long talks - it's worth advising the speaker to avoid talks of this duration unless some form of continual Q&A or audience participation takes place.
  - Share this with the venue if relevant. Our hosts Skillsmatter have their own website and newsletter which provides free advertisement. It's often helpful to gain a similar relationship with meetup's regular venue, as they will often have a bigger audience reach.
  - Add to meetup/group event page and enable RSVP if you have the capability.
- 3 weeks
  - Send out reminders via meetup, twitter or other social media.
- 2 weeks
  - Add lightning speakers
  - Send out reminders via meetup, twitter or other social media.
- 1 week to go
  - Send a follow up email with speakers:
    - Send details of location to venue, suggested route from nearest bus/train station.
  - Send out reminders via meetup, twitter or other social media
- On the day
  - Decide running order of speakers

## Time keeping

If you have more than one speaker, time keeping is essential. Failure to do so could result in other speakers having to short their talks or even worse lose their slot, because your venue has limited hours to host meetups i.e. 6pm-10pm.

Ensure that all speakers are aware of this limitation.

The recommended approach to advise the speaker of time left is to have warnings at 5 minute intervals. Start the count down when there are only 15 minutes left for the talk. 

Tip: you can tell the speaker through the use of signs/placard with the time remaining.
Tip: telling the speaker of the time remaining verbally if you are near to the speaker i.e. front row as most people including the recording equipment won't pick this up. 

Also don't forget to time keep the Q & A  section too!

## Hints and tips

### Automation

- Simplify your workflow for organising meetups by making use of [issue templates][link_gh_templates]. Templates can generate a standardised checklist. The use of [query parameters][link_gh_query_params] can also add labels and a title. An example template can be found [here][link_lon_talks_template].

### Venues

- Often companies that use Rust will provide a venue for free. There's a list of companies on the [Rust front page][link_rust_friends], some of these companies might be near to your city.

- Pre-book venues in quarters i.e. January to March, April to June, etc.

- If you attend other technical meetups, try booking their venue.

### Speakers

- If you're struggling to find local speakers, why not try a remote talk. These are trickier to setup, but can sometimes give you the access to speakers who wouldn't ordinarily be available because of your location.

#### Advertisement

- Add your events to the Rust community calendar, will automatically add you to [This Week in Rust][link_twir] (our weekly newsletter for all things Rust). You can get access by filling out the google [form][link_signup_form] to register your meetup.
- The Rust [@rustlang][link_rust_twitter] twitter account will usually retweet any tweets with the #rustlang hashtag, so use this to advertise your meetup.
- Also posting to our favourite Rust forum [users.rust-lang.org][link_urlo] is a great way to advertise too! Use the **announcements** category to gain maximum reach.

[link_lrug]: https://www.meetup.com/Rust-London-User-Group/
[link_rust_twitter]: https://twitter.com/rustlang
[link_urlo]: http://users.rust-lang.org
[link_signup_form]: https://docs.google.com/forms/d/e/1FAIpQLSf52YXGhqBaHtCXtVna4iHYMK7IQaTqUW6V-ztsZC8C2TBInQ/viewform
[link_google_group]: https://groups.google.com/forum/#!forum/rust-meetup-organizers
[link_rust_friends]: https://www.rust-lang.org/en-US/friends.html
[link_talks_repo]: https://github.com/rust-community/talks
[link_demo_issue]: https://github.com/rust-community/talks/issues/new?template=london-talks.md&title=LDN+:+Month+Year&labels=LDN,help+wanted,request
[link_gh_templates]: https://help.github.com/articles/creating-an-issue-template-for-your-repository/
[link_gh_query_params]: https://help.github.com/articles/about-automation-for-issues-and-pull-requests-with-query-parameters/
[link_lon_talks_template]: https://github.com/rust-community/talks/blob/master/ISSUE_TEMPLATE/london-talks.md
[link_twir]: https://this-week-in-rust.org