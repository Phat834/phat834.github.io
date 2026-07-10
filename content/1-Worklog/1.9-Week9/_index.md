---
title: "Week 9 Worklog"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Objectives for Week 9:
* Successfully visualize and implement the audio data processing flow from Mobile through Amazon S3 and Amazon SQS.
* Define and configure the speech-to-text conversion workflow utilizing the intelligent Amazon Transcribe service.
* Ensure the converted data is securely and integrally stored within the Amazon RDS system.

### Tasks for Week 9:

| Day | Task | Start Date | End Date | References |
| :---: | :--- | :---: | :---: | :--- |
| 2 | Set up the gateway to push audio files from the mobile application to Amazon S3 storage. | 2026-06-15 | 2026-06-16 | [AWS SDK for Mobile Audio Upload](https://docs.aws.amazon.com/s3/) |
| 3 | Configure S3 Event Notifications to trigger and push messages into the Amazon SQS queue. | 2026-06-16 | 2026-06-17 | [Amazon SQS Developer Guide](https://docs.aws.amazon.com/sqs/) |
| 4 | Research the mechanism for catching SQS events to invoke recognition processing via Amazon Transcribe. | 2026-06-17 | 2026-06-18 | [Amazon Transcribe Speech-to-Text](https://docs.aws.amazon.com/transcribe/) |
| 5 | Program the module to receive the text results from Transcribe and clean up the data formatting. | 2026-06-18 | 2026-06-19 | [Data Processing in Node.js](https://nodejs.org/) |
| 6 | Write queries to store the final text results into database tables on Amazon RDS. | 2026-06-19 | 2026-06-21 | [RDS Data Persistence Guides](https://docs.aws.amazon.com/rds/) |

### Week 9 Achievements:
* **AWS Service Operation:** Established a seamless service chain including Amazon S3, SQS, Transcribe, and RDS operating in perfect synchronization.
* **Technical Skills:** Successfully built an Event-driven Architecture to process multimedia files in a cloud environment.
* **Knowledge Foundation:** Mastered the application of artificial intelligence solutions (Speech-to-Text AI) to real-world problems, significantly enhancing system efficiency.