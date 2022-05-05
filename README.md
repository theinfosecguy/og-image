# BugBlogs OG Image Generator ⚡

Serverless service that generates dynamic Open Graph images for BugBlogs.

For each keystroke, headless chromium is used to render an HTML page and take a screenshot of the result which gets cached.

See the image embedded in the tweet for a real use case.

[![Sample Image](https://og.bugblogs.tech/api/image?fileType=png&layoutName=Blog&Theme=Dark&Title=Hey%21+I%27m+using+BugBlogs+%26+I%27m+loving+it%21&Author=Keshav+Malik)](https://bugblogs.tech)

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
