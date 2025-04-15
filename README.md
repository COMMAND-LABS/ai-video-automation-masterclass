# TLDR

A.I. Video Automation MASTERCLASS with Make.com, OpenAI, & JSON2Video

##

By the end of this video you’re going to understand EXACTLY what A.I. Video Automation is and how to leverage it for yourself, your company, and your brand!

The primary platforms we will be using are…

1. Make.com
    1. You should be able to get everything done with the FREE plan
    2. BUT if you run into any issues with the FREE plan try the CORE plan (which is $11/month) or the PRO plan (which is $19/month)
    3. FYI: You can cancel your Make.com subscription at any time
2. The OpenAI Platform
    1. You will need to add some credits so add like $5 or whatever the minimum allowed amount is
    2. You can always purchase more credits later as needed
3. JSON2Video
    1. JSON2Video comes with some FREE credits on sign up but after your FREE credits run out, you’ll need to likely spend $49.95
    2. One JSON2Video credit gets you about 1 second of HD video AND 1/4 of a second when generating 4k video
    3. So, to stretch your free credits, be sure to generate very short videos ie: while on the free plan, make sure each video you generate is max like 2-3 seconds. That way you should be able to get through this video without paying the $49.95.

Throughout this MASTERCLASS we will be using other platforms as well but these other platforms will be a bit more flexible

For the business folks watching, what we’re about to do will definitely be challenging if you’re new to A.I. Automation, BUT, at the end of the rainbow lies a new skill that will allow you to scale your efforts across several use cases including…

- Social Media Marketing
- Personalized Sales Outreach
- Personalized Onboarding
- As well as delivering presentational or informative information to your colleagues or customers

And, for the creatives watching, strap in cuz you’re about to learn another amazing tool for expressing your creativity at scale!

## Flow of sections

- Part 1 - Pre-reqs & Make.com
- Part 2 - JSON
- Part 3 - JSON2Video Elements
    - movie.json
    - audio
    - video
    - voice
    - image
    - subtitles
    - html
    - text
    - component
    - audiogram
- Part 4 - Scenes
- Part 5 - A.I. Video Automation

## Test media assets

Check out the `test_media_assets` folder

## PRO TIP - Customizing the transcription

- https://json2video.com/docs/v2/api-reference/json-syntax/element/subtitles

```sh
export JSON2VIDEO_PROJECT_ID=GbgYcdA5a4SbClFy
export JSON2VIDEO_API_KEY=<API_KEY_HERE>
curl --location --request GET "https://api.json2video.com/v2/movies?project=$JSON2VIDEO_PROJECT_ID" \
--header "x-api-key: $JSON2VIDEO_API_KEY"
```
