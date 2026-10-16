# Interstate

Sound, breath and light for calm, confidence and empowerment.

Interstate is a generative listening instrument by **Assaf Shatil**. Each state is its own slow composition: a sub movement, a pulse, winds, cluster harmony and an evolving timbre, always swelling in and out, asynchronously. Turning a ring never makes a layer louder; it changes its timbre, density, sparseness and variety.

**Live demo:** https://assafshatil.github.io/interstate/
(the same app also lives at `/web-demo-male/`)

Headphones recommended. Best on iPhone in Safari: add it to the Home Screen for a full-screen app.

## States (Volume I)

| State | Guide |
|---|---|
| Arrive | Breath |
| Control | Build and settle, with an arousal ring plus Vibration and Circle layers |
| Body | Kegel and reverse kegel, timed to the breath |
| Reset | Even breath |
| Practice | Breath, with a 528 Hz binaural layer |

## Using it

- **Rings:** circle a finger around a ring to change that layer. Its name appears only while you touch it.
- **Right edge:** slide up or down for volume.
- **Left edge:** slide for spread, from close and centred to wide, wandering stereo.
- **Long-press:** pause.
- **Rest:** after a while without touch the screen dims, and short lines of text fade in below the circle.
- **Lamp:** a soft coloured light that follows the breath.

## Files

```
index.html               the whole app (one self-contained file)
web-demo-male/index.html same app, kept for older links
README.md                this file
```

Everything runs in the browser: the sound is synthesised live in an AudioWorklet, with no audio files and no tracking. Settings and the journal are kept only on the device.

## Version

M40: sound stability for phones. The sound engine uses about a third of the processing it used to; there's a smooth internal limiter, a gentle output stage, a lighter hall reverb, capped screen drawing, recovery after calls or the lock screen, and a self-heal if the audio ever goes bad.

A native iOS app is planned.

---
Interstate is not a medical device and makes no medical claims. For health concerns, see a professional.

© Assaf Shatil · assafshatil.com
