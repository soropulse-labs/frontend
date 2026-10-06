# Deployment

Netlify builds with `npm run build` and publishes `dist`. Copy `.env.example` to the hosting environment. Set `VITE_DATA_MODE=demo` until a verified same-site or supported proxy topology exists for the backend. A production live deployment must verify OAuth redirects, SameSite cookies, CORS, and CSRF together; do not weaken authentication to work around them.
