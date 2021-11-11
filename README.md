# Hack PTY

We have included a PTY recording of a recorded session recording. 

1. Install [tsh](https://goteleport.com/docs/installation/)
2. Clone this repo
3. Play Session `tsh play session.tar` or `tsh play --format=json session`

## Hackathon Ideas.

- An embeddable player
- Adding annotations
- Infographic of commands
- Embedding ePBP data with raw input. `tsh play --format=json session.tar | jq '.event'`

