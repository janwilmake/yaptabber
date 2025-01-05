Yaptabber uploads your screen, video, and mic to your s3 whenever there's sound detected, with a minimum length of 10 seconds.

This is a proof of concept but could become a really useful tool I'd say, as it can be connected with any plugins using AI. Open to collaborate on this!

How to use:

1. `brew install ffmpeg`
2. `brew install sox`
3. `npx yaptabber --endpoint https://yours3endpoint.com --key S3_KEY --secret S3_SECRET --region S3_REGION`

Then go to yaptabber.com (or use index.html) and view your synced audio/video/screen recordings :D

~~ Happy Yapping!
