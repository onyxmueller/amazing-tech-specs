# Google Cast Specifications
Authors: Onyx Mueller\
Team: My Awesome Team\
Last Modified: 01.01.70\
Product Spec: https://link.to.product.spec \
JIRA Epic: https://link.to.jira.epic

## Table of Contents

- [Summary](#summary)
- [Background](#background)
- [Objective](#objective)
  - [Goals](#goals)
  - [Non-Goals](#non-goals)
- [Plan](#plan)
- [Debug/Testing](#debugtesting)
- [Measurements](#Measurements)
- [Security, Privacy, & Risks](#security-privacy--risks)
- [Other Considerations](#other-considerations)
- [Milestones](#milestones)
- [Open Questions](#open-questions)

## Summary

Remote media protocols like Google Cast enable users to stream video to the biggest screens in the home.

## Background

Cast allows mobile & web apps to "cast" video content to Cast-ready devices such as Chromecasts, TVs with Chromecast built-in, & Smart Displays. Since the introduction, Cast technology has become wildly popular. Having a Cast-capable app has become an expectation for video-centric apps.

## Objective

### Goals

* Provide another screen to mobile (Android/iOS) users to watch video.
* Increase video consumption.
* Integrate Google Cast SDK into mobile (Android/iOS) apps.

### Non-Goals

* Integration of Apple's Airplay.
* Integration Amazon's Fling SDK.
* Support for audio-only casting.

## Implementation

**Note: This section has purposely not been filled out.**

Use this section to describe out how this feature will evolve from product/design requirements into a viable project/service/feature/etc. This should include things like:

* APIs/Data references and connections
* Payload examples
* Breakdown of how to “connect the dots” to in UI/designs
* Recommended "game plan"
* Platform-specific details (e.g., Web vs. Mobile vs. Connected)
* Visual documentation

This will most likely be the longest and most in-depth section of the spec.

## Debug/Testing

Provide a means to change switch between staging and production Cast receiver app IDs within the mobile apps.

## Measurements

* Increase video consumption by 10% within 3 months of launch.

## Security, Privacy, & Risks

Beginning with iOS 14, applications that scan for devices on the local network require a permission to do so.

## Other Considerations

Integration of Cast SDK into Web was considered. Decided not to implement because low return in investment.

## Milestones

* Cast receiver development complete: August 1st
* Cast sender (Android/iOS) development complete: August 15th
* QA complete: Oct 1st

## Open Questions

How will we introduce Cast functionality to users?
