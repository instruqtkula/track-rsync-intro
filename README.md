# Rsync Intro --- An Instruqt Example Track

This is an example three challenge Instruqt track, designed
to show off the basics of how a track works.

## Requirements

You must have a [Team Secret](https://docs.instruqt.com/sandboxes/runtime/secrets) called
`IGGYS_SSH_PRIVATE_KEY_BASE64` which was created from the output of running

```
TMP=$(mktemp -d); ssh-keygen -t ed25519 -f "${TMP}/id_ed25519" -N "" >/dev/null; base64 -b 0 < "${TMP}/id_ed25519"; rm -rf "${TMP}"
```

**NOTE**: Your variant of `base64` or equivalent may have different command-line flags,
the output must have no line breaks.
