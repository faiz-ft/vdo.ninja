---
description: Audio capture device to select N-number of audio channels
---

# \&channelcount

Sender-Side Option! ([`&push`](push.md))

## Aliases

* `&ac`

## Options

| Value             | Description                            |
| ----------------- | -------------------------------------- |
| 2                 | Audio capture device set to 2 channels |
| 6                 | Audio capture device set to 6 channels |
| (integer value X) | Audio capture device set to X channels |

## Details

`&channelcount=N` tells the audio capture device explicitly to select N-number of audio channels. This shouldn’t be needed often, but may help with debugging or advanced use canses. Setting [`&stereo=0`](../general-settings/stereo.md) will set `&channecount=1` by default.

## Related

{% content-ref url="../advanced-settings/view-parameters/and-channeloffset.md" %}
[and-channeloffset.md](../advanced-settings/view-parameters/and-channeloffset.md)
{% endcontent-ref %}