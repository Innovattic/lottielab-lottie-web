
This repository is a fork of https://github.com/lottielab/lottie-web, which is in turn a fork of https://github.com/airbnb/lottie-web.

It's sole purpose is to serve as a workaround for https://github.com/airbnb/lottie-web

Usage in package.json:

```json
{
  "dependencies": {
    "lottie-web": "git+https://git@github.com/Innovattic/lottielab-lottie-web.git#04af782a500593d88172a26dc2b560ee98f02c98"
  },
  "overrides": {
    "lottie-web": "$lottie-web"
  }
}
```
