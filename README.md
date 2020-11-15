# Podcast Guide
A Guide For Building A Successful Podcast
![Podcast Guide](https://user-images.githubusercontent.com/17960677/99179708-37113280-2746-11eb-856c-4fd5f70675ef.png)

Creating a successful Podcast is a challenging Task, But, once you know the steps to create one, you can only focus on creating content. This guide will help you in creating a successful Podcast.

## Podcast Hosting

The first step to create a Podcast is finding a suitable hosting.  

An ideal hosting should provide a lots of features, should be scalable and easy to transfer if you ever wish to migrate.  

Based on These Criteria, The following Podcast Hosting Services might be useful.  

* Free
    * [Anchor.fm](https://anchor.fm)
    * [Substack](https://substack.com)
* Paid (Partially)
    * [Whooshkaa](https://www.whooshkaa.com/)
    * [HubHopper](https://hubhopper.com/)
* Paid (Fully)
    * [Blubrry](https://blubrry.com/)
    * [Megaphone.fm](https://www.megaphone.fm/)
    * [AudioBoom](https://audioboom.com/)

The Advantage of using these services is that they include all features required to host a podcast.  

### Self-hosting

You can otherwise do Self-hosting which would require you to host the Audio Files Somewhere.  

Hosting Audio Files is a difficult task as any hosting provider has a Bandwidth limit. So, just a 50 MB episode will exhaust 100 GB Bandwidth in just 2000 Plays which is not scalable.  

Hosting Audio files requires specific type of services, which are rarely free. If you can find one, that's great. Then you will have to create a Podcast Feed manually or through some tool. 

## Submitting To Podcast Directories

Either you Host podcast on some Service or do Self-hosting, You need an RSS Feed.  

This RSS Feed contains metadata related to your podcast, The episodes and their metadata and Links to the Audio files.  

An Example RSS Fees would look something like this.  

```xml
<?xml version="1.0" encoding="UTF-8"?>
<rss version="2.0"
    xmlns:googleplay="http://www.google.com/schemas/play-podcasts/1.0"
    xmlns:itunes="http://www.itunes.com/dtds/podcast-1.0.dtd">
  <channel>
    <title>Dafna's Zebra Podcast</title>
    <googleplay:owner>dafna@example.com</googleplay:owner>
    <googleplay:author>Dafna</googleplay:author>
    <description>A pet-owner's guide to the popular striped equine.</description>
    <googleplay:image href="https://www.example.com/podcasts/dafnas-zebras/img/dafna-zebra-pod-logo.jpg"/>
    <language>en-us</language>
    <link>https://www.example.com/podcasts/dafnas-zebras/</link>
    <item>
      <title>Top 10 myths about caring for a zebra</title>
      <description>Here are the top 10 misunderstandings about the care, feeding, and breeding of these lovable striped animals.</description>
      <pubDate>Tue, 14 Mar 2017 12:00:00 GMT</pubDate>
      <enclosure url="https://www.example.com/podcasts/dafnas-zebras/audio/toptenmyths.mp3"
                 type="audio/mpeg" length="34216300"/>
      <itunes:duration>30:00</itunes:duration>
      <guid isPermaLink="false">dzpodtop10</guid>
    </item>
    <item>
      <title>Keeping those stripes neat and clean</title>
      <description>Keeping your zebra clean is time consuming, but worth the effort.</description>
      <pubDate>Fri, 24 Feb 2017 12:00:00 GMT</pubDate>
      <enclosure url="https://www.example.com/podcasts/dafnas-zebras/audio/cleanstripes.mp3"
                 type="audio/mpeg" length="26004388"/>
      <itunes:duration>22:48</itunes:duration>
      <guid>dzpodclean</guid>
    </item>
  </channel>
</rss>
```

As you can see, this feed contains an email field, This email can be used to verify the ownership of the podcast. In self-hosting, you put your email there. On Hosting Services, they use their email which you can access.  

Thus, All you need to verify ownership of your podcast is RSS Feed Link and access to the email.  

### What are Podcast Directories?

Podcast Directories are services that fetch data about podcasts and Some of them even allow you to play them.  

For example, Apple podcast is the most popular Podcast Directory.  
