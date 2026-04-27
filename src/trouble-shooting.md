# Troubleshooting Guide

Use the symptom categories below to identify your problem, then follow the link to the fix in [Problem Solving](./problems.md).

---

## 1. Hardware / Power

**Something has no lights / appears completely off**

| What is off? | Go to |
|---|---|
| ATEM switcher | [ATEM switcher is powered off](./problems.md#atem-switcher-is-powered-off-no-lights) |
| Camera controller | [The camera controller is powered off](./problems.md#the-camera-controller-is-powered-off-no-lights) |

---

## 2. Display / Monitor

**A screen is black or shows nothing**

| What is black? | Go to |
|---|---|
| Multiview monitor | [The multiview monitor is black](./problems.md#the-multiview-monitor-is-black) |
| Streaming PC display | [The streaming PC display is black](./problems.md#the-streaming-pc-display-is-black) |

---

## 3. ATEM Switcher

**The ATEM switcher is behaving unexpectedly**

| Symptom | Go to |
|---|---|
| Preview / programme buttons lit blue instead of red/green | [ATEM switcher preview and programme buttons not working](./problems.md#atem-switcher-preview-and-programme-buttons-not-working) |
| ATEM software cannot connect to the switcher | [Cannot connect ATEM software control application to the ATEM switcher](./problems.md#cannot-connect-atem-software-control-application-to-the-atem-switcher) |
| Video is moving at the wrong speed (too fast) on YouTube | [Framerate problems](./problems.md#framerate-problems) |

---

## 4. Cameras

**A camera is not visible or cannot be controlled**

| Symptom | Go to |
|---|---|
| One or more cameras missing from the multiview display | [The video of a camera does not appear on the multiview display](./problems.md#the-video-of-a-camera-does-not-appear-on-the-multiview-display) |
| Camera controller joystick / buttons have no effect | [The camera controller fails to operate the cameras](./problems.md#the-camera-controller-fails-to-operate-the-cameras) |

---

## 5. Encoder / Stream

**The stream is not reaching YouTube or is not starting**

Start here: is the STREAM button on the NVS-34 encoder lit **continuously red**?

```text
STREAM button state
├── Not lit (white) or flashing red
│   ├── Check encoder input source → see "The encoder stream button flashes red" in problems.md
│   └── Reboot the encoder → see "No stream appears on the YouTube preview" in problems.md
└── Lit continuously red but stream still missing
    └── Check encoder settings → see "YouTube preview says encoder is not configured properly" in problems.md
```

---

## 6. YouTube / Streaming Platform

**Problems visible on the YouTube side**

| Symptom | Go to |
|---|---|
| No stream in the YouTube preview at all | [No stream appears on the YouTube preview](./problems.md#no-stream-appears-on-the-youtube-preview) |
| Stream does not appear in YouTube preview despite encoder running | [The live stream does not appear in the preview on YouTube](./problems.md#the-live-stream-does-not-appear-in-the-preview-on-youtube) |
| YouTube says "encoder not configured properly" | [YouTube preview says encoder is not configured properly](./problems.md#youtube-preview-says-encoder-is-not-configured-properly) |
| "Go live" button is greyed out | [The "go live" icon is greyed out on YouTube](./problems.md#the-go-live-icon-is-greyed-out-on-youtube) |
| YouTube shows "no data" or "poor connection" | [YouTube shows "no data" or "poor connection"](./problems.md#youtube-shows-no-data-or-poor-connection) |
| YouTube buffering / stream fails mid-service | [YouTube connection problems](./problems.md#youtube-connection-problems) |

---

## 7. Internet

**The streaming PC cannot reach the internet, or the whole site has lost internet**

| Symptom | Go to |
|---|---|
| Streaming PC only: no internet access | [The internet is not accessible from the live streaming PC](./problems.md#the-internet-is-not-accessible-from-the-live-streaming-pc) |
| Whole site has lost internet | [The internet is not accessible from the live streaming PC](./problems.md#the-internet-is-not-accessible-from-the-live-streaming-pc) (check camera controller IP conflict) |

---

## 8. Audio

**Sound quality is poor or volume is too low on the stream**

→ [Poor sound quality on the live stream](./problems.md#poor-sound-quality-on-the-live-stream)

---

## 9. Graphics / Overlays

**Song words or the Christ Church logo are not displaying correctly**

| Symptom | Go to |
|---|---|
| Song words not displaying | [Song words not displayed](./problems.md#song-words-not-displayed) |
| Song words have no black outline | [Song words not outlined in black](./problems.md#song-words-not-outlined-in-black) |
| Christ Church Winchester logo not visible | [Christ Church Winchester logo not visible](./problems.md#christ-church-winchester-logo-not-visible) |

---

## Quick Reference: All Problems

| Problem | Section in problems.md |
|---|---|
| ATEM switcher has no lights | [Link](./problems.md#atem-switcher-is-powered-off-no-lights) |
| Multiview monitor is black | [Link](./problems.md#the-multiview-monitor-is-black) |
| ATEM preview/programme buttons not working | [Link](./problems.md#atem-switcher-preview-and-programme-buttons-not-working) |
| Cannot connect ATEM software to switcher | [Link](./problems.md#cannot-connect-atem-software-control-application-to-the-atem-switcher) |
| Camera controller has no lights | [Link](./problems.md#the-camera-controller-is-powered-off-no-lights) |
| Streaming PC display is black | [Link](./problems.md#the-streaming-pc-display-is-black) |
| No stream on YouTube preview | [Link](./problems.md#no-stream-appears-on-the-youtube-preview) |
| YouTube says encoder not configured properly | [Link](./problems.md#youtube-preview-says-encoder-is-not-configured-properly) |
| Camera missing from multiview | [Link](./problems.md#the-video-of-a-camera-does-not-appear-on-the-multiview-display) |
| Camera controller not operating cameras | [Link](./problems.md#the-camera-controller-fails-to-operate-the-cameras) |
| Encoder STREAM button flashes red | [Link](./problems.md#the-encoder-stream-button-flashes-red) |
| "Go live" greyed out on YouTube | [Link](./problems.md#the-go-live-icon-is-greyed-out-on-youtube) |
| Stream not appearing in YouTube preview | [Link](./problems.md#the-live-stream-does-not-appear-in-the-preview-on-youtube) |
| YouTube "no data" or "poor connection" | [Link](./problems.md#youtube-shows-no-data-or-poor-connection) |
| No internet on streaming PC | [Link](./problems.md#the-internet-is-not-accessible-from-the-live-streaming-pc) |
| Poor sound quality | [Link](./problems.md#poor-sound-quality-on-the-live-stream) |
| Song words not outlined in black | [Link](./problems.md#song-words-not-outlined-in-black) |
| Logo not visible | [Link](./problems.md#christ-church-winchester-logo-not-visible) |
| YouTube buffering / connection failure | [Link](./problems.md#youtube-connection-problems) |
| Framerate wrong (people moving too fast) | [Link](./problems.md#framerate-problems) |

---

*If your problem is not listed here, ask on the "Streaming" Slack channel or find someone in church who can help. If you solve an unlisted problem, please add it to [problems.md](./problems.md).*
