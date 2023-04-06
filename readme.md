# diana config

the goal of this repo is to fully ansible-ise the setup and config of my media
server, `diana`.

## Troubleshooting

- i have discovered that it can hang on the `apt` step of installing jellyfin
if this happens, reboot the box and rerun the ansible against it.
