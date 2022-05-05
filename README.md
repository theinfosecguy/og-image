# BugBlogs OG Image Generator ⚡

Serverless service that generates dynamic Open Graph images for BugBlogs.

For each keystroke, headless chromium is used to render an HTML page and take a screenshot of the result which gets cached.

See the image embedded in the tweet for a real use case.

[![Sample Image](https://og.bugblogs.tech/Hey!%20I'm%20using%20BugBlogs%20%26%20I'm%20loving%20it!.png?theme=dark&md=1&fontSize=75px&images=https%3A%2F%2Fucarecdn.com%2Fcdc7a226-83a7-434d-95b6-66c93d276c24%2F)](https://bugblogs.tech)

## How to setup? 🚀

```
### Start local development server
vercel dev

### Build for production
tsc -p api/tsconfig.json && tsc -p web/tsconfig.json

### Deploy to Vercel
vercel deploy

```

## 🙌 Acknowledgement

Credit where credit is due. This started as a forked repo from [Railway's OG image generator](https://github.com/vercel/og-image). It is modified to suit the needs of [BugBlogs](https://bugblogs.tech).

![](https://ucarecdn.com/df49f525-7c66-4000-b9fa-f79d936aa697/)
