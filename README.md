# jarbas_online
self hosted microservices for demo purposes and personal usage, might get taken down any time but feel free to use them while they last

## OVOS STT Plugins

microservices running [ovos-stt-server](https://github.com/OpenVoiceOS/ovos-stt-http-server) 

| plugin | lang | url | source | docker |
|---|---|---|---|---|
| chromium  | all | https://stt.jarbasai.online | [github](https://github.com/OpenVoiceOS/ovos-stt-plugin-chromium) | [ghcr.io/openvoiceos/google-stt-proxy](https://github.com/OpenVoiceOS/pkgs/container/google-stt-proxy) |
| vosk | en | https://vosk.jarbasai.online | [github](https://github.com/OpenVoiceOS/ovos-stt-plugin-vosk) | [ghcr.io/openvoiceos/vosk-stt-http-server](https://github.com/OpenVoiceOS/pkgs/container/vosk-stt-http-server) |
| pocketsphinx | en | https://pocketsphinx.jarbasai.online | [github](https://github.com/OpenVoiceOS/ovos-stt-plugin-pocketsphinx) | [ghcr.io/openvoiceos/pocketsphinx-stt-http-server](https://github.com/OpenVoiceOS/pkgs/container/pocketsphinx-stt-http-server) |

## OVOS TTS Plugins

microservices running [ovos-tts-server](https://github.com/OpenVoiceOS/ovos-tts-server)

| plugin | lang | url | source | docker |
|---|---|---|---|---|
| glados | en | https://glados.jarbasai.online | [github](https://github.com/NeonGeckoCom/neon-tts-plugin-glados) | [ghcr.io/openvoiceos/glados-tts](https://github.com/orgs/OpenVoiceOS/packages/container/package/glados-tts) |
| mimic  | en | https://mimic.jarbasai.online | [github](https://github.com/OpenVoiceOS/ovos-tts-plugin-mimic) | [ghcr.io/openvoiceos/mimic](https://github.com/orgs/OpenVoiceOS/packages/container/package/mimic) |
| pico  | en, de, es, fr, it | https://pico.jarbasai.online | [github](https://github.com/OpenVoiceOS/ovos-tts-plugin-pico) | [ghcr.io/openvoiceos/pico](https://github.com/orgs/OpenVoiceOS/packages/container/package/pico) |
| S.A.M.  | en | https://sam.jarbasai.online | [github](https://github.com/OpenVoiceOS/ovos-tts-plugin-sam) | [ghcr.io/openvoiceos/sam](https://github.com/orgs/OpenVoiceOS/packages/container/package/sam) |
| espeak-ng  | all | https://espeak.jarbasai.online | [github](https://github.com/OpenVoiceOS/ovos-tts-plugin-espeakng) | [ghcr.io/openvoiceos/espeakng](https://github.com/orgs/OpenVoiceOS/packages/container/package/espeakng) |
| BeepSpeak  | all | https://r2d2.jarbasai.online | [github](https://github.com/OpenVoiceOS/ovos-tts-plugin-beepspeak) | [ghcr.io/openvoiceos/beepspeak-tts-server](https://github.com/orgs/OpenVoiceOS/packages/container/package/beepspeak-tts-server) |


## Microservices

other services that don't fit any existing category

| description | url | source |
|---|---|---|
| OVOS local backend - selene alternative | https://home.jarbasai.online | https://github.com/OpenVoiceOS/OVOS-local-backend |
| Snowboy wake word trainer | https://snowboy.jarbasai.online | https://github.com/seasalt-ai/snowboy |
| Larynx TTS | https://larynx.jarbasai.online | https://github.com/rhasspy/larynx |
| Mimic3 TTS | https://mimic3.jarbasai.online | https://github.com/MycroftAI/mimic3 |



## Frontends

These are alternative frontends to access existing platforms
Using these will protect you from browser fingerprinting, cookies etc. but your IP address may still leak

| description | url | source |
|---|---|---|
| invidious - youtube alternative frontend | https://invidious.jarbasai.online | https://github.com/iv-org/invidious |
| nitter - twitter alternative frontend | https://nitter.jarbasai.online | https://github.com/zedeus/nitter |
| teddit - reddit alternative frontend | https://teddit.jarbasai.online | https://github.com/teddit-net/teddit |
| libreddit - reddit alternative frontend | https://libreddit.jarbasai.online | https://github.com/spikecodes/libreddit |
| proxitok - tiktok alternative frontend | https://proxitok.jarbasai.online | https://github.com/pablouser1/ProxiTok |
| bibliogram - instagram alternative frontend | https://bibliogram.jarbasai.online | https://github.com/Booteille/bibliogram |
| whoogle - google search alternative frontend | https://whoogle.jarbasai.online | https://github.com/benbusby/whoogle-search |
| wikiless - wikipedia alternative frontend | https://wikiless.jarbasai.online | https://codeberg.org/orenom/Wikiless |
| minimalpedia - wikipedia alternative react frontend | https://minimalpedia.jarbasai.online | https://github.com/vantezzen/minimalpedia |
| simply translate - google translate alternative frontend | https://translate.jarbasai.online | https://codeberg.org/SimpleWeb/SimplyTranslate-Web |
