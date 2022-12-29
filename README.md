# MuslimSoulmates

**MuslimSoulmates** is a mobile-ready, real-time social app incorporating video profiles and one-to-one video chat.

## Tech stack

Read *mix.exs* and */assets/package.json* to see the dependencies required.

Uses Phoenix 1.7.

## Putative Deployment Infrastructure
- https://bunny.net/ for video storage and delivery via CDN
- Twilio for WebRTC.
- AWS for profile img storage.

## To run
To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.


## Useful links - configuration of app to use binary ids, esbuild setup etc.
- https://bernheisel.com/blog/ecto_changeset_tips

- https://cloudless.studio/wrapping-your-head-around-assets-in-phoenix-1-6

- https://sergiotapia.com/phoenix-160-liveview-esbuild-tailwind-jit-alpinejs-a-brief-tutorial