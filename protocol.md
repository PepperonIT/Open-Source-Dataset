# Photographing protocol
## Adding to existing dataset
Use Peppers built in camera to take the new pictures, as this makes the data more valuable since it is more representative of the actual use case. The images are taken in 1280x960 resolution, this is using Peppers AL::k4VGA setting. This is accessed through the id-parameter "3". The code for this process can be found in the ["Rock-Papper-Scissors"](https://github.com/D7017E/Rock-Paper-Scissors.git) repository. There are four basic hand gestures that for this dataset with three independent variations:
- Rock
- Paper
- Scissor
- Nothing

The variations are:
- Supported
  - A game gesture on top of a open, flat, hand.
- Unsupported
  - A game gesture with no support under the hand.
- Clenched
  - A tensed game gesture, with the proper form.
- Relaxed
  - A softer game gesture, with no stridt adherence to form.
- Close
  - A close up image of the player.
- Distant
  - A image of the player from further away.

Due to Peppers limited camera viewing angle the player should be in a seated position directly in front of Pepper.
## Distances from pepper
### Short distance
For close up game images use a distance of roughly 50 - 60 cm from Pepper.

### Long distance
For close up game images use a distance of roughly 110 - 120 cm from Pepper.

# Session list
- Rock
  - Supported clenched close
  - Supported relaxed close
  - Supported clenched distant
  - Supported relaxed distant
  - Unsupported clenched close
  - Unsupported relaxed close
  - Unsupported clenched distant
  - Unsupported relaxed distant
- Paper
  - Supported clenched close
  - Supported relaxed close
  - Supported clenched distant
  - Supported relaxed distant
  - Unsupported clenched close
  - Unsupported relaxed close
  - Unsupported clenched distant
  - Unsupported relaxed distant
- Scissor
  - Supported clenched close
  - Supported relaxed close
  - Supported clenched distant
  - Supported relaxed distant
  - Unsupported clenched close
  - Unsupported relaxed close
  - Unsupported clenched distant
  - Unsupported relaxed distant
- Nothing
  - Close no hands
  - Close supported gesture, other than rock, paper, or scissor
  - Close unsupported gesture, other than rock, paper, or scissor
  - Distant no hands
  - Distant supported gesture, other than rock, paper, or scissor
  - Distant unsupported gesture, other than rock, paper, or scissor