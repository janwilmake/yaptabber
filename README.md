Yaptabber uploads your screen, video, and mic to your s3 whenever there's sound detected, with a minimum length of 10 seconds.

How to use:

1. `brew install ffmpeg`
2. `brew install sox`
3. `npx yaptabber --endpoint https://yours3endpoint.com --key S3_KEY --secret S3_SECRET --region S3_REGION`