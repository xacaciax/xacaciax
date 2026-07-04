Here are some things I built or contributed to significantly, most recent first:

## 2024 to present

- [Teacher App on Web](https://teachers.hopestreetgroup.org/quests)
- [Teacher app v1 prototype](https://app.hopestreetgroup.org/dashboard)
- [Hope Street for students on web](https://discover.hopestreetgroup.org/)
- [Annual Slack Evals](https://github.com/xacaciax/slack-openai-evaluations) before Claude CoWork, built this to assist in yearly reflections and perf reviews
- [Hope Street for students on Android](https://play.google.com/store/apps/details?id=org.hopestreetgroup.hope_st&hl=en_US) 
- [Hope Street for students on iOS](https://apps.apple.com/us/app/hope-street/id6447386859)
- [Hope Street Group Main](https://www.hopestreetgroup.org/app) for product.  

Learn more about our product evolution [here](todo). We also have an event driven synchronous processing system that runs on AWS using SQS and Lamda that feeds our analytics data layer for both internal and external use. 

- [Ikigai Advisor](https://github.com/xacaciax/ikigai), take home turned personal project, playin' around with the openai api and dynamic inline chat ui elements

## 2023 at Edily as a sole mobile engineer

No longer in the app stores, but you can see it on [Product Hunt](https://www.producthunt.com/products/edily?launch=edily).

"Like TikTok for educational content." This is where I first worked on video-heavy mobile infra. I learned to handle large video files in a live feed, then went deeper into Flutter's [architecture](https://docs.flutter.dev/resources/architectural-overview) building cross-platform push notifications: sending and receiving across both APNs and FCM. From there I started working back into the stack: editing our infrastructure-as-code for Lambda, reading CloudWatch logs to debug in production, and using DynamoDB to ship full-stack features end to end.

## 2021 to 2023 at Uptrust as a sole mobile engineer

- [Uptrust (Android)](https://play.google.com/store/apps/details?id=com.uptrust.enduser&hl=en_US)
- [Uptrust (iOS)](https://apps.apple.com/us/app/uptrust/id1499549450)
- [Uptrust for Staff (Android)](https://play.google.com/store/apps/details?id=co.uptrust.staff_mobile&hl=en_US)
- [Uptrust for Staff (iOS)](https://apps.apple.com/us/app/uptrust-staff/id1544021735)

Uptrust's mission is reducing unnecessary incarceration. They help justice-involved individuals stay connected to court obligations through automated reminders, so people don't end up back in jail over a missed appointment instead of a new crime.

I came in knowing basically nothing and left as the person who owned mobile. Along the way I learned to handle streaming data (building a video chat feature), how mobile deployment actually works end to end, and how to use observability to inform product decisions, not just debug crashes. A contracting senior engineer, our staff-web engineer, and genuinely excellent docs, [Effective Dart](https://dart.dev/effective-dart) in particular, taught me why the opinions existed: why models, why strong typing, why null safety. That was the first time style guides clicked for me as reasoning tools, not just formatting rules.

I also wrote my first PRD, mostly because someone had to. I liked digging through user interviews for patterns, then turning around and building what they pointed to. I implemented the resulting feature myself, Sending Images, learning to use S3 and pre-signed URLs to store and serve images along the way.