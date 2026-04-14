# Integrations

Summary of third-party scripts and embeds detected from fetched HTML.

| id | name | category | confidence |
| --- | --- | --- | --- |
| google-tag-manager | Google Tag Manager | analytics | high |
| facebook-pixel | Facebook / Meta pixel | advertising | medium |
| youtube-embed | YouTube embed | video | medium |
| google-analytics-gtag | Google Analytics (gtag) | analytics | medium |
| vimeo-embed | Vimeo embed | video | medium |

## google-tag-manager

**Google Tag Manager** (analytics)

Detected from inline HTML / script references.

**Evidence**

- Script samples:
  - `https://www.googletagmanager.com`
  - `https://www.googletagmanager.com/ns.html?id=GTM-TVD6SGL3`
  - `https://www.googletagmanager.com/gtm.js?id=`
- Patterns:
  - `googletagmanager.com`


## facebook-pixel

**Facebook / Meta pixel** (advertising)

Detected from inline HTML / script references.

**Evidence**

- Patterns:
  - `connect.facebook.net`


## youtube-embed

**YouTube embed** (video)

Detected from inline HTML / script references.

**Evidence**

- Patterns:
  - `youtube.com/embed|youtu.be`


## google-analytics-gtag

**Google Analytics (gtag)** (analytics)

Detected from inline HTML / script references.

**Evidence**

- Patterns:
  - `gtag(`


## vimeo-embed

**Vimeo embed** (video)

Detected from inline HTML / script references.

**Evidence**

- Patterns:
  - `player.vimeo.com`

