#  Week 0 – RGB, Images, Video & Sound

##  Comeback Log

Just returned from one of the most cursed travel stories ever.  
150€ gone, fake live, 5 people in one room...  
BUT I’M BACK.

> **Beast mode reactivated.**  
> CS50 is not ready for what's coming.

---

##  RGB: How Colors Are Represented in Binary

Computers use the **RGB model** (Red, Green, Blue) to represent color digitally.

Each pixel = **3 bytes** (1 byte per color)  
Each byte = 8 bits  
→ So every pixel = **24 bits**

This gives us:
- 256 levels of red
- 256 levels of green
- 256 levels of blue  
**= 16.7 million colors total**

### Examples:
- Red: `255, 0, 0`
- Green: `0, 255, 0`
- Blue: `0, 0, 255`
- White: `255, 255, 255`
- Black: `0, 0, 0`

---

##  Realization:

> “I never thought about what made image files so big...  
Now I know: every pixel holds 3 bytes minimum. Multiply that by millions of pixels.”

---

##  Images = Pixels = Data

- Every image is a grid of pixels.
- Each pixel has RGB values → 3 bytes → 24 bits.
- That’s **why photo files take so much space**.

---

##  Video = Photos + Speed

- Videos are just **lots of images (frames) per second**.
- Example: 30 fps = 30 full image frames per second.
- That’s why video file sizes explode — it's image data times time.

> “Now I get why videos are huge.  
They’re a waterfall of photos, fooling my brain into seeing motion.”

---

##  Sound = Vibration to Binary

- Sounds are vibrations → represented digitally via sampling.
- Computers take **samples per second** (e.g. 44,100Hz).
- Each sample is stored as binary numbers.

More samples = higher quality = larger files.

---

##  What Hit Me the Most:

> “It’s all ones and zeroes.  
But what gives them power is that **we**, the programmers, decide what those bits do.”

---

##  Concepts Unlocked

- RGB and color representation  
- Pixels, bits, bytes  
- Image size explained  
- Video = many images = data times time  
- Sound = sampled vibration  
- Programming = controlling the meaning of binary

---

