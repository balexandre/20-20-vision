# Through My Glasses 👓

**Got 20/20 vision? This is what the rest of us see before we find our glasses.**

Through My Glasses is a small, playful web page that lets people with perfect eyesight experience what everyday blur feels like. Pick a scene, dial in a prescription, and watch a mountain view, a highway exit sign, or a newspaper go soft. Then flip the glasses switch and feel the relief.

> 🔗 **Try it:** https://balexandre.github.io/20-20-vision

---

## Why this exists

Telling someone "I'm −3.00" means nothing to them. Showing them that they'd have missed the highway exit makes it click.

This page is for friends, partners, coworkers, and kids who have never needed glasses and wonder why we panic when ours go missing. It's also for anyone curious about why reading gets harder after 45.

## What you can do

- **Pick a scene.** A mountain landscape far away, a highway with an exit sign about 50 m ahead, or a newspaper at reading distance.
- **Set a prescription.**
  - **Sphere:** minus for nearsighted, plus for farsighted.
  - **Astigmatism** and its **angle:** blur that smears in one direction.
  - **Age:** the eye's focusing power fades with the years.
- **Put the glasses on.** You look through a lens, with the frame softly out of focus at the edges, the way real frames are.
- **Read the verdict.** An estimated sharpness score like **20/125**, a caption for the moment ("Was that our exit?!"), and whether you'd be legal to drive.
- **Try a preset.** *Perfect vision*, *A bit nearsighted*, *Lost my glasses*, *Astigmatism*, *Farsighted* and *Over 50*.

There are a few jokes hidden in the pictures. The highway is Interstate 20, and the newspaper is *The Daily Squint*. Look closely at the desk, too.

## Works for everyone

- Fully usable with a keyboard. <kbd>Tab</kbd> moves between controls, the arrow keys change values and scenes, <kbd>G</kbd> toggles glasses, and <kbd>1</kbd> <kbd>2</kbd> <kbd>3</kbd> pick a scene.
- Screen readers hear every value in plain words, plus a short summary of how sharp the scene looks.
- Respects your device's reduced-motion and dark-mode settings.
- Works on phones: the picture stays pinned to the top while you play with the sliders.

## How it works, in plain words

Every scene has a distance. Every eye has a focusing error (the prescription) and a limited ability to refocus, which shrinks with age. The page works out how far out of focus the scene is for that eye and blurs the picture by that amount.

That's why the page behaves like real life:

- Nearsighted people read the newspaper fine but can't read the exit sign.
- Young farsighted people see clearly, but their eyes work hard to do it.
- Almost everyone over 50 ends up holding the newspaper at arm's length.

## How accurate is it?

**Right about what blurs and when, close on how much, and simpler in how the blur looks.**

- The sharpness score is usually within a line or two of an eye chart for a typical person in daylight.
- Real blur is messier: ghost images, halos around lights, and it gets worse at night when pupils open up.
- Real people also squint, and their brains get used to the blur. Both make real vision a bit better than the page shows.

It's built for empathy, not diagnosis. If something on the page feels familiar, go see an eye doctor 🙂

## Run it yourself

It's a single `index.html` file with no build step and nothing to install. Download it and open it in any modern browser.

To publish your own copy on GitHub Pages:

1. Fork or push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then pick `master` and `/ (root)`.
4. Wait a minute, then visit `https://<your-user>.github.io/<repo-name>/`.

## Ideas for later

- A softer, more realistic blur shape, with halos and ghosting
- A day/night switch, since blur gets worse in the dark
- A "squint" button
- Your own photos as scenes

Suggestions and pull requests are welcome.
